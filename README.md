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
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup.
first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
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
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />
<p>
<a href="https://imgur.com/rZ92VL7"><img src="https://i.imgur.com/rZ92VL7.jpg" title="source: imgur.com" /></a>
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />
<a href="https://imgur.com/Bf6mmTB"><img src="https://i.imgur.com/Bf6mmTB.jpg" title="source: imgur.com" /></a>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<a href="https://imgur.com/Qls8w8E"><img src="https://i.imgur.com/Qls8w8E.jpg" title="source: imgur.com" /></a>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<a href="https://imgur.com/svEtDhF"><img src="https://i.imgur.com/svEtDhF.jpg" title="source: imgur.com" /></a>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<a href="https://imgur.com/8wwfjvm"><img src="https://i.imgur.com/8wwfjvm.jpg" title="source: imgur.com" /></a>
</p>
<p>
<a href="https://imgur.com/ujc1fLa"><img src="https://i.imgur.com/ujc1fLa.jpg" title="source: imgur.com" /></a>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<a href="https://imgur.com/OKfBexf"><img src="https://i.imgur.com/OKfBexf.jpg" title="source: imgur.com" /></a>
</p>
<p>
<p>
<a href="https://imgur.com/5odAgWo"><img src="https://i.imgur.com/5odAgWo.jpg" title="source: imgur.com" /></a>
</p>
