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
<img src="https://i.imgur.com/9SdzpG5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 I first Configured Roles (for grouping permissions) in the 
Admin Panel -> Agents -> Roles and gave the role all permissions and the name 
Supreme Admin. 
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
<img src="https://i.imgur.com/MGRLcO0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Then Configured Departments</p> 
<p>(Ticket Visibility, Help Desk vs   Corpadmin, vs Networking)</p>
<p>Admin Panel -> Agents -> Departments</p>
 <p>and named the department corpadmin</p>
  <p>
    <mark>the purpose of  departments</mark>
  </p>
<ul>
  <li>essential for organazing and managing tickets based on the structure of your organization.</li>
  <li>they act as logical grouping for tickets</li>
  <li>allow you to control wich agent handles specific task</li>
</ul>

</p>
<br />

<p>
<img src="https://i.imgur.com/mBaPOxp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>In this section i Configured Teams</p>
<p>Admin Panel -> Agents -> Teams (Pull Agents from different Departments)</p>
<p>Online Banking</p>
<mark>The purpose of teams</mark>
<ul>
  <li>designed to enable collaboration across departments</li>
  <li>handling specific task that require a group of agents working together</li>
  <li>teams are more flexible and are meant for crossdepartments collaboraion</li>
</ul>
 
</p>
<br />
<p>
 <img src="https://i.imgur.com/lGmmqsD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>For this lab i unchecked the require registration and login to create a ticket </p>
<br/>
<p><img src="https://i.imgur.com/qoAacZw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p><img src="https://i.imgur.com/eFXiYNf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
  
<p>For me to be able to understand how to use the ticketing system</p>
<p>i created both agents and costumers</p>
<ul>
  <li>Admin Panel -> Agents -> Add New
Chase Garden (Dept: Support)</li>
John Doe (Dept: Corpadmin)</li>
  <li>Configure Users (customers)
Agent Panel -> Users -> Add New
Katty 
Alanis
</li>
</ul>
<br />
<p>For the finishing touches i configured SLA and created topics</p>
<br />
<p><img src="https://i.imgur.com/Hs2oCsd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<p>The SLAs i created a,b and c.</p>
<p>A being the most severe and c being the least.</p>
<mark>For what is it used for?</mark>
<ul>
  <li>Define resolution timeframe.</li>
  <li>ensures if teams are resolving it in time</li>
  <li>Helps identify bottlenecks ir inefficiencies</li>
  <li>Assign different SLAs to tickets based on urgency</li>
  <li>Ensure critical issues are adressed faster.</li>
  <li>and more</li>
</ul>
<p><img src="https://i.imgur.com/6HDI3Q9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<p>I created all these help topic simulating how it would be in a real job.</p>
<p>Now i can have a better grasp in how the software works and hoe navigate it.</p>
<p>Most importantly how to manage costumers.</p>


<mark>The purpose of help topic</mark>
<ul>
  <li>help topics group ticket based on their nature or type.</li>
  <li>improve ticket routing</li>
  <li>streamline user experience</li>
  <li>support branding and communication</li>
  <li>and more</li>
</ul>



