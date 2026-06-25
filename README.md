# Active Directory lab setup

# Goal
I'm building this lab to understand how a real domain environment works and how security teams detect attacks with one. This project is a little more complicated than a basic Active Directory setup by adding a SIEM (Splunk) to collect logs, Kali Linux as an attacker machine and Atomic Red Team to simulate real-world attack techniques. The end goal is to see an attack happen, find it in the logs and understand how a SOC analyst would detect it.

# Tools used
- Oracle Virtualbox
- Windows Server 2022 (evaluation ISO)
- Windows 10 (evaluation ISO)
- Kali Linux
- Splunk (SIEM)
- Atomic Red Team
- draw.io (network diagram)

## Network Diagram

<img width="963" height="931" alt="image" src="https://github.com/user-attachments/assets/942b1133-1c7b-4e63-be2a-de79ed7bbdd5" />

## Project log
# Part 1: Objective and planning
I watched the overview, understood the goal of the project (build a domain, attack it, detect the attack in the logs) before touching any tools.
It matters knowing what I'm actually building toward so I can prevent wasting time and can connect each technical step to the bigger picture.

# Part 2: Foundations
1. What is Active Directory?
I looked into what Active Directory actually is/does before building it: it manages user accounts, computer accounts and access permissions for an entire company network).
2. Installing VirtualBox
VirtualBox lets me run several virtual machines on one PC, which makes this lab possible without needing extra physical hardware.
