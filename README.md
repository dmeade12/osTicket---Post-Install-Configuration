<p align="center"><img src="https://i.imgur.com/RPZ9Gws.png" height="50%" width="50%" alt="image"/>
<h1>osTicket Post-Installation Configuration</h1>
<p> This tutorial outlines the post-installation configuration of the open-source help desk ticketing system <b>"osTicket"</b>.</p>

<h3>*Environments and Technologies Used</h3>
<p>Windows 11 Pro</p>
<p>Internet Information Services (IIS)</p>
<p>osTicket</p>

<h3>*Operating System Used</h3>
<p>Windows 11 Pro (24H2)</p>

<h3>*Configuring Roles</h3>
<p1>1. Configure Roles (for grouping permissions) - To do this, clicked on Admin Panel > Agents > Roles to examine all the roles available. And also created a new role called Supreme Admin and gave it all access and permissions.</p>
<p align="center"><img src="https://i.imgur.com/Pa76PHm.png" height="50%" width="50%" alt="image"/>

<p>2. Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking) - To create new departments, from the Admin Panel > Agents > Departments, then clicked on Add new departments called SysAdmins.</p>
<p align="center"><img src="https://i.imgur.com/m9MyVce.png" height="50%" width="50%" alt="image"/>

<p>3. Configure Teams - To do this, from the Admin Panel, clicked on Agents > Teams (Pull Agents from different Departments). Then created a new department called Online Banking</p>
<p align="center"><img src="https://i.imgur.com/1zPSkF4.png" height="50%" width="50%" alt="image"/>

<p>4. Allow anyone to create tickets - To configure this, from the Admin Panel > Settings > User Settings (UNCHECK: unregistered users can create tickets)</p>
<p align="center"><img src="https://i.imgur.com/qWQyuuX.png" height="50%" width="50%" alt="image"/>

<p>5. Configure Agents (workers) - To do this, from the Admin Panel go to Agents > Add New. Created two agents:Jane (Dept: SysAdmins) and  John (Dept: Support)</p>
<p align="center"><img src="https://i.imgur.com/253SVcp.png" height="50%" width="50%" alt="image"/>

<p>6. Configure Users (customers) - To do this from the Agent Panel > Users > Add New. Created two new users; Karen and Ken.</p>
<p align="center"><img src="https://i.imgur.com/GfbxBmi.png" height="50%" width="50%" alt="image"/>

<p>7. Configure SLA(Service Level Agreement) - To do this, from the Admin Panel > Manage > SLA
<p>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</p>
<p>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</p>
<p>Sev-C (Grace Period: 8 hours, Business Hours)</p>
</p>
<p align="center"><img src="https://i.imgur.com/PSueC2P.png" height="50%" width="50%" alt="image"/>

<p>8. Configure Help Topics (For when users create a ticket) -  To do this from Admin Panel > Manage > Help Topics</p>
<p>Business Critical Outage</p>
<p>Personal Computer Issues</p>
<p>Equipment Request</p>
<p>Password Reset</p>
<p>Other</p>
</p>
<p align="center"><img src="https://i.imgur.com/95CsOYi.png" height="50%" width="50%" alt="image"/>
