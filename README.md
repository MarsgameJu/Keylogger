# Keylogger Project

## Overview
This is a simple and lightweight keylogger built in Python using the `pynput` library. It records all key presses and stores them in a log file for later review. 

⚠ **Disclaimer:** This project is strictly for educational and ethical use only. Unauthorized use of keyloggers is illegal. Ensure you have explicit permission before running this software.

## Features
- Logs all key presses in real-time.
- Runs silently in the background without opening a console window.
- Stores logs in a specified file.
- Lightweight and easy to use.

## Requirements
- Python 3.x
- `pynput` library

## Installation

1. **Clone the repository** or download the script:
   ```bash
   git clone https://github.com/MarsgameJu/Keylogger.git
   cd keylogger
   ```
   
2. **Install the required dependency:**
   ```bash
   pip install pynput
   ```
   
3. **Modify the script** (optional):
   - Change the log file path if necessary.

## Usage

### Running the Script
1. Open a terminal or command prompt.
2. Run the script in the background without showing a console window:
   ```bash
   start pythonw.exe path\to\your\script.py
   ```
3. Alternatively, you can start the script by **double-clicking** a `.bat` file that contains the above command.

### Customizing Log Storage
- By default, logs are saved in `keyfile.txt`.
- To change this, edit the script and modify the file path accordingly.
