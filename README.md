

<h1>Virtual Private Networks</h1>
This tutorial outlines the configuration of a virtual private network.<br />


<h2>Video Demonstration</h2>

- ### [How To Configure a VPN](https://drive.google.com/file/d/1FFQRwzX2O0asLmqIX9zOtqh9rdsqmDYS/view)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- None

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, go to protonvpn.com, create an account, and sign up for a free VPN.
(Don't download anything yet)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, browse to whatismyipaddress.com. 
Open a new text file and take note of your FIRST current location and ip address. (This is the local PC)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will create a Virtual machine in Azure and connect to it, using Remote desktop protocol.
Opt for Windows 10, running 2 vcpus, with 16gb memory, and assign its "region" to a foreign country.
Now hit review and create.
When the VM is ready, launch Remote Desktop Protocol, and connect to your VM using its public IP address.
Once there, browse to "whatismyipaddress.com"
Take note of your SECOND location and ip address, in your text file. (VM without VPN)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, browse to whatismyipaddress.com. 
Open a new text file and take note of your FIRST current location and ip address. (This is the local PC)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, browse to whatismyipaddress.com. 
Open a new text file and take note of your FIRST current location and ip address. (This is the local PC)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, browse to whatismyipaddress.com. 
Open a new text file and take note of your FIRST current location and ip address. (This is the local PC)
</p>
<br />

