# Network-and-Port-Scanner
# 🔍 Network and Port Scanner

This tool scans a local network to identify active hosts and checks for open ports on each device. It helps users discover devices in their network and diagnose open or vulnerable ports.

## 📌 Features

- Scans a range of IP addresses to detect live hosts  
- Performs port scanning on active devices  
- Displays hostnames and open ports  
- Easy to customize IP range and port list  

## ⚙️ How It Works

1. **Ping Sweep** – Sends ping requests to a range of IP addresses to find which devices are online.  
2. **Port Scanning** – For each active host, scans for open ports (commonly 1–1024 or user-defined range).  
3. **Display Results** – Shows a summary of live hosts and their open ports.  

## 🛠️ Requirements

- Python 3.x  
- `socket`, `subprocess`, and `ipaddress` modules (standard libraries)  

## 🚀 How to Run

```bash
python network_port_scanner.py
```

You can customize the IP range and port range inside the script.

## 📷 Sample Output

```
Scanning network 192.168.1.0/24...

Host: 192.168.1.10 (Device_Name)
  → Port 22: Open
  → Port 80: Open

Host: 192.168.1.20 (Printer)
  → Port 9100: Open

Scan completed.
```

## 📌 Notes

- Make sure you have permission to scan the network.  
- Use responsibly. This tool is meant for educational and security auditing purposes only.
