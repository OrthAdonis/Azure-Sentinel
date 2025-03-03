<h1> LIVE CYBER ATTACKS</h1>


The project covers:
Configuring log analytics workspace,
forwarding logs and integrating with Sentinel,
querying failed login attempts and visualizing attack sources,
building an attack map to track real-time hacker activity


<h2>Environbents Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

I set up a virtual machine using Microsoft Azure. From there, I exposed the machine to live traffic. Attackers from all over the world began attempts to hack the virtual machine. I logged this data live and used a map to ping where the attacks were coming from around the world. Each screenshot shows a different step in the process, documenting the lab across each one.
<p align="center">
Failed RDP Login Attempts Logged in Event Viewer                                                       
  : <br/>
<img src="https://imgur.com/r2EDRfT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PowerShell Script Analyzing Failed RDP Attempts with Geo-Location Data: <br/>
<img src="https://imgur.com/JqkULko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured Windows Defender Firewall for Network Security: <br/>
<img src="https://imgur.com/2q7cU7m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Analyzed Security Event Logs for Intrusion Detection (Event ID 4625): <br/>
<img src="https://imgur.com/93uGrJ1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
Deployed & Monitored Virtual Machine as a Honeypot in Azure: <br/>
<img src="https://imgur.com/V94ZYYc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
Configured a High-Risk Honeypot Security Rule for SIEM: <br/>
<img src="https://imgur.com/Mg0YS3R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
Visualized Live Cyber Attack Data Using SIEM: <br/>
<img src="https://imgur.com/rb3XITQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 



