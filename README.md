# OTP-Generator-Verification-System

## Project Overview
This repository contains two Python-based mini projects related to **OTP (One-Time Password)** systems.
These projects simulate real-world authentication systems used in banking, apps, and secure logins.

##  Projects Included

### 1️ OTP Verification System
This program:
* Generates a random 4-digit OTP
* Allows user to enter OTP
* Gives **3 attempts** to enter correctly
* Blocks the account after maximum attempts

#### Features

* Random OTP generation
* Limited login attempts
* Exception handling for invalid input
* Simple authentication logic

####  Example Output

```
OTP: 1234
Enter OTP: 1111
Wrong OTP
Enter OTP: 1234
Login successful
```

---

### 2️ OTP Generator with File Storage

This program:

* Generates a random OTP
* Displays it to the user
* Stores OTP along with timestamp in a file (`otp.txt`)

#### Features
* Delay simulation using `time.sleep()`
* OTP logging with date and time
* File handling
* Real-world OTP storage simulation

####  Example Output

```
Generating OTP...
Your OTP is: 5678
Do not share this OTP
OTP saved in file successfully
```
##  Technologies Used

* Python
* `random` module
* `time` module
* `datetime` module
* File handling

##  How to Run

1. Install Python

2. Save the files:

   * `otp_verification.py`
   * `otp_generator_file.py`

3. Run the programs:

```bash
python otp_verification.py
python otp_generator_file.py
```
##  Concepts Used

These projects help you understand:

* Random number generation
* Loops and conditions
* Exception handling (`try-except`)
* File handling (read/write)
* Date and time handling
* Basic authentication logic

##  Learning Outcomes

After completing this project, you will be able to:

* Build a simple **OTP-based login system**
* Handle user input errors safely
* Store data in files
* Simulate real-world authentication systems
* Improve logical thinking in Python

##  Possible Improvements

* Add OTP expiry time
* Mask OTP display (security)
* Send OTP via email/SMS (advanced)
* Store OTP securely (encryption)
* Add GUI using Tkinter or web using Flask
  
##  Author
Harsha G
Learning Python | Embedded Systems | IoT
Harsha G
Learning **Python | Embedded Systems | IoT**
