<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project demonstrates the configuration of key features in osTicket, including ticket workflows, email integration, user roles, and automation, to optimize its functionality as an efficient and scalable helpdesk solution for IT support teams. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics
  
<h2>Configuration Steps</h2>

<p>
<img width="668" alt="1 2" src="https://github.com/user-attachments/assets/8ec1b839-be8a-4ef7-88b4-9f5a1d260ca5" />

</p>
<p>
osTicket provides two interfaces: the Admin Panel and the Agent Panel. The Admin Panel is used for configuring system settings, managing agents, and defining operational parameters such as roles, departments, and SLAs. The Agent Panel is focused on day-to-day ticket management and user interactions. Roles were configured to group permissions for agents by navigating to Admin Panel → Agents → Roles, where a role named Supreme Admin was created with full permissions. Departments were defined to determine ticket visibility and categorize support requests. For example, a department called SysAdmins was created via Admin Panel → Agents → Departments. To facilitate collaboration among agents from different departments, a team named Online Banking was created in Admin Panel → Agents → Teams.
</p>
<br />

<p>
<img width="656" alt="3" src="https://github.com/user-attachments/assets/5197885f-de1b-434c-9939-8cf33e832d01" />
</p>
<p>
User settings were adjusted in Admin Panel → Settings → User Settings to require registration and login for ticket creation, ensuring that only registered users can submit tickets. Agents were added to the system by navigating to Admin Panel → Agents → Add New. For instance, Jane was assigned to the SysAdmins department, while John was assigned to the Support department. Similarly, end-users, such as Karen and Ken, were added via Agent Panel → Users → Add New to allow them to submit tickets.
</p>
<br />

<p>
<img width="664" alt="4" src="https://github.com/user-attachments/assets/1a0d8081-f965-49b1-9d96-5d89f0ee0741" />
</p>
<p>
Service Level Agreements (SLAs) were configured to manage ticket response times based on severity. In Admin Panel → Manage → SLA, three SLA plans were created: Sev-A (1-hour grace period, 24/7 schedule), Sev-B (4-hour grace period, 24/7 schedule), and Sev-C (8-hour grace period, business hours schedule). Additionally, help topics were set up in Admin Panel → Manage → Help Topics to guide users when submitting tickets. Examples of help topics include Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other.
</p>
<p>
<img width="665" alt="5" src="https://github.com/user-attachments/assets/002758ba-12d5-4a9e-83d3-32537cbc2573" />
<p/>
<p>
  By following these steps, osTicket was configured to handle various organizational workflows effectively, ensuring streamlined ticket management and enhanced user support.
</p>
<br />
