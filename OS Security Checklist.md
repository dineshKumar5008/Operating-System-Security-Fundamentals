# OS Security Checklist – Task 2

## System Information
- Operating System: Kali Linux
- Environment: Virtual Machine
- User Type: Root & Normal User (via sudo)

---

## 1. User Accounts & Access Control
- [x] Verified current user using `whoami`
- [x] Checked user identity and groups using `id`
- [x] Understood difference between root and normal user
- [x] Root access used only when required (least privilege)

---

## 2. File Permissions & Ownership
- [x] Checked file permissions using `ls -l`
- [x] Understood permission format (r, w, x)
- [x] Modified file permissions using `chmod`
- [x] Changed file ownership using `chown`

**Commands used:**
```bash
ls -l
chmod 640 test.txt
chown user:user test.txt
3. Firewall Configuration (UFW)
 UFW firewall installed

 Firewall enabled successfully

 Firewall configured to start on boot

 Firewall status verified

Commands used:

bash
Copy code
sudo ufw enable
sudo ufw status verbose
Firewall Status:

Default policy: Deny incoming

Allow outgoing traffic

Logging enabled (low)

4. Running Processes & Services
 Identified running processes

 Identified active system services

Commands used:

bash
Copy code
ps aux
systemctl list-units --type=service --state=running
5. Service Hardening
 Reviewed unnecessary services

 Disabled unused services to reduce attack surface

Example command:

bash
Copy code
systemctl stop bluetooth
systemctl disable bluetooth
6. OS Hardening Best Practices
 Least privilege principle applied

 Firewall enabled

 Unnecessary services disabled

 Strong password usage

 Regular system updates recommended

Final Outcome
This task helped in understanding:

OS-level security concepts

Linux file permissions

Firewall configuration

Process and service management

System hardening techniques