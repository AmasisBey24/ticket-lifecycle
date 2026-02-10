<p align="center">
<img width="5120" height="560" alt="xbanner_osTicket-5120x560w jpg pagespeed ic VHDbUulfIn copy" src="https://github.com/user-attachments/assets/3e51d352-6694-44e3-8d41-58a0ebc4df10" />
</p>

<h1>osTicket - Ticket Lifecycle: Using Resolution Center</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Stage 1: Intake - Creating a Ticket</h3>


- Open osTicket
	- If you need help installing osTicket, please see Part 1 of this tutorial series [here](https://github.com/RoslyndWilliams/osTicket--Prerequisites-and-Installation)
 	- If you need help configuring osTicket, please see Part 2 of this tutorial series [here](https://github.com/RoslyndWilliams/osTicket--Post-Install-Configuration)

- Select Open a New Ticket
  - Email Address: <a href='#' style='text-decoration: none; color:#000000'>johnson@osTicket.com</a>
  - Name: Keyana Johnson
  - Help Topic Dropdown Menu: Business Critical Outage
    - Issue Summary: Entire mobile online banking is down
    - Details: Customers are reporting they are getting a 404 error when browsing to online banking
  - Create Ticket

<p align="center">
<img width="70%" height="70%" alt="68747470733a2f2f692e696d6775722e636f6d2f4737416b3675492e706e67 copy" src="https://github.com/user-attachments/assets/5faf04d8-a5c7-40f6-834a-edac0c267d2b" />
<img width="70%" height="70%" alt="68747470733a2f2f692e696d6775722e636f6d2f556469506331732e706e67 copy" src="https://github.com/user-attachments/assets/e9224646-df17-4edd-a8fc-1e7eb58ee251" />
</p>


<h3>Step 2: Assignment and Communication</h3>

- Sign in to osTicket as an Agent
  - We created jane.doe in the previous tutorial; log in with those credentials. 
  - Select the ticket we created in Step 1.
  
  
<p align="center">
<img src="https://i.imgur.com/sDgzS36.png" height="80%" width="80%" alt="Azure Free Account"/> 
</p>


 - Priority: Emergency. 
      - Mobile online banking down can lead to losses in revenue for the company. 
 - Assigned to: Jane Doe
 - SLA Plan: SEV-A 
      - Business impacting, critical incident
 - Department: System Administrators 
      - Sys Admins responsible for mobile banking infrastructure
 - Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.
    - Select Post Reply


<p align="center">
<img src="https://i.imgur.com/Du3kmui.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yg9TXep.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

<h3>Stage 3: Working the Issue</h3>

- On the back end, Jane is working with the Systems Administrative Team to resolve the issue. 


<h3>Stage 4: Resolution</h3>
     
- Once the issue is resolved, head back to the ticket and update the end user.
  - Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up. 
  - Ticket Status: Resolved
- Select Post Reply
- Since it has been resolved, the ticket should now be on the Closed tab.

<p align="center">
<img src="https://i.imgur.com/et8h651.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/TUo3T0Q.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>


🎉Congratulations! You have created and resolved your first ticket! You have completed the third and final part of this three-part osTicket Install/Configuration/Ticket-Creation tutorial series.🎉
  
