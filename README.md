# 🛡️ My Cybersecurity & Hands-on Labs Portfolio

Welcome to my cybersecurity learning and practical portfolio. This repository serves as a live proof of my technical skills, tools proficiency, and methodology applied during various virtual lab challenges (TryHackMe, Cisco, etc.).

---

## 💻 TryHackMe Completed Labs & Write-ups

### 1. Machine: Blue (Windows Exploitation)
*   **Difficulty:** Easy
*   **Objective:** Exploit a Windows machine vulnerable to the famous **EternalBlue (MS17-010)** vulnerability.
*   **Tools Used:** Nmap, Metasploit Framework.
*   **Key Learnings:**
    *   Conducted network reconnaissance using Nmap to identify open port 445 (SMB).
    *   Analyzed the vulnerability and used Metasploit to safely execute the payload.
    *   Gained NT AUTHORITY\SYSTEM (Root/Admin) privileges and captured flags.

### 2. Machine: RootMe (Linux CTF)
*   **Difficulty:** Easy
*   **Objective:** CTF room for beginners to practice basic Linux privilege escalation and web hacking.
*   **Tools Used:** Nmap, GoBuster, Netcat.
*   **Key Learnings:**
    *   Ran directory brute-forcing using **GoBuster** to find hidden upload panels.
    *   Bypassed file upload restrictions by renaming the reverse shell extension to `.phtml`.
    *   Set up a listener via **Netcat** to catch the reverse shell and escalated privileges via misconfigured SUID binaries.

### 3. Machine: Ice (Windows Exploitation)
*   **Difficulty:** Easy
*   **Objective:** Exploit a Windows machine via a vulnerable third-party media server software (Icecast).
*   **Tools Used:** Nmap, Metasploit, Mimikatz.
*   **Key Learnings:**
    *   Identified vulnerable Icecast service running on port 8000.
    *   Used Metasploit for initial access and bypassed User Account Control (UAC) to get admin rights.
    *   Used **Mimikatz** (via meterpreter) to dump plain-text credentials from memory.

---

## 🛠️ Core Tools & Skills Demonstrated
*   **Reconnaissance:** Nmap, GoBuster
*   **Exploitation:** Metasploit, Netcat (Reverse Shells)
*   **Traffic Analysis:** Wireshark basic logging
*   **Operating Systems:** Linux Terminal, Windows Administration basics
