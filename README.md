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

In this Tutorial, we are going to use our recently configured OS Ticket as an End User, an Agent, and as a Administartor. Let get to it.

Tickets have 3 stages that can be assigned to them. Assigned means that the ticket has been given to an Agent. Working the Issue(s) means that steps are being taken to reach a potencial resolution. Resolution means that a ticket was resolved or closed.

Start by using this link to create some tickets!

http://localhost/osTicket/

You will guided to this link. Click on create ticket, to get started.

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



















We can now see that the tickets have been updated to "Emergency". 

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/966c73d4-5352-4c0f-9c50-25c61bfe0a95)

After connecting with the Sys Admin team, we will recieve a response letting us know the ticket is resolved.

Now that the ticket has been resolved, it will be reflected in the "closed" tickets column.

![image](https://github.com/emodjeska/ticket-lifecycle/assets/143763072/4138c6bc-b7cd-4ff6-af7a-2ed0d1b2d93a)

Thank you for joining me today.

