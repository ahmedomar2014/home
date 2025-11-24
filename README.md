# AOSP

## Latest Projects

### FTPChat (File Transfer Chatting Project)

**Encrypted FTP-Based Messaging Protocol**  
**Version 1.4 — November 2025**  
**Author:** Ahmed Omar Saad  
**Contact:** <ahmedomardev@outlook.com>  

FTPChat © 2025/5/20 by Ahmed Omar Saad is licensed under **CC BY-NC-SA 4.0**.  
To view a copy of this license, visit <https://creativecommons.org/licenses/by-nc-sa/4.0/>  

---

#### Overview

FTPChat is a lightweight, encrypted messaging protocol implemented entirely in Python.  
It facilitates secure communication by reading and writing messages to a shared file hosted on an FTP server.  

FTPChat is specifically designed for deployment in legacy environments, including low-power routers equipped with USB and FTP capabilities. This makes it an ideal solution for resource-constrained scenarios or discreet operations.

---

#### Key Features (v1.4)

- 24-layer encryption ensuring robust payload security  
- File-based transport mechanism utilizing FTP/FTPS fallback  
- Single `.py` file deployment for simplicity  
- Optimized for legacy hardware and low-power devices  
- International chatting via [SFTPCloud Tool](https://sftpcloud.io/tools/free-ftp-server)  
- Local LAN support with `Documentation/Quick Start Guide (Making FTP Server).md`  
- Threaded send/receive — no UI freezing during FTP operations  
- Auto-refresh loop with restart-safe scheduling  
- Modern UI with ttkbootstrap (dark theme, styled buttons)  
- Blue primary buttons for clarity and aesthetics  
- Non-editable chat history with scrollable view  
- Modular encryption pipeline (easy to extend with new ciphers)  

---

#### New Features Added in v1.4

- Threaded FTP I/O: Both sending and reading run in background threads for smooth, non-blocking UI  
- Improved Error Handling: Clear fallbacks between FTP_TLS and FTP, with user-friendly error messages  
- Styled UI Elements: Buttons themed with ttkbootstrap’s `primary` style for a modern look  
- Auto-Scroll Chat Window: Messages always scroll to the latest entry  
- Help Menu Integration: Direct link to project documentation and exit option  
- Restart-Safe Loop Control: Auto-refresh loop can be started once and remains stable  
- Encryption Pipeline Refactor: Doubled 12-layer MAC encryption plus compression for symbolic resilience  

---

#### Protocol Operation

Messages are exchanged via a shared file on an FTP server.  
Each message contains a timestamp, username, and encrypted content.  

The protocol provides:
- Conflict-safe message writing  
- Encrypted message formatting  
- Lightweight, file-based communication  

---

#### Usage Instructions

1. Download `FtpChat.exe` for Windows 10/11, or run the Python script on macOS/Linux.  
2. Activate your FTP server. Refer to `Documentation/Quick Start Guide (Making FTP Server).md`.  
3. Enter your credentials as prompted.  
4. Review the `Notes Before Starting` section prior to use.  

---

#### License

FTPChat is distributed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.  
Commercial use is strictly prohibited without written permission from the author.  
All rights to the name “FTPChat” and its protocol specification are reserved by Ahmed Omar Saad.

---

#### Tlock (Text Locker Encryption Protocol)

**Secure Text & File Protection Software**  
**Version 1.8 — November 2025**  
**Author:** Ahmed Omar Saad  
**Contact:** <ahmedomardev@outlook.com>  

---

#### Overview

Tlock is a desktop application designed to protect text, files, and code with a simple, accessible interface.  
It combines modern usability features with strong protection, making it suitable for personal projects, education, and professional use.

---

#### Key Features (v1.8)

- Save and open protected text files (`.tetf`)  
- Encrypt and decrypt any file (`.tlock`)  
- Built‑in Python & JavaScript IDEs with secure save/load (`.tpy`, `.tjs`)  
- Accessibility tools: microphone input (speech‑to‑text) and text‑to‑speech  
- Fullscreen GUI with menus for text, files, and code  
- File compression for reduced file sizes  

---

#### Installation

**Option 1: Portable Executable**  
Download and run `tlock.exe` (portable version) from [here](https://github.com/ahmedomar2014/Tlock/blob/main/Exe/Tlock.exe).

**Option 2: Setup Executable**  
Download and install `tlock.exe` (setup version) from [here](https://github.com/ahmedomar2014/Tlock/blob/main/Exe/setup/Output/tlock-1.7-amd64.exe).

---

#### Usage

**Text Files**  
- Save protected text → `.tetf`  
- Open protected text → requires the key  

**Files**  
- Encrypt any file → `.tlock`  
- Decrypt with the key  

**Code IDEs**  
- Save/load protected Python (`.tpy`) or JavaScript (`.tjs`) files  
- Run code directly inside the IDE  

**Accessibility**  
- Microphone Writer → speech recognition  
- Text‑to‑Speech → listen to decrypted content  

---

### File Types

| Extension | Purpose                   |
| --------- | ------------------------- |
| `.tetf`   | Protected text files      |
| `.tlock`  | Protected binary files    |
| `.tpy`    | Protected Python code     |
| `.tjs`    | Protected JavaScript code |

---

#### License

Tlock is distributed under a **custom MIT‑style license**.  

- Free for personal and educational use.  
- **Commercial use requires prior written permission from the author.**  
- **The author reserves the right to relicense this software as closed‑source or commercial at any time.**  
- All rights to the name “Tlock” and its protocol specification are retained by Ahmed Omar Saad.  

**FTPChat  © 2023/8/20 by Ahmed Omar Saad is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/**

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Notes:  
The author may offer separate commercial licenses for enterprise or closed‑source use. Contact <ahmedomardev@outlook.com> for inquiries.  
This license applies to all source code, documentation, and project specifications included in the Tlock project.  
Further details in [`LICENSE`](https://github.com/ahmedomar2014/Tlock/blob/main/LICENSE).

---

## Releases

- **FTPChat v1.5 — November 2025**
  - Threaded FTP I/O, restart‑safe auto‑refresh, ttkbootstrap UI
- **Tlock v1.8 — November 2025**
  - 48‑layer encryption, multi‑format support, accessibility tools

---

## Packages

### FTPChat
- **Windows executable**: [Download from Releases](https://github.com/ahmedomar2014/FTPChat/releases)
- **Python source**: [View on GitHub](https://github.com/ahmedomar2014/FTPChat)

### Tlock
- **Windows executable**: [Download from Releases](https://github.com/ahmedomar2014/Tlock/releases)
- **Python source**: [View on GitHub](https://github.com/ahmedomar2014/Tlock)

---

## Deployments

### FTPChat
- Local LAN setup guide: `Documentation/Quick Start Guide (Making FTP Server).md`
- Global deployment via [SFTPCloud Tool](https://sftpcloud.io/tools/free-ftp-server)

### Tlock
- Desktop deployment: Windows 10/11 (portable and setup executables)
- Planned: Linux/macOS builds

---

## Contact

- Phone: +201040946638  
- Email: [ahmedomardev@outlook.com](mailto:ahmedomardev@outlook.com)  