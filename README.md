# AOSP

## _Latest Projects:_

### **FTPChat (File Transfer Chatting Project)**

#### **Overview:**

FTPChat is a lightweight, encrypted messaging protocol implemented entirely in Python.  
It facilitates secure communication by reading and writing messages to a shared file hosted on an FTP server.

FTPChat is specifically designed for deployment in legacy environments, including low-power routers equipped with USB and FTP capabilities. This makes it an ideal solution for resource-constrained scenarios or discreet operations.

#### **Key Features:**

- 24-layer encryption ensuring robust payload security
- File-based transport mechanism utilizing FTP
- Fully operational within a single `.py` file
- Optimized for legacy hardware and low-power devices
- Compatible with routers supporting USB and FTP
- Energy-efficient and environmentally conscious design
- You can also chat internationally (Non LAN) by using [SFTPCloud Tool](https://sftpcloud.io/tools/free-ftp-server) a free tool that you can make a globally accessible FTP server
- You can also make it work locally by using our guide `Documentation/Quick Start Guide (Making FTP Server).md`

#### **Protocol Operation:**

Messages are exchanged via a shared file on an FTP server.  
Each message contains a timestamp, username, and encrypted content.  
The protocol provides:

- Conflict-safe message writing
- Encrypted message formatting
- Lightweight, file-based communication

**Note:** FTPChat does not support auto-refresh or background polling.

#### **Usage Instructions:**

1. Download `FtpChat.exe` for Windows 10/11, or run the Python script on macOS or Linux.
2. Activate your FTP server. Refer to `Documentation/Quick Start Guide (Making FTP Server).md` for detailed setup instructions.
3. Enter your credentials as prompted.
4. Please review the `Notes Before Starting` section prior to use.

#### **License:**

FTPChat is distributed under a custom MIT-style license.  
Commercial use is strictly prohibited without written permission from the author.  
All rights to the name “FTPChat” and its protocol specification are reserved by Ahmed Omar Saad.

For full license details, refer to the `LICENSE

You can find its source code in this repository: https://github.com/ahmedomar2014/FTPChat, But don't forget to read the license😉.

---

### **Tlock (Text Locker Encryption Protocol)**

**Multi-Format Encryption System**  
**Version 1.8 — October 2025**  
**Author:** Ahmed Omar Saad  
**Contact:** ahmedomardev@outlook.com

---

#### **Overview:**

Tlock is a multi-layered encryption protocol designed to secure text, media, and document files with extreme depth and modularity.  
Built entirely in Python, it supports GUI-based workflows, password protection, and clipboard automation for fast and secure file handling.

Tlock is optimized for environments that need security, offline workflows.

---

#### **Key Features:**

- 48-layer encryption cycle
- Supports text, image, audio, video, document, presentation, and spreadsheet formats
- GUI interface with password prompts and text-to-speech
- Clipboard integration for key delivery
- Threading and multiprocessing support
- Fully operational within a single `.py` file

---

#### **Supported File Types (GUI Menu):**

| File Type       | Extension | Menu Label       |
| --------------- | --------- | ---------------- |
| Text            | `.tetf`   | Text Files       |
| Image           | `.teif`   | Image Files      |
| Audio           | `.teaf`   | Audio Files      |
| Video           | `.tevf`   | Video Files      |
| Word Document   | `.tedf`   | Word Files       |
| PowerPoint      | `.teppf`  | Powerpoint Files |
| Excel Sheet     | `.teef`   | Excel Files      |
| Access Database | `.teadf`  | Access Files     |
| Publisher File  | `.tempf`  | Publisher Files  |
| OneNote File    | `.temof`  | OneNote Files    |
| PDF Document    | `.tepf`   | PDF Files        |
| Zip Archive     | `.tezf`   | Zip Files        |

---

#### **Usage Instructions:**

**🔐 To Encrypt Files**:

1. Run `Tlock.exe` on Windows.
2. Choose the file type you wish to encrypt.
3. A key will be generated and auto-copied for later access for the file.
4. The encrypted file will be saved with a `.te*` extension.

**🔓 To Decrypt Files**:

1. Run `Tlock.exe` on Windows.
2. Choose the file type you wish to decrypt.
3. Enter the decryption key that was auto-copied.
4. The decrypted file will be restored to its original format (e.g., `.txt`, `.jpg`, `.mp3`, `.docx`, etc.).
5. You can view or play the decrypted content immediately after recovery.

**🔐 To Encrypt Text Files**:

1. Run `Tlock.exe` on Windows.
2. Navigate to the **Text Files** menu and select **Save a Tetf**.
3. Type or paste your text into the input field.
4. Enter a password when prompted.
5. Save the encrypted file when prompted. It will be saved with a `.tetf` extension.

**🔓 To Decrypt Text Files**:

1. Run `Tlock.exe` on Windows.
2. Navigate to the **Text Files** menu and select **Open a Tetf**.
3. Choose the `.tetf` file you wish to decrypt.
4. Enter the correct password when prompted.
5. The decrypted content will be displayed in a new window.
6. You can optionally activate **Text to Speech** to read the content aloud, but it needs network connection.

---

#### **Performance Benchmark:**

- Encrypted approximately 100,000 characters under full 48-layer mode
- Tested on:

  - **Intel Core i5-13420H**, RTX 2050 GPU, 16GB RAM DDR5

    - Result: ~30 seconds

  - **Intel Core i7-8650U**, Intel UHD 620, 16GB RAM DDR3
    - Result: ~1 minute 30 seconds

- Environment: Windows 11, Python 3.13
- Result: The program performs faster on higher-end CPUs
- Note: Less size = Faster speeds and vice versa

---

#### **License:**

Tlock is distributed under a custom MIT-style license.  
Commercial use requires prior written permission from the author.  
All rights to the name “Tlock” and its protocol specification are reserved by Ahmed Omar Saad.

For full license details, refer to the `LICENSE` file.

---

Source code: [github.com/ahmedomar2014/Tlock](https://github.com/ahmedomar2014/Tlock), But don't forget to read the license😉.

---

## **Keep In Touch!**

You can get help or a business inquiry by contacting me by these ways:

- Phone Number: +201040946638
- Email: ahmedomardev@outlook.com
- Alt Email: ahmedomarhuawei@gmail.com
