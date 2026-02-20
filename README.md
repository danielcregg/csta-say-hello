# Say Hello

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/danielcregg/csta-say-hello?style=flat-square)

> **Note:** This repository is a fork of the [CSTA Conference](https://www.csteachers.org/) example Java assignment originally created by [jeffrafter](https://github.com/jeffrafter/csta-say-hello).

## Description

A beginner-friendly Java assignment designed for the CSTA (Computer Science Teachers Association) Conference. The project introduces students to basic standard I/O in Java, covering how to print text to `stdout` and read user input from `stdin`.

## Prerequisites

- [Java JDK](https://www.oracle.com/java/technologies/downloads/) 8 or higher

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/csta-say-hello.git
   cd csta-say-hello
   ```

2. Compile the Java files:
   ```bash
   javac Hello.java
   javac HelloName.java
   ```

## Usage

### Task 1 -- Hello World

In `Hello.java`, change the output string so the program prints `Hello world!` to the console.

Run it with:
```bash
java Hello
```

### Task 2 -- Hello Name

In `HelloName.java`, add code that reads the user's name from standard input and then prints a greeting. For example, if the user enters "Alice", the program should output `Hello Alice!`.

Run it with:
```bash
java HelloName
```

## Project Structure

```
csta-say-hello/
├── Hello.java      # Basic "Hello world" output exercise
├── HelloName.java  # User input and greeting exercise
├── .gitignore
├── LICENSE
└── README.md
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
