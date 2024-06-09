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

![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/f4d26b9f-6f8e-4e01-8440-1c399a155c1e)

Setting up an Azure virtual network involves the following steps:

Sign in to the Azure Portal: Access the Azure Portal using your Azure account credentials.

Create a Virtual Network (VNet): Search for "Virtual Networks" in the search bar and select "Virtual Networks" from the search results. Click on "Add" to create a new VNet.

Define VNet settings: Give your VNet a name and choose the subscription, resource group, and location. Specify the address space for the VNet, which defines the IP address range. You can also configure DNS server settings if necessary.

Configure subnets: Within the VNet, create one or more subnets. Define the subnet name and IP address range for each subnet. Ensure that the subnet ranges do not overlap.

Advanced networking options: You may choose to configure additional settings, such as Network Security Groups (NSG) for controlling inbound/outbound traffic, User-Defined Routes (UDR) for custom routing, and VPN Gateway for connecting on-premises networks.

Peer virtual networks (optional): If you have multiple VNets and want to enable communication between them, you can set up VNet peering. This allows network traffic between the peered VNets.

Set up network security: Configure NSGs to enforce network security rules for subnets and control inbound/outbound traffic. You can define rules for allowing or denying specific protocols and port access.

Associate resources: Associate resources like virtual machines (VMs), load balancers, and other services with the virtual network. Ensure that the resources are deployed within the desired subnets.

Test connectivity: Validate connectivity by testing communication between resources within the virtual network. Verify that the configured network settings are functioning as expected.

By following these steps, you can easily set up a virtual network in Azure, which provides a secure and isolated network environment for your applications and services, enabling seamless communication and connectivity.

![image](https://github.com/derekjonesaa/osticket-prereqs/assets/167825508/7bc8fbbc-ca26-41c5-996b-6db86d03c20b)

Im using Remote Desktop technology. Which can be used with various operating systems, including Windows, macOS, and Linux. It provides a secure and efficient way to access computers remotely, enabling users to work, troubleshoot, or collaborate from different locations.To set up and use Remote Desktop, follow these general steps:

1. Enable Remote Desktop on the target computer: Open the System Properties on the computer you want to access remotely. Go to the Remote tab and enable "Allow Remote Connections to this computer." You may need to adjust firewall and network settings to allow Remote Desktop connections.

2. Obtain the IP address or hostname of the target computer: Note down the IP address or hostname of the computer you want to connect to remotely. You will need this information to establish the Remote Desktop connection.

3. Connect to the remote computer from another device: On your remote device (e.g., another computer or mobile device), launch the Remote Desktop client application. If it is not pre-installed, you can download it from the official website for your operating system.

4. Enter the IP address or hostname: In the Remote Desktop client, enter the IP address or hostname of the target computer you want to connect to.

5. Authenticate and connect: Enter the login credentials (username and password) for the target computer when prompted by the Remote Desktop client. Make sure you have the necessary permissions to access the remote computer.

6. Configure display and other settings (optional): The Remote Desktop client may offer options to adjust display settings, audio settings, and other preferences. Customize these settings as needed.

7. Connect and access the remote desktop: After providing the necessary information and settings, click on the "Connect" or "Start" button in the Remote Desktop client. This will establish the connection to the remote computer and show you its desktop interface.

8. Interact with the remote desktop: Once connected, you can use your local device's mouse, keyboard, and touch controls (if applicable) to interact with the remote desktop just as if you were physically sitting in front of it. You can run applications, access files, and perform tasks as if you were using the remote computer directly.

9. Disconnect and end the session: When you are finished with the remote session, you can either log off from the remote computer or simply close the Remote Desktop client application. This will end the connection and return you to your local device.

you have to ensure that the target computer has Remote Desktop access enabled and is reachable from your remote device. Additionally, check for any firewall or network restrictions that might affect the Remote Desktop connection.



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



