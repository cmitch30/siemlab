<h1>Failed RDP to IP Geolocation Information</h1>

<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>: Extract RDP failed logon logs from Windows Event Viewer 
- <b>Virtual Machine</b>
- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Microsoft Azure</b>
- <b>Microsoft Sentienel</b>

<h2> Attacks coming in; Custom logs being output with geodata<h2/>
 
<p align="center">
<img src="https://i.imgur.com/n4rpIq1.png" height="85%" width="85%" alt="Image Analysis"/>
</p>

<h2>World map of incoming attacks after 24 hours<h2/>
 
<p align="center">
<img src="https://i.imgur.com/A7efQfw.png" height="85%" width="85%" alt="Attack Map"/>
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
