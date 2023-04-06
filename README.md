# post-install-config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments 
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/0FzCdcQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to the Admin Panel -> Agents -> Roles.
Create a new role called "Admin" that has all available privileges. You can add these under the "permissions" tab and click all boxes.
</p>
<br />

<p>
<img src="https://i.imgur.com/R2kPzj2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel -> Agents -> Departments and add a new department. Label it "System Administrators". 
</p>
<br />

<p>
<img src="https://i.imgur.com/KRV4TVG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel -> Agents -> Teams and create a team. "Level II Support"; there should already be a Level I Support team existing. 
</p>
<br />
