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


<h2>Configuration Steps</h2>

<p>
Now that osTicket has been successfully configured from the ground up, the next steps will consist of system administration and post installation setup.
First, configure new roles within the help desk. To do so, go to Admin panel -  Agents - Roles. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Be aware that roles are used to determine an agents permissions. That being said, not all agents will have unlimited access. During the setup process your screen should resemble something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>
<a href="https://imgur.com/H7T2Ho9"><img src="https://i.imgur.com/H7T2Ho9.jpg" title="source: imgur.com" /></a>
</p>
<p>
<a href="https://imgur.com/iAFWxKZ"><img src="https://i.imgur.com/iAFWxKZ.jpg" title="source: imgur.com" /></a>
</p>
<br />
<p>
</p>
<p>
Select the "Departments" in the agents tab. You will be able to create a new department from here. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. For this example, you will be create the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be established in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Each time a new department is configfured, a new team is required to be established. Teams allow you to pull agents from various departments. For example, you may have an A team that has specialists from a number of specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To create a team, go to Agents - Teams. A Level I support team has been created by default. In this example, a Level II Support Team will be created. 
</p>
<br />
<p>
<a href="https://imgur.com/rZ92VL7"><img src="https://i.imgur.com/rZ92VL7.jpg" title="source: imgur.com" /></a>
</p>
<p>
After the creation of a new team, you will configure settings that will enable anyone to create tickets. Admin Panel-Settings-User Settings.

</p>
<br />
<a href="https://imgur.com/Bf6mmTB"><img src="https://i.imgur.com/Bf6mmTB.jpg" title="source: imgur.com" /></a>
</p>
<p>
After the configuration of ticket settings, next you will be required to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<a href="https://imgur.com/Qls8w8E"><img src="https://i.imgur.com/Qls8w8E.jpg" title="source: imgur.com" /></a>
</p>
<p>
After creating the required agents, you will then create users. Users are customers that create tickets when they are have issues of varying degrees. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<a href="https://imgur.com/svEtDhF"><img src="https://i.imgur.com/svEtDhF.jpg" title="source: imgur.com" /></a>
</p>
<p>
SLAs provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLAs are created by going to Admin Panel-Manage SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<a href="https://imgur.com/8wwfjvm"><img src="https://i.imgur.com/8wwfjvm.jpg" title="source: imgur.com" /></a>
</p>
<p>
<a href="https://imgur.com/ujc1fLa"><img src="https://i.imgur.com/ujc1fLa.jpg" title="source: imgur.com" /></a>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage". This particualr topic could be in reference to customers inability to access mobile banking or any number of other user related issues.
</p>
<br />
<a href="https://imgur.com/OKfBexf"><img src="https://i.imgur.com/OKfBexf.jpg" title="source: imgur.com" /></a>
</p>
<p>
<p>
<a href="https://imgur.com/5odAgWo"><img src="https://i.imgur.com/5odAgWo.jpg" title="source: imgur.com" /></a>
</p>
