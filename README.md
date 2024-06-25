

# OTP Verification Project

This project demonstrates a simple One-Time Password (OTP) verification system using Python. It includes generating a 6-digit OTP, sending it to a user's email, and verifying the OTP entered by the user.

## Features

- Generates a 6-digit OTP
- Sends the OTP to a specified email address
- Verifies the OTP entered by the user

## Prerequisites

- Python 3.x
- An email account (Gmail recommended for simplicity)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/otp-verification.git
cd otp-verification
```

2. Install any necessary dependencies (if any). For sending emails, the `smtplib` and `email` libraries are used, which are part of the Python standard library, so no additional installations are required.

## Usage

1. Run the `otp-verification.py` script:

```bash
python otp-verification.py
```

2. Follow the on-screen prompts:

- Enter your email address to receive the OTP.
- Enter the sender email address (the email from which the OTP will be sent).
- Enter the sender email password securely.

3. Check your email for the OTP.

4. Enter the received OTP in the console to verify.

## Security Notes

- The sender's email password is entered securely using the `getpass` library to avoid echoing it in the console.
- Ensure that "Less secure app access" is enabled in your Gmail account settings or use an app-specific password if two-factor authentication is enabled.
- Do not hardcode sensitive information like email passwords in the script.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project uses Python's `smtplib` for sending emails and `random` for OTP generation.
