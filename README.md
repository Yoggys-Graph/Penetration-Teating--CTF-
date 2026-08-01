# Penetration Testing CTF Write-up
  Capture time flag
🛡️ CTF Write-up: [SOC Analyst]

---

## 📌 Challenge Overview

- Platform: [TryHackMe]
- Difficulty: [Easy]
- Category: [Network / Web / Forensics / SOC / Threat Detection]
- Date Completed: [DD-05-2026]

---

## 🎯 Objective

Briefly describe the goal of the challenge.

«Example: Detect suspicious activity and identify the flag from compromised system logs.»

---

### 🧠 Scenario (Very Important for Analysts)

Describe the real-world context.

«Example: A company detected unusual login attempts. As a security analyst, your task is to investigate logs and identify potential compromise.»

---

## 🛠️ Tools & Technologies

- Wireshark
- Splunk / ELK
- Nmap
- Linux CLI
- [Add others]

---

### 🔎 Step 1: Initial Analysis

Explain how you started.

- Reviewed logs / scanned system
- Identified unusual activity

### 🔍 Key Findings:

- Suspicious IP:
- Unusual port activity:
- Abnormal login attempts:

---

### 📊 Step 2: Investigation

Break down your analysis process.

Example:

- Checked login logs
- Identified repeated failed attempts
- Found successful login after brute-force

grep "Failed password" auth.log

Findings:

- Multiple failed logins detected
- Successful login from unknown IP

---

### 🚨 Step 3: Threat Identification

Explain what type of attack occurred.

- Brute-force attack
- Phishing attempt
- SQL Injection
- Malware activity

---

## 🧾 Evidence Collected

- IP addresses
- Log entries
- File names
- URLs

---

## 🏁 Flag

flag{THM{PENTEST_COMPLETE}

⚠️ Follow platform rules when sharing flags.

---

## ⚠️ Risk Assessment

Explain impact clearly (this impresses recruiters):

- Unauthorized system access
- Data exposure risk
- Potential lateral movement

---

## 🔐 Mitigation & Recommendations (VERY IMPORTANT)

Provide real-world solutions:

- Enable account lockout policies
- Implement multi-factor authentication (MFA)
- Monitor logs continuously
- Block malicious IP addresses
- Use SIEM alerts

---

## 🧠 Lessons Learned

- Importance of log analysis
- Detecting brute-force patterns
- Real-world SOC workflow

---

## 🔗 Mapping to Frameworks (Optional but Powerful)

- MITRE ATT&CK:
  - T1110 – Brute Force
  - T1078 – Valid Accounts

---

## 📸 Screenshots

Include:

![Image 1](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-1.png)
![Image 2](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-2.png)
![Image 3](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-3.png)
![Image 4](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-4.png)
![Image 5](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-5.png)
![Image 6](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-6.png)
![Image 7](https://github.com/Yoggys-Graph/SIEM-Dashboard/blob/main/assets/Pentesting%20for%20Portfolio-7.png)

---

