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

---

<p>
  Here I am going to show you essentially the life of a ticket that you could recieve and work on. First we are going to create the ticket as someone would to report an issue. Then we will log in as Mr. John Doe and work the ticket to completion.
</p>

![Screenshot 2025-02-04 072824](https://github.com/user-attachments/assets/50e35d17-d6bb-4940-aa40-9a44c3c0632c)

<p>
  You can head to: http://localhost/osTicket and then click 'Open a New Ticket' at the top.
</p>

---

![Screenshot 2025-02-04 073158](https://github.com/user-attachments/assets/a5a48036-4eb4-41a3-8853-d287cf0b62da)
![Screenshot 2025-02-04 073604](https://github.com/user-attachments/assets/c9cdd212-318f-47aa-8a27-4bb89f669602)


<p>
  We are going to fill out a ticket as Karen, in this case, an employee reporting the issue of the CFO's laptop not being able to turn on. You can choose any issue you would like and fill the help topic, issue summary, and details how you would like. Go ahead and hit 'Create Ticket' at the bottom, and the ticket will be submitted into the osTicket system.
</p>

---
![Screenshot 2025-02-04 074239](https://github.com/user-attachments/assets/9790c982-ce79-4d61-ba9f-bf5ae717770c)
![Screenshot 2025-02-04 074352](https://github.com/user-attachments/assets/e307d734-d782-4fbf-948b-043f1cb32de4)

<p>
Next, we are going to log in as one of the agents that we created, I will be using the John Doe that I created. Remember, you can log in as an Agent/Admin at: http://localhost/osTicket/scp/login.php. Upon logging in, you will see the new ticket Karen created. 
</p>

<p>
  John here is going to click on the new open ticket.
</p>

---

![Screenshot 2025-02-04 081054](https://github.com/user-attachments/assets/eac092e0-6a58-40f2-9527-9d6fce7c41b4)
![Screenshot 2025-02-04 081133](https://github.com/user-attachments/assets/a9fef11d-e428-4d5b-be43-71db01664e25)
![Screenshot 2025-02-04 081302](https://github.com/user-attachments/assets/e036d839-3b8a-4891-bbdc-0c91dca73977)

<p>
  He will be presented with the ticket info shown in the first screenshot, he is going to click on and fill out the 'Assigned To:' and 'SLA Plan:' options. He will decide to assign it to himself, and set it to Sev-B in the SLA section. You can decide to put any information that would make sense. These steps are shown in the second and third screenshot.
</p>

<p>
  In our example here, we are going to imagine somehow that John got to inspect the CFO's laptop, whether that be contacting the CFO, or contacting Karen. Upon inspection, John has found that the charger was the issue.
</p>

---
![Screenshot 2025-02-04 081819](https://github.com/user-attachments/assets/9b2d49df-98af-43c6-a8f3-494b83325b0f)

<p>
  At the bottom, John will post his findings and close the ticket, since the issue has been solved successfully.
</p>

---
![Screenshot 2025-02-04 082043](https://github.com/user-attachments/assets/aa332c2d-e532-47ae-92b7-50274224649b)
![Screenshot 2025-02-04 082134](https://github.com/user-attachments/assets/fb4d1aa5-38bb-4456-94b3-9a2adc4aa0f3)


<p>
  You can see John's findings added to the ticket in the message at the bottom. John can now click on the status of the ticket and set it to 'Resolved' since he has successfully fixed the issue.
</p>

---
![Screenshot 2025-02-04 082315](https://github.com/user-attachments/assets/9e3680b2-a64f-420f-8dbe-1a4f75fcb176)


<p>
  Everything is now running smoothly, John has solved all current issues at the moment, and can enjoy a bagel.
</p>
