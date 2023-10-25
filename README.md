<h1>Windows Event Log: HoneyPot</h1>

<h2>Description</h2>
Project consists of setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. We will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure</b>
- <b>Virtual Machine</b>
- <b>ipgeolocation.io </b>: IP Address to Geolocation API

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Microsoft Azure</b>
- <b>Microsoft Sentienel</b>

<h2>Program walk-through:</h2>

<p align="center">
Attacks coming in; Custom logs being output with geodata:  <br/>
<img src="https://i.imgur.com/n4rpIq1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the VM Attacks:  <br/>
<img src="https://i.imgur.com/A7efQfw.png" height="80%" width="80%" alt="Attack Map"/>
 <br />
 <br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
