
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



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

<p>
<img width="839" alt="Screen Shot 2024-07-08 at 9 57 58 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/28686e30-2a0e-4158-a9f9-96b425ee1a76">


</p>
<p>
Browse to End-User URL for OsTicket: http://localhost/osTicket/. From here we can create tickets as our users created in the previous repository. 
</p>
<br />

<p>
<img width="789" alt="Screen Shot 2024-07-08 at 9 57 47 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/dd24fe47-0d23-471e-b09f-69b3b18e8111">
</p>
<br />
<img width="789" alt="Screen Shot 2024-07-08 at 10 00 21 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/3babf61a-0093-4ec6-874d-f77cd9194fc7">


</p>
<p>
Enter Credentials of either of the created users and create tickets for common business issues. Select one of the help topics we created in a previous repository. For example:"Business Critical outage" or general inquiry. This should coincide with the issue that you are entering. For example:  "Entire online mobile banking system is down!" would be classified as a "Business Critical Outage". You should also enter a quick summary of the issues to make it easier on the agents working the tickets. 
</p>
<br />

<p>
<img width="961" alt="Screen Shot 2024-07-08 at 10 00 08 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/c90a7713-16cb-4a7d-9ccf-26831ba2bbbd">

</p>
<p>
Go to the help desk login page: http://localhost/osTicket/scp/login.php and login as one of the agents that we created in the previous repositry. Navigate to Tickets -> Open and observe the tickets you just created.    
</p>
<br />

<p>
<img width="958" alt="Screen Shot 2024-07-08 at 9 59 57 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/61bf71ba-7d3b-48f9-8421-d66c25438e96">
</p>
<br />
<img width="872" alt="Screen Shot 2024-07-08 at 9 59 31 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/6a521d7e-f650-402a-b90b-b5223bf81f81">



</p>
<p>
Click inside one of the tickets and update it to the approporiate Priority, SLA plan, and Department. The Priority and SLA plan should coincide with the percieved impact that the event has on the business. 
</p>
<br />


<p>
<img width="935" alt="Screen Shot 2024-07-08 at 9 59 03 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/3286e6cc-d85c-47e8-98a2-60ed9455a503">
</p>
<br />
<img width="958" alt="Screen Shot 2024-07-08 at 9 58 22 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/90818619-360e-48f1-adee-a2974d4bf1b2">


</p>
<p>
Go down to the ticket threads and start closing the tickets. To do this you will have to go to the "
post reply" section and provide a summary of what you did to resolve the issue. You can also use this section to provide updates on the ticket to the team. Once you enter the summary, in the ticket status section, you have to select "Resolved" to close the ticket. Certain tickets are assigned to certain agents so you will have to login as that agent to close it. 
</p>
<br />

<p>
<img width="953" alt="Screen Shot 2024-07-08 at 9 58 54 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/4f27fbc3-488f-4546-a731-5f5a6f6d2be7">
</p>
<br />
<img width="967" alt="Screen Shot 2024-07-08 at 9 58 44 AM" src="https://github.com/Bpeduru/ticket-lifecycle/assets/171273980/784afa41-ad72-4e4e-a649-130843673e45">
</p>
</p>

While closing the tickets, observe that they will start to dissappear from the "Open" section under the tickets tab, and appear in the "Closed" Section. Once you close all of them, none will be left in the open section and all of them will appear under the closed section!
