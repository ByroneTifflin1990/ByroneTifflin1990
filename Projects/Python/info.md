# Failed Login Attempts Parser

This Python script is designed to assist cybersecurity professionals in quickly extracting **failed login attempts** from raw CSV log files. It scans a specified log file for lines containing the keyword `"fail"` and writes them to a new output file for further investigation. This is particularly useful for incident response, log analysis, or threat hunting.

---

## 🔍 Features

- Parses raw log files line-by-line
- Extracts and exports entries containing failed login attempts
- Outputs results to a clean, separate file (`failed_logins.txt`) - you can rename this to whatever file you desire.
- Lightweight and easy to integrate into larger analysis workflows

---

## 💡 Use Case

You're analyzing system logs or authentication records and need to identify all failed login attempts for review or reporting. This script automates that task, saving time and ensuring accuracy in detection.

---

## 🛠️ How to Use

1. Place your CSV log file in the same directory as the script.
2. Open the script and update the `log` variable to point to your log file:
