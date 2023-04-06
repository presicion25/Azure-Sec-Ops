<p align="center">
<img src="https://imgur.com/el8K3NN.png alt="Azure SecOps"/>
</p>
<br />
<br />

<h1>Microsoft Azure - Active Directory Overview and Failed Authentication/Log Observation (April 2023)</h1>
In this tutorial I demonstrate the install of MS SQL Server on a VM and the failed login attempts into SQL server from another VM, an "attack VM" I created. I show this through the security logs on windows event viewer in the main VM.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Cloud Platform

- Microsoft Azure (Virtual Machines) abbreviated VM. VMs are used to install the SQL Server and also view the event logs.

- Remote Desktop Protocol (RDP) is used to connect to the virtual machines. (For this demonstration I use the RDP app in the Microsoft Store). 

- Windows Event Viewer to view the logs showing the failed authentication attempts.


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>Video Demonstrations</h2>


1. Part one below I complete the follwing:

- I demonstrate the install of MS SQL Server 
- Configure the VM firewall too accept all inbound traffic
- Turn off windows firewall
- The install of SQL Server Management Studio 
- Enable logging for the SQL server to be ported into event viewer
- Test logging in event viewer

[![Part 1](https://i.vimeocdn.com/video/1650149187-dbc92c7f41fefa893af4cea7af7745ac8e5230cceb54b97206d23413472315d2-d_295x166?r=pad)](https://vimeo.com/815368596 "Azure Lab Part 1")
<br />
<br />


2. In Part two below I complete the following:

- Attempt to RDP five times into the main VM from the attack VM using the wrong credentials
- RDP into the main VM from the attack VM using the correct credentials
- From the main VM, inspected the failures and successes (Security log for RDP, Application log for SQL)

[![Part 1](https://i.vimeocdn.com/video/1650064553-0578d5b933051abaa0dc9628a65d599e7605b3e2ff5f627fc168d9e7b3f471dc-d_295x166?r=pad)](https://vimeo.com/815395656 "Azure Lab Part 2")

<b>This is the end of the lab. I hope it was helpful.</b>


<h1>Thank Your for looking! For more content like this, visit <a href="https://exemplarysecurity.com">my website</a>☺</h1>













