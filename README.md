# Simple Shell Project README

This repository contains the implementation of a simple shell program as described below:

## Files Included

### `man_1_simple_shell`
This file is the manual page for the shell that is implemented in this project.

### `AUTHORS`
At the root of the repository, there is an `AUTHORS` file that lists all individuals who have contributed content to this repository.

### `main.h`
The `main.h` file serves as the header file for the project. It contains standard header files and prototypes of functions used in the program.

### `main.c`
This file initializes the program by implementing an infinite loop that calls the `prompt` function, responsible for providing the user with a command prompt.

### `prompt.c`
The `prompt.c` file uses the `getline` system call to read input from the user and implements an infinite loop with fork to maintain the command prompt functionality.

### `special_character`
This component identifies special inputs, such as determining if the first input is a slash, if the user typed "exit" or "env," and similar functionalities.

### `string.c`
The `string.c` file handles various string operations, including string length calculation, string writing, finding strings in directories, string concatenation, and more.

### `cmd.c`
Responsible for parsing and finding the command entered by the user within the shell.

### `execute.c`
This file is responsible for executing the identified command.

## How to Use

To utilize this simple shell program, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your_username/simple-shell.git
    ```

2. **Compile the Program**
    ```bash
    gcc -Wall -Werror -Wextra -pedantic *.c -o shell
    ```

3. **Run the Shell**
    ```bash
    ./shell
    ```
    This will start the shell program and display a command prompt where you can input commands.

4. **Execute Commands**
    Enter commands as you would in a regular shell environment. The implemented shell should execute the commands accordingly.

## Contributors
List of contributors to this project:
- [Alpha Chukwuemeka](https://github.com/010binary)

---
