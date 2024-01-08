<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=HGywPhfKt4E)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/aeKPki7.png" height="80 " width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Log into (http://localhost/osTicket/scp/login.php) with the admin username and password that was created in the previous installation of osTicket
</p>
- Click on the Admin panel > Agents > Roles
</p>
- Add a new role ("Supreme Admin") that includes all checked Permissions
</p>
<br />

<p>
<img src="https://i.imgur.com/xPQaVio.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
- From Admin panel > Agents > Departments 
</p>
- Add a new department ("System Administrators") 
</p>
<br />

<p>
  <img src="https://i.imgur.com/LA4om7x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  <p>
- Still in Admin Panel > Agents > Teams 
</p>
- Add new teams > "Level I Support" & "Level II support "
</p>
<br />


<p>
  <img src="https://i.imgur.com/HZ7Ta1v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
  - Allow anyone to create tickets: Admin Panel > Settings > Users 
</p>
-Registration Required: Requires registration and login to create tickets 
</p>

<p>
  <img src="https://i.imgur.com/lUc0H3r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/tTphq0c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  <p>
- Lets create an agent: Admin Panel > Agents > Add new  
</p>
- Add new teams > "Level I Support" & "Level II support "
</p>
<br />


