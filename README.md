# PVGUARD - Change Login Background

![Version](https://img.shields.io/badge/version-1.0%20%7C%202.0-brightgreen)
![Python](https://img.shields.io/badge/python-3.x-blue)
![Platform](https://img.shields.io/badge/platform-Kali%20Linux-black)
![GUI](https://img.shields.io/badge/v2.0-GUI%20Tkinter-green)
![License](https://img.shields.io/badge/license-MIT-green)

## Description

**PVGUARD - Change Login Background** is a Python tool designed to change the Kali Linux login background.

The project includes two versions:

- **v1.0**: initial command-line version.
- **v2.0**: improved GUI version with backup, restore, privilege elevation, image preview, and Dark Hacker Edition interface.

---

## Versions

### PVGUARD v1.0

The first version works from the terminal and changes the Kali Linux login background by passing the image path as an argument.

Main features:

- CLI-based execution.
- Simple image replacement.
- Requires privileged execution.
- Lightweight and direct.

Example:

<img width="529" height="405" alt="image" src="https://github.com/user-attachments/assets/9aa4a40e-d987-4d45-b706-8f306858a3ae" />

---

### PVGUARD v2.0

The second version includes a graphical interface and several improvements.

Main features:

-Python GUI built with Tkinter.
-Image picker from the file explorer.
-thumbnail preview.
-Automatic backup of the current login background.
-Restore option for the previous background.
-Automatic privilege elevation using pkexec.
-No need to manually run the tool with sudo.
-GUI and CLI support.
-Responsive layout with vertical and horizontal scrollbars.
-Visual fixes and stability improvements.
-Spanish and English version.

Example:

Version Spanish

<img width="1034" height="751" alt="image" src="https://github.com/user-attachments/assets/bdca8af6-5ea9-4a1e-9875-cdcc760bf8c4" />

Version English

<img width="1028" height="757" alt="image" src="https://github.com/user-attachments/assets/0770fb40-142f-4e5c-bd9f-6c78dc86a8ac" />

---
## Installation

Clone the repository:

```bash
git clone https://github.com/joepm21/change-login-background.git
cd change-login-background
```

Install requirements:

```bash
pip install -r requirements.txt
```

---

## Author

Gh0s7m4n 

---

## Disclaimer

This tool modifies system theme files related to the Kali Linux login screen. Use it responsibly and keep backups before applying changes.

---

## License

This project can be distributed under the MIT License.
