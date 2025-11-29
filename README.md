# 0x03. Shell, init files, variables and expansions

This project explores shell initialization files, variables, expansions, and aliases in Bash scripting.

## Project Structure

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias `ls` with value `rm *` |
| `1-hello_you` | Prints "hello" followed by the current Linux user |
| `2-path` | Adds `/action` to the PATH |
| `3-paths` | Counts the number of directories in PATH |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists all local variables and functions |
| `6-create_local_variable` | Creates a local variable `BEST` with value `School` |
| `7-create_global_variable` | Creates a global variable `BEST` with value `School` |
| `8-true_knowledge` | Adds 128 to the value stored in `TRUEKNOWLEDGE` |
| `9-divide_and_rule` | Divides `POWER` by `DIVIDE` |
| `10-love_exponent_breath` | Calculates `BREATH` to the power `LOVE` |
| `11-binary_to_decimal` | Converts a binary number to decimal |
| `12-combinations` | Prints all possible two-letter combinations except 'oo' |
| `13-print_float` | Prints a number with two decimal places |
| `14-decimal_to_hexadecimal` | Converts a decimal number to hexadecimal |
| `100-rot13` | Encodes and decodes text using rot13 encryption |
| `101-odd` | Prints every other line from input |
| `102-water_and_stir` | Adds two numbers and prints in base `bestchol` |

## Requirements

- All scripts are exactly two lines long
- First line: `#!/bin/bash`
- All files end with a new line
- All files are executable
- No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk`

## Learning Objectives

- Shell initialization files (`/etc/profile`, `~/.bashrc`)
- Local vs global variables
- Shell expansions and arithmetic
- Command substitution
- Creating and using aliases

## Usage

To run any script:
```bash
./script_name
