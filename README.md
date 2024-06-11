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

![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/8fb95fb7-ec10-4bea-8e1d-ed0c7cf00163)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/488855a1-1726-45f6-b601-aa197a93c0ff)
![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/bb4f43e9-2b1b-46c8-9f93-3ce38d0691d0)
Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel" up top then you are currently in the admin panel and vice versa) reference picture # 1. Click agents --> roles --> add new role --> create a "super admin" whom can do every task and has all permissions/access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create a "System Administrators department" & "level II Support team"). Please reference screenshots above.




![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/6709a74b-c7eb-46e8-8fa9-d7774e30d871)
Go to settings -> Users -> settings again and make sure the box titled "Require registration and login to create tickets" is unchecked. This is will allow everyone access to make tickets without restrictions.



