<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin

- Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

- Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support

- Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 

- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John

- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

- Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dqSYoEf.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After doing doing all the prequisie and installions for osTicket, this is where I configured everything as a admin. As the admin I was going through the settings to see what I can congfigure. I also have the ablitiy to add any number of agents and users as well. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ZIcLyfW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this picture I where I was configuring the new agents into the database and giving them access to since roles in their according departments. Also, for one of the Access levels or Department types, the Supreme Admin is a category that I created and configured it so that who ever has this has fully access to everything like a administrator.  
</p>
<br />

<p>
<img src="https://i.imgur.com/TfLWRza.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These are the following agents that I have created that will be taking the tickets from other users.
</p>
<br />

<p>
<img src="https://i.imgur.com/AyBQ1Z7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These are the following users that I configured to give the the other agents that are configured into the system already. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WJUVCyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These are the roles that I was able to configure for the agents and the Supreme Admin the is the custom one made from the admin. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Poy0pKK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/QRCNnTf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/U5Gu4Lh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
