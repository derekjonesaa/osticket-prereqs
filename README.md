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
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/61e194d8-6a27-4076-87d1-53fcca8ab059)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/0ce583c1-3b8f-4ac5-8366-bf3aa1b0e9bd)

Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel" up top then you are currently in the admin panel and vice versa) reference picture # 1. Click agents --> roles --> add new role --> create a "super admin" whom can do every task and has all permissions/access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create a "System Administrators department" & "level II Support team"). Please reference screenshots above.




![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/6709a74b-c7eb-46e8-8fa9-d7774e30d871)
Go to settings -> Users -> settings again and make sure the box titled "Require registration and login to create tickets" is unchecked. This is will allow everyone access to make tickets without restrictions.


![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/ea654a90-e1d3-42b0-be47-087571156d90)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/846452b8-9e61-4a07-abd6-5c5c9971bbac)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/6e683a39-f469-4ce4-a362-ef8c0d7713c1)
Create two new test agents ("John Doe" and "Jane Doe")--> Assign John to "System Administrators" department with "Super admin" permissions level & add him to "Level II support" team. All of these options are located under the "access & Teams" tabs on the same agent screen. Next add "Jane Doe" the same way as previously completed for John Doe. Please reference pictures above that are in order.


