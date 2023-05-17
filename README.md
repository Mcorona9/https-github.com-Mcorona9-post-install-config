
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This lab demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
After successfully configuring osTicket, it's time to perform system administration and post-installation setup. Our first task is to create new roles within the help desk. To do this, go to the Admin panel, navigate to Agents, and click on Roles. Click "Add new role" to create a role, specifying a name like "Supreme Admin." You can also customize permissions for specific roles, but in this case, the Supreme Admin role will have unrestricted access. Remember that roles determine an agent's permissions, so not all agents will have unlimited access. Once completed, the screen should display the successful creation of the "Supreme Admin" role.

By following these steps, you'll be able to efficiently configure new roles within the help desk, including the creation of a "Supreme Admin" role with unrestricted access.
</p>
<img src="https://i.imgur.com/d17F8hV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
To create a new department and manage specific settings, navigate to the Agents tab and select the "Departments" button. Here, you can create the "System Administrators" department, which will be designated for Supreme Admins. The Departments section also allows you to configure additional settings such as SLAs, managers, and email settings, tailored to each department's requirements.
</p>
<br />
<p>
<img src="https://i.imgur.com/dxLWBgu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department, the next step is to set up a new team. Teams enable you to bring together agents from different departments, allowing you to create specialized groups. For instance, you can form an "A team" consisting of top technicians from specific departments. As an example, you can create a help topic associated with a specific product and assign it to a team of agents who specialize in that product. To set up a team, navigate to Agents and select Teams. By default, a Level I support team is already created. In this scenario, we will create a Level II Support Team as an additional team.
</p>
<br />
<p>
<img src="https://i.imgur.com/4TWQWC7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up the new team, proceed to the Admin Panel in osTicket. From there, access the Settings section and navigate to User Settings. Within this section, enable the option that allows anyone to create tickets. By making this configuration adjustment, individuals without specific user accounts will have the ability to create tickets in osTicket.

</p>
<br />
<img src="https://i.imgur.com/OcTFr1D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let's focus on creating agents. Agents are the employees of the helpdesk who handle and resolve tickets. Each agent is assigned a primary department and a primary role for the tickets assigned to that department. Agents can also be granted access to other departments, and their roles can vary depending on the department they belong to. To manage permissions, access, and teams for agents, navigate to the Agents tab. In this section, you can assign permissions, control access levels, and assign agents to specific teams, ensuring efficient ticket management across the helpdesk. 
</p>
<br />
<img src="https://i.imgur.com/p0iHljD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating agents, the next step is to create users. Users are the customers who submit tickets when they encounter issues. Each user is identified by their email address. To create a user, access the Agent Panel and navigate to Users. Click on User Directory and select "Add new" to create a new user profile. Fill in the required details, including the user's email address, to complete the user creation process. This enables customers to create tickets and seek assistance using their email addresses.
</p>
<br />
<img src="https://i.imgur.com/bC4BPg2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To ensure timely ticket resolution, SLA Plans define the expected time frame for solving specific tickets within the help desk. Creating SLA Plans involves accessing the Admin Panel, navigating to Manage, and selecting SLA Plans. Within this section, you can create new plans that include schedules and corresponding grace periods. For example, the SEV-A plan in this instance has a 24/7 schedule and a one-hour grace period. By utilizing SLA Plans, you can establish clear time expectations for resolving different types of tickets within osTicket.
</p>
<br />
<img src="https://i.imgur.com/3ToUFdk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics are useful for users to categorize their tickets based on specific issues or topics. In the given example, a help topic has been created for "Business Critical Outage," which can be used when customers are unable to access mobile banking. This categorization helps streamline ticket management and ensures that tickets related to similar issues are grouped together, allowing for efficient handling and resolution within osTicket.
</p>
<br />
<img src="https://i.imgur.com/UPvzkgI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
