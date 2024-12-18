<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket –Configuration and Ticket Creation</h1>

![image](https://github.com/user-attachments/assets/73f0b1ff-311a-4399-b226-fd03c30107b2)


What is being done?<br />
-Configuration<br />
-Explore osTicket from a Help Desk Perspective<br />
-create, interact, close tickets<br />

<h2>steps</h2>

Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
End Users osTicket URL: http://localhost/osTicket

Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles<br />
Supreme Admin<br />
![image](https://github.com/user-attachments/assets/4f4c594a-f479-4edb-b645-e4fa5aa3fd26)

![image](https://github.com/user-attachments/assets/3a15a3ee-561d-4696-9e3e-3ee74bac5156)

Configure Departments (Ticket Visibilityfor different departments)<br />
Admin Panel -> Agents -> Departments<br />
SysAdmins<br />

![image](https://github.com/user-attachments/assets/991d98de-9c3b-47be-8360-11d1cd83e28d)

Configure Teams<br />
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)<br />
Online Banking<br />

![image](https://github.com/user-attachments/assets/08484856-2948-4dd5-a47f-685b2472fbd3)

Next, Allow anyone to create tickets<br />
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)<br />
Registration Required: Require registration and login to create tickets<br />

![image](https://github.com/user-attachments/assets/92638e16-0ee9-403e-8dfe-7a4ff5a1644f)

Configure Agents (workers)<br />
Admin Panel -> Agents -> Add New<br />
Rahul Sharma (Dept: SysAdmins)<br />
Golu Gupta (Dept: Support)<br />

![image](https://github.com/user-attachments/assets/9f766b26-186f-4420-87a2-712c1ce4439b)

![image](https://github.com/user-attachments/assets/b9954eb2-13ed-4cbc-89a2-5835ccac6634)


![image](https://github.com/user-attachments/assets/d435a5f1-cb16-484a-ae50-b0acb880bb70)

![image](https://github.com/user-attachments/assets/9dbdc5fb-ffd1-479f-8de1-95ac14da0b85)

Configure Users (customers)<br />
Agent Panel -> Users -> Add New<br />
Akansha Trivedi
![image](https://github.com/user-attachments/assets/1f56560d-616d-4bad-b634-40851984007c)

Configure SLA(service level agreement)<br />
Admin Panel -> Manage -> SLA<br />
● Sev-A (Grace Period: 1 hour, Schedule: 24/7)<br />

![image](https://github.com/user-attachments/assets/1b82a8c6-f903-4634-8636-066c01f6742f)

● Sev-B (Grace Period: 4 hours, Schedule: 24/7)<br />

![image](https://github.com/user-attachments/assets/49a0e63c-ef67-413a-8106-543a56939d7b)

● Sev-C (Grace Period: 8 hours, Business Hours)<br />

![image](https://github.com/user-attachments/assets/9f614c26-659c-4fa5-b3b8-628670209d5d)












