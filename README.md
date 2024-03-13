<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles, departments, and teams.
- Configure Agents (workers) and Users (customers).
- Configure and learn about SLAs. 
- Configure Help Topics. 

<h2>Configuration Steps</h2>

<p>
  <img width="494" alt="Capture" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/6022d340-c584-4405-a7a4-1189aecc1c31">
</p>
<p>
We started this lab by navigating to the "Admin Panel" section. Under "Users & Groups," we selected "Roles" to define different roles such as admin, agent, or manager. In this case, we created the role "Supreme Admin." Roles in osTicket define the permissions and responsibilities assigned to different user types within the system.
</p>
<br />

<p>
  <img width="492" alt="Capture2" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/06f19805-55ba-4a4d-9d93-e38c148e9827">
</p>
<p>
Next, we continued with "Departments." Departments categorize tickets based on organizational structure or functional areas. Each department typically corresponds to a specific team or group responsible for addressing particular types of issues or inquiries. In this case, we created the System Administrators Department. 
</p>
<br />

<p>
<img width="491" alt="Capture3" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/d0468c27-f536-4d4f-8ffa-db27dd2ae0f8">
</p>
<p>
List of all Departments that we used for the execution of this lab. 
</p>
<br />

<p>
<img width="491" alt="Capture4" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/f5a49434-4bf5-4a2a-ad18-368ae9d27d6c">
</p>
<p>
In te same section where we created the Roles and Deparments, now we added Teams. Teams in osTicket are subsets of departments, consisting of agents who collaborate on resolving tickets within a specific area of expertise or responsibility. For instance, within the IT support department, there may be separate teams for network troubleshooting, software support, and hardware maintenance. In this case, we create the Level II Support. 
</p>
<br />

<p>
<img width="492" alt="Capture5" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/7ed90038-2289-4cc7-8581-b6898f25d5d8">
</p>
<p>
In te same section where we created the Roles, Deparments and Teams, now we added Agents. Agents are staff members responsible for handling tickets submitted by end-users. They interact directly with customers to address their issues, provide support, and resolve inquiries in a timely manner. In this case, we added Jane Doe and Johhny Doe to the agents section. Jane Doe is part of the System Administrators Deparment also Jane Doe had Supreme Admin Role. In addition, Johnny Doe is part of the Support Deparment. 
</p>
<br />

<p>
<img width="496" alt="Capture6" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/f993cb71-fe01-4cea-99c2-387a5510b15c">
</p>
<p>
We continued the lab by adding users. Users, also known as customers or end-users, are individuals or entities that submit tickets to osTicket for assistance or support. They interact with the system primarily through the ticket submission interface, providing details about their issues, inquiries, or requests. In this lab, we added two users to osTicket. 
\</p>
<br />

<p>
<img width="469" alt="Capture7" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/78cbe038-90d7-40f8-a92e-9ec1ffcba52b">
<img width="459" alt="Capture8" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/d183d348-e011-48a8-ab9f-6975a1665f9e">
<img width="485" alt="Capture9" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/2b11f661-4546-48ad-8af0-cc341fd7e204">
<img width="471" alt="Capture10" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/55331727-bc7e-4490-9526-d2704e2c30ea">
</p>
<p>
Now we experimented with different SLA configurations to understand their impact on ticket management and service delivery. By configuring SLAs, administrators can prioritize tickets, set performance targets, and monitor service delivery to meet customer expectations effectively. In this lab, we created three types of SLAs: SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), and SEV-C (8 hours, business hours). 
\</p>
<br />

<p>
<img width="512" alt="Capture11" src="https://github.com/gabromerorodriguez/post-install-config/assets/163021104/b0e7fc4d-a673-4519-8f60-097af2e950e8">
</p>
<p>
As the last part fo this lab, we created Help Topics. Help Topics classify tickets based on common issues, inquiries, or request types. They provide a structured way to organize and categorize incoming tickets, making it easier for agents to identify and prioritize tickets for resolution. Help topics may cover a wide range of topics, such as technical support, account inquiries, billing issues, or product feedback. In this lab, we creted 4 different help topics: Business Critical Outage, Personal Computer Issues, Equipment Request and Password Reset. 
\</p>
<br />
