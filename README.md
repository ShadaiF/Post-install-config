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

<p> Step 1: <b>Configure Roles </b> </p>
<p>
<img src="https://i.imgur.com/aeKPki7.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
- <a href=http://localhost/osTicket/scp/login.php>Log in</a> with the admin username and password that was created in the previous installation of osTicket
</p>
- Click on the Admin panel > Agents > Roles
</p>
- Add a new role ("Supreme Admin") that includes all checked Permissions
</p>
<br />

<p> Step 2: <b>Configure Departments</b> </p>
<p>
<img src="https://i.imgur.com/xPQaVio.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
</p>
<p>
- From Admin panel > Agents > Departments 
</p>
- Add a new department ("System Administrators") 
</p>
<br />

<p> Step 3: <b>Configure Teams </b> </p>
<p>
  <img src="https://i.imgur.com/LA4om7x.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
  <p>
- Still in Admin Panel > Agents > Teams 
</p>
- Add new team > "Level I Support" & "Level II support "
</p>
<br />

<p> Step 4: <b>Allow anyone to create tickets</b> </p>
<p>
  <img src="https://i.imgur.com/HZ7Ta1v.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
</p>
<p> - Admin Panel > Settings > Users  </p>

</p>
-Registration Required: Requires registration and login to create tickets 
</p>

<p> Step 5: <b>Configure Agents (workers) </b> </p>
<p>
  <img src="https://i.imgur.com/lUc0H3r.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/tTphq0c.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
  <p>
   -Admin Panel > Agents > Add new agent </p>
   - Create two new agents </p>
   <b>* Dont forget to create a password for the two agents* </b></p>
  
</p>
<br />

<p> Step 6: <b>Configure Users (customers)</b></p>
<p>
<img src="https://i.imgur.com/D38loiG.png" height="60%" width="60%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/qE8XJwG.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

</p>
<p> - Click on Agent Panel > Users > Add New User </p>
- Create two new users </p>
- Always remember to click Register and create a password for both users </P
- Click Create account and don't forget the passwords </p>


<p> Step 7: <b>Configure SLA</b> </p>
<p>
<img src="https://i.imgur.com/4JyVMBF.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
</p>
<p> - Click back over to Admin Panel > Manage > SLA </p>
<p>Add 3 SLA's</p>
<p> 
i. Sev-A: grace period of 1 hour, 24/7 </p>
ii. Sev-B: grace period of 4 hour, 24/7 </p>
iii. Sev-C: grace period of 8 hour, business hours </p>
<p> <b>* SLA is the turnaround time in which a ticket needs to be answered or resolved* </b></p>

<p> Step 8: <b>Configure Help Topics </b> </p>
<p>
<img src="https://i.imgur.com/48W3f19.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> 
</p>
<p>
- Still being in Admin panel > Manage > Help Topics 
</p>
- Add a new department ("System Administrators") </p>
i. Business Critical Outage </p>
ii. Personal Comouter Issues </p>
iii. Equipment Request </p>
iv. Password Reset </p>

</p>
<br />

