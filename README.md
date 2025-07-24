# day 01
 1. Introduction to Ethical Hacking
Ethical Hacking is the process of deliberately probing a computer system, network, or application for security weaknesses — but with legal authorization and intent to fix them. The objective is to simulate potential attacks from malicious hackers (known as Black Hats) and proactively safeguard the system before any real attack occurs.

Ethical hacking is a key part of cybersecurity and risk assessment frameworks used by businesses, governments, and individuals to secure sensitive data and systems.

🔑 Think of ethical hackers as "digital locksmiths" — they try to break in to ensure the locks are strong!

🧠 2. Types of Hackers (Based on Intent)
Hacker Type	Intent	Description
White Hat	Good	Ethical hackers who work with permission to secure systems.
Black Hat	Malicious	Criminal hackers who break into systems illegally for theft, revenge, or damage.
Grey Hat	Mixed	Hackers who may break into systems without permission but do not intend harm. Often report flaws without legal clearance.
Script Kiddie	Inexperienced	Amateurs who use pre-made tools/scripts to hack without understanding the underlying techniques.
Hacktivist	Ideological/Political	Hackers driven by social or political causes; aim to bring attention to issues through cyberattacks.
State-Sponsored	Government-driven	Professional hackers employed by governments for espionage, surveillance, or cyber warfare.

🧰 3. Five Phases of Ethical Hacking
Ethical hacking follows a structured methodology. Each phase simulates the lifecycle of a cyberattack.

1️⃣ Reconnaissance (Information Gathering)
The preparatory phase — like a thief studying a bank's layout.

Goal: Gather as much information about the target as possible.

Types:

Passive Reconnaissance – Collecting information without interacting directly with the target (e.g., social media, public records).

Active Reconnaissance – Interacting directly with the target system (e.g., pinging IPs).

Tools: Nmap, Maltego, Google Dorking, Whois Lookup.

2️⃣ Scanning
Actively probing for weak points after gathering data.

Goal: Identify live systems, open ports, running services, and potential vulnerabilities.

Types:

Port Scanning

Network Mapping

Vulnerability Scanning

Tools: Nessus, Nikto, Angry IP Scanner, OpenVAS

3️⃣ Gaining Access
This is the "break-in" phase — trying to exploit a known flaw.

Goal: Exploit discovered vulnerabilities to gain control of the system or data.

Techniques: SQL Injection, Brute-force attacks, Buffer Overflow, Cross-Site Scripting (XSS)

Tools: Metasploit, Hydra, SQLMap

4️⃣ Maintaining Access
Once inside, the attacker ensures long-term control or backdoor entry.

Goal: Remain in the system undetected for future attacks or data extraction.

Techniques: Rootkits, Backdoors, Trojans, Remote Access Tools (RATs)

Ethical hackers will test how long such access can be maintained and how to prevent it.

5️⃣ Clearing Tracks
Black hats erase footprints. Ethical hackers simulate this to test for traceability.

Goal (for malicious hackers): Delete logs, mask identity.

Ethical hackers simulate this to test the system's logging, monitoring, and alerting mechanisms.

🧪 4. Common Tools Used by Ethical Hackers
Tool	Functionality
Nmap	Network scanner for port mapping and host discovery.
Wireshark	Network packet sniffer for real-time traffic analysis.
Metasploit	Framework for developing and executing exploit code.
Burp Suite	Web vulnerability scanner; ideal for testing web apps for XSS, CSRF, etc.
Aircrack-ng	Cracking Wi-Fi passwords using packet sniffing.
John the Ripper	Password cracking tool that supports many hash types.
Nikto	Web server vulnerability scanner.
Kali Linux	A Linux distro loaded with pre-installed tools for hacking and penetration testing.

🔐 5. Common Cyber Attacks Studied and Simulated
Ethical hackers must study the following attacks in depth and simulate them to evaluate a system's robustness:

Phishing – Trick users into revealing sensitive information via fake websites or emails.

SQL Injection – Injecting malicious SQL commands into input fields to access databases.

Denial of Service (DoS/DDoS) – Flooding a server with traffic to disrupt its services.

Cross-Site Scripting (XSS) – Injecting malicious scripts into websites viewed by users.

Man-in-the-Middle (MitM) – Intercepting and altering communication between two parties.

Brute Force – Guessing passwords by trying many combinations.

Privilege Escalation – Gaining higher access rights through vulnerability exploits.

⚖️ 6. Legal and Ethical Considerations
💼 Ethical hackers must always have written permission from the organization before testing.

✅ Responsibilities of an Ethical Hacker:
Never exploit system vulnerabilities for personal gain.

Document every step taken during the penetration test.

Report all findings to the organization honestly.

Follow responsible disclosure procedures.

📜 Relevant Laws:
IT Act 2000 (India)

General Data Protection Regulation (GDPR - Europe)

Cybersecurity Information Sharing Act (CISA - US)

Non-compliance can lead to imprisonment or fines, even for well-meaning hacking.

📚 7. Popular Certifications for Ethical Hackers
Certification	Organization	Level
CEH (Certified Ethical Hacker)	EC-Council	Intermediate
OSCP (Offensive Security Certified Professional)	Offensive Security	Advanced
CompTIA Security+	CompTIA	Beginner
CISSP (Certified Information Systems Security Professional)	ISC²	Expert
CHFI (Computer Hacking Forensic Investigator)	EC-Council	Specialized

🌐 8. Ethical Hacking vs Penetration Testing
Aspect	Ethical Hacking	Penetration Testing
Scope	Broad – includes networks, people, policies	Narrow – focuses only on systems vulnerabilities
Duration	Can be continuous	Usually project-based, short-term
Legal Permission	Always required	Always required
Reporting	Detailed documentation, risk analysis	Report on specific exploits and fixes

💼 9. Career Roles in Ethical Hacking
Penetration Tester – Simulates attacks on systems.

Cybersecurity Analyst – Monitors and secures networks.

Security Consultant – Advises businesses on security strategies.

Incident Responder – Handles real-time cyberattacks.

Vulnerability Researcher – Identifies and reports new system flaws.

👩‍💻 Skills Required:
Networking (TCP/IP, DNS, VPNs)

Programming (Python, Bash, C/C++)

Linux & Windows OS knowledge

Cryptography basics

Knowledge of ethical hacking tools and methodologies

🧭 10. Case Study – Real Life Example
Company: XYZ E-Commerce
Problem: Unauthorized login attempts noticed.
Action: An ethical hacker team was hired.
Findings: A critical vulnerability in the login page allowed SQL injection, letting attackers bypass login.
Solution: The vulnerability was patched, and input sanitization was added.
Impact: Potential customer data breach prevented, company reputation protected.

✨ Conclusion
Ethical hacking is not about breaking rules — it's about protecting people, systems, and information in a world full of cyber threats. It blends technical knowledge, legal responsibility, and moral judgment. As technology grows, the role of ethical hackers becomes more crucial in maintaining a secure digital environment.

# day 02
To successfully install Kali Linux on a Windows system using Oracle VirtualBox, ensure you have the following:

1. Kali Linux VirtualBox Image
Download the official pre-configured VirtualBox image of Kali Linux:
🔗 Kali Linux VirtualBox Image (2025.2)

2. Oracle VirtualBox
Oracle VirtualBox is a free and open-source virtualization software required to run Kali as a virtual machine:
🔗 Download VirtualBox 7.1.12 (Windows Host)

3. 7-Zip File Archiver
Used for extracting the .7z compressed Kali image:
🔗 Download 7-Zip (64-bit)

💾 Storage Requirement: Ensure you have at least 15–20 GB of free disk space available.

🪛 Step-by-Step Installation Guide
🧩 Step 1: Installing Oracle VirtualBox
Locate the downloaded VirtualBox .exe installer and double-click to run it.

When prompted by User Account Control, click "Yes" to allow administrator privileges.

The setup wizard launches. Click "Next" on the welcome screen.

On the Custom Setup screen, leave default settings as is. Note the install path, then click "Next".

Click "Next" again, accepting options like creating a shortcut and file associations.

A warning may appear: "Network Interfaces will be reset temporarily." Click "Yes" to proceed.

Click "Install" on the confirmation screen.

Wait for installation to complete, then click "Finish" to launch VirtualBox.

⚠️ Troubleshooting During VirtualBox Installation
❗ Problem 1: Missing Microsoft Visual C++ Redistributable
If an error appears about a missing component:

Download and install this dependency:
🔗 vc_redist.x64.exe

After installation, re-run the VirtualBox setup.

❗ Problem 2: Virtualization Not Enabled in BIOS
You may see: “AMD-V/Intel VT-x is disabled.”

To fix:

Reboot your system and enter BIOS/UEFI settings:

Dell: F2 or F12

HP: Esc or F10

Lenovo: F2 or Fn + F2

Acer: DEL or F2

Find and enable options such as:

Intel Virtualization Technology or VT-x

SVM Mode (for AMD)

Save changes and exit BIOS.

📦 Step 2: Installing 7-Zip
Locate the downloaded 7z2500-x64.exe file.

Right-click it and select “Run as Administrator.”

The setup window appears. Click "Install", wait for the installation to finish, then click "Close."

🗃️ Step 3: Extracting Kali Linux Image
Navigate to the location where you downloaded the Kali .7z archive.

Right-click the file and select “Show more options” (if on Windows 11), hover over 7-Zip, then choose “Extract Here.”

Wait patiently — extraction may take several minutes due to file size (~3–4 GB).

After completion, you will see two extracted files:

.vbox (VirtualBox Machine Definition)

.vdi (Virtual Disk Image)

🖥️ Step 4: Loading Kali Linux in VirtualBox
(Optional but recommended) Create a new drive partition or use a dedicated folder (10–15 GB minimum) to store the extracted Kali VM.

You can refer to this guide: How to create new partition

Copy the extracted Kali folder to that partition or location.

Locate the .vbox file (usually named like kali-linux-2025.2.vbox) and double-click it.

This automatically opens Oracle VirtualBox and registers the Kali VM.

In VirtualBox, you’ll now see “Kali Linux” listed as a virtual machine. Select it and click “Start.”

🔓 Step 5: Booting and First Login
On first boot, loading may take longer than usual — don’t worry!

Once you reach the login screen, use the default credentials:

Username: kali
Password: kali

You’ll now enter the Kali Linux desktop environment.

# day 03
Change Mode (chmod) Meaning & Purpose
The chmod, or change mode, command allows an administrator to set or modify a file’s permissions. Every UNIX/Linux file has an owner user and an owner group attached to it, and every file has permissions associated with it. The permissions are as follows: read, write, or execute.

Change Mode (chmod) Meaning & Application
UNIX/Linux systems have many users. In this context, a user may refer to an individual or a system operation. UNIX/Linux identifies each user with a UID, and users may be organized into groups.

Change Mode (chmod) Syntax & Mode Parameters
The syntax of the chmod command is:

chmod mode file
Example:

chmod 720 readme.txt
Each number in the mode parameter represents the permissions for a user or group of users:

The first number represents the file’s owner.
The second number represents the file’s group.
The third number represents everyone else.
The Change Mode (chmod) Meaning & Mode Parameters Reference Table below shows the eight numbers that can be used within the chmod parameter. The rwx column specifies read, write, and execute access, offering a binary value for each operation. A “1” means “yes,” a “0” means “no.” If rwx reads 110, then that permission may read and write, but not execute.

Change Mode (chmod) Meaning & Mode Parameters Reference Table
#	Permission	rwx
0	none	000
1	execute only	001
2	write only	010
3	write and execute	011
4	read only	100
5	read and execute	101
6	read and write	110
7	read, write, and execute	111
For example, if you set your directory permissions to 720, then your permissions would function as follows:

The file’s owner may read, write, and execute the file.
The file’s group may only write the file.
All others cannot access the file.
-------------------

 What Are Linux Commands?
Linux commands are text-based instructions used in the terminal (command line) to perform various tasks like managing files, running programs, checking system status, and more.

 BASIC LINUX COMMANDS (Must-Know)
Here's a table with common Linux commands and what they do:

| Command | Description                         | Example                 |
| ------- | ----------------------------------- | ----------------------- |
| `pwd`   | Shows **current working directory** | `pwd` → `/home/anamika` |
| `ls`    | Lists **files and folders**         | `ls` → shows contents   |
| `cd`    | **Change directory**                | `cd Documents`          |
| `mkdir` | **Make new directory**              | `mkdir project1`        |
| `touch` | **Create new file**                 | `touch notes.txt`       |
| `cp`    | **Copy files/folders**              | `cp file.txt backup/`   |
| `mv`    | **Move or rename** files/folders    | `mv old.txt new.txt`    |
| `rm`    | **Remove file** or folder           | `rm file.txt`           |
| `clear` | **Clear terminal screen**           | `clear`                 |
| `exit`  | Exit the terminal session           | `exit`                  |


 FILE VIEWING & INFO COMMANDS
| Command         | Description                        | Example            |
| --------------- | ---------------------------------- | ------------------ |
| `cat`           | View content of a file             | `cat story.txt`    |
| `more` / `less` | View large files page by page      | `less bigfile.txt` |
| `head`          | View **first 10 lines** of a file  | `head report.txt`  |
| `tail`          | View **last 10 lines**             | `tail log.txt`     |
| `wc`            | Count **words, lines, characters** | `wc data.txt`      |
| `file`          | Shows file type                    | `file image.png`   |

 SYSTEM COMMANDS
| Command    | Description                         | Example    |
| ---------- | ----------------------------------- | ---------- |
| `whoami`   | Displays **current logged-in user** | `whoami`   |
| `uname -a` | Shows **system info**               | `uname -a` |
| `top`      | View running processes              | `top`      |
| `ps`       | Shows active processes              | `ps`       |
| `df -h`    | Disk space usage                    | `df -h`    |
| `free -h`  | Shows memory usage                  | `free -h`  |


PERMISSION & OWNERSHIP COMMANDS
| Command | Description                 | Example               |
| ------- | --------------------------- | --------------------- |
| `chmod` | Change file **permissions** | `chmod 755 script.sh` |
| `chown` | Change **file owner**       | `chown user file.txt` |
| `ls -l` | See permissions of files    | `ls -l`               |

 PACKAGE MANAGEMENT (Debian/Ubuntu)
| Command            | Description                    | Example                |
| ------------------ | ------------------------------ | ---------------------- |
| `sudo apt update`  | Update package lists           | `sudo apt update`      |
| `sudo apt upgrade` | Upgrade all installed packages | `sudo apt upgrade`     |
| `sudo apt install` | Install new software           | `sudo apt install vlc` |
| `sudo apt remove`  | Remove software                | `sudo apt remove vlc`  |

