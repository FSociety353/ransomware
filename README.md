# simple-ransomware-in-python
Just a simple ransomware in python with a command and control server (C2) that is running flask
# Ransomware Setup & Execution Guide

## 📌 Prerequisites
Make sure you have Python 3 installed on Kali Linux. If not, install it using:

```bash
sudo apt update && sudo apt install python3 python3-pip python3-venv -y
```

---

## 🔥 Installing Required Libraries
To install all necessary dependencies, run:

```bash
pip install requests getmac colored pycryptodome
```

If you are using a **virtual environment** (recommended):

```bash
python3 -m venv myenv
source myenv/bin/activate
pip install requests getmac colored pycryptodome
```

---

## 🚀 Running the Ransomware Script
1. Navigate to the directory containing the script:

```bash
cd /home/kali/Desktop/ransomware/simple-ransomware-in-python-main/ransomware
```

2. Run the script:

```bash
python3 ransomware.py
```

If you want to specify a target directory for encryption:

```bash
python3 ransomware.py /home/kali/Desktop/insensitive-files
```

---

## ⚠️ Warning
- **Do not run this script on important files**, as they will be encrypted without recovery unless you have the decryption keys.
- Use in a **controlled environment** (such as a virtual machine) for testing.

---

### ❓ Need Help?
If you encounter any issues, feel free to ask! 🔥
