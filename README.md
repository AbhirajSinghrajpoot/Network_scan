# 🛡️ Network Port Scanner (GUI)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-00599C?style=for-the-badge)
![Networking](https://img.shields.io/badge/Networking-Sockets-FF6F00?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Reconnaissance-101010?style=for-the-badge&logo=security&logoColor=white)

Welcome to the **Network Port Scanner** repository! 

A fast, lightweight, and user-friendly reconnaissance tool built entirely in Python using `socket`, `threading`, and `tkinter`. This application allows you to map network perimeters by scanning a range of ports on any target IP or hostname to identify open services and potential vulnerabilities.

---

## ✨ Key Features

* ⚡ **Multi-threaded Scanning:** Built with Python's `threading` and `Semaphore` (max 500 concurrent workers) to scan hundreds of ports simultaneously, making reconnaissance extremely fast and efficient.
* 🖥️ **Real-time GUI:** A clean, responsive interface built with `tkinter`, featuring a live progress bar, elapsed time tracker, and real-time result appending.
* 🔍 **Service Identification:** Automatically maps common open port numbers to their respective protocols (e.g., `80 -> HTTP`, `443 -> HTTPS`, `22 -> SSH`, `3389 -> RDP`).
* 🛑 **Dynamic Control:** Ability to instantly halt an ongoing scan or clear the results buffer with a single click.
* 💾 **Export Results:** Save the list of identified open ports directly into a `.txt` file for documentation or further vulnerability analysis.
* 🌐 **Automatic DNS Resolution:** Seamlessly resolves hostnames (e.g., `google.com` or `scanme.nmap.org`) to their corresponding IPv4 addresses before initiating the scan.

---

## 🛠️ Tech Stack & Requirements

* **Language:** Python 3.x (Tested on Python 3.13)
* **Libraries:** No external `pip` installations required! This project utilizes standard, built-in Python libraries:
  * `socket` (Network connections)
  * `threading` & `queue` (Concurrency and thread-safe data handling)
  * `tkinter` (Graphical User Interface)
  * `time` & `sys`

---

## 🚀 Getting Started

### 1. Installation
Clone the repository to your local machine:
```bash
git clone [https://github.com/AbhirajSinghrajpoot/Network_scan.git](https://github.com/AbhirajSinghrajpoot/Network_scan.git)
cd Network_scan

```
### 2. Run the Application
Execute the Python script to launch the GUI:
```bash
python portscanergui.py

```
## 📖 How to Use
 1. **Target:** Enter the target IPv4 address (e.g., 127.0.0.1 or 192.168.1.1) or a domain name (e.g., scanme.nmap.org).
 2. **Start Port:** Enter the beginning of your scan range (Default: 1).
 3. **End Port:** Enter the end of your scan range (Default: 1024).
 4. **Action:** Click **"Start Scan"**. The GUI will display open ports in real-time.
 5. **Save:** Once completed, click **"Save Results"** to export the findings to a text file.
*(⚠️ Disclaimer: Only scan networks and IP addresses that you own or have explicit permission to test. Unauthorized port scanning can be considered illegal network probing.)*
## 👨‍💻 About the Developer
**Abhiraj Singh Rajpoot** | *Computer Science Engineering (IoT, Cybersecurity & Blockchain)*
I build applications like a developer and test them like a hacker. This project was built to apply core networking, socket programming, and concurrent processing concepts into a practical cybersecurity tool.
📫 **Let's Connect:**
 * **GitHub:** @AbhirajSinghrajpoot
 * **LinkedIn:** Abhiraj Singh Rajpoot
 * **Portfolio:** wizards-portfolio.vercel.app
