# IoTDSCreator-generated Datasets

Each directory corresponds to each scenario. The directory contains a scenario description with four types of datasets.

## Types of Datasets
We generate 16 datasets, which are categorized as five types including single attacks, multi-step attacks, CVEs, energy-related attacks, and others.

## Single Attacks

### 1. flooding (#1)

 - Simple example of the flooding attack
 - An attacker performs the SYN flooding to a target

### 2. log4j malicious server (#2)

 - Example of the Log4j malicious server
 - An attacker (i.e., the malicious server) reponds with the malicious response on a valid request from a victim

### 3. ldap server (#3)

 - Example of the LDAP server, which is typically used in the log4j attack
 - An attacker launches the ping to find a LDAP server, and performs the SYN flooding to the LDAP server.

### 4. port scanning

 - Example of the port scanning
 - An attacker performs the port scanning attack to find a vulnerable hole

### 5. 

## Multi-step Attacks

### 1. ping-nmap-flooding-1

 - Example of the multi-step attack with the large sliding window
 - An attacker launches the three-step attack. First, the attacker searches an IP address that the attacker can communicate with by sending ICMP packets to arbitrary IP addresses (labeled as ''reconnaissance''). Once the attacker finds a victim, the attacker scans open ports from the victim (also labeled as ''reconnaissance''). Finally, the attacker launches the TCP SYN flooding attack to an open port (labeled as ''action'').
 - You can find the example scenario description under the directory of ''ping-nmap-flooding''

### 2. ping-nmap-flooding-2 (much detailed with a smaller window)

 - Example of the multi-step attack with the small sliding window
 - An attacker launches the three-step attack. First, the attacker searches an IP address that the attacker can communicate with by sending ICMP packets to arbitrary IP addresses (labeled as ''reconnaissance''). Once the attacker finds a victim, the attacker scans open ports from the victim (also labeled as ''reconnaissance''). Finally, the attacker launches the TCP SYN flooding attack to an open port (labeled as ''action'').
 - You can find the example scenario description under the directory of ''ping-nmap-flooding''

## CVE Datasets

### 1. CVE-2021-44228

 - The Log4j attack

### 2. CVE-

### 3. CVE-

### 4. CVE-

### 5. CVE-

## Energy-related Attacks

### 1. Modbus Probing and Flooding Attack

## Others
