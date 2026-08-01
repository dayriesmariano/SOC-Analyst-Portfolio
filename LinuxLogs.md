# Linux Log Report – Day 8

## Findings
- Successful login by user1 from 192.168.1.10  
- Failed login attempt for root from 192.168.1.20  
- Sudo session opened by user1  

## Evidence
![images](linuxlogs.png)

## Conclusion
Authentication logs show normal sudo usage but failed root login attempts may indicate brute‑force activity.
