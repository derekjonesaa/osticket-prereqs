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





![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/0e048494-264a-473d-82f7-5a8569571454)

I set up the different department's in os ticket. One was named system administrator and the other was support. Jane miltion was working in the system administrator position and edward hill was working in the support positon. 

To set up osTicket follow these steps:

1. Verify Server Requirements: Ensure that your server meets the requirements for osTicket, such as a compatible web server (e.g., Apache or Nginx), PHP, and a supported database (MySQL or PostgreSQL).

2. Download osTicket: Visit the official osTicket website (osticket.com) and download the latest stable release of the software.

3. Upload Files: Extract the downloaded osTicket files and upload them to your web server's document root directory or a designated subdirectory.

4. Create Database: Create a new database for osTicket to store its data. You can use tools like phpMyAdmin or the MySQL command line to create the database.

5. Run the Installation Wizard: Open your web browser and visit the URL where you uploaded osTicket files. The installation wizard should automatically launch. If not, check if the "install" directory is present.

![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/7da1d601-4563-49c0-837b-ab52705d5240)





![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/2d11c9d9-8d51-4853-a492-5410629d6e0c)



