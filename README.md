# rCore-Camp-Code-2024A

### Code
- [Soure Code of labs for 2024A](https://github.com/LearningOS/rCore-Camp-Code-2024A)
### Documents

- Concise Manual: [rCore-Camp-Guide-2024A](https://LearningOS.github.io/rCore-Camp-Guide-2024A/)

- Detail Book [rCore-Tutorial-Book-v3](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)


### OS API docs
- [ch1](https://learningos.github.io/rCore-Camp-Code-2024A/ch1/os/index.html) [ch2](https://learningos.github.io/rCore-Camp-Code-2024A/ch2/os/index.html) [ch3](https://learningos.github.io/rCore-Camp-Code-2024A/ch3/os/index.html) [ch4](https://learningos.github.io/rCore-Camp-Code-2024A/ch4/os/index.html)
- [ch5](https://learningos.github.io/rCore-Camp-Code-2024A/ch5/os/index.html) [ch6](https://learningos.github.io/rCore-Camp-Code-2024A/ch6/os/index.html) [ch7](https://learningos.github.io/rCore-Camp-Code-2024A/ch7/os/index.html) [ch8](https://learningos.github.io/rCore-Camp-Code-2024A/ch8/os/index.html)


### Related Resources
- [Learning Resource](https://github.com/LearningOS/rust-based-os-comp2022/blob/main/relatedinfo.md)


### Build & Run

```bash
# setup build&run environment first
$ git clone https://github.com/LearningOS/rCore-Camp-Code-2024A.git
$ cd rCore-Camp-Code-2024A
$ git clone https://github.com/LearningOS/rCore-Tutorial-Test-2024A.git user
$ git checkout ch$ID
$ cd os
# run OS in ch$ID
$ make run
```
Notice: $ID is from [1-9]

### Grading

```bash
# setup build&run environment first
$ git clone https://github.com/LearningOS/rCore-Camp-Code-2024A.git
$ cd rCore-Camp-Code-2024A
$ rm -rf ci-user
$ git clone https://github.com/LearningOS/rCore-Tutorial-Checker-2024A.git ci-user
$ git clone https://github.com/LearningOS/rCore-Tutorial-Test-2024A.git ci-user/user
$ git checkout ch$ID
# check&grade OS in ch$ID with more tests
$ cd ci-user && make test CHAPTER=$ID
```
Notice: $ID is from [3,4,5,6,8]
