# Week 2 - Footprinting & Reconnaissance

Cybersecurity & Ethical Hacking Project | Networkwalks

## Tools Used
- Maltego - Visual link analysis for networkwalks.com
- theHarvester - Email & subdomain harvesting for microsoft.com
- Zenmap / Nmap - Network scanning & live hosts discovery

## What I Did

### 1. Maltego
- Created a Domain entity for networkwalks.com
- Ran DNS transforms to find IP addresses, DNS names & related infrastructure
- Visualized the footprint as a graph

### 2. theHarvester
- Task 1: `theHarvester -d microsoft.com -l 1000 -b baidu`
- Task 2: `theHarvester -d microsoft.com -l 50 -b all`
- Collected emails, sub-domains & hosts from public sources

### 3. Zenmap (Nmap)
- Found my local IP & subnet using `ipconfig`
- Ran Ping Scan to find live hosts in my subnet
- Recorded IP addresses & MAC addresses
- Exported topology as PDF

## Key Learning
Footprinting is passive recon. Attackers gather all this WITHOUT touching the target - that's why defenders must minimize what they expose publicly.

## Screenshots
See /assets folder for Maltego graph, theHarvester output & Zenmap topology.

## Penetration Testing Report
[View the penetration testing report (PDF)](./PENETRATION%20TESTING%20REPORT_Alvin-Supeeti.pdf)
