<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- VC_redist.x86.exe
- Item 3
- Item 4
- Item 5
https://drive.google.com/drive/folders/1dVwii7TNJpaFgj0uG4hpdJhc-Tag0kH9?usp=drive_link
<h2>Installation Steps</h2>

<p>

![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/68d380c1-a0a0-4de6-b4b6-5f02eb88770a)
</p>
<p>
			Create a Vertual Machine (VM) in Azure, while creating the VM in the basics page create a resource group, name the VM, change the image to windows 10, pick a size with 2-4 vcpus, create a username and password and remember it.
</p>
<br />

<p>
  
![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/6b73aac3-df64-4512-92e3-cf93ad971fff)
![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/c0e19a48-ee58-4358-8a49-afd3ac5b994e)
</p>
<p>
On the Networking page make sure there is a new virtual network then at the botton click review+create then creat the VM
</p>
<br />

![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/e8307b1e-f8ad-4dee-ba75-82d7536a1ee4)
![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/6d403331-01df-470f-80e6-1209a6b0010c)

<p>
Click on the VM in the resource group then copy the public ip address
</p>
<p>

</p>
<br />

<p>

  ![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/01bc12a6-32a4-4645-a495-bd5132e928d4)
![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/3579eeac-9b12-475e-b92e-ca4dd1a103e5) ![image](https://github.com/GarrettBlackwell/osticket-prereqs/assets/146894477/47d55c70-20b1-4f63-b94a-d2d6f0ae1068)
Open remote desktop and paste the IP address and press connect then enter your username and password
</p>
<p>
Open remote desktop and paste the IP address and press connect then enter your username and password
</p>
<br />

<p>

</p>
<p>
Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console
</p>
<br />

<p>

</p>
<p>
From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi)

Create the directory C:\PHP

From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP

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
