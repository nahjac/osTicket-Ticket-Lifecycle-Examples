![image](https://github.com/user-attachments/assets/96741d84-29a8-4528-b59a-56bd57004853)
# osTicket- Ticket Lifecycle: Intake Through Resolution
This tutorial follows along the lifecycle of a help desk support ticket from the initial intake to final resolution. This will be demonstrated through the open-source help desk ticketing system osTicket.
# Environments and Technologies Used
+ Microsoft Azure
+ Remote Desktop
+ Internet Information Services (IIS)
# Operating Systems Used
+ Windows 10 (21H2)
# Ticket Lifecycle Stages
+ Intake
+ Assignment and Communication
+ Working the Issue
+ Resolution
# Lifecycle Stages
## Stage 1: Intake
Open osTicket and click "Open a New Ticket". Enter the following parameters and create the ticket:
*pic of creating ticket (email: jane@user.com name: jane help topic: business critical outage issue summary: entire mobile online banking is down details: customers are reporting a 404 error when browsing to online banking.
## Stage 2: Assignment and Communication
Now we will assign the ticket to a help desk agent. Sign in to osTicket as an agent. I used the ken.jay credentials. Select the ticket we just created.
*pic of ticket*
Agent Ken would see that this is a a Sev-A emergency ticket as mobile online banking being down can lead in a loss in profits for the organization. Therefore, they reassign the ticket to the System Administrators Department. As an effective and thorough agent, Ken leaves a message documenting and explaining the situation:
*pic of transferring ticket (message: coordinating with sys admin team to address critical system outage)*
## Stage 3: Working the Issue
Agent Mary on the back-end works on the issue and communicates with agent Ken. She also makes sure to switch the status of the ticket from "open" to "resolved".
*pic of changing ticket status and message: Hi Barbie, we discovered a failed load balancer. The issue has been fixed and online systems should be working now)*
## Stage 4: Resolution
Support Agent Ken should be able to see in his portal that Sys Admin Mary has left a message that the ticket is now closed. Awesome! You've successfuly created a resolved a support ticket. This was a very simple scenario that walked you through the lifecycle of a support ticket. 
