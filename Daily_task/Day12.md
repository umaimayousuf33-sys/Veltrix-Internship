# Day 12 – XSS Theory

## Objective
To understand Cross-Site Scripting (XSS) and demonstrate it in a safe lab environment.

## Practical
- Used a local demo page / vulnerable lab
- Injected: `<script>alert(1)</script>`
- Observed alert popup (XSS)

## Screenshot
<img width="1366" height="728" alt="xss demo alert" src="https://github.com/user-attachments/assets/b99daa80-5567-4091-b097-5d6ece4d0497" />
<img width="1366" height="728" alt="xss demo" src="https://github.com/user-attachments/assets/e0479a4a-e162-41f7-9551-211719639ace" />


## Theory

### What is XSS?
Cross-Site Scripting (XSS) is a vulnerability where malicious scripts are injected into web pages.

### Stored vs Reflected XSS
- **Stored XSS**: Script is saved on the server and runs when users open the page.
- **Reflected XSS**: Script is reflected in the response and runs immediately.

## Conclusion
Understood XSS and demonstrated it safely in a controlled lab
