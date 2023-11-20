# Keylogger Project

## Description

This keylogger project, implemented in Python, captures and logs keystrokes on a system. The project consists of two main files:

### keylogs.py

This Python script utilizes the `keyboard` library to capture keylogs and the `smtplib` library for sending email using the SMTP protocol (specifically configured for Gmail). The script logs key presses and includes special handling for non-character keys. It provides options to report the keylogs either to a file or via email at regular intervals. The keylogger runs continuously until manually stopped.

#### Usage:
bash
``` python keylogs.py ```

### run.bat
This batch file is a simple script that starts the keylogger by executing the keylogs.py script using the Python interpreter.

#### Usage:
```Start " " python "keylogs.py"```


## Configuration

The SEND_REPORT_EVERY variable in keylogs.py determines the interval for reporting keylogs (in seconds).

The report_method variable in keylogs.py specifies the reporting method (file for saving to a file).

## Disclaimer
__Note: This project is intended for educational purposes only. Unauthorized use of keyloggers or similar tools may violate privacy and legal regulations. Use responsibly and respect privacy laws.__
