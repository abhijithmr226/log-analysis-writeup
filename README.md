# Portable Log Analysis Tool for Isolated Networks

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%20|%20Linux%20|%20Mac-lightgrey)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

---

## **Project Overview**
Continuous monitoring of systems and networks is crucial to detect, prevent, and respond to cybersecurity threats.  
While Security Operation Centers (SOC) monitor networks in real-time, isolated networks require portable, self-contained tools for offline log collection, analysis, and reporting.

This project aims to build a **portable log analysis tool** for isolated networks with the following key features:

- **Cross-platform portability** (Windows, Linux, Mac)
- **Multi-source log collection** (Syslog, Event Logs, USB devices, network traffic)
- **Log parsing and normalization**
- **Anomaly & threat detection**
- **Offline web-based dashboard**
- **Secure encryption & authentication**
- **Reporting and export capabilities**

---

## **1. Programming Language**
[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)

**Purpose:** Core language for scripting, automation, and cross-platform execution.  

**Key Modules:**  
`os`, `subprocess`, `hashlib`, `sqlite3`, `logging`  

**Reference:** [Python Docs](https://docs.python.org/3/)

---

## **2. Log Collection & Parsing**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `syslog-ng` | Capture Syslog logs from network devices | ![Syslog](https://img.shields.io/badge/Syslog-NG-orange) [Docs](https://www.syslog-ng.com/technical-documents) |
| `pywin32` | Parse Windows Event Logs | ![Windows](https://img.shields.io/badge/Windows-WinEvent-blue) [GitHub](https://github.com/mhammond/pywin32) |
| `pyudev` | Access USB / Peripheral logs on Linux | ![Linux](https://img.shields.io/badge/Linux-USB-red) [Docs](https://pyudev.readthedocs.io/) |
| `scapy` | Capture & analyze network traffic | ![Scapy](https://img.shields.io/badge/Scapy-Network-green) [Docs](https://scapy.net/) |

---

## **3. Log Normalization & Analysis**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `pandas` | Structure and analyze logs | ![Pandas](https://img.shields.io/badge/Pandas-Data-blue) [Docs](https://pandas.pydata.org/) |
| `pyod` | Detect anomalies & outliers | ![PyOD](https://img.shields.io/badge/PyOD-Anomaly-orange) [Docs](https://pyod.readthedocs.io/) |
| `scikit-learn` | Machine learning-based analysis | ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-lightgrey) [Docs](https://scikit-learn.org/stable/) |

---

## **4. Threat Detection & Intelligence**
| Framework / Method | Purpose | Logo / Link |
|-------------------|---------|-------------|
| MITRE ATT&CK | Map logs to known TTPs for attacks | ![MITRE](https://img.shields.io/badge/MITRE-ATT&CK-red) [Docs](https://attack.mitre.org/) |
| Rule-based / Heuristic Analysis | Custom detection using signatures & behavior | ![Rules](https://img.shields.io/badge/Rules-Detection-yellow) N/A |

---

## **5. User Interface & Visualization**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `Flask` | Offline web-based dashboard | ![Flask](https://img.shields.io/badge/Flask-Web-grey) [Docs](https://flask.palletsprojects.com/) |
| `Matplotlib` / `Plotly` | Charts & log visualization | ![Plotly](https://img.shields.io/badge/Plotly-Charts-purple) [Docs](https://plotly.com/python/) |

---

## **6. Offline Security & Encryption**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `cryptography` | AES encryption of logs | ![Crypto](https://img.shields.io/badge/Cryptography-Secure-blue) [Docs](https://cryptography.io/) |
| `Flask-Login` | User authentication for access control | ![Auth](https://img.shields.io/badge/Flask-Login-orange) [Docs](https://flask-login.readthedocs.io/) |

---

## **7. Reporting & Export**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `ReportLab` / `FPDF` | Generate PDF reports | ![PDF](https://img.shields.io/badge/Report-PDF-red) [ReportLab](https://www.reportlab.com/) |
| `pandas` | Export CSV / Excel files | ![CSV](https://img.shields.io/badge/Export-CSV-blue) [Docs](https://pandas.pydata.org/) |

---

## **8. Cross-platform Portability**
| Tool / Library | Purpose | Logo / Link |
|----------------|---------|-------------|
| `PyInstaller` / `cx_Freeze` | Package Python scripts as executables | ![PyInstaller](https://img.shields.io/badge/PyInstaller-Package-green) [Docs](https://pyinstaller.org/) |

---

## **9. Research & Case Studies**
- **YouTube Tutorials:**  
  - *Offline Log Analysis Tool Using Python*  
  - *Syslog Monitoring & Visualization with Python*  
  - *Detecting Network Anomalies using PyOD*  
- **GitHub Repositories:** Python-based log analyzers for isolated networks  
- **Articles / Blogs:** Medium tutorials on log analysis, network security, and offline SOC tools  

---

## **10. Conclusion**
The portable log analysis tool leverages Python and its rich ecosystem to create a **fully functional, offline, and cross-platform solution** for isolated networks. Key features include multi-source log collection, parsing, anomaly detection, secure storage, offline visualization, and reporting.

---

### **Badges / Shields Legend**
- ![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white) Python version  
- ![License](https://img.shields.io/badge/License-MIT-green) License type  
- ![Platform](https://img.shields.io/badge/Platform-Windows%20|%20Linux%20|%20Mac-lightgrey) Supported platforms  
- ![Status](https://img.shields.io/badge/Status-Active-brightgreen) Project status  

---

