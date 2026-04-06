# THM_Cyber-Defence-Frameworks

## Table of Contents
1. [Pyramid Of Pain](#pyramid-of-pain)

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
