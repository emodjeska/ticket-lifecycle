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

In this Tutorial, we are going to use our recently configured OS Ticket as an End User, an Agent, and as a Administartor, to outline the lifecycle of a ticket in OS Ticket. Let get to it.

Tickets have 3 stages that can be assigned to them. Assigned means that the ticket has been given to an Agent. Working the Issue(s) means that steps are being taken to reach a potencial resolution. Resolution means that a ticket was resolved or closed.

Start by using this link to create some tickets!

http://localhost/osTicket/

You will guided to this link. Click on create new ticket, to get started.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/21f1de03-cd11-4805-ba3e-81196673aba9)

Create a new Ticket, Fill out the information for Karen Karen, from our last tutorial, and set it to be a SEV-A SLA for a Business Critical outage. This will simulate a high level sevarity ticket.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/1e44a097-f267-423e-a8a2-ac12cbc9045b)

The customer will recieve notifications letting them know that their request has been recieved.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/fde2552a-1a75-484d-b38a-040e1d87f536)

Now, create a few more tickets with varying levels of importance, so we can take a look at them as an agent and Admin. Go ahead and log into the Agent panel on your OS Ticket, Jane Doe.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/1b03b05c-3574-4a69-aaa5-bb94ee02659a)

Here, you will see the new tickets that we just created. Click on the Critical Business Outage ticket.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/9213d80e-15d8-43ad-ae84-c5e9860cf396)

Assign the Priority to "Emergency", Assign it to yourself, set the department to System Administrators, and set the SLA to SEV-A because it is an emergency.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/c230bb07-b9b1-49a8-bac4-b7a60d4bfd5c)

We will now log onto the Agent Portal and you will see that the ticket has been assign to you, Jane Doe, and you can see that there have been updates sent automatically from us changing the SLA. Go ahead and post a comment, to say that "You are reaching out to the system Administartors".

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/c2d2e1af-bba6-4b69-bef4-6999fb728dd5)

You can see here, that the changes you have made are reflected in the "tickets" page

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/44bab7fe-21b7-46ed-a783-e0e930bd583a)

After that, we are going to update all the tickets to have SLA's and assignments that make sense for them. Then go into The Ticket for Jane that says the she is wondering about the network reset and mark it as Resolved. This will simulate completing a ticket. 

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/a79fdf0f-184a-4a1e-9434-a067ddf12e29)

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/04ac0865-c3fb-4aa1-8f27-2112715f9afe)

Take note that the ticket has been removed from our tickets.

Go through and work through the rest of the tickets in a way that makes sense. When you are finished responding to all the tickets, you will see that this is reflected in Jane's tickets.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/4cca7b2e-9fce-4471-b77a-042564bebcbd)

From there, Logon to The Admin Portal -> click Agents -> click Manage Agents -> click on Johns profile -> Then click on access/ Permissions. Take a look and get familar with the different features within OS Ticket as an Admin. This will simulate Admin related tasks.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/13c896a0-b5f7-4127-a4c1-6d04be96cb11)

Login into the Agent Portal-> Click Tickets -> Click Closed. This will show you all of the closed tickets that you just completed. Look through the tickets and see how they were resloved.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/1f92da45-c537-40d4-bfec-f2d561974c5e)

That is the end of today's tutorial, we have outlined the lifecycle of a ticket in OS Ticket. Be sure to clean up and delete your resources in Azure so that you do not run into any issues later on.

Thank you for joining me today.
