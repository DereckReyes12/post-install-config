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

- assign roles
- assign departments
- assign teams  
- configure agents
- configure user
- configure SLA
- configure Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

 <h2 align="center;">Configuring Roles (for grouping permissions)</h2>

 <p>Admin Panel -> Agents -> Roles and gave the role all permissions and the name 
Supreme Admin.</p> 
  <p>
    <mark>the purpose of the roles</mark>
  </p>
<ul>
  <li>access Control </li>
  <li>task segregation</li>
  <li>security</li>
  <li>giving agents only tools they need</li>
  <li>track actions by role to  maintain a record of changes or activity.
  
</ul>

</p>
<br />

<p>
<img src="https://i.imgur.com/2BGdr6j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/roPAEQ0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bzKvxfm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UciluZe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vuFYxZd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h3 align="center;">Configure Departments</h3>
<br />
<p>(Ticket Visibility, Help Desk vs   Corpadmin, vs Networking)</p>
<p>
    <mark>the purpose of  departments</mark>
  </p>
<ul>
  <li>essential for organazing and managing tickets based on the structure of your organization.</li>
  <li>they act as logical grouping for tickets</li>
  <li>allow you to control wich agent handles specific task</li>
</ul>
</p>
<p>Admin Panel -> Agents -> Departments</p>
<p>system administrator</p>
<br />
<p>
<img src="https://i.imgur.com/83gWQsO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/oGLXmQv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<p>Online Banking</p>
<mark>The purpose of teams</mark>
<ul>
  <li>designed to enable collaboration across departments</li>
  <li>handling specific task that require a group of agents working together</li>
  <li>teams are more flexible and are meant for crossdepartments collaboraion</li>
</ul>
 </p>
 <p>Admin Panel -> Agents -> Teams (Pull Agents from different Departments)</p>
<br />
<p>
 <img src="https://i.imgur.com/BnPrcDH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Level II support</p>
<br />
<br /><h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>Admin Panel -> Settings -> User Settings.</p>
 <p>Make sure "required registration and login to create tickets" is not selected:
 </p>
 <img src="https://i.imgur.com/QsJjOuM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
 <br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
 <P>Admin Panel -> Agents -> Add New.</P>

  Jane Doe:
</p>
  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/NcCP0v9.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/aKTJ01A.png" height="75%" width="100%" alt="agent two access"/>

<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
  

 
</li>
</ul>
<br />
<h3 align="center;">Configure SLA</h3>
<br />
<mark>For what is it used for?</mark>
<ul>
  <li>Define resolution timeframe.</li>
  <li>ensures if teams are resolving it in time</li>
  <li>Helps identify bottlenecks ir inefficiencies</li>
  <li>Assign different SLAs to tickets based on urgency</li>
  <li>Ensure critical issues are adressed faster.</li>
  <li>and more</li>
</ul>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/izcD74X.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/xKzdp7w.png" height="75%" width="100%" alt="sev three"/>
</p>
  <h3 align="center;">Configure Help Topics</h3>

<mark>The purpose of help topic</mark>
<ul>
  <li>help topics group ticket based on their nature or type.</li>
  <li>improve ticket routing</li>
  <li>streamline user experience</li>
  <li>support branding and communication</li>
  <li>and more</li>
</ul>
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/3Y7k2o1.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/Z0eIGea.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/ndOdtTZ.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<br />
<p>
  Your osTicket is now fully configured. I hope this guide has been helpful in clarifying the set up process
</p>
<p>
 and assisting you with configuring osticket.it's highly recommended to practice triaging and resolving tickets
</p>
<p>to futher enhance your familiarity with the system.</p>
<p>
 This is a crucial skill for any help desk specialist,as they serve as the first point of contact between a company
</p>
<p>
 and its costumers when addressing issues related to the products or services provided.
</p>




