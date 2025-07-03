<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system.
<p>
<br />

<h2>Video Demonstration</h2>

- ### [YouTube: Lab 3.2. osTicket Post Configuration Setup | Azure | IT Tutorial Speedrun w/o Commentary](https://youtu.be/YpmGZxVk4uY)
<h2>Installation Steps (8 Steps)</h2>

<p>
</p>
<p>
Now that osTicket is configured, next is system administration and post installation setup.

1.) Create a role within the Helpdesk titled "Supreme Admin".

    - Note: Roles are used to determine an agent's permissions.
  
  - Admin panel -> Agents -> Roles -> Add New Role -> "Supreme Admin" -> Permissions: allow ALL permissions -> Add Role
   
  - Finally, observe the successfully created "Supreme Admin" tab below:

</p>
<img src="https://github.com/user-attachments/assets/81f4a89e-83bc-4539-af98-ce804b26caa1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
2.) Create a department for your Supreme Admin(s) titled "SysAdmins".

    - Note: Agents are to be assigned to a specific department depending on their role within the Helpdesk.
  
  - In the Agents tab, select "Departments" -> Add New Department
    
  Note: Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.

</p>
<img src="https://github.com/user-attachments/assets/d3a690bb-603d-4411-be42-e912d2f2cf1f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
3.) After configuring a new department we will set up a new team. 

  - Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments.
  - For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product.
  - To set up a team go to Agents -> Teams.
  - A Level I support team has been created by default, in this example we will create a Level II Support Team.

<p>
<img src="https://github.com/user-attachments/assets/ac1466e3-68fd-4fb0-a322-568df5f7d969" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
4.) Now that we have a new team set up, we can create a setting which will permit the creation of tickets for anyone.

 - Admin Panel -> Settings -> User Settings.

</p>
<img src="https://github.com/user-attachments/assets/e7cb9f23-d2a2-4401-b07e-094a6cf86bf4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
5.) It is now time to create Agents. 
  
  - Agents are the employees of the helpdesk that actually work on solving tickets. 
  - Agents are assigned primary departments and given a primary role for tickets sent to their department.
  - Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in.
  - Permissions, Access, & Teams are be assigned in the Agents tab.
    
</p>
<img src="https://github.com/user-attachments/assets/b0c206ee-8d9a-4ae7-ac3d-fcffb8403574" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
6.) After creating some agents we will create users. 

  - Users are customers that create tickets when they are having issues.
  - A user is identified with their E-mail address.
  - To create a user follow this path Agent Panel -> Users -> User Directory -> Add new. 

</p>
<img src="https://github.com/user-attachments/assets/46f3dfca-1f4a-468e-bcfa-18e7d8f2ecd3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
7.) SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. 

  - SLA Plans are created by going to Admin Panel -> Manage -> SLA Plans.
  - Each SLA has a schedule and within that schedule there is a grace period.
  - In this example SEV-A has a 24/7 and a one hour grace period. 

</p>
<img src="https://github.com/user-attachments/assets/fe78784e-9fb0-40e0-9b25-da6b910339ad" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
8.) Help topics help users categorize their tickets. 

  - In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 

</p>
<img src="https://github.com/user-attachments/assets/5d7b424f-4a1a-4148-9306-0cff72ca5c56" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
