# 📅 Day 5 — Linux Navigation & Process Management

## 🐧 Linux Basic Navigation

On Day 5, I learned basic Linux navigation commands used to navigate through the filesystem and work with directories and files.

These commands can be used when working with a Linux system through an **SSH terminal**. PowerShell can also be used from Windows to establish an SSH connection to a Linux machine.

### 📂 Navigation Commands

| Command  | Description                                               |
| -------- | --------------------------------------------------------- |
| `pwd`    | Displays the current working directory                    |
| `ls`     | Lists files and directories                               |
| `ls -l`  | Displays detailed information about files and directories |
| `ls -a`  | Displays hidden files and directories                     |
| `ls -la` | Displays detailed information including hidden files      |
| `cd`     | Changes the current directory                             |
| `cd ..`  | Moves to the parent directory                             |
| `cd ~`   | Moves to the user's home directory                        |
| `cd /`   | Moves to the root directory                               |
| `clear`  | Clears the terminal screen                                |

### Example

```bash
pwd
ls
cd /home
ls -la
cd ..
pwd
```

---

# ⚙️ Process Management

A **process** is a program that is currently running.

Linux assigns each running process a unique **PID (Process ID)**.

### Process Management Commands

| Command   | Description                                           |
| --------- | ----------------------------------------------------- |
| `ps`      | Displays running processes                            |
| `ps aux`  | Displays detailed information about running processes |
| `ps -ef`  | Displays all processes in full format                 |
| `top`     | Monitors running processes in real time               |
| `htop`    | Interactive process monitoring tool                   |
| `pstree`  | Displays processes in a tree structure                |
| `pgrep`   | Finds the PID of a process by name                    |
| `pidof`   | Finds the PID of a running program                    |
| `kill`    | Sends a signal to a process                           |
| `kill -9` | Forcefully terminates a process                       |
| `pkill`   | Terminates processes based on their name              |
| `killall` | Terminates processes by name                          |
| `jobs`    | Displays jobs running in the current shell            |
| `fg`      | Brings a background job to the foreground             |
| `bg`      | Continues a stopped job in the background             |
| `nice`    | Starts a process with a specified priority            |
| `renice`  | Changes the priority of an existing process           |

### Example

```bash
ps
```

```bash
ps aux
```

```bash
top
```

```bash
pgrep nginx
```

```bash
kill 1234
```

```bash
kill -9 1234
```

---

# 🔐 SSH & Terminal

Linux commands can be executed remotely by connecting to a Linux machine through **SSH (Secure Shell)**.

Example:

```bash
ssh username@ip-address
```

After connecting, commands such as:

```bash
pwd
ls
cd
ps
top
```

can be executed on the remote Linux system.

---

# 🛡️ Cybersecurity Relevance

Linux navigation and process management are important cybersecurity skills because security professionals need to:

* Navigate Linux systems
* Access remote systems securely
* Identify running processes
* Monitor system activity
* Investigate suspicious processes
* Terminate unwanted processes
* Understand system behavior

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
* [x] OS Connectivity
* [x] Linux Navigation Commands
* [x] SSH Basics
* [x] Process Management
* [ ] File Management
* [ ] File Permissions
* [ ] User & Group Management
* [ ] Networking Commands
* [ ] Linux Security
* [ ] Shell Scripting
