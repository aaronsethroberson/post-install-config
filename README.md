<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Post Installation Configuration</h1>
This project will concentrate on configuring osTicket as a ticketing system. We'll set up multiple agents, assigning them to specific departments, roles, and permissions. Additionally, we will configure Service Level Agreements (SLAs), help topics, and users to ensure the system is fully operational<br />

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

![Screenshot 2024-09-27 143009](https://github.com/user-attachments/assets/207dd691-cfef-4d8b-9b31-dc5f8c862efa)

<br/> 

<p align="center">
In the "Permissions" tab, we will grant this role full permissions for "Tickets," "Tasks," and "Knowledgebase." This is why we’ve named it "Super Admin.
<br />

![image](https://github.com/user-attachments/assets/957d5397-dd91-4971-b4d1-99b704b20a63)

<br/>

<p align="center"> 
To create or set up a department, click on "Departments" found just below the "Agents" tab. Enter "SysAdmin" as the department name and proceed to create the department.
<br />

![Screenshot 2024-09-27 143554](https://github.com/user-attachments/assets/e864c87a-83aa-46a8-aa82-edd5d41133f4)

<br/>

<p align="center"> 
Next, we'll create a team by navigating to the "Teams" tab under the "Agents" section. We'll name this team "Level II Support.
<br/>

![image](https://github.com/user-attachments/assets/40a0a8fd-1d0c-4756-81aa-4991ca56326f)

<br/>

<p align="center">
To allow anyone to create a ticket, navigate to Settings > Authentication Settings and ensure that the "Require Registration and Login to Create Tickets" option is unchecked.
<br/>

![Screenshot 2024-09-27 143959](https://github.com/user-attachments/assets/2e313b6a-86f4-4cde-8c6c-2158b2323f9e)

<br/>
To create agents (Helpdesk Workers), go back to the "Agents" tab, select "Agents," and complete the required fields
<p align="center">

<br/>

![Screenshot 2024-09-27 145802](https://github.com/user-attachments/assets/89c536a3-bbe6-4083-8f45-7d50d0cf66d9)

<br/>

<p align="center">
Located next to the username. Select "Set Password". Uncheck "Send the agent a password reset email" and "Require password change at next login"
<br/>

![Screenshot 2024-10-16 020827](https://github.com/user-attachments/assets/71b3e060-e464-4a83-a58a-1bf73887619f)

<br/>

<p align="center">
Lets create another Agent with the same steps as the previous Agent. This Agent will be assigned to the "Support" department. 
<br/> 

![image](https://github.com/user-attachments/assets/c9eb93d8-8d14-442b-92fd-e706f0c75cfe)
![image](https://github.com/user-attachments/assets/8cebe886-476d-4106-9a16-327276dc7b89)

<br/>

<p align="center"> 
Next, we'll create some users (the customers). Go to the "Agent Panel" in the top right corner of the page, then select Users > Add Users and fill in the required fields. Follow these steps to create two users.
<br/>

![Screenshot 2024-09-27 150535](https://github.com/user-attachments/assets/e669d492-58d9-44c1-bb02-7d98684e161b)

<br/>

<p align="center">
Next, we'll configure SLA plans. Go to the Admin Panel, then navigate to Manage > SLA. Create three different severity levels, each with its own grace period and schedule.
<br/>

![Screenshot 2024-09-27 150923](https://github.com/user-attachments/assets/3d6aabb5-da4d-45f6-ad2c-8ec5baf26f66)
![Screenshot 2024-09-27 151009](https://github.com/user-attachments/assets/54b4cfc1-d21f-4ea1-b5fd-dfbfa49e83a7)
![Screenshot 2024-09-27 151105](https://github.com/user-attachments/assets/215e1d85-ed99-4354-8535-da729d43364d)

<br/>

<p align="center">
Latly, we will create Help Topics. Help topics help categorize the tickets. Manage> Help Topics and create: "Buisness Critical Outage", "PersonaL Computer Issues", "Equipment Request",and "Password Reset". 
<br/>

![image](https://github.com/user-attachments/assets/497cd728-6d60-468a-be17-0e73fccceba5)
![image](https://github.com/user-attachments/assets/552835af-81e5-4267-b6cc-f3a25aec4c45)

