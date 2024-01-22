<h1>Active Directory Dynamics : Server Administration</h1>

<b>This project guides you through process of establishing a virtual environment running Active Directory and enabling the creation of multiple users using PowerShell. Setting up an Active Directory Virtual Environment serves two primary purposes:</b>
<br />
<p>
a) Identity Management - Businesses globally rely on Active Directory as a robust identity provider, facilitating efficient user account management and precise access regulation. 
<br />
<br />
b) Information Security - Active Directory is pivotal in information security, offering diverse defense mechanisms while being susceptible to various attack vectors, demanding users to comprehend its functionality and vulnerabilities.
</p>

<h2 align="center">Network Infrastructure</h2>
<p align="center">
<img src="https://i.imgur.com/5sqdBqf.jpg" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h4>Technologies Used:</h4>

- <b>Active Directory:</b> To familiarize users with the configuration and management of Active Directory, a crucial component in network administration and identity management.
- <b>PowerShell:</b> To enable users to harness the power of scripting and automation for efficient and effective management of tasks within the Active Directory environment
- <b>Windows Server:</b> To provide a practical understanding of configuring and utilizing Windows Server, a fundamental platform for hosting Active Directory services.
- <b>Virtualization (Oracle VirtualBox/VMware):</b> To introduce users to virtualization technology using Oracle VirtualBox or VMware, facilitating the creation and management of virtual environments for testing and learning Active Directory configurations.

<h2>Description</h2>
Follow this step-by-step process to create and manage an Active Directory environment in a virtual setting. 
</p>

<b>1. Set Up Virtual Machines:</b> <br />
- Open VirtualBox and click on "New" to create a new virtual machine
- Name the virtual machine and select "Type" as "Microsoft Windows" and "Version" as per your Windows Server ISO.
- Allocate sufficient memory (RAM) and create a virtual hard disk.
- Adjust additional settings like network configurations and processor settings.
  
<b>2. Install Windows Server on Virtual Machines:</b> <br />
- Mount the Windows Server ISO to the virtual machine.
- Start the virtual machine and begin the Windows Server installation process.
- Follow on-screen instructions to complete the installation, including setting up a password and specifying roles.

<b>3. Configure Active Directory:</b> <br />
- After Windows Server installation, open Server Manager.
- Click on "Add roles and features" and select "Active Directory Domain Services (AD DS)."
- Follow the wizard to install AD DS, including configuring a new forest and domain.
- Promote the server to a domain controller.

<b>4. Create Additional Virtual Machines:</b> <br />
- Repeat Steps 1 and 2 to create additional virtual machines for the Active Directory environment.
- Join these virtual machines to the domain created in Step 3

<b>5. Test Active Directory:</b> <br />
- Log in to different virtual machines using domain credentials.
- Test user and group management within Active Directory.
- Verify DNS settings and ensure proper replication.

<b>6. Conclusion:</b> <br />
- By following these steps, you have successfully created a full-blown Active Directory lab on your personal computer. This hands-on experience will deepen your understanding of Active Directory and Windows networking.

<h2 align="center">Server Manager - Windows Server 2019</h2>

<p align="center">
<img src="https://i.imgur.com/rtNFaeJ.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2 align="center">User Creation using powershell script</h2>

<p align="center">
<img src="https://i.imgur.com/3Mjb8oR.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2 align="center">Active Directory Users and Computers</h2>

<p align="center">
<img src="https://i.imgur.com/17Hz5Du.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
