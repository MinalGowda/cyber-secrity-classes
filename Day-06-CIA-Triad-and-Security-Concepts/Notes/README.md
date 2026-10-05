# 📅 Day 6 — CIA Triad & Security Tools

## 🔐 CIA Triad

The **CIA Triad** is a fundamental model in cybersecurity consisting of:

* **Confidentiality**
* **Integrity**
* **Availability**

It helps organizations protect information and systems from security threats.

---

## 1. 🔒 Confidentiality

Confidentiality ensures that information is accessible only to **authorized users**.

### Examples of security mechanisms

* Authentication
* Authorization
* Access control
* Encryption
* Passwords
* Multi-factor authentication (MFA)

### Example

Encrypting sensitive data so that unauthorized users cannot read it.

---

## 2. 🛡️ Integrity

Integrity ensures that data remains **accurate, complete, and unaltered** unless an authorized change is made.

### Examples of security mechanisms

* Hashing
* Digital signatures
* Checksums
* File integrity monitoring
* Access controls

### Example

A hash can be used to verify whether a downloaded file has been modified.

```text
Original File
     ↓
   Hash
     ↓
Compare with expected hash
     ↓
Same → File likely unchanged
Different → File was changed
```

---

## 3. ⚡ Availability

Availability ensures that systems, applications, and data are **accessible when authorized users need them**.

### Examples of security mechanisms

* Backups
* Redundancy
* Failover systems
* Load balancing
* Disaster recovery
* DDoS protection
* System monitoring

### Example

Using backup servers so that a service can continue operating if one server fails.

---

# 🔗 CIA Triad Summary

| Principle       | Goal                              | Example             |
| --------------- | --------------------------------- | ------------------- |
| Confidentiality | Prevent unauthorized access       | Encryption          |
| Integrity       | Prevent unauthorized modification | Hashing             |
| Availability    | Keep systems accessible           | Backup / Redundancy |

---

# 🛡️ Security Tools & Techniques

Different cybersecurity tools and techniques can help protect the three CIA principles.

### Confidentiality

```text
Encryption
Authentication
Authorization
Access Control
MFA
```

### Integrity

```text
Hashing
Digital Signatures
Checksums
File Integrity Monitoring
```

### Availability

```text
Backups
Redundancy
Failover
Load Balancing
DDoS Protection
Monitoring
```

---

## 🎯 Key Takeaway

The CIA Triad provides a foundation for understanding cybersecurity:

```text
          CIA TRIAD
             /\
            /  \
           /    \
Confidentiality — Integrity
           \    /
            \  /
         Availability
```

A secure system should protect **confidentiality**, maintain **integrity**, and ensure **availability**.
