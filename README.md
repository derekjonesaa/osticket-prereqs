<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles
- Configure SLA
- Configure Departments
- Configure teams
  
<h2>Configuration Steps</h2>


![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/c9d707f3-c523-406f-93e1-fd42c8c42570)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/03b4d0c4-65b2-43e5-b146-530eadfdaf16)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/51a61ab7-8127-4d47-b0b2-61e7e8e7a831)

Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel" up top then you are currently in the admin panel and vice versa) reference picture # 1. Click agents --> roles --> add new role --> create a "super admin" whom can do every task and has all permissions/access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create a "System Administrators department" & "level II Support team"). Please reference screenshots above.



![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/a8c6ef48-2e3d-42ff-9ac8-5cebbbaa1be3)
Go to settings -> Users -> settings again and make sure the box titled "Require registration and login to create tickets" is unchecked. This is will allow everyone access to make tickets without restrictions.

![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/f6cb6950-e1ce-4ef7-92a2-e6af64bc3394)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/e67d726c-6fa6-4814-8225-4f3ebf7f38d4)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/f0f95c21-731a-41ee-9384-e8cdc9f34bcc)
Create two new test agents ("John Doe" and "Jane Doe")--> Assign John to "System Administrators" department with "Super admin" permissions level & add him to "Level II support" team. All of these options are located under the "access & Teams" tabs on the same agent screen. Next add "Jane Doe" the same way as previously completed for John Doe. Please reference pictures above that are in order.


