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

</p>
<br />

First login to your VM and load up your browser.

Open up two tabs, one tab for the End Users creating tickets and the other for your agents to login and work the tickets.

End Users osTicket URL: http://localhost/osTicket

Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php

First we can create a ticket as a End User. 

Go to the End User page, click Open a New Ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/6c1e6560-8a54-423b-bc66-5fb0555ce4a9)

</p>
<br />

Next fill out your information for the ticket, (you can use the Karen user we created in the previous lab or you can make it up).

Then from the drop down select Report a Problem. 

Some end users will not select the right one, this is still correct but it might not be the most accurate one to choose. The most accurate one to choose would be Report a Problem / Business Critical Outage.

Next write a Issue summary and explain the problem. Then click Create Ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/15d99c86-4060-4997-bd23-e5c405d0beb3)

</p>
<br />

Now hop on over to the other tab and login as John from the previous project.

As John we can see the ticket on the Open dashboard.

</p>
<br />

![image](https://github.com/user-attachments/assets/73420dbb-841f-40df-b90d-843f31cb5aef)

</p>
<br />

Click on either the ticket number or name to examine the ticket. 

</p>
<br />

![image](https://github.com/user-attachments/assets/48b5a3eb-d9ab-43e8-a553-12c090674d23)

</p>
<br />

After reading the problem this seems like a Sev-A because its a critical business outage. As, John we need to change some of the properties of the ticket to better reflect the problem.

First we can chnage the priority, click Normal next to Priority, and select Emergency. Then type a reason for the change in the text box. Then click Update.

</p>
<br />

![image](https://github.com/user-attachments/assets/fafdcbad-596b-40dd-a7c9-5a578485b05d)

</p>
<br />

This updates the ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/09398da8-a22e-4804-8e2b-de39e3c9ef47)

</p>
<br />

Next we can change the SLA by clicking on Default SLA next to SLA Plan. Then in the drop down select Sev-A and write the reason for in the text box.

</p>
<br />

![image](https://github.com/user-attachments/assets/5c7f405c-4a19-460b-a68e-5abc3bea5a52)

</p>
<br />

Next we can assign it to a specific department that will resolve the issue. To do this click Support next to Department, then in the drop down select SysAdmins and click transfer

</p>
<br />

![image](https://github.com/user-attachments/assets/3c9ae7c5-0001-42ac-80d5-bb8565651124)

</p>
<br />

This will take the ticket from John and send it to the Sys Admins department where Jane is at.

Next logout from John and login as Jane.

Now as Jane we can see the ticket, and see  that it has been updated by John.

</p>
<br />

![image](https://github.com/user-attachments/assets/5ad9ed25-e56f-4991-886e-70e5978b839f)

</p>
<br />

![image](https://github.com/user-attachments/assets/c9e6a6ec-9c81-4c5b-9a70-d0f28a6321fc)

</p>
<br />

Now we can assign it to the Online Banking team by clicking Unassigned beside Assign To and in the drop down select Online Banking. Then click Assign.

</p>
<br />

![image](https://github.com/user-attachments/assets/f9c090f0-08bc-49e6-8f86-f1804f894664)

</p>
<br />

This assigns it to the appropriate team that can resolve the problem.

Now as Jane on the banking team, you need to respond to the User. 

In the text box below you can type your response to the User and update them. After you write your response, click Post reply to update the ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/97892d30-5c2a-4c6f-a5ed-26915fdb18fa)

</p>
<br />

Here we can see the ticket is updated with a response and the customer can see the update.

</p>
<br />

![image](https://github.com/user-attachments/assets/c4ae29ed-7892-4d73-8c19-37472844c46d)

</p>
<br />

Now we can say that the issue has been identified and the fix has been sent out.

</p>
<br />

![image](https://github.com/user-attachments/assets/7422cb55-0f8a-4fd8-94e5-c047c7a3e8d5)

</p>
<br />

![image](https://github.com/user-attachments/assets/9085cec0-1c0a-4c03-8712-53b03e86389f)

</p>
<br />

Now that we resolved the ticket we can go to the top of the ticket to reflect that we resloved the issue. Click on Open, then click Resolved. Then write a message in the text box and click Close. 

</p>
<br />

![image](https://github.com/user-attachments/assets/658c9f74-d32a-4342-ac62-ad9c3037b1c7)

</p>
<br />

This then removes the ticket from Open tickets and sends it to Closed tickets.

In the next scenario, the accounting department is having some issues and sends in a ticket.
John gets the ticket. As John, we will observe the ticket and decide what to do from there.

We received a new ticket, it appears the accounting department is having trouble with some software on their computer.

</p>
<br />

![image](https://github.com/user-attachments/assets/79c1b78f-6f66-4282-9ae3-22147ceee068)

</p>
<br />

![image](https://github.com/user-attachments/assets/4e4319e3-7875-43d0-aca4-ef2ea903528c)

</p>
<br />

After reveiwing the ticket, I would call the User to get more clarification on the problem.

He states that "Adobe is either not loading or just shuts off when trying to use it"

I ask him " How many people are having the issue?

Ken says it is only two of them having issues in the department.

After all of this information I inform Ken to have them turn their computers off, wait 30 seconds, then turn them back on. He says they will do that and call me back after lunch to see if that resolves the issue.

After receiving all this information we can make some updates to the ticket.

First I can chnage the SLA Plan. Although it is hindering business operations, it is only affecting two people, so we can set it to Sev-C. 

</p>
<br />

![image](https://github.com/user-attachments/assets/3dc1c124-c4c0-4808-8747-f18acbd83a7b)

</p>
<br />

Then we can assign the ticket to ourself and we will work the ticket to completion as John. We can also change the Help Topic issue to Report a Problem.

</p>
<br />

![image](https://github.com/user-attachments/assets/3a7e1d92-b476-41a3-b119-da2c6f0b8071)

</p>
<br />

Next we can write a reply to update the ticket of the actions taken so far.

</p>
<br />

![image](https://github.com/user-attachments/assets/2a606020-bb62-4f04-8fd3-b905b9fce20d)

</p>
<br />

Here we can see all the updates we made to the ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/08689eaa-1f7b-4d5f-a970-712581e705ee)

</p>
<br />

Now, after lunch time Ken calls back and says that the restart fixed their computers and adobe is working now and they have no more problems.

Now we can close out the ticket as the issue has been resolved.

</p>
<br />

![image](https://github.com/user-attachments/assets/6f595442-c555-47d2-b589-976258593e5f)

</p>
<br />

This will then update and close out the ticket.

While creating tickets you can write notes only Agents can see and the customer cannot see by clicking Post Internal Note.

</p>
<br />

Now, for our last scenario we received a ticket from Karen, an employee.

After further review, it appears the cheif financial officer is having some problems with their laptop.

As John we can set the priority to Emergency since it is a C-suite person.

</p>
<br />

![image](https://github.com/user-attachments/assets/000a9389-f240-4618-abc7-ae18cced3ba2)

</p>
<br />

Next we can update the SLA to Sev-B for now and we can always go back and re-classify after we get more info.

</p>
<br />

![image](https://github.com/user-attachments/assets/27c79f19-359d-4a78-8111-5acc0e23cd91)

</p>
<br />

Then we can assign the ticket to ourself and complete the ticket to completion as John.

</p>
<br />

![image](https://github.com/user-attachments/assets/d2c86773-a45b-4bd8-a80e-3f1e4dc9b806)

</p>
<br />

Next we can call the CFO or their secretary to get more info, and possibly set up a meeting time to look at the laptop in person.

Their secretary picks up and says we can go look at the laptop, and it turns out that the charger was broken and could not charge the battery and the laptop died. We bring them a new charger and get the laptop charging.

Now we can update the ticket.

</p>
<br />

![image](https://github.com/user-attachments/assets/45af03bc-4024-457c-a593-ad41e2786413)

</p>
<br />

Now the ticket is updated and resolved.

</p>
<br />

Now if we want to we can look at both the closed tickets we completed as John.

Click the Tickets header, then click the Closed tab. Here you can see both closed tickets we resolved.

</p>
<br />

![image](https://github.com/user-attachments/assets/428a8f89-ab3f-4c46-8be9-06961c514191)

</p>
<br />

In most Ticketing Systems there is an email ability for customers to use to check the status and receive updates about their tickets. This also gives them a chance to respond within the ticket.

Sometimes the ticket is not always created by the customer. The customer can call, email, etc. into the help desk and the agent recieving the request would be the one creating the ticket. Make sure to create tickets for everything you fix and do to create a paper trail of your work.

Congratulations! You have successfully downloaded and installed osTicket, configured the settings within osTicket, and created/reacted to scenarios and followed the life cycle of tickets.
