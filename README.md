<p align="center">
<img src="https://imgur.com/HGz9rxB.png alt="Azure SecOps"/>
</p>
<br />
<br />

<h1>Azure SecOps - Failed Authentication and Log Observation (April 2023)</h1>
In this tutorial I demonstrate the install of MS SQL Server on a VM and the failed login attempts into SQL server from another VM, an "attack VM" I created. I show this through the security logs on windows event viewer in the main VM.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Cloud Platform

- Microsoft Azure (Virtual Machines) abbreviated VM. VMs are used to install the SQL Server and also view the event logs from the failed login attempts.

- Remote Desktop Protocol (RDP) is used to connect to the virtual machines and it is one type of traffic observed in wireshark. (For this demonstration I use the RDP app in the Microsoft Store). 



<h2>Operating Systems Used </h2>

- Windows 10 (21H2)



