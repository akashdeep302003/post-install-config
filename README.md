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

- Configure access for Admin and End User panels.
- Set up Roles and Departments for better organization.
- Create Teams for cross-department collaboration.
- Establish Ticket Permissions to define user access.
- Add Agents (staff) and Users (customers).
- Configure SLA (Service Level Agreements) to define response times.
- Create Help Topics to streamline ticket categorization.

<h2>Configuration Steps</h2>
1. Acess Admin and End User Panels
<p>
<img src="https://i.imgur.com/rrNUb0H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>After completing the installation we can access the following panels to manage osTicket:
Admin Panel URL: http://localhost/osTicket/scp/login.php
 End User Panel URL: http://localhost/osTicket
</p>
2. Configured Roles for Permissions
<br />

<p>
<img src="https://i.imgur.com/oktDHqi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Roles allows us to group permissions for agents effectively. Now as an Admin we set up roles to control what agents can do.
Navigated to Admin Panel → Agents → Roles.
Example Role: Supreme Admin (full permissions).
</p>
3. Configured Departments for Ticket Visibility
<br />

<p>
<img src="https://i.imgur.com/Zgot9oA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Departments help categorize tickets and assign visibility to specific groups, such as Help Desk, SysAdmins, or Networking.
Navigated to Admin Panel → Agents → Departments.
Example Department: SysAdmins (manages system-related tickets).
</p>
4. Configured Teams for Cross-Department Collaboration
<br />

<p>
<img src="https://i.imgur.com/n6j5t9w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Teams allow agents from different departments to work together on specific tasks or tickets.
Navigated to Admin Panel → Agents → Teams.
Example Team: Online Banking (pulls agents from multiple departments for banking-related tickets).
</p>
5. Configured User Registration and Ticket Creation Settings
<br />

<p>
<img src="https://i.imgur.com/stw3Ljk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Control whether users (customers) need to register to create tickets.
Navigated to Admin Panel → Settings → User Settings.
Example: Allow unregistered users to create tickets: Uncheck this option if you want only registered users to create tickets.
Require registration and login to create tickets: Enable this option for stricter control.
</p>
6.Configured Agents (Workers) 
<br />

<p>
<img src="https://i.imgur.com/vA3EXqL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Agents are the staff members who can manage tickets. Now we Assigned agents to specific departments for efficient ticket handling.
Navigate to Admin Panel → Agents → Add New.
Example Agents:
Jane (assigned to SysAdmins Department).
John (assigned to Support Department).
</p>
7. Configured Users (Customers)
<br />

<p>
<img src="https://i.imgur.com/bz5tMuc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users are the end customers who can submit tickets. Here we added new users and managed their profiles.
Navigate to Agent Panel → Users → Add New.
Example Users:
Karen
Ken
</p>
8.
<br />

<p>
<img src="https://i.imgur.com/86Q9ISD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We Define Service Level Agreements (SLAs) and help topics for better ticket prioritization and user experience.
- Configured SLA (Service Level Agreement):
Navigate to Admin Panel → Manage → SLA.
Examples:
Sev-A: Grace Period: 1 hour, Schedule: 24/7.
Sev-B: Grace Period: 4 hours, Schedule: 24/7.
Sev-C: Grace Period: 8 hours, Schedule: Business Hours
- Configured Help Topics:
Navigate to Admin Panel → Manage → Help Topics.
Examples:
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<br />

