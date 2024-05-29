# osTicket-Post-Installation-Configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=HGywPhfKt4E)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

- ![image](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/01acca90-4c14-444e-85f9-0d15195f4d2d)

- Remote Desktop

- ![Screenshot 2024-05-24 103710](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/3bdc5f5a-2ea8-410b-aef1-7a3292850cb7)

- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1 Confifure Roles
- Roles
Admin Panel -> Agents -> Roles
Supreme Admin

- ![image](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/800e1476-b36d-40c1-a87c-2e488ac3cee4)

- Step 2 Configure Departments
- Departments
Admin Panel -> Agents -> Departments
System Administrators

-![image](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/260491fc-17ee-4728-9373-927a5de60400)


- Step 3 Configure Teams
- Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support

-![Screenshot 2024-05-29 092307](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/0e854a2c-cc58-4d81-89eb-480f194e4b6d)


- Step 4 Configure Agents
- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John

-![Screenshot 2024-05-29 092629](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/7854eb52-176a-4946-8350-acf1b28dd515)


- Step 5 Configure Customers
- Users 
Agent Panel -> Users -> Add New
Karen
Ken

-![Screenshot 2024-05-29 092959](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/3359f541-6ee0-4a12-a36f-80610271835a)


- Step 6 Configure SLA
- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

-![Screenshot 2024-05-29 093344](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/c67178b8-0540-41d0-9490-4e2a51019235)


- Step 7 Configure Help Topics
- Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

-![Screenshot 2024-05-29 094030](https://github.com/MarvisKidd/osTicket-Post-Installation-Configuration/assets/169103317/4fe9ed3b-b215-4c4a-9fb5-8d2c23adaf13)


