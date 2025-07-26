# 🚪 Python Port Scanner

This is a basic port scanner I wrote in Python. It checks a range of ports on a given IP to see what's open. Super handy when you're doing quick recon or just messing around with networking.

## ⚙️ What It Does

- Takes a target IP or domain as a command-line argument
- Tries to connect to each port
- Prints out which ports are open
- Gracefully handles errors like bad hostnames or Ctrl+C

## 🧠 How to Use It

1. Make sure you have Python 3 installed.

2. Run the script like this:

```bash
python3 scanner.py 127.0.0.1
