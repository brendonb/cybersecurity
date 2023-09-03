<h1>Cybersecurity Engineering Lab</h1>


<h2>Description</h2>
This lab project is a introduction to Cybersecurity and the implementation.
<br />


<h2> Applications and Utilities Used</h2>

- <b>Ubuntu Linux: Apache,Mysql,Php,Wordpress</b> 
- <b>Pfsense Firewall: DHCP,DNS,Proxy,DMZ,NAT</b>
- <b>SIEM: AlienVault OSSIM</b>
- <b>Vulnerability Scanning: Nessus</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Oracle Virtualbox</b>
- <b>Ubuntu Linux 22.04.03
<h2>Program walk-through:</h2>

<p align="center">
Configuration: <br/>
<img src="https://i.imgur.com/joIXVNv.jpg" height="80%" width="80%" alt="Lab topology"/></p>

- <b>The windows 10 endpoint is configured to receive a DHCP IP from the Firewall and uses Squid Proxy for internet access.<b>
- <b>The SIEM Monitors our network and also receives a DHCP IP from the firewall.</b>
- <b>The Ossim Server will scan for vulnerabilities to assess webserver and firewall capabilities</b>
- <b>Both Webserver and Vulnerability scanner are placed outside the network as part of the simulation</b>

<b><b>


<br />
<br />
<h2>Overview </h2>
Firewall  <br/>
<img src="https://i.imgur.com/qWrmGPN.jpg" height="80%" width="80%" alt="Dashoard setup"/>
<br />
<br />
AlienVault Ossim: <br/>
<img src="https://i.imgur.com/xvbAHeV.jpg" height="80%" width="80%" alt="SIEM login screen"/>
<br />
<br />
Nessus Pro:  <br/>
<img src="https://i.imgur.com/3xd8Irb.jpg" height="80%" width="80%" alt="Vulnerability login screen"/>
<br />
<br />
Wordpress site:  <br/>
<img src="https://i.imgur.com/SH6E9FS.jpg" height="80%" width="80%" alt="Webserver"/>
<br />
<br />
Endpoint:  <br/>
<img src="https://i.imgur.com/FdUZ42b.jpg" height="80%" width="80%" alt="Workstation"/>
<br />
<br />
<h2>Video Link to Project</h2>  <br/>
<b>Video in progress!!!</b>
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
