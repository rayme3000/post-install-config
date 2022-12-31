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

- Reload IIS and Enable Extensions in IIS
- Continue Setting up osTicket in the browser
- Download and Install HeidiSQL
- Continue Setting up osticket in the browser
- Clean up

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installation Go to sites -> Default -> osTicket and  click “Browse *:80”. From there enable extensions in IIS. Then go back to IIS, sites -> Default -> osTicket. Double-click PHP manager and Click “Enable or disable an extension”.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Assign Permissions: ost-config.php. Disable inheritance -> Remove All, New Permissions -> Everyone -> All.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download, install and open HeidiSQL. Create a new session and create a database called “osTicket”. Continue Setting up osTicket in the browser and click “Install Now!”
</p>
<br />
