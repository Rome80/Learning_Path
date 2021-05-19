# 5 Stages of Penetration Testing


##Stage 1 - Reconnaissance

This is the preparatory phase where we collect information about the target, it's used a set of techniques that can help us to get more familiar with our target. We can perform a passive reconnaissance or an active reconnaissance.

- Passive: we do not interact directly with the victim's system, it's mostly an external analysis of the target. Ex: Physical reconnaissance, Social Engineering

- Active: we have permission to perform a more direct approach. 

Target Validation: WhoIS, nslookup, dnsrecon

Finding Subdomains. Google Fu, dig, Nmap, Sublist3r, Bluto, crt.sh. What server, versions of services

Fingerprinting: Nmap, Wappalyzer, WhatWeb, BuiltWith, Netcat

DataBreaches: HaveIBeenPwned, Breach-Parse, WeLeakInfo


## Stage 2 - Scanning

- Port Scanning:Scan the target to gather informations about open ports, services running and their respective versions

- Vulnerability Scanning: finding existing weaknesses in the target sustem that could be exploited

- Network Mapping: Topology of network, routers, host information. Drawing a network diagram with available information

Tools: Nmap, Nessus

## Stage 3 -Gaining Access

This stage is where we entered the system through some previous identified vulnerability. The main goal consists in obtain root access.

## Stage 4 - Maintaining Access

We need to maintain the connection to the victim without the user's knowledge

## Stage 5 - Clearing Track

 This involves modifying/corrupting/deleting the values of Logs, modifying registry values and uninstalling all applications he used and deleting all folders he created. 
