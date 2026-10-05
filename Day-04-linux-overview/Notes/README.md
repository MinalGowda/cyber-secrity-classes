# 📅 Day 4 — Linux Overview & OS Connectivity

## 🐧 Linux Overview

Linux is an **open-source, Unix-like operating system** widely used in servers, cloud computing, networking, cybersecurity, and embedded systems.

### Key Features of Linux

* Open source
* Multiuser
* Multitasking
* Secure and stable
* Highly customizable
* Powerful command-line interface
* Widely used in servers and cybersecurity

### Linux Architecture

```text
+----------------------+
|      Applications    |
+----------------------+
|        Shell         |
+----------------------+
|        Kernel        |
+----------------------+
|       Hardware       |
+----------------------+
```

### Kernel

The **kernel** is the core component of Linux. It manages:

* CPU
* Memory
* Processes
* Filesystems
* Devices
* Networking

### Shell

The shell provides an interface through which users interact with the operating system using commands.

Examples:

* Bash
* Zsh
* Fish

---

# 🌐 Connecting Different Operating Systems

Different operating systems can communicate with each other over a network using common networking protocols and remote-access technologies.

The operating systems covered were:

* Windows
* Linux
* macOS

---

## 🪟 Windows → Windows

Windows systems can connect to other Windows systems using technologies such as:

* **RDP (Remote Desktop Protocol)**
* SMB/File Sharing

Example:

```text
Windows PC
    ↓
   RDP
    ↓
Windows PC
```

RDP is commonly used for remotely accessing a Windows desktop.

---

## 🪟 Windows → 🐧 Linux

Windows can connect to Linux using:

* **SSH**
* RDP (when a Linux graphical remote-desktop server is configured)
* SFTP for file transfer

Example:

```text
Windows
   ↓
  SSH
   ↓
Linux
```

A commonly used SSH client on Windows is:

```bash
ssh username@ip-address
```

---

## 🪟 Windows → 🍎 macOS

Windows can connect to macOS using remote-access solutions such as:

* SSH
* Remote desktop software
* File sharing protocols

For SSH:

```bash
ssh username@ip-address
```

---

# 🐧 Linux → 🪟 Windows

Linux can connect to Windows using:

* RDP clients
* SMB
* SSH if an SSH server is enabled on Windows

Example:

```text
Linux
  ↓
 RDP
  ↓
Windows
```

---

# 🐧 Linux → 🐧 Linux

Linux systems commonly communicate using:

* SSH
* SCP
* SFTP
* NFS
* SMB

Example:

```bash
ssh username@ip-address
```

For copying files:

```bash
scp file.txt username@ip-address:/home/username/
```

---

# 🐧 Linux → 🍎 macOS

Linux can connect to macOS using:

* SSH
* SCP
* SFTP
* File-sharing protocols

Example:

```bash
ssh username@ip-address
```

---

# 🍎 macOS → 🪟 Windows

macOS can connect to Windows using:

* RDP
* SMB
* Other remote-access tools

---

# 🍎 macOS → 🐧 Linux

macOS can connect to Linux using:

* SSH
* SCP
* SFTP

Example:

```bash
ssh username@ip-address
```

---

# 🍎 macOS → 🍎 macOS

Mac systems can connect to each other using:

* SSH
* Screen Sharing
* File Sharing
* Remote Management

SSH example:

```bash
ssh username@ip-address
```

---

# 🔑 Important Protocols

| Protocol | Purpose                                                     |
| -------- | ----------------------------------------------------------- |
| **SSH**  | Secure remote command-line access                           |
| **RDP**  | Remote graphical access, commonly Windows                   |
| **SMB**  | File and printer sharing                                    |
| **SFTP** | Secure file transfer over SSH                               |
| **SCP**  | Securely copy files over SSH                                |
| **NFS**  | Network file sharing, commonly used with Unix/Linux systems |

---

# 🧩 OS Connectivity Matrix

| From ↓ / To → | Windows          | Linux            | macOS                |
| ------------- | ---------------- | ---------------- | -------------------- |
| **Windows**   | RDP / SMB        | SSH / SFTP       | SSH / File Sharing   |
| **Linux**     | RDP / SMB / SSH* | SSH / SCP / SFTP | SSH / SFTP           |
| **macOS**     | RDP / SMB        | SSH / SFTP       | SSH / Screen Sharing |

> `SSH*` on Windows requires an SSH server such as OpenSSH Server to be enabled.

---

# 🛡️ Cybersecurity Relevance

Understanding OS connectivity is important in cybersecurity because security professionals need to understand:

* Remote access
* Network protocols
* Authentication
* IP addresses
* Ports
* Secure file transfer
* Remote administration
* Access control
* Network security

For example, **SSH normally uses TCP port 22**, while **RDP normally uses TCP/UDP port 3389**.

---

## 📚 Learning Progress

* [x] Cybersecurity Fundamentals
* [x] Information Security
* [x] CIA Triad
* [x] Types of Cyber Attacks
* [x] Private IP vs Public IP
* [x] OSI Model
* [x] Booting Process
* [x] Linux Overview
* [x] Windows ↔ Windows Connectivity
* [x] Windows ↔ Linux Connectivity
* [x] Windows ↔ macOS Connectivity
* [x] Linux ↔ Linux Connectivity
* [x] Linux ↔ macOS Connectivity
* [x] macOS ↔ macOS Connectivity
* [ ] TCP/IP Model
* [ ] Networking Protocols
* [ ] Ports & Protocols
* [ ] Linux Security
