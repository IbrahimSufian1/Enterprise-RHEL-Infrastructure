# Enterprise Linux System Rebuild & Storage Optimization

## 📌 Project Overview
This project demonstrates a comprehensive infrastructure rebuild using **Red Hat Enterprise Linux (RHEL 9)**. The primary focus was on system initialization, advanced storage management, and security hardening in a simulated enterprise environment.

## 🛠 Technologies Used
* **OS:** Red Hat Enterprise Linux 9 (RHEL 9)
* **Storage:** LVM (Logical Volume Manager), VDO (Virtual Data Optimizer)
* **Automation:** Kickstart (Automated Installation), Bash Scripting
* **Security:** SSH Hardening, User Permission Management

## 🚀 Key Implementations

### 1. Automated Deployment
* Utilized **Kickstart** files to automate the OS installation process, ensuring consistent configuration across environments.
* Partitioned disks efficiently during the boot process.

### 2. Advanced Storage Management (LVM & VDO)
* Implemented **LVM** to manage physical and logical volumes dynamically.
* Configured **VDO (Virtual Data Optimizer)** to apply inline data deduplication and compression, significantly optimizing storage efficiency.
* **Achievement:** Reduced storage footprint for redundant data blocks.

### 3. System Hardening & Security
* Configured **SSH Key-Based Authentication** and disabled root login for enhanced security.
* Implemented strict user and group permissions (`finance`, `admin` groups) to enforce least-privilege access control.

### 4. Data Persistence & Migration
* Configured `/etc/fstab` to ensure persistent mounting of logical volumes after reboots.
* Executed data migration strategies to move critical data to optimized VDO volumes.

## 📸 Screenshots

<img width="544" height="102" alt="Picture1" src="https://github.com/user-attachments/assets/0395476b-4550-4389-af30-39aec51ecf33" />

---
*This project was part of the DevOps Bootcamp Capstone at Al Hussein Technical University (HTU).*
