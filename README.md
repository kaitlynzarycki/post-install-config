<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to creat tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/vMuuS5A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/H2JYJlW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ok8wsID.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
<p>
1.) Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/eiknhPN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/x3UgGYO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Gk2KFHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/RAGdeZh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



</p>
<p>
2.) Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
<p/>
<br />

<p>
<img src="https://i.imgur.com/wYikJYH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3OgQlKB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

3.)Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>
<br />

<p>
<img src="https://i.imgur.com/1qPkcwg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ijYpmUZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

4.) Configure Users (customers)
Agent Panel -> Users -> Add New
Karen

<p>
<img src="https://i.imgur.com/i3FszT4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours

<p>
<img src="https://i.imgur.com/ySESpI9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rdQhZce.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
