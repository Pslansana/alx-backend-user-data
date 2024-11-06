# 0x00. Personal Data

## Project Overview
This project focuses on essential back-end skills for handling and protecting personal data. You’ll learn how to identify Personally Identifiable Information (PII), encrypt sensitive data, log securely, and authenticate to a database. These tasks are designed to reinforce privacy and security practices in backend systems.


## Learning Objectives
By the end of this project, you should be able to:

1. **Identify Examples of Personally Identifiable Information (PII):**
   - Understand what qualifies as PII, which includes any data that could potentially identify a specific individual. This could be direct identifiers (like name, Social Security number) or indirect identifiers (like IP addresses or login IDs).
   - Be able to distinguish between PII, non-PII, and general personal data to ensure sensitive information is handled appropriately.

2. **Implement a Log Filter to Obfuscate PII Fields:**
   - Learn how to use Python’s `logging` module effectively to keep track of application activities without exposing sensitive data.
   - Build a custom filter to obfuscate sensitive fields in log messages (such as emails or usernames) so that PII is hidden when stored in logs. This ensures logs can be shared or stored without risking data privacy.

3. **Encrypt Passwords and Check Password Validity:**
   - Use encryption to store passwords securely, protecting against unauthorized access even if the database is compromised.
   - Utilize the `bcrypt` package to hash passwords before storing them in a database and check the validity of an input password during login. This is essential for implementing strong, secure user authentication practices.

4. **Authenticate to a Database Using Environment Variables:**
   - Learn to secure sensitive database credentials (like usernames and passwords) by storing them in environment variables instead of hard-coding them into the application. This minimizes the risk of exposure in code repositories or during deployment.
   - Understand how to retrieve these environment variables within the code to connect securely to the database, ensuring the application’s connection credentials are protected.

## Resources
Be sure to review these materials for additional insights:
- [What Is PII, non-PII, and Personal Data?](#)
- [Logging documentation](#)
- [bcrypt package](#)
- [Logging to Files, Setting Levels, and Formatting](#)

## Project Tasks

### 1. Identifying PII
Identify examples of PII data, such as:
- Names
- Social Security numbers
- Email addresses
- IP addresses

### 2. Implementing Log Filtering
Implement a log filter to obfuscate sensitive information like emails or usernames:
- Use Python’s `logging` module to log actions.
- Set up a custom filter to obfuscate sensitive fields, replacing portions of the data (e.g., hiding parts of an email).

### 3. Password Encryption
Use the `bcrypt` package to:
- Encrypt user passwords before storage.
- Check the validity of passwords upon login.

### 4. Secure Database Authentication
Authenticate your application to a database using environment variables to protect sensitive information:
- Store database credentials securely in environment variables.
- Access these variables in your code to connect to the database without exposing credentials.

### Prerequisites
- Python 3.x
- Virtual environment setup (optional but recommended)
- `bcrypt` package (install with `pip install bcrypt`)
- `.env` file to store environment variables securely


