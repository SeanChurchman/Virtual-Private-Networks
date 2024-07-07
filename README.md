

<h1>Virtual Private Networks</h1>
This tutorial outlines the configuration of a virtual private network.<br />


<h2>Video Demonstration</h2>

- ### [How To Configure a VPN](https://drive.google.com/file/d/1FFQRwzX2O0asLmqIX9zOtqh9rdsqmDYS/view)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- None

<h2>Installation Steps</h2>

![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/4ee2d170-b2f9-4f29-beeb-47fe141dc3f7) 

<p>
First, go to protonvpn.com, create an account, and sign up for a free VPN.
(Don't download anything yet)
</p>
<br />

![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/d7ec29de-664d-4f97-9d08-e5ef472484d1)

<p>
Next, browse to whatismyipaddress.com. 
Open a new text file and note your FIRST current location and ip address. (This is the local PC)
</p>
<br />

![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/12ad6050-7d9d-4a23-85c3-81eb5b2364eb)

<p>
Now we will create a Virtual machine in Azure and connect to it, using Remote desktop protocol.
Opt for Windows 10, running 2 vcpus, with 16gb memory, and assign its "region" to a foreign country.
Now hit review and create.


![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/de15cd37-407e-4eab-9f06-4eaf826bcf42)

  
When the VM is ready, launch Remote Desktop Protocol, and connect to your VM using its public IP address.


![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/c633e822-41e1-464e-b79b-e7a4fcaa077e)


Once there, browse to "whatismyipaddress.com"
Take note of your SECOND location and ip address, in your text file. (VM without VPN)
  
</p>
<br />

![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/ec115677-4b9d-4030-b98a-4b29c884db0d)

<p>
Now, visit https://account.protonvpn.com/downloads
Sign in, and download the Windows VPN client


![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/187956a6-5e2d-4be2-9211-081c3879eece)


Install and launch the app.
</p>
<br />

![image](https://github.com/SeanChurchman/Virtual-Private-Networks/assets/165851799/dfd26673-fbc0-4fc2-b71b-2f283ccd1a3d)


<p>
Select "quick connect."
(the rdp connection might get interrupted for a second, but it should reconnect automatically).
We are now connected to a VPN server!

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
So next, browse back to "whatismyipaddress.com" and refresh the page
Observe that our ip address has changed again.
Take note of your THIRD location and ip address, in the text file.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations. We're done! 
You can browse to any of your favorite websites and view the new localized results.
And lastly, remember to clean up your azure environment, when you're done with the lab.
