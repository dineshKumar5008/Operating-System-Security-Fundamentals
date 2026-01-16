# 🔐 Task 2 – Operating System Security Fundamentals

> “The first system you must secure is the operating system itself.”

---

## 🧠 Overview
This repository documents my hands-on work for **Task 2: Operating System Security Fundamentals** as part of a **Cyber Security Internship**.

The objective of this task is to understand how operating systems (Linux) can be **secured, hardened, and monitored** to reduce the attack surface and prevent unauthorized access.

---

## 🛠 Environment & Tools
- **Operating System:** Kali Linux (Virtual Machine)
- **Virtualization:** VirtualBox / VMware
- **Core Tools & Commands:**
  - `chmod`, `chown`, `ls -l`
  - `ufw` (Uncomplicated Firewall)
  - `ps`, `systemctl`
  - `sudo`

---

## ⚙️ What Was Done (Hands-On)

### 👤 User & Privilege Management
- Verified current user and groups
- Understood **root vs normal user**
- Applied **least privilege principle**
- Used `sudo` only when required

---

### 📁 File Permissions & Ownership
- Inspected Linux file permissions using `ls -l`
- Modified permissions using `chmod`
- Changed file ownership using `chown`
- Learned how misconfigured permissions can lead to privilege escalation

---

### 🔥 Firewall Configuration (UFW)
- Installed and enabled UFW firewall
- Configured default rules:
  - ❌ Deny incoming traffic
  - ✅ Allow outgoing traffic
- Verified firewall status and logging

---

### ⚡ Process & Service Analysis
- Identified running processes using `ps aux`
- Enumerated active services with `systemctl`
- Reviewed unnecessary services

---

### 🛑 Service Hardening
- Disabled unused services (example: Bluetooth)
- Reduced system attack surface
- Improved baseline OS security posture

---

## 🧱 OS Hardening Principles Applied
- Least privilege principle
- Minimal services running
- Firewall enforcement
- Secure file permissions
- Defense-in-depth mindset

---

## 📸 Evidence
Screenshots are included to demonstrate:
- Firewall installation and status
- File permission handling
- Running services and processes

📁 See the `screenshots/` directory.

---

## 📄 Deliverables
- `os_security_checklist.md` → OS security checklist
- `README.md` → Task documentation
- `screenshots/` → Proof of execution

---

## 🎯 Learning Outcome
Through this task, I gained practical understanding of:
- OS-level security controls
- Linux access control mechanisms
- Firewall configuration
- Process and service hardening
- Real-world system hardening techniques

---

## 🧑‍💻 Author
**Cyber Security Intern**  
> Learning how to break systems by first learning how to secure them.

---
