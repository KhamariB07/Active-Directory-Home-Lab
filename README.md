# Active Directory & IT Infrastructure Home Lab

<img width="1611" height="960" alt="Screenshot 2026-10-02 at 2 50 46 PM" src="https://github.com/user-attachments/assets/c1b0ef0d-fc14-4baa-bbc1-83a30306f153" />



## Objective
This project demonstrates the deployment of a functional home lab environment using **Active Directory Domain Services (AD DS)**. The lab simulates my ability to establish network structure, including virtualized routing, user provisioning, and centralized authentication.
## Skills & Environments
* **Operating Systems:** Windows Server 2019, Windows 10
* **Infrastructure:** Active Directory (AD DS), DNS, DHCP, NAT/Routing
* **Automation:** PowerShell (scripting user creation)
* **Virtualization:** Oracle VirtualBox

## Network Architecture
* **Domain Controller (DC):** Windows Server 2019 running AD DS, DHCP, and DNS. Contains two network adapters (NAT for external internet access, Internal for the private network).
* **Client Machine:** Windows 10 Enterprise, joined to the domain, receiving its IP address via the DC's DHCP scope.

## Acknowledgements
* Lab concept and PowerShell script structure inspired by [Josh Madakor's Active Directory Hands-On Course](https://www.youtube.com/).
