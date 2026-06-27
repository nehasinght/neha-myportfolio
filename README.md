Cyber Security CTF Machine

This repository contains a Linux-based Capture The Flag (CTF) machine developed as part of a Cyber Security assignment. The machine simulates a real-world penetration testing environment where participants perform reconnaissance, enumeration, credential discovery, SSH access, privilege escalation, and steganography to capture flags.


## objective

Objectives
Practice Linux enumeration.
Perform web reconnaissance.
Discover hidden credentials.
Access the machine through SSH.
Capture user and root flags.
Solve a steganography challenge.


## specifications

Machine Specifications
Operating System: Kali Linux
Web Server: Apache2
SSH Service: OpenSSH
Hostname: Neha Singh
Open Ports
Port	Service
22	    SSH
80  	HTTP


## challenge feature


Personal portfolio website
Hidden HTML comments
Hidden JavaScript clues
CSS hints
robots.txt enumeration
Base64 encoded hints
Hidden credentials
SSH access
User and Root flags
Resume hidden inside an image using steganography



Repository Structure
CTF-Machine/
│
├── README.md
├── CTF_Report.pdf
├── VM.zip
│
├── Website/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   ├── robots.txt
│   └── images/
│       └── profile.jpg
│
└── Screenshots/
    ├── homepage.png
    ├── website.png
    ├── robots.png
    ├── ssh.png
    ├── userflag.png
    ├── rootflag.png
    └── steghide.png
Setup Instructions
Import the provided virtual machine into VMware or VirtualBox.
Start the virtual machine.
Determine the machine's IP address.
Verify that only SSH (22) and HTTP (80) are accessible.
Begin enumeration using your preferred security tools.

Example:

nmap -A <Target-IP>

Open the website:

http://<Target-IP>
Challenge Walkthrough (High-Level)
Scan the target.
Enumerate the website.
Discover hidden clues.
Decode encoded information.
Recover SSH credentials.
Log in via SSH.
Capture the user flag.
Escalate privileges.
Capture the root flag.
Extract the hidden resume from the image using steganography.

Note: This repository intentionally does not disclose usernames, passwords, flag values, or the steganography passphrase to preserve the challenge.

Deliverables
Exported Virtual Machine (.zip)
Website Source Files
CTF Report (PDF)
README.md
Screenshots
Author

Neha Singh

Cyber Security Student

Disclaimer

This project was created solely for educational purposes as part of a Cyber Security CTF assignment. It is intended for learning and demonstration in an authorized environment only.