# 🎯 Phishing Attack Simulation & Malware Analysis

### 📌PROJECT OVERVIEW

🔍 This project simulates and analyzes a realistic phishing attack campaign, demonstrating how attackers use automation tools and social engineering to compromise user credentials.

💡 The attack mimics a WordPress invoice scam, combining:

Phishing email delivery

Fake login page cloning

Credential harvesting

Infrastructure obfuscation

---
### 🧠ATTACK FLOW
Phishing Email

        ↓
  Shortened URL
  
        ↓
  Obfuscated Link
  
        ↓
  Fake WordPress Login Page
  
        ↓
  Credential Input 
  
        ↓
  ZPhisher Capture Logs
  
        ↓
  Data Exfiltration 
---
  ### 🎯 OBJECTIVES

✔️ Simulate a real-world phishing attack

✔️ Analyze attacker tools and techniques

✔️ Map behaviors to MITRE ATT&CK

✔️ Identify detection gaps

✔️ Provide defensive strategies
---
### 🛠️ TOOLS & TECHNOLOGIES
| Tool             | Purpose                     |
| ---------------- | --------------------------- |
| 🐍 ZPhisher      | Phishing automation toolkit |
| 🌐 LocalXpose    | Tunneling service           |
| 🐧 Kali Linux    | Attack environment          |
| 📊 AbuseIPDB     | IP reputation analysis      |
| 📧 Email Headers | Forensic investigation      |

---
### 🧪 ATTACK BREAKDOWN
⚙️ 1. Tool Initialization

ZPhisher launched

WordPress phishing template selected

📸 Add image: Page 3
---
### 🌐 2. Infrastructure Setup

Local server → 127.0.0.1:8080

Tunnel → .loctx.io

📸 Add image: Page 5–6
---
### 🔗 3. URL Obfuscation

Shortened link (is.gd)

@ trick used to disguise domain

📸 Add image: Page 10

---

### 📧 4. Phishing Email

Pretext: Invoice payment request ($2,500)

Sent via Microsoft 365 (trusted source)

📸 Add image: Page 12–13

---

### 🔐 5. Credential Harvesting

Fake WordPress login page

Victim enters credentials

📸 Add image: Page 15

---

### 📡 6. Data Capture

Email + password logged

Victim IP recorded

📸 Add image: Page 17 & 21

---

### 🔍 KEY FINDINGS
#### 🚨 Attack Success Factors

Legitimate email infrastructure bypassed filters

Dynamic tunnel evaded URL blocking

Realistic phishing email increased trust

#### ⚠️ Security Weaknesses
Weak password usage

No MFA enabled

Lack of user awareness

---

### 📊 SECURITY IMPACT KPI RESULTS
| Metric           | Before | After   |
| ---------------- | ------ | ------- |
| Click Rate       | 42.8%  | 7.1%    |
| Credential Theft | 14.3%  | 0%      |
| Reporting Rate   | 3.5%   | 64.3%   |
| Detection Time   | >4 hrs | <8 mins |


📸 Add image: Page 28

---

### 🧩 MITRE ATT&CK MAPPING
| Tactic               | Technique             |
| -------------------- | --------------------- |
| 🎯 Initial Access    | Phishing (T1566)      |
| 🔐 Credential Access | Credential Harvesting |
| 🌐 Command & Control | Web Protocols (T1071) |
| 🕵️ Defense Evasion  | Obfuscated Links      |
| 📤 Exfiltration      | Data Theft            |


---
🛡️ DEFENSIVE STRATEGY
👤 User Protection
Awareness training
Identify suspicious links
🔐 Identity Security
Enforce MFA
Strong password policies
🌐 Network Defense
Block tunneling domains
Monitor outbound traffic
📧 Email Security
Detect shortened links
Flag invoice-based phishing
💡 KEY TAKEAWAY

🚀 This project shows how attackers can combine:

Automation tools
Social engineering
Infrastructure evasion

to execute highly effective phishing campaigns with minimal effort.

👨‍💻 AUTHOR

Martins Adeyanju
Cybersecurity Analyst

