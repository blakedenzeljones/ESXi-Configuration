<h1>ESXi Configuration</h1>



<h2>Description</h2>
This lab's objective is to configure an ESXi host and prepare it to be uploaded to vCenter.
<br />


<h2>Languages and Utilities Used</h2>

- <b>None</b> 

<h2>Environments Used </h2>

- <b>ESXi</b>(Version 8.0)

<h2>Program walk-through:</h2>

<p align="center">
Loading the ISO: <br/>
 
*Caption: Installing ISO, setting password, removing ISO, and restarting host*
<img src="https://i.imgur.com/dDj4OuL.png" height="80%" width="80%" alt="Teams Cleanup"/>
<br />
<br />

<p align="center">
Setting Static IP:  <br/>

*Caption: Network IP Configuration*
<img src="https://i.imgur.com/7ixOnhs.png" height="80%" width="80%" alt="Teams Cleanup"/>
<br />
<br />

<p align="center">
DNS Configuration: <br/>

 *Caption: Configuring the DNS settings *
 
<img src="https://i.imgur.com/imEco0L.png" height="80%" width="80%" alt="Teams Cleanup"/>
<br />
<br />

<p align="center">
Troubleshooting Configuration:  <br/>

 *Caption: Enabled SSH and ESXi shell for troubleshooting*
<img src="https://i.imgur.com/hMMGZa6.png" height="80%" width="80%" alt="Teams Cleanup"/>
<br />
<br />

<p align="center">
Next Steps:  <br/>

I am currently using the evaluation version. The next steps would be to log in to the host directly and assign a license (or apply it through vCenter), then create a new Datacenter object in vCenter and add the host. After that, the post-configuration tasks include adding VMkernel ports for vMotion, vSAN, and other services, configuring networking and datastores, and setting up NTP and Lifecycle Manager.
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
