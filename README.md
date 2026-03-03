# 🔐 Secure Password Generator

A simple yet customizable command-line password generator built with Python.

## Features

- Custom password length
- Toggle uppercase letters, lowercase letters, numbers and symbols
- Input validation — raises an error if no character type is selected
- Clean and minimal CLI interface

## Usage

```bash
python password_generator.py
```

You will be prompted to configure your password:

```
Enter the desired password length: 16
Include uppercase letters? (y/n): y
Include lowercase letters? (y/n): y
Include numbers? (y/n): y
Include symbols? (y/n): n

Generated password: FkT3mXqLw8ZrNpA2
```

## Requirements

No external dependencies — uses Python's built-in `random` and `string` modules.

```bash
python 3.x
```

## What I learned

- Structuring code into reusable functions
- Using Python's `string` module constants
- Handling edge cases with `raise ValueError`
- Boolean logic from user input

## License

MIT License — feel free to use, modify and distribute this project.

## Author

Benjamin Montenegro — [GitHub](https://github.com/BenjaminMontenegro16)
