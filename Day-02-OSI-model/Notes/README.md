# 📅 Day 2 — IP Addresses & OSI Model

## 🌐 Private IP vs Public IP

An **IP address (Internet Protocol address)** is a numerical address used to identify a device on a network and enable communication.

### 🔒 Private IP Address

A private IP address is used for communication **within a local/private network**.

Common private IPv4 ranges:

| Range   | Private Range                   |
| ------- | ------------------------------- |
| Class A | `10.0.0.0 – 10.255.255.255`     |
| Class B | `172.16.0.0 – 172.31.255.255`   |
| Class C | `192.168.0.0 – 192.168.255.255` |

Examples:

```text
192.168.1.10
10.0.0.5
172.16.5.20
```

Private IP addresses are **not directly routable on the public Internet**.

---

### 🌍 Public IP Address

A public IP address is an address used to identify a network/device **on the Internet**.

Example:

```text
203.0.113.10
```

Public IP addresses are assigned by Internet Service Providers (ISPs) or cloud providers and are routable over the Internet.

### Private IP vs Public IP

| Feature             | Private IP                                  | Public IP              |
| ------------------- | ------------------------------------------- | ---------------------- |
| Used for            | Local networks                              | Internet communication |
| Internet routable   | ❌ No                                        | ✅ Yes                  |
| Uniqueness          | Can be reused in different private networks | Globally unique        |
| Example             | `192.168.1.10`                              | `8.8.8.8`              |
| Usually assigned by | Router/DHCP                                 | ISP/Cloud provider     |

---

# 🧩 OSI Model

The **OSI (Open Systems Interconnection) model** is a conceptual model that explains how data travels between network devices.

It consists of **7 layers**.

| Layer | Name         | Main Function                             | Examples           |
| ----- | ------------ | ----------------------------------------- | ------------------ |
| 7     | Application  | Provides network services to applications | HTTP, FTP, DNS     |
| 6     | Presentation | Data formatting, encryption, compression  | Encryption, JPEG   |
| 5     | Session      | Establishes and manages sessions          | Session management |
| 4     | Transport    | End-to-end communication and reliability  | TCP, UDP           |
| 3     | Network      | Routing and logical addressing            | IP, Router         |
| 2     | Data Link    | Frames, MAC addressing, local delivery    | Ethernet, MAC      |
| 1     | Physical     | Transmits raw bits over physical media    | Cables, Signals    |

### 🧠 Easy way to remember

From Layer 7 to Layer 1:

**A P S T N D P**

> **All People Seem To Need Data Processing**

---

## 🔄 Data Flow Through OSI Layers

When sending data:

```text
Application
     ↓
Presentation
     ↓
Session
     ↓
Transport
     ↓
Network
     ↓
Data Link
     ↓
Physical
```

At the receiving device, the process happens in reverse.

---

## 🔐 Cybersecurity Relevance

Understanding IP addresses and the OSI model is important in cybersecurity because they help in:

* Network troubleshooting
* Network monitoring
* Packet analysis
* Understanding network attacks
* Firewall configuration
* Intrusion detection
* Vulnerability assessment
* Network security

---

## 📚 Learning Progress

* [x] Cybersecurity Fundamentals
* [x] Information Security
* [x] CIA Triad
* [x] Types of Cyber Attacks
* [x] Private IP vs Public IP
* [x] OSI Model
* [ ] TCP/IP Model
* [ ] Networking Protocols
* [ ] Ports & Protocols
* [ ] DNS
* [ ] Linux Networking
* [ ] Network Security
