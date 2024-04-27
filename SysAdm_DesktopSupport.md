
<h1> Multi-OS Hypervisor Setup </h1>

- Configured a virtualization environment using Proxmox to run multiple operating systems concurrently, including Windows 10, Windows 11, Ubuntu, Fedora and RHEL.

- Employed standardized networking protocols and configurations to interconnect these OS instances within an internal network. 

- Established seamless communication and data exchange among the OSs, replicating collaboration and resource sharing. Proficiently implemented firewall rules, VLANs, or other networking techniques to ensure security and optimize performance within the virtualized environment.



<h1> Active Directory Domain Establishment and PowerShell User/Group Management </h1>

- Established a robust Active Directory (AD) domain infrastructure utilizing Server Manager, configuring core domain services and policies to ensure a secure and efficient network environment.

<strong> Promiting Server to Domain Controller </strong>

<img src="https://i.imgur.com/NTAdkVg.png" alt="Promoting Server to Domain Controller">

<strong> Adding RAS role to DC </strong>

<img src="https://imgur.com/IvwWHg0.gif" alt="Adding RAS role to DC">

<strong> Adding DHCP role to DC </strong>

<img src="https://i.imgur.com/o7I8iql.gif" alt="Adding DCHP role to DC">

<strong> Bulk account creation with Powershell </strong>

- Implemented PowerShell scripting to automate user and group creation processes within the AD, optimizing administrative workflows and ensuring consistent naming conventions and security settings. Rigorously tested the domain functionality by seamlessly joining desktop systems to the domain controller using PowerShell-generated Windows profiles.

https://github.com/Rvangine/Rvangine/assets/99094300/ada93def-3369-49d5-bf2c-524ae03ad66d


- Validated user access to designated resources provisioned via security groups, confirming precise access control and streamlined resource allocation based on defined permissions.

<strong> Image & Domain Join VM on Domain </strong> 



https://github.com/Rvangine/Rvangine/assets/99094300/1f7dad4a-09fd-4dcc-90dc-62a3c537eb46



- Developed comprehensive documentation outlining the domain setup, user provisioning procedures, and group-based resource access for future reference and scalability.

<h1> Automated Network Printer Assignment via AD-based GPOs </h1>

- Engineered and implemented a dynamic solution utilizing Windows Group Policy Objects (GPOs) to automate network printer assignments for users based on their Active Directory (AD) object locations.

- Designed and deployed customized GPOs, leveraging AD organizational structure to seamlessly assign network printer objects to users upon login, optimizing printing workflows and enhancing user productivity. 

- Conducted thorough testing and validation to ensure accurate and efficient printer mappings across diverse AD organizational units (OUs) and user groups. Documented the process and provided comprehensive user guides for seamless future maintenance and scalability.
