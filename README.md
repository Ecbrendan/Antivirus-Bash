# Antivirus&Bash
## 📌 Overview of Tasks

1. ✅ Create an antivirus test file using the EICAR standard
2. ✅ Write a Bash script to shut down a Linux system
3. ✅ Install Kali Linux inside a VMware virtual machine
4. ✅ Share the experience in a professional LinkedIn post


## 1️⃣ EICAR Test File – Antivirus Testing

### 🔍 Description:
The [EICAR test string](https://www.eicar.org/?page_id=3950) is a harmless file designed to test the response of antivirus software.

### 📄 File: [`eicar_test_file.txt`](./eicar_test_file.txt)
This file is a `.txt` version of the standard `eicar.com` test file to avoid automatic antivirus flags or GitHub restrictions.

### 🧪 How to Test:
1. Copy and paste this string into a text editor:
X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*

2. Save as `eicar.com`
3. Your antivirus should immediately detect and quarantine it

### 📸 Screenshot:
![EICAR Detection](screenshots/EICAR detection.jpg)

---

## 2️⃣ Bash Script – Power Off System

### 📜 File: [`shutdown.sh`](./shutdown.sh)
A basic Bash script that powers off the system.

#!/bin/bash
# shutdown.sh
# A basic script to shut down the system using the 'poweroff' command.
# Note: Requires sudo privileges.

echo "Shutting down system in 60s!!!..."
sudo shutdown

▶️ How to Use:
Open terminal in Linux

Create file:
nano shutdown.sh

Paste the script and save (Ctrl + O, then Ctrl + X)
Make it executable:

chmod +x shutdown.sh
Run it:

./shutdown.sh
