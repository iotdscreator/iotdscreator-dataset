# IoTDSCreator-generated Datasets

Each directory corresponds to each scenario. The directory contains a scenario description with four types of datasets.

## Types of Datasets
We generate 16 datasets, which are categorized as five types including single attacks, multi-step attacks, CVEs, energy-related attacks, and others.

## Single Attacks

### 1. flooding

 - Simple example of the flooding attack
 - An attacker 

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
