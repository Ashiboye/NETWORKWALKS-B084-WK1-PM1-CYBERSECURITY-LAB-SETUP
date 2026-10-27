# NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP

## Week 1: Linux Lab Setup

### Overview
This repository documents my Week 1 cybersecurity lab setup as part of my NetworkWalks cybersecurity internship training. The task involved setting up a Linux environment using Kali Linux and Oracle VirtualBox on an Intel-based Mac.

### Objectives
- Download and extract the Kali Linux virtual machine image.
- Set up Kali Linux in Oracle VirtualBox.
- Configure the virtual machine to boot successfully.
- Troubleshoot installation and boot issues.
- Prepare a Linux environment for future cybersecurity practical exercises.

### Tools and Technologies
- **Operating System:** macOS (Intel)
- **Virtualization Software:** Oracle VirtualBox 7
- **Linux Distribution:** Kali Linux
- **Virtual Disk Format:** VDI (VirtualBox Disk Image)

### Lab Setup Process
1. Downloaded the prebuilt Kali Linux VirtualBox image.
2. Extracted the downloaded RAR archive to obtain the virtual disk.
3. Created a virtual machine in VirtualBox.
4. Attached the correct Kali Linux VDI file under the SATA storage controller.
5. Configured the boot order and processor settings.
6. Started the virtual machine and confirmed that Kali Linux booted successfully.

### Troubleshooting
**Issue:** "No bootable medium found"

**Cause:** VirtualBox was not using the correct virtual disk file.

**Solution:** I checked the storage settings, located the correct extracted VDI file, detached the incorrect disk attachment without deleting the file, and attached the correct 16.17 GB VDI under the SATA controller. I saved the settings and restarted the virtual machine.

**Result:** Kali Linux booted successfully.

### Learning Outcomes
Through this exercise, I gained practical experience in:
- Setting up a Linux virtual machine.
- Understanding virtual disks and SATA storage controllers.
- Configuring boot order in VirtualBox.
- Troubleshooting virtual machine boot errors.
- Building a Linux environment for cybersecurity learning.

### Conclusion
Successfully setting up Kali Linux provided me with a working environment for future cybersecurity labs. This exercise also taught me the importance of checking virtual disk attachments and configuration settings when troubleshooting boot issues.

<img width="1400" height="873" alt="Screenshot 2026-10-27 at 14 44 47" src="https://github.com/user-attachments/assets/7bd6707a-7049-4741-918f-c8196b77df2e" />
<img width="712" height="462" alt="Screenshot 2026-10-27 at 14 18 43" src="https://github.com/user-attachments/assets/d6d31172-8191-4784-b86a-9238e9399cae" />

### Author
Ashiboye Jeffery Amarh — NetworkWalks

**Repository:** `NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP`
