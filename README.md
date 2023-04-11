<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial is the continuation of the first repository and outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users (Customers)
- Configure SLA
- Configure Help Topic

<h2>Configuration of Roles</h2>

<h4>Configuration of Super Admin</h4>

<p>
Go to this <a href="http://localhost/osTicket/scp">URL</a> and login.
</p>

<p>
<img src="https://i.imgur.com/p0HkG1k.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
You will be redirected to this page.
</p>

<p>
<img src="https://i.imgur.com/BkeLnUv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
Now we will make a Supreme Admin Role. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/ERi0a9H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/D5d2MOz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/nRKWIPq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/PdrL7sn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Vv9qOhn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/dXTf6fj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/EQA5trH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Configuration of Department Role</h4>

<p>
Follow these steps to make a department role.
</p>

<p>
<img src="https://i.imgur.com/RsNe6o7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/BQjz6xH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/13xYPvw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/eOzlq5o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Configure Teams</h4>

<p> 
Now let's configure our teams, we'll create Level 2 Support since Level 1 Support already exists. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/u6CBjkH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/RT3etPu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Zc3L37Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/HKsky6F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Allow anyone to create tickets</h4>

<p>
Let's allow anyone as long as they are registered in our system to create tickets. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/LcopHN5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/tNpWpR6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Configure Agents (Workers)</h4>

<p>
Let's add agents by doing the following steps.
</p>

<p>
<img src="https://i.imgur.com/Bx4mUN4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/IIMGOqa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/bFYdJqm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/z1iNE2K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/TQyKF3i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/LC40abC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create a new user and choose whatever name you want. But this time choose these options.
</p>

<p>
<img src="https://i.imgur.com/omgmqiJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/9xv3AZu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Now click <ins>Save Changes</ins> and now we should have 3 agents.
</p>

<p>
<img src="https://i.imgur.com/ZOiFvi0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Configure Users (Customers)</h4>

<p>
Follow these steps to create a registered user so they can send tickets.
</p>

<p>
<img src="https://i.imgur.com/vs610Rx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Ntnjvgl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/6vuBNVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/618eqvd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/6fdEKGI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Btji5w4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create another user using the same steps. After you finished creating another user, it should appear like this.
</p>

<p>
<img src="https://i.imgur.com/S3Tjc9V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Configure SLA (Service Level Agreement)</h4>

<p>
Setup our SLA (NOTE: SLA depends on the company so we are just using some examples here). SLAs are guidelines of the company for how long you can fix the tickets based on their severity. Follow these steps for creating SLA.
</p>

<p>
<img src="https://i.imgur.com/Y7ix93i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/9YnLxMn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/yi4pJfL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Lu9BVVp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- <b>Repeat the process and create 2 more SLAs. Follow these guide.</b> 
  - Name: Sev-B, Grace Period: 4 Hours, Schedule: 24/7. Click <ins>Add Plan</ins> after doing this.
  - Name: Sev-C, Grace Period: 8 Hours, Schedule: Mon - Fri 8am - 5pm. Click <ins>Add Plan</ins> after doing this.

<p>
After saving the changes, we should see our 3 SLAs.
</p>

<p>
<img src="https://i.imgur.com/wU9dA0l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>












<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

















<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
