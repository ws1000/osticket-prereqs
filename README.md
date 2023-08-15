<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Virtual Machine in Azure
- Subscription in Azure
- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs4
- When creating the VM, allow it to create a new Virtual Network (Vnet)


<h2>Installation Steps</h2>


<p>
<img src="https://i.imgur.com/wobMGO7.png" height="80%" width="25%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/UGdYC5b.png" height="80%" width="25%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/0PG2FRX.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Install / Enable IIS in Windows WITH: 
- CGI and Common HTTP Features
- IIS Management Console
<h2></h2>  
</p>
<br />

<p>
<img src="https://i.imgur.com/DaCgytw.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Dependencies downloaded to install osTicket.

</p>
<br />

<h2>Install osTicket</h2>
<p>
<img src="https://i.imgur.com/z43kfO0.png" height="80%" width="30%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/OmPLgkX.png" height="80%" width="30%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Download osTicket from the Installation Files Folder
- Extract and copy “upload” folder to c:\inetpub\wwwroot
- Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

</p>
<br />

<h2>Configure Extensions for osTicket</h2>
<p>
<img src="https://i.imgur.com/nQApEDD.png" height="80%" width="30%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Enable: php_imap.dll
- Enable: php_intl.dll
- Enable: php_opcache.dll

</p>
<br />

<h2>Assign Permissions: ost-config.php</h2>
<p>
<img src="https://i.imgur.com/CjHz9gu.png" height="80%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DBfNt6A.png" height="80%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Disable inheritance -> Remove All
- New Permissions -> Everyone -> All

</p>
<br />

<h2>Download and Install HeidiSQL</h2>
<p>
<img src="https://i.imgur.com/AAIcORL.png" height="80%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Create a new session
- Connect to the session
- Create a database called “osTicket”

</p>
<br />

<h2>Links to osTicket</h2>

- INSERT HERE

