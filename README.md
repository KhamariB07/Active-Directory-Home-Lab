# Active Directory & IT Infrastructure Home Lab

## Objective
This projection demonstrates the deployment of a functional home lab environment using **Active Directory Domain Services (AD DS)**. The lab simulates my ability to establish network structure, including virtualized routing, user provisioning, and centralized authentication.
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
