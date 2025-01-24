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

### 4. port scanning (#4)

 - Example of the port scanning
 - An attacker performs the port scanning attack to find a vulnerable hole

### 5. SSH bruteforce attack (#5)

 - Example of the dictionary attack
 - An attacker attempts to find a SSH credential on a target device based on several potential credentials.

## Multi-step Attacks

### 1. ping-nmap-flooding-1 (#6)

 - Example of the multi-step attack with the large sliding window
 - An attacker launches the three-step attack. First, the attacker searches an IP address that the attacker can communicate with by sending ICMP packets to arbitrary IP addresses (labeled as ''reconnaissance''). Once the attacker finds a victim, the attacker scans open ports from the victim (also labeled as ''reconnaissance''). Finally, the attacker launches the TCP SYN flooding attack to an open port (labeled as ''action'').
 - You can find the example scenario description under the directory of ''ping-nmap-flooding''

### 2. ping-nmap-flooding-2 (much detailed with a smaller window) (#7)

 - Example of the multi-step attack with the small sliding window
 - An attacker launches the three-step attack. First, the attacker searches an IP address that the attacker can communicate with by sending ICMP packets to arbitrary IP addresses (labeled as ''reconnaissance''). Once the attacker finds a victim, the attacker scans open ports from the victim (also labeled as ''reconnaissance''). Finally, the attacker launches the TCP SYN flooding attack to an open port (labeled as ''action'').
 - You can find the example scenario description under the directory of ''ping-nmap-flooding''

## CVE Datasets

### 1. CVE-2021-44228 (#8)

 - The Log4j attack. There are the LDAP server and the malicious HTTP server.

### 2. CVE-2022-35934 (#9)

 - A denial-of-service due to TensorFlow via the CHECK-failure.

### 3. CVE-2022-35986 (#10)

 - A denial-of-service due to TensorFlow via a segfault.

### 4. CVE-2023-25667 (#11)

 - An integer overflow in TensorFlow

### 5. CVE-2023-25801 (#12)

 - A double free issue in TensorFlow

### 6. CVE-2024-33664 (#13)

 - A denial-of-service during a decode via a crafted JSON Web Encryption (JWE)

## Energy-related Attacks

### 1. IEEE 2030.5 Flooding (#14)

 - The flooding attack from an IEEE 2030.5 server to an IEEE 2030.5 client where a server is an inverter and a client is a main utility
 - When a client sends a request to a server, a server responds with messages with an incorrect CRCs as a flooding attack

### 2. IEEE 2030.5 Invalid Certificate (#15)

 - The attack from an IEEE 2030.5 server to an IEEE 2030.5 client where a server is an inverter and a client is a main utility
 - When a client attempts to establish a TLS session with a server, a server sends an invalid certificate, expecting any kinds of memory corruption on a client due to any kind of an implementation error in parsing

## Others

### 1. Reconnaissance example (#16)

 - The example of an nmap scanning attack toward an IoT network from an external attacker.
 - There are an mqtt broker, a log4j web server, and a temperature in the IoT network. The attacker outside the network performs the nmap scanning to find any vulnerability of the gateway.
