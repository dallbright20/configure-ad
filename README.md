# configure-ad
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Install and Configure Active Directory </h1>
In this tutorial I will show the basic set up of Active Directory .<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Linux(Ubuntu)
- Windows 10 (21H2)

<h2>Prerequisite</h2>

- Azure Subscription


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/8VcEv5B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Navigate to the Windows Server Manager.
2. Click Add Roles and Features
3. It will open Add Roles and Features wizard. Click Next
4. Select the server from the server pool and click Next.
5. Click Checkbox to select Active Directory Domain Servicesom the server pool and click Next
6. On the popup Window, just click Add Features.
7. On the description window of Active Directory Domain Services, click Next
8. Click Install on the Confirmation window
9. Installation process begins
10. After installing AD DS Role, you can promote this Server to a Domain Controller
11. Select Add a new forest and give the Root domain name, ad.gpfs.net. Click Next.
12. Enter the Directory Services Restore Mode password.
13. Ignore the warning message.
14. Use the default NetBIOS domain name and click Next
15. Use the default paths and click Next
16. Review and click Next if no errors
17. Click Install and wait for the installation to finish
18. The Domain Controller is now set up.
</p>
<br />

<p>
<img src="https://i.imgur.com/tE6BBAM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Log in to the Windows AD domain server
2. Click Start
3. Point to Administrative Tools
4. Click Active Directory Users and Computers
5. Click the domain name you created
6. Expand the contents
7. Right-click Users
8. Point to New
9. Click User
10. In the New Object -- User dialog, enter a first name, last name, and user logon name
11. Click Next
12. Type and confirm a password, then click Next
</p>
<br />

