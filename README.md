# System Forensics Project

Author: Safa Muhammad Ali  
Course: CSEC 140.602 – System Forensics  
Institution: Rochester Institute of Technology Dubai  
 

---

## Project Overview

This project demonstrates practical skills in system forensics, including:

- Forensically copying files and verifying integrity.
- Forensic deletion of files to prevent recovery.
- Extracting and analyzing volatile memory (RAM) to retrieve sensitive data.
- Imaging and analyzing USB drives for evidence preservation.
- Detecting suspicious USB devices using USBDeview.

This submission is designed to validate practical cybersecurity capabilities and document the workflow for professional reference.

---

## Project Workflow

### 1. Forensically Copying Files
- **Tools used:** `dd` command on Linux
- **Purpose:** Demonstrates byte-by-byte file copying to maintain integrity and metadata.
- **Screenshot:** `screenshots/file_copy_cp_dd.png`  

### 2. Forensic Deletion of Files
- **Tools used:** `dd` with `/dev/zero`, `xxd` for binary view
- **Purpose:** Ensures deleted files cannot be recovered.
- **Screenshot:** `screenshots/forensic_deletion.png`  

### 3. RAM Analysis (Volatile Memory)
- **Tools used:** LiME, grep
- **Purpose:** Extract sensitive information from RAM before it is lost on power-off.
- **Screenshot:** `screenshots/ram_dump.png`  

### 4. USB Imaging and Forensics
- **Tools used:** FTK Imager
- **Purpose:** Create forensic images of USB drives to recover hidden or deleted files.
- **Screenshot:** `screenshots/usb_ftk_imager.png`  

### 5. Detecting Suspicious USB Devices
- **Tools used:** USBDeview
- **Purpose:** Identify USB devices with unusual properties for potential security risks.
- **Screenshot:** `screenshots/suspicious_usb_devices.png`  

---

## Results & Key Findings

- Forensic copying ensures **data integrity** using `dd` vs `cp`.
- Files deleted with `/dev/zero` cannot be recovered, demonstrating **forensic deletion**.
- RAM extraction revealed sensitive plain-text passwords, highlighting **importance of volatile memory acquisition**.
- USB imaging and analysis recovered files, including previously hidden or deleted data.
- Suspicious USB devices were detected based on **unrecognized VID/PID and anomalous patterns**.

---

## Conclusion

This project demonstrates core practical capabilities in system forensics, focusing on integrity, evidence preservation, and analysis. These workflows validate current skills and prepare for deeper specialization in cybersecurity.

---
