<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. In this lab, we will perform activites acting as the Administrator. In the next lab we will perform activities acting as the Agent or the Help Desk Tech.<br />


<h2>Overview</h2>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1: Configure Roles
- Item 2: Configure Departments
- Item 3: Configure Teams
- Item 4: Configure to Allow Anyone to Create Tickets
- Item 5: Configure Agents (workers)
- Item 6: Configure Users (customers)
- Item 7: Configure SLA
- Item 8: Configure Help Topics
  
<h2>Configuration Steps</h2>
<b> Item 1: Configure Roles</b>
<p>
  <img width="1440" alt="01" src="https://github.com/user-attachments/assets/62fb5c0a-4aef-4e57-a2af-67b3fe923cf1">
</p>
<p>
  <img width="1440" alt="02" src="https://github.com/user-attachments/assets/1872cdaf-04c3-45af-b5db-0e3110d71e7c">
</p>
<p>
  <img width="1440" alt="03" src="https://github.com/user-attachments/assets/876821f9-db01-4ce3-9464-f570beb83066">
</p>
<p>
Click Agent > Roles > Add New Role > Name your Role > Click Permissions > Under all categories (Tickets, Tasks, and Knowledgebase) check the boxes for all permissions > Click Add Role.
</p>
<br />

<b> Item 2: Configure Departments</b>
<p>
<img width="1388" alt="4" src="https://github.com/user-attachments/assets/07a86377-9772-484a-9159-e5b559a50c92">
</p>
<p>
<img width="1356" alt="5" src="https://github.com/user-attachments/assets/bebe41eb-324d-438d-b88a-0ca98547c3d5">
</p>
<p>
Ensure you are on the Agents tab still. Click Departments > Add New Department > Give it a name > Click Add Dept.
</p>
<br />

<b> Item 3: Configure Teams</b>
<p>
<img width="1369" alt="6" src="https://github.com/user-attachments/assets/876fc060-bb4a-495a-935d-e2e3db37fe7b">
</p>
<p>
<img width="1270" alt="7" src="https://github.com/user-attachments/assets/7600eee0-c1af-4b65-b611-5b0ed29b3d93">
</p>
<p>
Ensure you are on the Agents tab still. Click Teams > Add New Team > Name it > Click Members and add yourself to the team > Click Create Team.
</p>
<br />

<b> Item 4: Configure to Allow Anyone to Create Tickets </b>
<p>
  <img width="1340" alt="8" src="https://github.com/user-attachments/assets/670a19f0-4ac2-4838-8eaa-6c91fe44f2f9">
</p>
<p>
Click settings > Users > Settings > and ensure that the box next to Require Registration and Login to Create Tickets is unchecked.
</p>
<br />

<b> Item 5: Configure Agents (workers) </b>
<p>
<img width="1171" alt="9" src="https://github.com/user-attachments/assets/97db964c-d02c-4e3a-b52a-ffdcdac05b84">
</p>
<p>
<img width="1351" alt="10" src="https://github.com/user-attachments/assets/976ef460-e03f-4dd2-bd66-cba1f9e25297">
</p>
<p>
<img width="1253" alt="11" src="https://github.com/user-attachments/assets/1ea0b46e-06a6-4ae3-87c7-fc56dbac5124">
</p>
<p>
We are still in the Admin panel. From here Click Agents > Add New > Add the names of the individuals (ex: Jane Doe or John Doe) > Set username and password (Don't forget these credentials) > Uncheck the box next to Send the Agent a password reset email and uncheck the box next to Require a password change at the next login > Click Set. Next go to Access > Set the Primary Department to System Administrators and Supreme Admin > Click Teams > Add Jane.doe to Level II Support > Create. You can repeat this process to create another user if needed. 
</p>
<br />

<b> Item 6: Configure Users (customers)</b>
<p>
<img width="1364" alt="12" src="https://github.com/user-attachments/assets/74592881-b47a-47f8-9216-69493ce3b138">
</p>
<p>
<img width="1186" alt="13" src="https://github.com/user-attachments/assets/2f445caf-5f58-45ed-beaa-2c0785dd6cb2">
</p>
<p>
<img width="1240" alt="14" src="https://github.com/user-attachments/assets/5f1cc7f9-dcc0-4db5-8f6b-a805b8f69526">
</p>
<p>
Click the Agent Panel > Users > Add New User > Type in the customer Name and Email > Add User. Repeat this process to add more users if needed. 
</p>
<br />

<b> Item 7: Configure SLA </b> 
<p>
<img width="1345" alt="15" src="https://github.com/user-attachments/assets/8de442e4-1ad7-4a3f-a5c7-90bcdc28296f">
</p>
<p>
<img width="1268" alt="16" src="https://github.com/user-attachments/assets/c638b376-dd5a-4139-af87-79e94143c32c">
</p>
<p>
Return to the admin panel > Click Manage > SLA > Click Add New SLA Plan > Name SEV-A > Grace Period of 1 > Schedule 24/7 > Add Plan > Add New SLA Plan > Name SEV-B > Grace Period 4 > Schedule 24/7 > Add Plan > Add New SLA Plan > Name SEV-C > Grace Period 8 > Schedule Mon-Friday (Business Hours).
</p>
<br />

<p>
<img 
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
