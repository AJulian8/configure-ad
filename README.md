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
This diagram above is the easiest way to show  what I created as far as my client-1 and how it will be communicating with the domain controller. I also went in and created my rescourse groups along with a virtual network and subnet that will be shown in the next slides.
</p>
<br />

<p>
<img src="https://i.imgur.com/XOkkW9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we can see that I successfully created my domain controller and set it up properly allowing me to use Server Manager. In this VM is where I can make changes to the firewall and also change client-1 and change the IP to point to my domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/X8I8Pet.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this image we simply logged into client-1 just to make sure all the information is right and to retrieve the right IP adress.
</p>
<br />
