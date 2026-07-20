# NetScan
Network Scanner for Online Machines in Python
# 🛰️ NetScan

**NetScan** is a lightweight Python-based network scanner that discovers active hosts on a local network using ICMP (Ping). It automatically detects the local network or allows users to specify a custom network in CIDR notation.

---

## 📖 Overview

NetScan is designed to help users quickly identify active devices on a network. It performs parallel ping scanning using multithreading, making the scanning process fast and efficient.

This project was developed to demonstrate networking concepts, Python programming, and concurrent execution.

---

## ✨ Features

-  Automatically detects the local network
-  Scan custom networks using CIDR notation
-  Fast multithreaded host discovery
-  Cross-platform support (Windows, Linux, and macOS)
-  Displays active hosts on the network
-  Simple command-line interface
-  Built-in help menu

---

## 🛠️ Technologies Used

- Python 3
- socket
- ipaddress
- concurrent.futures
- subprocess
- platform
- re
- os

---

## 📂 Project Structure

```
NetScan/
│── netscan.py
│── README.md
│── LICENSE
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/kalirayees/NetScan.git
```

Navigate to the project directory:

```bash
cd NetScan
```

No external dependencies are required.

---

## 🚀 Usage

### Scan the current local network

```bash
python3 netscan.py
```

### Scan a specific network

```bash
python3 netscan.py 192.168.1.0/24
```

### Scan using a partial network

```bash
python3 netscan.py 192.168.1
```

### Display help

```bash
python3 netscan.py --help
```

---

## 📷 Sample Output

```
NETSCAN

Welcome to NetScan, a Network Scanner.

Scanning network: 192.168.1.0/24

Online hosts:

192.168.1.1
192.168.1.5
192.168.1.10
192.168.1.20
```

---

##  How It Works

1. Detects the local IP address and subnet mask.
2. Converts the subnet mask into CIDR notation.
3. Generates all available host IP addresses.
4. Uses multithreading to ping each host simultaneously.
5. Displays all devices that respond.

---

## 📌 Supported Platforms

- ✅ Windows
- ✅ Linux
- ✅ macOS

---

##  Future Improvements

- Port Scanning
- Hostname Resolution
- MAC Address Detection
- Vendor Identification
- Export Results to CSV or JSON
- Progress Bar
- Colored Terminal Output
- Network Service Detection
- GUI Version using Tkinter or PyQt

---

##  Contributing

Contributions are welcome!

If you would like to improve NetScan:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the Apache 2 License.

---

##  Author

** Ahad Rayees **

B.Tech Computer Science & Information Technology (Cyber Security)

GitHub: https://github.com/kalirayees

---

⭐ If you found this project useful, consider giving it a star on GitHub!
