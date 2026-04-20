#Day 4 – Nmap Basics

## Objective
To understand and perform basic network scanning using Nmap.

## Tools Used
- Kali Linux
- Nmap

## Practical Steps
- Verified Nmap installation using `nmap --version`
- Performed SYN scan using:
  nmap -sS scanme.nmap.org

## Output
- Successfully scanned the target and identified open ports

## Screenshot
 

## Theory

### What is Port Scanning?
Port scanning is the process of identifying open, closed, and filtered ports on a network to detect active services.

### Types of Scans
- SYN Scan (-sS): Fast and stealthy scan
- TCP Connect Scan (-sT): Full connection scan
- UDP Scan (-sU): Scans UDP ports

## Conclusion
Learned how to use Nmap for basic network scanning and understood different types of scans.
