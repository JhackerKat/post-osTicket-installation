<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/aclhHTZvS_M)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
<img width="502" alt="Step 1 - a" src="https://github.com/user-attachments/assets/5f5a74b3-8fa6-42b6-9795-406aa866d6fb" />
<img width="500" alt="Step 1 - b" src="https://github.com/user-attachments/assets/56ad82d9-9fc8-4a08-81e7-b6b9e29ebe23" />
<img width="501" alt="Step 1 - c" src="https://github.com/user-attachments/assets/fa1d07dd-071f-4ddf-b57f-81255e6f0696" />
<img width="502" alt="Step 1 - d" src="https://github.com/user-attachments/assets/a23f2ee7-448e-4f93-afbc-bde28f4c212e" />

</p>
<p>
Step 1: Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
• Supreme Admin
</p>
<br />

<p>
<img width="501" alt="Step 2" src="https://github.com/user-attachments/assets/f9aa127e-2fde-4f82-ab28-1534b26fa500" />
</p>
<p>
Step 2: Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
• SysAdmins
</p>
<br />

<p>
<img width="502" alt="Step 3" src="https://github.com/user-attachments/assets/d7e80d25-a90a-4e51-9eb4-85850a91a059" />
</p>
<p>
Step 3: Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
• Online Banking
</p>
<br />

<p>
<img width="501" alt="Step 4" src="https://github.com/user-attachments/assets/de2b5ba8-e3bd-4d7f-9083-304c652f9482" />
</p>
<p>
Step 4: Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
• Registration Required: Require registration and login to create tickets
</p>
<br />

<p>
<img width="502" alt="Step 5 - a" src="https://github.com/user-attachments/assets/2908564f-1ad1-48bf-9e0a-4091903750d9" />
<img width="504" alt="Step 5 - b" src="https://github.com/user-attachments/assets/1c182817-db1c-4c91-83b6-7fd07c08b6c3" />
<img width="500" alt="Step 5 - c" src="https://github.com/user-attachments/assets/e53b16ae-813b-485e-83d2-fd1c515f97e5" />
</p>
<p>
Step 5: Configure Agents (workers)
Admin Panel -> Agents -> Add New
• Jane (Dept: SysAdmins)
</p>
<br />

<p>
<img width="501" alt="Step 6 - a" src="https://github.com/user-attachments/assets/1e1905ae-0bff-44f4-892c-75b68032afa2" />
<img width="502" alt="Step 6 - b" src="https://github.com/user-attachments/assets/7141f996-9a8d-4bde-ba42-cbe7f5c28ff7" />
</p>
<p>
Step 6: Configure Agents (workers)
Admin Panel -> Agents -> Add New
• John (Dept: Support)
</p>
<br />

<p>
<img width="500" alt="Step 7 - a" src="https://github.com/user-attachments/assets/2d1b9467-52f0-4a8d-ab6c-e17c667a3741" />
<img width="500" alt="Step 7 - b" src="https://github.com/user-attachments/assets/3fde8ef4-647e-46c5-8e3b-c60e3f799624" />
</p>
<p>
Step 7: Configure Users (customers)
Agent Panel -> Users -> Add New
• Karen
• Ken
</p>
<br />

<p>
<img width="501" alt="Step 8 - a" src="https://github.com/user-attachments/assets/b0d197b8-8796-4609-8675-09b21d7bd440" />
<img width="503" alt="Step 8 - b" src="https://github.com/user-attachments/assets/ee9f4765-9f0b-4e4a-af3a-cc83c02bdd88" />
<img width="502" alt="Step 8 - c" src="https://github.com/user-attachments/assets/672a91f8-8791-48a2-aa16-133ecd687a4b" />
</p>
<p>
Step 8: Configure SLA
Admin Panel -> Manage -> SLA
• Sev-A (Grace Period: 1 hour, Schedule: 24/7)
• Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />

<p>
<img width="501" alt="Step 9 - a" src="https://github.com/user-attachments/assets/34855238-4d8f-4e82-97d0-fe72aeec35df" />
<img width="500" alt="Step 9 - b" src="https://github.com/user-attachments/assets/9cf239dd-4324-45d0-8729-45f666ec1350" />
<img width="501" alt="Step 9 - c" src="https://github.com/user-attachments/assets/739d59f5-b660-44d6-a0dd-704f55bef384" />
<img width="501" alt="Step 9 - d" src="https://github.com/user-attachments/assets/8cd19110-d468-458e-ba6e-2ec91d24065f" />
<img width="501" alt="Step 9 - e" src="https://github.com/user-attachments/assets/d0959a6f-0580-4fd4-90d3-b960ecda616c" />
</p>
<p>
Step 9: Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
• Business Critical Outage
• Personal Computer Issues
• Equipment Request
• Password Reset
• Other
</p>
<br />


