**OTP Generation:** A Secure One-Time Password Generator in Python

### Overview

Generate one-time passwords (OTPs) on the command line for added security in authentication processes. This OTP generator is designed to provide a simple, yet robust solution for generating time-based OTPs.

### Features:

- Command-line interface for ease of use.
- Generates OTPs based on the current time and a secret key.
- Supports different hash algorithms for increased security.
- Compatible with Google Authenticator and other TOTP-based applications.

### Technologies Used:

- Python 3.6 or higher
- PyOTP for OTP generation
- Click for command-line parsing

### Getting Started:

1. Clone the repository:
```
git clone https://github.com/iamaloksy/otp_genrate.git
```

2. Install the required Python packages:
```
pip install -r requirements.txt
```

3. Run the OTP generator:
```
python otp_generate.py
```

### Usage:

The OTP generator script accepts the following command-line arguments:

- `-h`, `--help`: Display the help message and exit.
- `-s`, `--secret-key`: Specify the secret key to use for OTP generation.
- `-a`, `--algorithm`: Specify the hash algorithm to use. Supported algorithms: SHA1, SHA256, SHA512 (default: SHA512).
- `-l`, `--length`: Specify the length of the OTP (default: 6).
- `-t`, `--time-step`: Specify the time step in seconds for OTP generation (default: 30).

### Contribution Guidelines:

Contributions and feedback are welcome! Please follow these guidelines to contribute:

- Fork the repository and create a new branch for your changes.
- Write concise commit messages explaining the purpose of your changes.
- Adhere to the existing coding style and conventions.
- Submit pull requests for your changes and provide a clear description of your contribution.

### License:

This project is licensed under the MIT License.

### Contact:

For further inquiries or support, reach out to [Aloksy](https://github.com/iamaloksy).
