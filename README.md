# SLOT-A-ECA6101-COMPUTER-NETWORK-
# Multi-Factor Authentication (MFA) Portfolio

## Introduction

This project is about studying and understanding Multi-Factor Authentication (MFA). MFA provides an additional layer of security by requiring more than one method to verify a user's identity.

## Objective

The main objective of this project is to understand how MFA works, study different MFA methods, implement an authentication method, perform security testing, and analyze the results.

## MFA Methods Studied

I studied different MFA techniques such as:

1. SMS OTP
2. Email OTP
3. TOTP Authenticator
4. Push Notification
5. Hardware Security Key
6. Biometric Authentication
7. Smart Card
8. Passkeys / FIDO2

## Implementation

For this experiment, I configured MFA authentication and registered an authentication factor. I then tested the authentication process using valid and invalid authentication details.

The authentication process was:

User → Username and Password → Password Verification → MFA Challenge → MFA Verification → Access Granted or Denied

## Testing

I performed authentication tests to check whether MFA correctly allowed or rejected users.

### Test 1: Valid Authentication

I entered the correct username, password, and valid MFA code.

**Result:** Authentication was successful.

### Test 2: Invalid OTP

I entered the correct password but used an incorrect OTP.

**Result:** Authentication was rejected.

### Test 3: Expired OTP

I tested an OTP after it was no longer valid.

**Result:** Authentication was rejected.

## Screenshots

The screenshots included in this project show:

- MFA configuration
- MFA registration
- Authentication process
- Successful login
- Failed login
- Testing results

## Security Analysis

MFA provides better security than using only a password. Different MFA methods provide different levels of protection.

OTP-based authentication is simple to use, while authenticator applications provide stronger protection than relying only on SMS. Hardware security keys and passkeys provide strong protection against phishing attacks.

## Learning Outcome

Through this project, I learned how Multi-Factor Authentication works and how an additional authentication factor can improve account security.

I also learned how to configure MFA, test different authentication scenarios, analyze authentication results, and understand the security advantages and limitations of different MFA methods.

## Conclusion

This experiment helped me understand the practical importance of Multi-Factor Authentication. Using an additional authentication factor reduces the risk of unauthorized access when a password is compromised.

The security method should be selected according to the requirements and risk level of the system.

## Repository Structure

MFA-Portfolio/

├── README.md

├── 01-Introduction/

├── 02-MFA-Methods/

├── 03-Comparison/

├── 04-Implementation/

├── 05-Testing/

├── 06-Screenshots/

├── 07-Analysis/

├── 08-Reflection/

└── 09-References/
![Uploading image.png…]()

