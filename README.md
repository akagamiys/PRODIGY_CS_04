# Keylogger 

## Overview

A keylogger is a program that records the keystrokes typed on a computer's keyboard. It can be used for various purposes, including debugging, monitoring user activity (with consent), or testing software. This script captures keystrokes and logs them into a text file (keylog.txt in this case).

## Features

Keystroke Logging: Records all keystrokes typed by the user.

Logging Configuration: Uses Python's logging module to configure logging settings.

Listener Setup: Monitors keyboard events using pynput.keyboard.Listener.

Output: Saves logged keystrokes in a specified text file (keylog.txt).

## Requirements
-Python 3.x

-pynput library

-logging library

## How It Works

Logging Configuration: Initializes logging to save keystrokes with timestamps.

Listener Setup: Defines an on_press function to handle keystrokes and log them.

Start Keylogger: Initiates a pynput.keyboard.Listener to capture and log keystrokes continuously.

Output: Saves logged keystrokes to a text file (keylog.txt) in the current directory.

## Usage

Run the Script: Execute the Python script in your terminal or IDE.

Monitor Keystrokes: Once started, the keylogger will silently monitor and log all keystrokes.

Stop the Keylogger: To stop logging keystrokes, terminate the script manually or close the terminal/IDE session.

## Security and Legal Considerations

Consent: Always obtain explicit consent before using a keylogger, especially in contexts involving other users' devices.

Security: Use keyloggers responsibly and ensure that captured data is handled securely.

Privacy: Avoid logging sensitive information (e.g., passwords) without proper security measures.
