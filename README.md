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


![php enable](https://user-images.githubusercontent.com/59034949/211162308-149ec4c3-fa10-4620-af19-3230bfd6272e.png)


<p>
After installation Go to sites -> Default -> osTicket and  click “Browse *:80”. From there enable extensions in IIS. Then go back to IIS, sites -> Default -> osTicket. Double-click PHP manager and Click “Enable or disable an extension”.
</p>
<br />

![dpermissions](https://user-images.githubusercontent.com/59034949/211162082-8e2baa7b-2879-47ad-9765-5df12cdd29b1.png)


<p>
Assign Permissions: ost-config.php. Disable inheritance -> Remove All, New Permissions -> Everyone -> All.
</p>
<br />

![hedi](https://user-images.githubusercontent.com/59034949/211162120-8b609bad-0d51-4cc7-b4aa-6dbefae658bf.png)


<p>
Download, install and open HeidiSQL. Create a new session and create a database called “osTicket”. Continue Setting up osTicket in the browser and click “Install Now!”
</p>
<br />
