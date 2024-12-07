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

To begin configuring "Roles," go to the "Agents" tab and select "Roles" from the dropdown menu. Enter "Super Admin" as the Role name.<br/>
<br/>
<br/>
<img src="https://i.ibb.co/MP1WQRF/1.jpg" alt=""/>
<br/>
<br/> 
In the "Permissions" tab, we will grant this role full permissions for "Tickets," "Tasks," and "Knowledgebase." This is why we’ve named it "Super Admin.
<br/>
<br/> 
<img src="https://i.ibb.co/Nxfjw9n/2.jpg" alt=""/>
<br/>
<br/> 
To create or set up a department, click on "Departments" found just below the "Agents" tab. Enter "SysAdmin" as the department name and proceed to create the department.
<br/>
<br/>
<img src="https://i.ibb.co/ZgH1f6J/3.jpg" alt=""/>
<br/>
<br/> 
Next, we'll create a team by navigating to the "Teams" tab under the "Agents" section. We'll name this team "Level II Support.
<br/>
<br/> 
<img src="https://i.ibb.co/1X2PrGs/4.jpg" alt=""/>
<br/>
<br/> 
To allow anyone to create a ticket, navigate to Settings > Authentication Settings and ensure that the "Require Registration and Login to Create Tickets" option is unchecked.
<br/>
<br/> 
<img src="https://i.ibb.co/bLJtx3W/5.jpg" alt=""/>
<br/>
<br/> 
To create agents (Helpdesk Workers), go back to the "Agents" tab, select "Agents," and complete the required fields
<br/>
<br/> 
<img src="https://i.ibb.co/qM02CGy/6.jpg" alt=""/>
<br/>
<br/> 
Located next to the username. Select "Set Password". Uncheck "Send the agent a password reset email" and "Require password change at next login"
<br/>
<br/>
<img src="https://i.ibb.co/QNs9JFx/7.jpg" alt=""/>
<br/>
<br/>
Lets create another Agent with the same steps as the previous Agent. This Agent will be assigned to the "Support" department. 
<br/>
<br/>
<img src="https://i.ibb.co/J2RbZgg/8.jpg" alt=""/>
<img src="https://i.ibb.co/hcTGKkL/9.jpg" alt=""/>
<br/>
<br/>
Next, we'll create some users (the customers). Go to the "Agent Panel" in the top right corner of the page, then select Users > Add Users and fill in the required fields. Follow these steps to create two users.
<br/>
<br/> 
<img src="https://i.ibb.co/HdDD6zw/10.jpg" alt=""/>
<br/>
<br/> 
Next, we'll configure SLA plans. Go to the Admin Panel, then navigate to Manage > SLA. Create three different severity levels, each with its own grace period and schedule.
<br/>
<br/> 
<img src="https://i.ibb.co/vx6gNsH/11.jpg" alt=""/>
<img src="https://i.ibb.co/1R99hLS/12.jpg" alt=""/>
<img src="https://i.ibb.co/qFw46YT/13.jpg" alt=""/>
<br/>
<br/> 
Finally, we will set up Help Topics, which are used to categorize tickets. Navigate to **Manage > Help Topics** and create the following: "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."
<br/>
<br/>
<img src="https://i.ibb.co/Ssw6HHn/14.jpg" alt=""/>
<img src="https://i.ibb.co/6vFFPZ3/15.jpg" alt=""/>
