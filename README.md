# RISC-V SoC Tapeout Program – Tool Installation Guide  

This repository documents the installation steps for the tools required in the **RISC-V SoC Tapeout Program (VSD)**.  

---

## ✅ System Requirements  
Before proceeding, ensure your system meets the following requirements:  

- **RAM**: 6 GB or higher  
- **Disk Space**: 50 GB HDD/SSD  
- **OS**: Ubuntu 20.04 or higher  
- **CPU**: 4 vCPU  

---

## 🔧 Setting up Ubuntu Screen Resolution (VirtualBox Users)  
If your Ubuntu window does not fit the screen properly, run the following commands:  

```bash
sudo apt update
sudo apt install build-essential dkms linux-headers-$(uname -r)

cd /media/<username>/VBox_GAs_<version>/
./autorun.sh
