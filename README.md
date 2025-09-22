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

- Configure Roles (For grouping permissions)
- Configure Departments (Ticket Visibility, Help desk vs SysAdmins, vs Netowrking)
- Configure Teams
- Configure Agents (Workers)
- Configure Users (Customers)
- Confirgure SLA's and Help Topics ( or when users create a ticket)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/SmWatdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/MlwLV8R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once I logged into the Admin account, I started configuring the main components: Roles, Departments, Teams, Agents (Workers), Users, SLAs, and Help Topics.
I began with Roles. From the Agent Panel, I went into the Roles section to check the pre-existing options. There were already some preset roles available, but I decided to create a new one called “Supreme Admin”, which I gave full access to every feature in osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/1AJ3MQl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/NnGEZH3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I went to the Departments tab and created a new department called Sysadmin, which I classified as a Top-Level Department. At this stage, I didn’t assign anyone to it yet. I planned to come back and do that later.
From there, I moved on to Teams. By clicking the Teams tab, I created a new team called “Online Banking.” I chose that name specifically to prepare for future tickets I planned to generate as part of the lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/mw9vcQJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
From there, I created a new Agent to handle the tickets we’ll be generating in future projects. I named her Jane. I assigned Jane to the SysAdmins department and gave her Supreme Admin access. Obviously, in a real work environment you wouldn’t give one agent unrestricted access, but for the sake of this lab, I wanted her to have everything she needed to resolve tickets without limitations.
I also added Jane to the Online Banking team we set up earlier.
Next, I created another account named John. Unlike Jane, John was configured with very limited permissions, this way I could simulate the difference between a fully privileged admin role and a restricted user.
</p>
<br />

<p>
<img src="https://i.imgur.com/g8I0GGY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/YtS47aK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I added a User, since users are the ones who actually create the tickets. To do this, I went into the Admin Panel, selected Users, and created a new account.
After that, I moved on to configuring SLAs. I set up three tiers to simulate real-world ticket priorities:
Sev-A – the highest priority, for the most critical issues.
Sev-B – medium priority, for important but less urgent problems.
Sev-C – the lowest priority, for minor or routine issues.
Finally, I began setting up Help Topics, which guide users when submitting tickets by categorizing their issues into the right workflow.
</p>
<br />

<p>
<img src="https://i.imgur.com/cw8Z6QE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, I set up the Help Topics. These give users options to categorize their problems, which makes it easier for the techs to quickly understand what type of issue needs to be resolved.
By default, osTicket already includes three topics, but I added six more to give broader coverage:
Password Reset
Equipment Request
Business Critical Outage
Personal Computer Issues
Access Issues
Other
With those in place, users now have a wide selection to choose from when submitting tickets, and the system is much easier to manage from the tech side.
And with that, I was done configuring osTicket for this project.
</p>
<br />
