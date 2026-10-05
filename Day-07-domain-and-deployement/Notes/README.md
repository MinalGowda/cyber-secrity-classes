# 📅 Day 7/8 — Domain Registration & Portfolio Deployment

## 🌐 Domain Registration

I purchased a `.shop` domain from **BigRock** and configured it for my personal portfolio website.

### Domain

```text
minalgowda.shop
```

The domain was purchased and configured to point to my deployed website.

---

# ☁️ Amazon Linux Virtual Machine

I configured an **Amazon Linux virtual machine/server** and used it to deploy my portfolio website.

The server was accessed remotely using **SSH**.

Example:

```bash
ssh -i "key.pem" ec2-user@<PUBLIC-IP>
```

---

# 🚀 Portfolio Deployment

I deployed my portfolio website to the Amazon Linux server.

### Basic deployment workflow

```text
Local Portfolio Code
        ↓
Amazon Linux Server
        ↓
Web Server
        ↓
Public IP Address
        ↓
Domain DNS Configuration
        ↓
minalgowda.shop
        ↓
Portfolio Website
```

---

# 📂 File & Directory Commands Used

Some of the Linux commands used during deployment included:

```bash
pwd
ls
cd
mkdir
cp
mv
rm
```

These commands were used to navigate directories and manage website files on the Linux server.

---

# 🔑 Connecting to the Server

I used SSH to remotely access the Amazon Linux machine.

```bash
ssh -i "key.pem" ec2-user@<PUBLIC-IP>
```

Where:

* `ssh` → Secure Shell
* `-i` → Specifies the private key
* `key.pem` → SSH private key
* `ec2-user` → Amazon Linux user
* `<PUBLIC-IP>` → Public IP address of the server

---

# 📤 Uploading Website Files

Website files can be transferred from a local Windows machine to the Linux server using `scp`.

Example:

```powershell
scp -i "key.pem" -r .\html ec2-user@<PUBLIC-IP>:/home/ec2-user/
```

`scp` stands for **Secure Copy Protocol** and transfers files securely over SSH.

---

# 🌍 Domain & DNS Configuration

After deploying the website, the domain was configured to point toward the server's public IP address.

```text
Domain
   ↓
DNS
   ↓
Public IP
   ↓
Amazon Linux Server
   ↓
Web Server
   ↓
Portfolio
```

I also used DNS lookup commands to verify the domain configuration.

Example:

```bash
nslookup minalgowda.shop
```

---

# 🔍 Verifying the Server

I used Linux/networking commands to troubleshoot and verify the deployment.

Examples:

```bash
ip addr
```

Displays network interface and IP information.

```bash
ping <IP>
```

Tests network connectivity.

```bash
nslookup minalgowda.shop
```

Checks DNS resolution.

---

# 🛡️ Cybersecurity Relevance

This practical exercise helped me understand:

* Linux server administration
* SSH remote access
* Public IP addresses
* DNS
* Domain configuration
* File transfer using SCP
* Web server deployment
* Cloud/virtual machine deployment
* Basic server troubleshooting
* Remote system administration

---

# 🎯 Practical Outcome

Successfully deployed my personal portfolio website on an **Amazon Linux virtual machine** and configured my purchased `.shop` domain to access the website publicly.

```text
Local Machine
     ↓
SSH / SCP
     ↓
Amazon Linux VM
     ↓
Web Server
     ↓
Public IP
     ↓
DNS
     ↓
minalgowda.shop
     ↓
Portfolio Website
```

---

## 📚 Learning Progress

* [x] Cybersecurity Fundamentals
* [x] Information Security
* [x] CIA Triad
* [x] Types of Cyber Attacks
* [x] Private & Public IP
* [x] OSI Model
* [x] Booting Process
* [x] Linux Overview
* [x] OS Connectivity
* [x] Linux Navigation
* [x] Process Management
* [x] Domain Registration
* [x] Amazon Linux
* [x] SSH
* [x] SCP
* [x] DNS Configuration
* [x] Portfolio Deployment
* [ ] Linux Security
* [ ] Networking Security
* [ ] Security Tools
