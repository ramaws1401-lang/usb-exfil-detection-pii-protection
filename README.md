# usb-exfil-detection-pii-protection
# USB Data Exfiltration Detection & PII Protection Model for SMEs

An open-source **USB data exfiltration detection** and **PII protection** model designed for **small and medium businesses (SMBs/SMEs)** with minimal infrastructure.  
The model uses Python **watchdog**, **regex**, and **Microsoft Presidio** to monitor file transfers, identify sensitive data, and trigger alerts.

---

## Key Features
Detect removable USB device connection events  
Monitor file copy/move operations in real-time  
PII detection using Regex + Microsoft Presidio  
Email alerts for suspicious activity  
Logs securely stored for audit trail  
Lightweight & cost-efficient — no commercial DLP required  

---

## Tech Stack
- Python 3.x
- Watchdog (filesystem monitoring)
- Microsoft Presidio Analyzer
- Regex-based Detector
- SMTP Email Notifications
- Linux (Ubuntu) endpoint

---

## 📂 Project Structure
