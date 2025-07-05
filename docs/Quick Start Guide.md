# Quick Start Guide for FTPChat


This document outlines the procedure for configuring a home router with a USB interface as an FTP server. The recommended model for this setup is the **D-Link Dual Band Wireless AC1200 VDSL Modem Router (DSL-245GE)** due to its robust feature set and reliable performance.

---

## 📡 Recommended Hardware

### D-Link DSL-245GE – Key Features

- Dual-band wireless connectivity with AC1200 throughput
- Integrated VDSL modem functionality
- USB 2.0 port supporting external storage devices
- Native support for FTP and Samba services
- User-friendly configuration interface

---

## 📝 Prerequisites

To proceed with the configuration, ensure the following components are available:

- ✅ D-Link DSL-245GE Router (or any compatible router supporting FTP and USB storage)
- ✅ External storage device (USB flash drive or external HDD/SSD), formatted using NTFS or FAT32
- ✅ Computer connected to the router's local area network (LAN)

---

## ⚙️ Configuration Procedure

### Step 1: Connect USB Storage Device

- Insert the USB storage device into the router’s designated USB port
- Confirm device detection via the router’s management interface

### Step 2: Access Web Interface

- Open a browser and navigate to `192.168.1.1` or the assigned local IP
- Authenticate using administrative credentials

### Step 3: Activate FTP Functionality

- Navigate to: **USB Settings** → **FTP Server**
- Enable the **FTP Server** toggle
- Configure the following parameters:
  - Directory Path: `/usb1_1/` (depending on router’s storage mapping)
  - Authentication: Enable login protection
  - FTP Port: `21` (default)
  - Access Mode: LAN only or WAN if external connectivity is required

### Step 4: Manage User Access

- Create user profiles with individual credentials
- Define read/write permissions per user
- Save and apply configuration settings

### Step 5: Validate FTP Connectivity

- Launch an FTP client (e.g., FileZilla) or access via browser or windows file explorer and try copying file in the 
directory that starts with `usb`

## 🔍 Troubleshooting and Optimization

- USB formatting should use **NTFS** for large file handling
- Restart the router if USB storage is not recognized
- Verify router firewall permissions for FTP traffic
- Utilize strong, secure passwords for all user accounts

---

## 🎯 Applications

- Internal file sharing across LAN-connected devices
- Remote access to personal media or documents
- Localized backup and storage solutions

---

## 📘 Additional Considerations

While this guide emphasizes the DSL-245GE model, similar procedures are applicable across various USB-capable routers with embedded FTP server functionality.

---

_This quick start guide makes efficient file distribution and personal cloud access using residential network infrastructure._

## 🌐 Links
D-Link Dual Band Wireless AC1200 VDSL Modem Router (DSL-245GE) : [Buying Link](https://www.amazon.eg/-/en/D-Link-Wireless-AC1200-Router-DSL-245GE/dp/B09MMSPJDG/ref=sr_1_4?crid=3XTKMTQA9D0&dib=eyJ2IjoiMSJ9.gC1n6l6fG5VEj-PJ7XiMYBCuOoa7V2imJRvZt5wcZyWXZvF_t3V38mFCGqKRA94kFSKWblX6ogHhmsGRXfgZSE8IjPVknLAIMD_LJEIqC3Zg8bPdxwEMTe13y2xWH5UnO5wtsgWr_g0bdXdQI5RzNLKCK8ZxRCPuBFQpz2Y1HrICozflX_vIxBmFNL_FGuMZIS264PnCKNgF59OmKvk9-IqXT0KVy6D2jdS4ML0S5lAXbqGOHXCQEnrQqDZDyp3nNshi8D48c-qSLQg-XOUR82GuLMnUo1bUo5IIJIkonLE.Odk0kZZAEdLwOAYO6iqW7HDuQZqSBtcaNnqRA2pmw_o&dib_tag=se&keywords=dlink&qid=1751670760&sprefix=dlink%2Caps%2C280&sr=8-4)
