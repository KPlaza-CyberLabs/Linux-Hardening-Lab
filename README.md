# Linux-Hardening-Lab
In this lab, I practiced basic Linux system hardening by updating the system and enabling the UFW firewall.  

## Tools Used
- Linux system
- Ubuntu VM (home lab)

## Steps Performed
1.  I used sudo apt update and sudo apt upgrade -y to apply security patches
2.  Enabled the firewall with sudo ufw enable
3.  I allowed SSH traffic on port 22 and verified the firewall status. Allowing SSH prevents accidental lockouts and keeps the VM accessible for future labs.  These steps demonstrate essential hardening practices for securing a Linux system.

## Screenshots
![linux hardening lab 1](https://github.com/user-attachments/assets/ecf46ad4-4b68-49f6-863d-dfa8d4b50da6)

![Linux hardening lab 2](https://github.com/user-attachments/assets/2e086df9-0021-4679-8ba9-1fba45ae6dec)


## What I learned
In this lab, I strengthened my understanding of foundational Linux hardening practices. I learned how important it is to keep a system updated with the latest security patches using sudo apt update and sudo apt upgrade, and how these updates help reduce vulnerabilities. I also gained hands‑on experience configuring the UFW firewall to control inbound traffic and protect the system from unauthorized access. Allowing SSH on port 22 reinforced the idea that firewall rules must be planned carefully to maintain both security and accessibility. Overall, this lab helped me build confidence in securing a Linux environment through routine patching and basic firewall configuration.

## Security Objective
Reduce the attack surface of a Linux system by applying security patches and enforcing firewall rules to control inbound traffic. 

## Risks Mitigated
- Unpatched vulnerabilities could allow attackers to exploit known CVEs
- Open ports increase exposure to unauthorized access and brute-force attacks
- Lack of firewall controls allows unrestricted inbound traffic from untrusted sources