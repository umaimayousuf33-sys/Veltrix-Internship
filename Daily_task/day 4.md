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
<img width="2976" height="1985" alt="1000654936" src="https://github.com/user-attachments/assets/fb3325de-fde7-4815-a670-30c9c84b1fbc" />
<img width="2976" height="2897" alt="1000654937" src="https://github.com/user-attachments/assets/c7883634-25b4-4d79-ae9b-7ab6a07d71a2" />
 <img width="2976" height="2945" alt="1000654935" src="https://github.com/user-attachments/assets/604513e1-bf8d-4370-9786-83fce2d9296b" />

## Theory

### What is Port Scanning?
Port scanning is the process of identifying open, closed, and filtered ports on a network to detect active services.

### Types of Scans
- SYN Scan (-sS): Fast and stealthy scan
- TCP Connect Scan (-sT): Full connection scan
- UDP Scan (-sU): Scans UDP ports

## Conclusion
Learned how to use Nmap for basic network scanning and understood different types of scans.
