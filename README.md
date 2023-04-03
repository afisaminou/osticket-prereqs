<p align="center">
<img src="https://i.imgur.com/ZOUm27S.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Widely-used open source support system, osTicket seamlessly integrates inquieries creared via email, phone and web-based forms into a simple easy-to-use multi-user web interface.Manage, organize and archive all your support requests and responses in one place while providing your customers the high quality service they deserve.
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Technologies and Environments Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL
- Item 4
- Item 5

<h2>Installation Steps</h2>
Welcome to this tutorial!

I have provided a link here: https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6 That link will provide you with all the material needed to download and get osTicket up and running.

**Here a Step by step guide line Doc**: [CLICK ME](https://docs.google.com/document/d/1NwkGnj89wmbUcU-N2-20DjQNER1iwr_t/edit?usp=share_link&ouid=111907008899833271635&rtpof=true&sd=true)

Let's get started quickly by creating our resource group and virtual machine (VM) in the Microsoft Azure portal. In order to protect our physical machine from any event that may occur, we will use a VM and connect to it via RDP (Remote Desktop Protocol) for the next steps in our tutorial.

<img src="https://i.imgur.com/quWtguU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now ,simply connect to our newly created VM via RDP using the VM public IPv4 address. 
Note:If you are a Mac user, you will have to download Microsoft RDP to be able to remotely connect to the VM.
<img src="https://i.imgur.com/jcHgeUc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Great!  Now that you are connected to your VM you will have to enable **IIS (Internet Information Services)**. To do so, 1-Access the Control Panel > 2-Program > 3-On the upper left hand side select **"Turn Windows features On or Off"**> 4- Enable the **IIS** (Internet Information Services) > 5-Expand the World Wide Web Services > 6-Expand Application Development features > 7-Check the **CGI box and click OK to install**.


<img src="https://i.imgur.com/WTZReTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Perfect! Now that you have enabled IIS we need to install Web Platform Installer. 
Simply click  the file and install the Web Platform Installer
</p>
<br />
<p>
<img src="https://i.imgur.com/nBYUaCi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
From the installation files, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
From the installation files, install the Rewrite Module (rewrite_amd64_en-US.msi)

<p>
<img src="https://i.imgur.com/ONqi3c8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
<br />
Create the directory C:\PHP

From the installation files, unzip PHP 7.3.8(phph-7.3.8-nts-Win32-VC15-x86.zip) into the C:/PHP directory you created.

<p>
<img src="https://i.imgur.com/q5e5xS1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
From the installation files install VC_redist.x86.exe.

<p>
<img src="https://i.imgur.com/0HP8dI0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
From the installation files install MySQL 5.5.62 (mysql-5.5.62-win32.msi)

Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1

<p>
<img src="https://i.imgur.com/NHm3jYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p></p>
<br />
