# Day 13 – XSS Testing

## Objective
To find and test working XSS payloads.

## Practical
Tested the following payloads:

1. `<img src=x onerror=alert(!)>`
2. `<iframe src="javascript:alert(2)"></iframe> `

Both payloads executed successfully and triggered alert popups.

## Screenshot
<img width="1366" height="728" alt="day 13 1 paylopad" src="https://github.com/user-attachments/assets/2d756ed0-12b6-42a2-8a9d-89d2b4f505a5" />
<img width="1366" height="728" alt="payload 2" src="https://github.com/user-attachments/assets/33812190-c38f-4943-90ee-655adc1ca151" />


## Conclusion
Successfully identified working XSS payloads
