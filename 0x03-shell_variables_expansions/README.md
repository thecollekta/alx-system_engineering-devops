# 0x03. Shell, init files, variables and expansions

Welcome to the `Shell Variables and Expansions` project! This project introduces you to the powerful features of the shell — including how to create aliases, manage variables, and perform expansions.

---

## Project Structure

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias `ls` that runs `rm *` |
| `1-hello_you` | Prints a greeting to the current Linux user |
| `2-path` | Adds `/action` to the end of the PATH environment variable |
| `3-paths` | Counts the number of directories in the PATH environment variable |
| `4-global_variables` | Lists all environment variables |
| `5-local_variables` | Lists all local variables, environment variables, and functions |
| `6-create_local_variable` | Creates a local variable named `BEST` with value `School` |
| `7-create_global_variable` | Creates a global variable named `BEST` with value `School` |
| `8-true_knowledge` | Adds 128 to the value stored in the TRUEKNOWLEDGE environment variable |
| `9-divide_and_rule` | Divides the values of POWER by DIVIDE environment variables |
| `10-love_exponent_breath` | Calculates BREATH raised to the power of LOVE |
| `11-binary_to_decimal` | Converts a binary number in $BINARY to decimal |
| `12-combinations` | Prints all two-letter combinations from a-z, excluding 'oo' |
| `13-print_float` | Prints the value of NUM with exactly two decimal places |
| `100-decimal_to_hexadecimal` | Converts a decimal number in $DECIMAL to hexadecimal |
| `101-rot13` | Encodes and decodes text using the ROT13 cipher |
| `102-odd` | Prints every other line from input, starting with the first line |

## Usage

To run a script, proceed as follows:

```bash
$ chmod +x script_name.sh
$ ./script_name.sh
```

For script changes, of the shell environment, use `source`:

```bash
$ source 0-alias
```

## Requirements

* Ubuntu 20.04 LTS
* Bash shell
* Scripts should be executable and start with shebang `#!/bin/bash`

## License

This project is part of the ALX BE Software Engineering Program.
