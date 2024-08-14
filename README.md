# PasswordAnalyzer
A simple yet powerful Python tool to analyze and evaluate the strength of passwords.
It uses the zxcvbn library to evaluate the strength of passwords based on factors such as length, complexity, and common usage.

## Features

* Checks password length, complexity, and entropy
* Identifies weak and commonly used passwords
* Provides recommendations for improvement
* Supports multiple password hashing algorith

<p align="center">
<img src="https://www.duplichecker.com/asets/img/password-manager-tools.svg" height="300">
</p>

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [Contact](#contact)
6. [License](#license)

## Requirements

* Python 3.x
* `zxcvbn` library

## Usage

1. Clone the repository:

```sh
git clone https://github.com/errorwiki/PasswordAnalyzer
```

2. Change into directory:

```sh
cd Password-Strength-Checker
```

3. Install the `zxcvbn` library:

```
pip3 install zxcvbn
```

4. Run the script:

```
python password_strength_checker.py.
```

5. Follow the prompts to enter the number of passwords to test, the path to the weak wordlist file (optional), and the path to the banned wordlist file (optional). Enter the passwords to test when prompted.

**NOTE:** To exit the tool, enter 0 when prompted for the number of passwords to test.

### Example Output

```
$ python password_strength_checker.py
Enter the number of passwords to test (enter 0 to exit): 2
Enter the path to the weak wordlist file (leave blank for default):  
Enter the path to the banned wordlist file (leave blank for default):

Enter a password: password123
Too short: Password should be at least 12 characters long.

Enter a password: securePassword123!
Strong: Password meets all the requirements. Score: 4/4

Enter the number of passwords to test (enter 0 to exit): 0
Exiting the tool.
Thank you for using the Password Strength Checker.
```

## Contributing

Pull requests are welcomed. For major changes, please open an issue first to discuss what you would like to change.

## Contact

Shubham Sharma - [My LinkedIn](https://www.linkedin.com/in/heyvikas/) .

## License

This project is licensed under the GPL 3.0 License - see the [LICENSE](LICENSE) file for details.
