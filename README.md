# Explorer (Linux)

A lightweight, fast terminal file explorer built in Risk.

## Features
* Navigate through your local directories.
* File Management: Create, delete, and view file details directly from the terminal.

[Screencast from 2026-10-20 13-30-19.webm](https://github.com/user-attachments/assets/8c2385a3-4c36-4711-9d46-12b564f8a7e2)


## Prerequisites
To run or build this project, you need:
* `riskc`

## Installation & Setup

To make explorer accessible globally from any terminal window, follow these steps:

1. **Make the binary executable:**
   Navigate to the directory containing your compiled explorer binary and run:
   ```bash
   chmod +x explorer
   ```

2. **Move it to your system PATH:**
   Copy the executable to /usr/local/bin so Linux can recognize it as a global command:
   ```bash
   sudo cp explorer /usr/local/bin/
   ```

## Usage

Once installed, simply open any terminal and type:
```bash
explorer
```
