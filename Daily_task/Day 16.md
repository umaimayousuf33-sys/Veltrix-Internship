# Day 16 – Directory Brute Force

## Objective
To identify hidden directories using Gobuster.

## Practical
Executed:

gobuster dir -u http://127.0.0.1:8000 -w /usr/share/wordlists/dirb/common.txt

## Results
Discovered:
- /admin
- /login
- /hidden
<img width="1366" height="728" alt="day 16 snap" src="https://github.com/user-attachments/assets/54fd680c-0947-4c79-bfb3-35531ef13d9b" />

## Theory
Directory brute forcing helps identify hidden folders on web servers.

## Conclusion
Learned how Gobuster works for discovering hidden directories.
