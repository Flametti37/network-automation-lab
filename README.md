# network-automation-lab

Integrating network automation using Ansible playbooks with GitHub Self-Hosted Runners

Hardware:
Cisco 6800IA-FPD running 2960X IOS to work as a standalone switch
Cisco 2821 ISR running IOS 15.x
Windows Laptop
2 Patch cables
1 Rollover cable + DB9<->USB adapter for initial setup

Software:
WSL
Git
Ansible
GitHub Self-Hosted Runner
PuTTY (any terminal emulator that supports serial and SSH access)

Action runs -> Runs the ansible playbook (using the inventory file) -> runs a config commmand + uses ansible's backup utility
    backups get saved in folder
        git commit + push to GitHub


![successfulWorkflow](https://github.com/user-attachments/assets/d080dec1-4173-4267-96f2-7f47b47e4259)

![backupsOnGithub](https://github.com/user-attachments/assets/08445cdd-8ab0-4728-b0b7-9c4630a13094)
