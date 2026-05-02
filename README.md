# azure-network-protocols<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1  To set up your lab, create a Resource Group, then deploy a Windows 10 VM (generating a new VNet/Subnet in the process), and finally add an Ubuntu VM using the Password authentication type while ensuring it joins that exact same Resource Group and VNet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
- Step 2 Connect to your Windows VM via Microsoft Remote Desktop, install and filter Wireshark for ICMP, then observe the traffic as you ping both the Ubuntu VM's private IP and a public website.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
- Step 3 Run a perpetual ping from your Windows VM to your Ubuntu VM while toggling Inbound ICMP in the Network Security Group to observe traffic changes in Wireshark, then switch to an SSH filter and capture the encrypted traffic as you remotely log into the Linux machine via PowerShell.                                                                                                                                                                                                                                                                                                                                                                                                                                     
- Step 4 Filter Wireshark for DHCP while running ipconfig /renew, for DNS while performing nslookup for websites, and for RDP (tcp.port == 3389) to observe the constant traffic stream required to maintain your live remote session.



<p>


</p>
<p>


</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />
