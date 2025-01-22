<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
This is a continuation of the insert repository
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<h3>Step 1.</h3>

![1  admin analyst login](https://github.com/user-attachments/assets/4f7b6e42-ff66-48a6-a9c7-4e389f93840a)

<p>Login as the admin using the user and password you created for osTicket</p>

<h3>Step 2.</h3>

![2  admin analyst panel](https://github.com/user-attachments/assets/13425064-ed9e-4314-a39c-8acdcc817527)

<p>You should now be inside the agent panel</p>

<h3>Step 3.</h3>

![3  End users url](https://github.com/user-attachments/assets/c8a87d8a-b621-492a-9d86-c2907e2f90f7)

<p>This is the web page where end users can generate a new support ticket</p>

<h3>Step 4.</h3>

![4  go to admin panel](https://github.com/user-attachments/assets/36b29dff-bff0-418f-a2c1-d7b589b7eb00)

<p>Go to the admin panel</p>

<h3>Step 5.</h3>

![5  find add new role](https://github.com/user-attachments/assets/c12c33aa-4a44-4fbf-a9f1-644623cd62b8)

<p>Click Agents, Roles, then click Add New Role></p>

<h3>Step 6.</h3>

![6  name of role](https://github.com/user-attachments/assets/7593938b-e9ba-4185-8eed-25bda33df3ce)

<p>Name the role "Supreme Admin", then click Permissions.</p>

<h3>Step 7.</h3>

![7  permissions   add role](https://github.com/user-attachments/assets/69b7c861-62c3-41ef-8bcc-c8c08297f3c7)

<p>Check all permissions within Tickets, Tasks, and Knowledgebase. Then click Add Role</p>

<h3>Step 8.</h3>

![8  supreme admin added](https://github.com/user-attachments/assets/9fd28125-9ec9-41fb-8648-347f47eef099)

<p>The role should now have been successfully added and listed within Roles.</p>

<h3>Step 9.</h3>

![9  find add new department](https://github.com/user-attachments/assets/0db24ed4-84af-455c-abd4-15d0e5234a20)

<p>Go to Agents, Departments, then click Add New Department.</p>

<h3>Step 10.</h3>

![10  create department](https://github.com/user-attachments/assets/a20904ef-0572-44c5-9c3a-104dc9c70fa5)

<p>Name the department SysAdmins, then click Create Dept</p>

<h3>Step 11.</h3>

![11  sysadmins created](https://github.com/user-attachments/assets/a6867323-6e17-4ffe-ad37-f07e17821343)

<p>The department "SysAdmins" should have been successfully added and listed under Departments</p>

<h3>Step 12.</h3>

![12  find add a new team](https://github.com/user-attachments/assets/a84cc7e7-4fa1-4465-87e3-1ce38289ab09)

<p>Go to Agents, Teams, and click Add New Team</p>

<h3>Step 13.</h3>

![13  create banking team](https://github.com/user-attachments/assets/1db81152-5d34-4a2f-8247-7d32f53592a4)

<p>Name the team "Online Banking", then click Create Team</p>

<h3>Step 14.</h3>

![14  team added](https://github.com/user-attachments/assets/187acd83-0ae3-48bd-b1e0-21ac9ec22f3b)

<p>The team "Online Banking" should have been successfully created.</p>

<h3>Step 15.</h3>

![15  uncheck](https://github.com/user-attachments/assets/a4f0d674-b115-4703-9741-d21d67bed4cf)

<p>Go to Settings, Users, uncheck Registration Required, then click Save Changes</p>

<h3>Step 16.</h3>

![16  find add new agent](https://github.com/user-attachments/assets/9ccfa4e0-fa2f-45e6-a49a-e49c379b0564)

<p>Go to Agents, Agents, and click Add New Agent</p>

<h3>Step 17.</h3>

![17  agent credentials](https://github.com/user-attachments/assets/f1962921-4794-4893-934e-e5d37a30e686)

<p>Fill out the information accordingly such as the image above, then click Set Password</p>

<h3>Step 18.</h3>

![18  set agents password](https://github.com/user-attachments/assets/4bc4bb43-5597-44eb-93f5-9087d61305f4)

<p>Uncheck both boxes and create a username and password for this agent, then click Set</p>

<h3>Step 19.</h3>

![19  access](https://github.com/user-attachments/assets/8221589b-821a-44d1-91c1-6b1ec843deab)

<p>Go to Access, select SysAdmins and Supreme Admin, then click Teams.</p>

<h3>Step 20.</h3>

![20  create](https://github.com/user-attachments/assets/074a6c59-3433-458f-b898-0f6a84b69854)

<p>Select the Online Banking team, then click create.</p>

<h3>Step 21.</h3>

![21  Jane Doe created](https://github.com/user-attachments/assets/f473a345-6dea-472f-bd02-571dd1f8122e)

<p>Your agent should have been successfully created and listed under Agents associated with the SysAdmins department.</p>

<h3>Step 22.</h3>

![22  add another agent](https://github.com/user-attachments/assets/8e102867-f56f-4a24-b7d8-fa175ad0033a)

<p>Add another agent by clicking Add New Agent</p>

<h3>Step 23.</h3>

![23  agent credentials](https://github.com/user-attachments/assets/10d5ed8c-1065-4a01-9d03-b4258d03f73f)

<p>Fill out the credentials for the second agent, then click Set Password</p>

<h3>Step 24.</h3>

![24  set pass](https://github.com/user-attachments/assets/86144aeb-9444-46f4-8ca5-9561c5a8dfc1)

<p>Uncheck the boxes, create the password for this agent, then click Set</p>

<h3>Step 25.</h3>

![25  access   create](https://github.com/user-attachments/assets/6c7f6861-fcd3-4fd9-8677-bc595e012871)

<p>Go to Access, select Support and View only, then click Create</p>

<h3>Step 26.</h3>

![26  agent created](https://github.com/user-attachments/assets/c0f0dd91-b7f8-405b-9b68-7022a9c3cbd0)

<p>Your second agent should have been successfully created and listed under the Agents associated with the Support department.</p>

<h3>Step 27.</h3>

![27  go to agent panel](https://github.com/user-attachments/assets/443a6c17-d271-4410-96f7-0b72d180c0c3)

<p>Go to the Agent Panel</p>

<h3>Step 28.</h3>

![28  find add user](https://github.com/user-attachments/assets/4127769b-6082-4c86-bbcf-a20b818b1d5b)

<p>Go to Users, then click Add User</p>

<h3>Step 29.</h3>

![29  add user karen](https://github.com/user-attachments/assets/75bf82f2-396e-420f-b385-2e9f786443ed)

<p>Fill in the information for a new user similar to the image above, then click Add User</p>

<h3>Step 30.</h3>

![30  karen created](https://github.com/user-attachments/assets/ce759a0a-4d79-4c6b-9c7e-e4ad33e42eee)

<p>Your new user should now have been created successfully</p>

<h3>Step 31.</h3>

![31  admin panel](https://github.com/user-attachments/assets/e4815b22-60c4-44a4-bf9f-a306aaadce79)

<p>Go to the Admin Panel</p>

<h3>Step 32.</h3>

![32  find add new sla plan](https://github.com/user-attachments/assets/513dacf4-54ff-4047-989b-2adf68d80469)

<p>Go to Manage, SLA, then click Add New SLA Plan</p>

<h3>Step 33.</h3>

![33  add sev-a plan](https://github.com/user-attachments/assets/fb262a80-1e9a-4f47-ba1b-c205b1978c71)

<p>Name the plan Sev-A, with a grace period of 1 hour, a 24/7 schedule, then click Add Plan</p>

<h3>Step 34.</h3>

![34  add sev-b plan](https://github.com/user-attachments/assets/409d8298-e762-4244-ae3f-a58a1bc70fc0)

<p>Add another plan. Name the plan Sev-B, with a grace period of 4 hours, a 24/7 schedule, then click Add Plan</p>

<h3>Step 35.</h3>

![35  add sev-c plan](https://github.com/user-attachments/assets/d57c59a7-66b5-4199-a089-1e3628ca0541)

<p>Add another plan. Name the plan Sev-C, with a grace period of 8 hours, a Monday-Friday schedule, then click Add Plan</p>

<h3>Step 36.</h3>

![36  sla plans created](https://github.com/user-attachments/assets/96ced6be-1f63-4c07-9e11-4b508523bc63)

<p>All 3 severity plans should have now been successfully created and listed under Service Level Agreements with the appropriate grace periods.</p>

<h3>Step 37.</h3>

![37  find add a new help topic](https://github.com/user-attachments/assets/704b0cd0-186c-4423-a629-2f01215850c0)

<p>Go to Manage, Help Topics, then click Add New Help Topic</p>

<h3>Step 38.</h3>

![38  add bco](https://github.com/user-attachments/assets/1c4dd2ae-f366-42c4-bce5-216c98a64515)

<p>Name the topic "Business Critical Outage" with a Parent Topic of Report a Problem, then click Add Topic.</p>

<h3>Step 39.</h3>

![39  help topics added](https://github.com/user-attachments/assets/a7bf47db-3383-4c61-8c8c-5038cd94072b)

<p>Add 4 more Help Topics with the same method, each one named like the ones highlighted in the image above.</p>

<a href="http://localhost/osTicket/scp/login.php">Help Desk Login Page</a>
<br>
<a href="http://localhost/osTicket/">End User osTicket URL</a>




























