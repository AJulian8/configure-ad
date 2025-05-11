# configure-ad
<p align="center">
<img src="https://i.imgur.com/g4LY2yK.png" width="400"/> 
</p>

<h1>Active Directory - Prerequisites and Installation</h1>
This tutorial outlines the installation and use of actice directory in our Azure VM's.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install Internet Information Services (IIS)
- Set up Domain Controller
- Create a Virtual Network and Subnet
- Create the Domain Controller VM's
- Log into the VM and edit the firewall

<h2>Active Directory Lab Steps</h2>

<p>
<img src="https://i.imgur.com/EkICON4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Azure the first step in setting up our Domain Controller is creating a resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/BqrIYoY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we want to create a Virtual Network and Subnet.
</p>
<br />

<p>
<img src="https://i.imgur.com/Lg5J3oL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then we will creat a virtual machine for the domain controller.
</p>
<br /> 

<p>
<img src="https://i.imgur.com/Q08nQmY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we just want to go in and change the IP to static just to make the movement between vm's easier for us.
</p>
<br /> 

<p>
<img src="https://i.imgur.com/8nJRxW4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then went in and turned off the firewall within dc-1 just for testing connectivity. 
</p>
<br /> 

<p>
<img src="https://i.imgur.com/NvGLKHV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we create our client-1 virual machine and set it to the same resource group and make it Windows 10 Pro. 
</p>
<br /> 

<p>
<img src="https://i.imgur.com/V8jRxrs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
So within client-1 since I want it to point directly to my comain controller I went in to changed the netowrk interface card and used it's IP for my DNS server. 
</p>
<br /> 

<p>
<img src="https://i.imgur.com/BTcdFI5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the final step in this section were just going to ping dc-1's private IP address to make sure everything worked properly. 
</p>
<br /> 
