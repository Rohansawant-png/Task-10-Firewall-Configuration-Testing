# Cyber Security Internship – Task 10  
## Firewall Configuration & Testing

---

### 📌 Objective
The objective of this task is to configure and test firewall rules to control inbound and outbound network traffic.  
This task demonstrates how firewalls help protect systems from unauthorized access and network-based attacks.

---

### 🛠 Tools & Technologies
- **UFW (Uncomplicated Firewall)**
- Operating System: Linux
- Alternatives: Windows Defender Firewall, iptables

---

### 🔐 Firewall Overview
A firewall is a network security system that monitors and filters incoming and outgoing traffic based on predefined security rules.  
It acts as a protective barrier between trusted internal networks and untrusted external networks.

---

### ⚙️ Firewall Configuration Steps
1. Checked the current firewall status  
2. Enabled the firewall  
3. Allowed essential services such as SSH and HTTP  
4. Blocked unused and insecure ports  
5. Blocked a simulated malicious IP address  
6. Verified and documented all firewall rules  

---

### 💻 Commands Executed
```bash
sudo ufw status
sudo ufw enable
sudo ufw allow 22
sudo ufw allow 80
sudo ufw deny 21
sudo ufw deny from 203.0.113.45
sudo ufw status numbered
