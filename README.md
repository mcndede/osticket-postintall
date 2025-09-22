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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we log into the admin account we are going to configure the Roles, Departments, Teams, Agents(Workers), Users, Sla, and Help Topics. Starting with the roles, we first go to the agent panel then the role section to view all pre-existing roles. There are already some preset but I made an additional role called "Supreme admin" which has access to everything. From there we will create a new department called Sysadmins
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Going to the departments tab we create the department Sysadmin which is classified as "Top Level Department". As of now it doesnt have anyone assigned to it but we will do that soon. For now we will Configure the teams by clicking the teams tab and creating a new team called "Online Banking". I named it that for the sake of future tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From there we will make a new agent to be able to work the tickets we will create in future projects. I named her jane. She is apart of the "SysAdmins department" and has "Spreme access". Obviously you wouldnt want to do this in a real work enviroment but for the sake of this project she had everything she needs to complete tickets. Also I added her to the "Banking team" we created earlier. Now I will create another account named john who will lack most permissions
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will add a user. They will be the one to create tickets for us. To do so we will go to admin panel then users and create user. Finally we will configure SLA's and Help Topics.  For the SLA's we will create three tiers: Sev-A being the highest and most important, Sev-B being second Highest, Sev-c being the least important.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then we will make the help topics. These will be here for the users to choose what there problems relate to to help the techs decipher what needs to be done to resolve the issue. We will create 6 topics in addition to the 3 the osTicket created for us, Those being: Password reset, Equipment Request, Business Critical Outage, Personal Computer issues, Access Issues, and Other. This will allow for a broad selection for the users to choose from.
</p>
<br />
