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

# day 04
ETHICAL HACKING NOTES – NETWORKING CONCEPTS
1. NAT – Network Address Translation
Definition:
NAT is a technique used by routers or firewalls to map private IP addresses within a local network to a public IP address for communication over the internet. It acts as a bridge between internal and external networks by hiding internal IP addresses from the outside world.
There are three main types of NAT. Static NAT is a one-to-one mapping between private and public IPs and is often used when a specific internal server must be accessed from the outside. Dynamic NAT maps private IPs to a pool of public IPs dynamically, but only works when enough public IPs are available. The most common and practical type is PAT (Port Address Translation), also known as NAT Overload, where many internal IPs share one public IP with different port numbers. In ethical hacking, NAT can be a hurdle because it masks internal IPs. However, techniques like reverse shells or NAT traversal using STUN/TURN servers are used to bypass it and gain access.

Purpose & Use:
NAT helps preserve IP address space (especially IPv4) and provides a basic layer of security. Devices inside a home or office network may use private IPs like 192.168.1.2, but to the internet, they all appear to be using a single public IP.

Types of NAT:

Static NAT: One private IP is mapped to one public IP. Useful when a server inside the LAN needs to be accessed from the internet.

Dynamic NAT: A pool of public IPs is available and assigned dynamically to internal devices.

PAT (Port Address Translation) or NAT Overload: Many private IPs share one public IP using different port numbers.

Ethical Hacking Relevance:

Makes internal devices unreachable from the internet unless port-forwarding is configured.

Attackers use reverse shells or tunneling tools (like ngrok) to bypass NAT and establish control.

2. Network
Definition:
A network is a group of interconnected computers or devices that can communicate and share resources such as files, printers, or internet connections.It is an arrangement of interconnected devices such as computers, servers, switches, and routers that can communicate with each other and share resources. Networks can be wired or wireless, and they vary in size from small local area networks (LANs) to wide area networks (WANs) like the internet. The basic purpose of networking is to enable efficient communication, data transfer, and access to shared resources like files, printers, or applications.

Types of Networks:

LAN (Local Area Network): Covers small areas like homes or offices.

WAN (Wide Area Network): Covers larger areas like cities or countries (e.g., the internet).

MAN (Metropolitan Area Network): Spans a city or campus.

Components:

Routers: Direct traffic between networks.

Switches: Connect devices within a LAN.

Firewalls: Filter traffic and provide security.

Ethical Hacking Relevance:

Understanding how networks are structured helps a hacker determine entry points, attack vectors, and potential pivot paths to move laterally inside a network.

3. IP Address (Internet Protocol Address)
Definition:
An IP address is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. It serves two main purposes: identification and location addressing.
It is a unique number assigned to each device on a network, allowing them to identify and communicate with each other. The most common format is IPv4, which is a 32-bit address written in dotted decimal format, like 192.168.1.1. 
Types:

IPv4: 32-bit address, written as 192.168.1.1. Limited to around 4.3 billion addresses.

IPv6: 128-bit address, written as 2001:0db8:85a3:0000:0000:8a2e:0370:7334. Provides a vastly larger address space.

Public vs. Private IPs:

Private: Used within local networks (e.g., 192.168.x.x, 10.x.x.x)

Public: Routable on the internet (e.g., 8.8.8.8)

Ethical Hacking Relevance:

IP Scanning tools like Nmap are used to find live hosts.

Helps in geolocation, OS fingerprinting, and targeting specific devices in a subnet.

4. MAC ID (Media Access Control Address)
Definition:
The MAC address is a hardware identifier assigned to a network interface controller (NIC) at the factory. It is unique for each device and operates at Layer 2 (Data Link Layer) of the OSI model.
It is a unique identifier assigned to a device's network interface card (NIC) by the manufacturer. It operates at the Data Link Layer (Layer 2) of the OSI model and is used for local communication within a network segment. Unlike IP addresses, which can change or be assigned dynamically, MAC addresses are hardcoded into the hardware and follow a format like 00:14:22:01:23:45.
Format:
Six groups of two hexadecimal digits separated by colons, e.g., 00:1A:2B:3C:4D:5E.

Ethical Hacking Relevance:

MAC Spoofing: An attacker can change their MAC address to bypass MAC filtering, impersonate another device, or hide identity.

Used in Wi-Fi attacks like deauthentication or ARP spoofing.

5. TCP and UDP
🔸 TCP (Transmission Control Protocol)
A reliable, connection-oriented protocol that ensures data is delivered in order and without loss.TCP (Transmission Control Protocol) is a connection-oriented protocol that ensures reliable, ordered, and error-checked delivery of data. Before transmitting, it performs a three-way handshake (SYN, SYN-ACK, ACK) to establish a session. TCP is used in applications where data integrity matters — like web browsing (HTTP/HTTPS), email (SMTP), and file transfer (FTP).

Uses handshaking (SYN, SYN-ACK, ACK) to establish a connection.

Suitable for applications like web browsing (HTTP/HTTPS), email, SSH, and file transfers.

🔸 UDP (User Datagram Protocol)
A connectionless, unreliable protocol that sends data without checking if it arrived.
On the other hand, UDP (User Datagram Protocol) is connectionless and focuses on speed rather than reliability. It does not guarantee delivery, order, or error checking, making it ideal for real-time applications like video streaming, online gaming, or DNS queries.

Much faster, used in real-time applications like gaming, VoIP, streaming, and DNS.

Ethical Hacking Relevance:

Tools like Nmap use both TCP and UDP scanning to identify open ports.

TCP can be exploited for SYN flood attacks, while UDP is used for amplification attacks.

6. Reconnaissance
Definition:
Reconnaissance is the first and most crucial phase of ethical hacking, often referred to as the information gathering stage. The goal is to collect as much information as possible about the target — be it an individual, a server, or a network — without alerting the target. Recon lays the foundation for the next stages of attack by identifying potential vulnerabilities and entry points.

There are two types of reconnaissance:

Passive Reconnaissance involves gathering information without interacting directly with the target. Techniques include browsing company websites, social engineering, performing WHOIS lookups, searching leaked credentials, or exploring DNS records.

Active Reconnaissance involves directly probing the target through tools like Nmap, Ping, Netcat, or Shodan. These activities generate traffic and may alert security systems, but they provide more precise and actionable data.

Tools:

Nmap, Netcat, Recon-ng, theHarvester, Shodan

Purpose:

Identify IP ranges, open ports, services, OS versions, and network topology to plan the attack strategy.

7. Subnet (Subnetwork)
Definition:
A subnet is a smaller division of a large network that is created to organize and secure the network more effectively. Subnetting allows administrators to segment a network logically.It is the process of dividing a large IP network into smaller, more manageable segments called subnets. This technique is used to improve network performance, security, and organization. Each subnet can have its own policies, security settings, and routing rules, making it easier to isolate and manage devices.
Example:

Original network: 192.168.1.0/24 (254 hosts)

Subnets:

192.168.1.0/26 → 64 addresses

192.168.1.64/26 → 64 addresses

Subnet Mask:

Helps determine the network and host portion of the IP.

For example, 255.255.255.0 for /24 means first 24 bits are network bits.

Ethical Hacking Relevance:

Helps hackers isolate target machines within subnets.

Understanding subnetting is critical when performing internal reconnaissance, privilege escalation, and lateral movement.

