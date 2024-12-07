<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Post Installation Configuration</h1>
This project focuses on setting up osTicket as a ticketing system. It involves configuring multiple agents, assigning them to designated departments, roles, and permissions. Furthermore, Service Level Agreements (SLAs), help topics, and users will be set up to ensure the system operates seamlessly.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop 
- osTicket
- Virtual Machine

<h2>Operating Systems Used </h2>

- Windows 10</b>


<h2>Project Walk-through</h2>

<p align="center">
In order to start configuring "Roles", navigate over to the "Agents' tab and select "Roles" underneath the "Agents" tab. Enter the Role name "Super Admin". 
<br/>

<img src="https://i.ibb.co/MP1WQRF/1.jpg" alt=""/>

<br/> 

<p align="center">
In the "Permissions" tab, we will grant this role full permissions for "Tickets," "Tasks," and "Knowledgebase." This is why we’ve named it "Super Admin.
<br />

<img src="https://i.ibb.co/Nxfjw9n/2.jpg" alt=""/>

<br/>

<p align="center"> 
To create or set up a department, click on "Departments" found just below the "Agents" tab. Enter "SysAdmin" as the department name and proceed to create the department.
<br />

<img src="https://i.ibb.co/ZgH1f6J/3.jpg" alt=""/>

<br/>

<p align="center"> 
Next, we'll create a team by navigating to the "Teams" tab under the "Agents" section. We'll name this team "Level II Support.
<br/>

<img src="https://i.ibb.co/1X2PrGs/4.jpg" alt=""/>

<br/>

<p align="center">
To allow anyone to create a ticket, navigate to Settings > Authentication Settings and ensure that the "Require Registration and Login to Create Tickets" option is unchecked.
<br/>

<img src="https://i.ibb.co/bLJtx3W/5.jpg" alt=""/>

<br/>
To create agents (Helpdesk Workers), go back to the "Agents" tab, select "Agents," and complete the required fields
<p align="center">

<br/>

<img src="https://i.ibb.co/qM02CGy/6.jpg" alt=""/>

<br/>

<p align="center">
Located next to the username. Select "Set Password". Uncheck "Send the agent a password reset email" and "Require password change at next login"
<br/>

<img src="https://i.ibb.co/QNs9JFx/7.jpg" alt=""/>

<br/>

<p align="center">
Lets create another Agent with the same steps as the previous Agent. This Agent will be assigned to the "Support" department. 
<br/> 

<img src="https://i.ibb.co/J2RbZgg/8.jpg" alt=""/>
<img src="https://i.ibb.co/hcTGKkL/9.jpg" alt=""/>

<br/>

<p align="center"> 
Next, we'll create some users (the customers). Go to the "Agent Panel" in the top right corner of the page, then select Users > Add Users and fill in the required fields. Follow these steps to create two users.
<br/>

<img src="https://i.ibb.co/HdDD6zw/10.jpg" alt=""/>

<br/>

<p align="center">
Next, we'll configure SLA plans. Go to the Admin Panel, then navigate to Manage > SLA. Create three different severity levels, each with its own grace period and schedule.
<br/>

<img src="https://i.ibb.co/vx6gNsH/11.jpg" alt=""/>
<img src="https://i.ibb.co/1R99hLS/12.jpg" alt=""/>
<img src="https://i.ibb.co/qFw46YT/13.jpg" alt=""/>

<br/>

<p align="center">
Lastly, we will create Help Topics. Help topics help categorize the tickets. Manage> Help Topics and create: "Buisness Critical Outage", "PersonaL Computer Issues", "Equipment Request",and "Password Reset". 
<br/>

<img src="https://i.ibb.co/Ssw6HHn/14.jpg" alt=""/>
<img src="https://i.ibb.co/6vFFPZ3/15.jpg" alt=""/>

