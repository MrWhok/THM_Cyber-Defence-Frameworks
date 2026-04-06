# THM_Cyber-Defence-Frameworks

## Table of Contents
1. [Pyramid Of Pain](#pyramid-of-pain)
2. [Cyber Kill Chain](#cyber-kill-chain)
3. [Unified Kill Chain](#unified-kill-chain)

## Pyramid Of Pain
### Hash Values
1. Analyse the report associated with the hash "b8ef959a9176aef07fdca8705254a163b50b49a17217a4ff0107487f59d4a35d" here. What is the filename of the sample?

    The answer is `Sales_Receipt 5606.xls`.

### IP Addresses
1. Read the following report to answer this question. What is the first IP address the malicious process (PID 1632) attempts to communicate with? 

    The answer is `50.87.136.52`.

2. Read the following report to answer this question. What is the first domain name the malicious process (PID 1632) attempts to communicate with?

    The answer is `craftingalegacy.com`.

### Domain Names
1. Go to this report on app.any.run (opens in new tab) and provide the first suspicious domain request you are seeing, you will be using this report to answer the remaining questions of this task.

    The answer is `craftingalegacy.com`.

2. What term refers to an address used to access websites?

    The answer is `Domain Name`.

3. What type of attack uses Unicode characters in the domain name to imitate the a known domain?

    The answer is `Punycode Attack`.

4. Provide the redirected website for the shortened URL using a preview: https://tinyurl.com/bw7t8p4u

    The answer is `https://tryhackme.com/`.

### Host Artifacts
1. A process named regidle.exe makes a POST request to an IP address based in the United States (US) on port 8080. What is the IP address?

    The answer is `96.126.101.6`.

2. The actor drops a malicious executable (EXE). What is the name of this executable?

    The answer is `G_jugk.exe`.

3. Look at this report by Virustotal. How many vendors determine this host to be malicious?

    The answer is `9`.

### Network Artifacts
1. What browser uses the User-Agent string shown in the screenshot above?

    The answer is `Internet Explorer`.

2. How many POST requests are in the screenshot from the pcap file?

    The answer is `6`.

### Tools
1. Provide the method used to determine similarity between the files 

    The answer is `Fuzzy Hashing`.

2. Provide the alternative name for fuzzy hashes without the abbreviation 

    The answer is `context triggered piecewise hashes`.

### Tactics, Techniques, and Procedures (TTPs)
1. Navigate to ATT&CK Matrix webpage. How many techniques fall under the Exfiltration category?

    The answer is `9`.

2. Chimera is a China-based hacking group that has been active since 2018. What is the name of the commercial, remote access tool they use for C2 beacons and data exfiltration?

    The answer is ` Cobalt Strike`. We can check it in the ATT&CK Matrix under the Exfiltration category.

### Practical
1. Complete the static site. What is the flag?

    Here the correct answer to get the flag:

    ![alt text](<Assets/Tactics, Techniques, and Procedures (TTPs) - 1.png>)

    The flag is `THM{PYRAMIDS_COMPLETE}`.


## Cyber Kill Chain
### Reconnaissance
1. What is the name of the Intel Gathering Tool that is a web-based interface to the common tools and resources for open-source intelligence?

    The answer is `OSINT Framework`.

2. What is the definition for the email gathering process during the stage of reconnaissance?

    The answer is `Email harvesting`.

### Weaponization
1. What is the term for automated scripts embedded in Microsoft Office documents that can be used to perform tasks or exploited by attackers for malicious purposes?

    The answer is `Macro`.

### Delivery
1. What do you call an attack targeting a specific group by infecting their frequently visited website?

    The answer is `Watering Hole Attack`.

### Exploitation
1. What is the term for a cyber attack that exploits a software vulnerability that is unknown by software vendors?

    The answer is `Zero-Day`.

### Installation
1. What technique is used to modify file time attributes to hide new or changes to existing files?

    The answer is `Timestomping`.

2. What malicious script can be planted by an attacker on the web server to maintain access to the compromised system and enables the web server to be accessed remotely?

    The answer is `Web Shell`.

### Command and Control (C2)
1. What is the C2 communication where the victim makes regular DNS requests to a DNS server and domain which belong to an attacker. 

    The answer is `DNS Tunneling`.

### Actions on Objectives
1. What technology is included in Microsoft Windows that can create backup copies or snapshots of files or volumes on the computer, even when they are in use? 

    The answer is `Shadow Copy`.

### Practice Analysis
1. What is the flag after you complete the static site?

    Here the correct answer to get the flag:

    ![alt text](<Assets/Cyber Kill Chain - 1.png>)

    The flag is `THM{7HR347_1N73L_12_4w35om3}`.

## Unified Kill Chain
### What is a "Kill Chain"
1. Where does the term "Kill Chain" originate from?

    The answer is `Military`.

### What is "Threat Modeling"
1. What is the technical term for a piece of software or hardware in IT (Information Technology?)

    The answer is `Asset`.

### Introducing the Unified Kill Chain
1. In what year was the Unified Kill Chain framework released?

    The answer is `2017`.

2. According to the Unified Kill Chain, how many phases are there to an attack?

    The answer is `18`.

3. What is the name of the attack phase where an attacker employs techniques to evade detection?

    The answer is `Defense Evasion`.

4. What is the name of the attack phase where an attacker employs techniques to remove data from a network?

    The answer is `Exfiltration`.

5. What is the name of the attack phase where an attacker achieves their objectives?

    The answer is `Objectives`.

### Goal: In (Initial Foothold)
1. What is an example of a tactic to gain a foothold using emails?

    The answer is `Phishing`.

2. Impersonating an employee to request a password reset is a form of what?

    The answer is `Social Engineering`.

3. An adversary setting up the Command & Control server is what phase of the Unified Kill Chain?

    The answer is `Weaponization`.

4. Exploiting a vulnerability present on a system is what phase of the Unified Kill Chain?

    The answer is `Exploitation`.

5. Moving from one system to another is an example of?

    The answer is `Pivoting`.

6. Leaving behind a malicious service that allows the adversary to log back into the target is what?

    The answer is `Persistence`.

### Goal: Through (Network Propagation)
1. As a SOC analyst, you pick up an alert pointing to failed logins from an administrator account. What phase of the Unified Kill Chain would an attacker be seeking to achieve?

    The answer is `Privilege Escalation`.

2. Mimikatz, a known post-exploitation tool, was detected on the IT Manager's workstation. The Security logs show that the tool was attempting to dump OS and user secrets. Which Unified Kill Chain phase does this activity correspond to?

    The answer is `Credential Access`.

### Goal: Out (Actions on Objectives)
1. While monitoring the network as a SOC analyst, you observe a big traffic spike. Most of the network traffic is sent to an unknown, suspicious IP address. What Unified Kill Chain phase could describe this activity?

    The answer is `Exfiltration`.

2. Personally identifiable information (PII) has been released to the public by an adversary. Your organisation is facing reputational losses and scrutiny for the breach. What part of the CIA triad would be affected by this action?

    The answer is `Confidentiality`.

### Practical
1. Match the scenario prompt to the correct phase of the Unified Kill Chain to reveal the flag at the end. What is the flag?

    The flag is `THM{UKC_SCENARIO}`.