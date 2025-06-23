# task1-port-scan
 Basic network reconnaissance using Nmap to identify open ports
 # Task 1 – Port Scanning Using Nmap (Zenmap)

## 🔍 Objective:
To identify open ports on a device in my local network using Nmap, via its GUI tool Zenmap.

## 🛠 Tools Used:
- Zenmap (GUI version of Nmap) on Windows

## 🧪 Steps Followed:
1. Opened Zenmap
2. Entered my local IP range: `192.168.1.0/24`
3. Selected profile: **Regular Scan**
4. Ran the scan and found a live host: `192.168.1.17`
5. Identified open ports: `135`, `139`, and `445`
6. Saved the results to `scan_results.txt`

## 📁 Files Included:
- `scan_results.txt` – Output from the scan

## 🔒 Security Insights:
- These open ports are commonly used in Windows systems:
  - Port 135: RPC (Remote Procedure Call)
  - Port 139: NetBIOS Session Service
  - Port 445: Microsoft Directory Services
- If exposed on the internet, these services can be vulnerable to exploits like **EternalBlue** or **SMB attacks**
- Recommended to block such ports at firewall level unless needed internally

## ✅ Outcome:
Learned how to scan a local network using Zenmap and interpret the open ports and services found.

