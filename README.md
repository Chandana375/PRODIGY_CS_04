simple keylogger 🛡️

Mini EDR Pro Dashboard is a task-ready Endpoint Detection & Response simulation for demo and assignment purposes. It detects high-risk processes and suspicious files on your system and alerts the user in real-time

Features ✨

✅ Automatic scanning of running processes
✅ Detection of suspicious files like keyloggers
✅ Color-coded alerts in the dashboard (red for HIGH risk, green for LOW risk)
✅ Pop-up notifications for high-risk processes
✅ Logs all findings to edr_report.csv
✅ Fully automated — no typing needed

How it Works ⚡

The dashboard continuously scans running processes and files

Suspicious processes matching keywords or unusual behavior are flagged as HIGH or LOW risk

High-risk detections trigger a pop-up alert

Suspicious files are listed in the dashboard in real-time

All results are saved to edr_report.csv for review

Requirements 🧰

Python 3.x

psutil library

Install psutil using
pip install psutil

Usage 🚀

Clone the repository or copy the project folder

Open PowerShell or Terminal

Run the provided script:
powershell -ExecutionPolicy Bypass -File Mini_EDR_Demo.ps1

The dashboard opens automatically and starts scanning

Safety Note ⚠️

This project simulates high-risk detections for learning and demo purposes. It does not harm your system. Always use caution with real keyloggers or malware.

Output 📊

Dashboard shows processes and files detected

