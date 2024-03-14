---
tags:
  - README
---
# SY0-601 Security+ Notes
This is my Obsidian vault for my Security+ notes. 
I am currently studying for the [CompTIA SY0-601 Certificate](https://www.comptia.org/certifications/security). Even though the SY0-701 is the most current one, there are vastly more resources for studying the 601. I have until July to take this test to get the certificate.

The course I am taking is Professor Messer's [SY0-601 CompTIA Security+ Course](https://www.professormesser.com/security-plus/sy0-601/sy0-601-video/sy0-601-comptia-security-plus-course/) which he provides for free via YouTube.

# What is contained here?
Basically, this is my note taking system for learning new things. One of the ways I like to use to learn new material is to take notes on it, and then have everything linked together so that if I am on some page, I can easily click around to get more information on something else.

There is an added benefit here as well, that with "linking my thinking", I can more easily make connections to different pieces of information, and I can better see how different topics might relate.

# The SY0-601 Dashboard
This page is essentially being used as a hub for the notes. This way, I do not have to manually search the long list of notes.

To accomplish this, I am using DataView, along with tags to sort things into different categories.
- #Acronym  | To have a complete list of all the acronyms recommended to learn for the test.
- #ApplicationAttacks  | Notes taken from the "Network Attacks" section.
- #AttackTypes   | Notes taken from the "Attack Types" part of the course.
- #NetworkAttacks  | Notes taken from the "Network Attack Section"
- #SocialEngineering  | Notes taken from the "Social Engineering" part of the course.

# Obsidian Plugins Used
- [Dataview](https://blacksmithgu.github.io/obsidian-dataview/) - Lets me generate lists and graphs of my different pages. Each note will show you a list of related notes, sorted alphabetically. The SY0-601 Dashboard page will aggregate all the new stuff I add automatically, so long as I use the tags mentioned above.
- [Templater](https://github.com/SilentVoid13/Templater) - Lets me use templates within Obsidian to make faster notes.

# Updates
### `3-1-24 Update`
- I am well into my journey of learning this material, but I am just now staring the process of making these notes and linking them.
- In addition to the below changes, I also fixed the DataView code on _all_ pages. There was an error in the code where I did not sort everything correctly.
- Pages Added to `Individual Notes`:
	- Anti-Virus (AV), Credential Harvesting, Dumpster Diving, Hoaxes, Impersonation, Influence Campaigns, Intrusion Prevention System (IPS), Invoice Scams, Pretexting, Reconnaissance, Request for Comments (RFC), Reverse DNS (rDNS), Shoulder Surfing, Secure Mail Transfer Protocol (SMTP), Spam over Instant Messaging (SPIM), Tailgating, Watering Hole Attacks
- Pages Updated:
	- Phishing, Social Engineering
- Folders Added:
	- Related Notebook Assets (All images are stored here)
### `Version 0.01`
- Added a `Stubs` folder. This is for any note that I created that has a relation, that I have not yet filled out, or is a note for a topic I would like to cover at some point. The following files have been added to the Stubs folder for future use:
	- Adware, Backdoors, Binaries, Bots & Botnets, Crypto-Malware, Drive-by Downloads, Edge Computing, Fog Computing, Fuzzers, Infrastructure as Code, Internet of Things (IoT), Intrusion Detection System (IDS), Kernels, Keyloggers, Operating System (OS), Personally Identifiable Data (PII), Public-Key Cryptography, Random-Access Memory (RAM), Ransomware, Rootkits, Spyware, Trojan Horses, Virtual Machine Sprawl, Viruses, Worms
- The following have been moved from `Stubs` --> `Individual Notes` and have had at least some information filled out:
	- Backdoors, Crypto-Malware, Ransomware, Trojan Horses, Viruses, Worms
- The following have been created as new:
	- Fileless Viruses, Malware, Potentially Unwanted Program (PUP), Remote Access Trojans (RATs)
- Updated the SY0-601 Dashboard to include Section 1.2 Attack Types and all related notes.
- Updated the title of the Anti-Viruses (AV) page, as it contained a typo.

### `Version 0.02`
- Added the "AttackTypes" tag to the following pages as I had forgotten previously:
	- Ransomware, Worms

### `Version 0.03`
- Pages Updated:
	- Pretexting
	- Various Pages, anywhere where a 'Signature' was mentioned, I added a link to Malware Signatures, as this was a topic that I initially had a hard time understanding.
- Pages added to `Individual Notes`:
	- Basic Input Output System (BIOS), Logic Bombs, Unified Extensible Firmware Interface (UEFI)
- Pages added to `Stubs`:
	- Command & Control (C&C), Distributed Computing Attacks, Distributed Denial of Service (DDoS), Firewalls, Graphical User Interface (GUI), Malware Signatures, Peer to Peer (P2P), Relay Spam, Supervisory Control and Data Acquisition (SCADA)
- Pages moved from `Stubs` --> `Individual Notes`
	- Adware, Backdoors, Bots & Botnets, Kernels, Rootkits, Spyware, Trojan Horses
- Pages moved from `Individual Notes` --> `Stubs`. The following are empty notes that should not have been in this folder yet.
	- Anti-Virus (AV), Intrusion Prevention System (IPS), Request for Comments (RFC), Reverse DNS (rDNS), Secure Mail Transfer Protocol (SMTP), Spam Over Instant Messaging (SPIM)

### `Version 0.03b`
- Removed a link I kept in the readme by accident when testing how to link pages within obsidian.

### `Version 0.04`
- Pages added `Individual Notes`:
	- Adversarial Artificial Intelligence, AI Training Data Poisoning, Card Cloning, Card Skimming, Evasion Attacks, Hashing, Human Interface Device (HID), Machine Learning, Malicious Flash Drives, Malicious USB Cables, Password Attacks, Password Brute-Force, Plaintext, Rainbow Tables, Salting, Secure Hashing Algorithm 256bit (SHA-256), Supply Chain Attacks
- Pages added to `Stubs`:
	- Artificial Intelligence (AI), Card Validation Code (CVC), Distributed Cracking, GPU Cracking, Heating, Ventilation, and Air Conditioning (HVAC), Universal Serial Bus (USB)

### `Version 0.05`
- Misc Updates:
	- Added "AttackTypes" tag to Supply Chain Attacks
	- Added new "ApplicationAttacks" tag, and updated SY0-601 Dashboard to include notes tagged with this.
- Pages Added to `Individual Notes`: 
	- Application Programming Interface (API), API Attacks, Birthday Attacks, Buffer Overflows, Cloud-Based & On Premises Security, Cookies, Cross Site Scripting (XSS), Cryptographic Attacks, DHCP Starvation, Directory Traversal, Downgrade Attacks, Driver Manipulation, Error Handling, Input Handling, Integer Overflow, Memory Leak, Memory Vulnerabilities, NULL Pointer Reference, Pass The Hash, Persistent (Stored) XSS Attack, Privilege Escalation, Non-Persistent (Reflected) XSS Attack, PHP - Hypertext Preprocessor (PHP), Race Conditions, Refactoring (Metamorphic Malware), Replay Attacks, Request Forgeries, Resource Exhaustion, Secure Sockets Layer (SSL), Session Hijacking, Session IDs, Shimming, Supply Chain, ZIP Bombs
- Pages Added to `Stubs`:
	- Address Resolution Protocol (ARP), Cascading Style Sheets (CSS), Denial of Service (DoS), Dynamic Host Configuration Protocol (DHCP), Fault Tolerance, Hypertext Markup Language (HTML), Hypertext Transfer Protocol Secure (HTTPS), No Operation (NOP), On-Path Attacks, Padding Oracle and Downgrade Legacy Encryption (POODLE), Transport Layer Security (TLS), User Account Control (UAC), Virtual Private Network (VPN)
- Pages Updated:
	- Hashing
- Pages moved: `Stubs` --> `Individual Notes`
	- Transport Layer Security (TLS)

### `Version 0.06`
- Misc Updates
	- Added "NetworkAttacks" tag.
	- Updated README to use actual tags for the different sections.
	- Updated SY0-601 Dashboard to not include the README in the lists of documents.
- Pages added to `Individual Notes`
	- 802.11 Management Frames, Bluejacking, Bluesnarfing, Rogue Access Points, Wireless Disassociation Attacks, Wireless Evil Twins, Wireless Jamming
- Pages added to `Stubs`
	- Access Point (AP), Institute of Electrical and Electronics Engineers (IEEE), Network Access Control (NAC), Quality of Service (QoS), Radio Frequency (RF), Server Set Identifier

### `Version 0.07`
- README Notes:
	- I am no longer going to alphabetize the pages added, moved, updated, etc. on the README. Going forward, the lists will be in the order of actions. For example, looking below on pages added to `Stubs`, "Relay Attacks" was added to the folder before "Spanning Tree Protocol (STP)".
		- This helps me see what order files got added in.
- Misc Updates
	- Added an "Acronyms" page
		- It lists all acronym pages created, All acronym pages in `Stubs` (they need more information), and all acronyms in `Individual Notes` (they have some information filled out about what the acronym means).
- Pages Moved:
	- `Stubs` --> `Individual Notes`
		- On-Path Attacks, Personally Identifiable Information (PII)
- Pages Added:
	- `Stubs`
		- Relay Attacks, Subnets, Wired Equivalent Privacy (WEP), Local Area Network (LAN), Organizational Unique Identifier (OUI), Spanning Tree Protocol (STP), Domain Name System (DNS), IP Address, Universal Resource Locator (URL)
	- `Individual Notes`
		- ARP Poisoning, Cryptographic Nonce, Initialization Vector (IV), Near Field Communication (NFC), On-Path Browser Attacks, Radio-Frequency Identification (RFID), LAN Switching, MAC Cloning, MAC Flooding, Media Access Control Address (MAC Address), DNS Poisoning, Domain Hijacking, URL Hijacking, Typosquatting
- Pages Updated with new information:
	- Phishing