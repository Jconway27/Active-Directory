<h1>Active Directory</h1>

<h2>Description</h2>
Active directory created through VirtualBox using Windows 10 and Windows Server 2019. Usernames created with PowerShell script.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019</b>

<h2>Homelab walk-through:</h2>

<br />
<br />
<p align="center">
1. Domain controller virtual machine created:  <br/>
<img src="https://imgur.com/XlBqDrj.png" height="80%" width="80%"/>
<br />
<br />
2. Logged into domain controller virtual machine: <br/>
<img src="https://imgur.com/CklQ7Mb.png" height="80%" width="80%"/>
<br />
<br />
3. Set up IP addressing. Network Interface Controllers distinguished. Internet from home network and internal adaptor:  <br/>
<img src="https://imgur.com/8cdEYfC.png" height="80%" width="80%"/>
<br />
<br />
4. IP address given to internal network:  <br/>
<img src="https://imgur.com/QRLNtJx.png" height="80%" width="80%"/>
<br />
<br />
5. PC renamed DC (Domain Controller):  <br/>
<img src="https://imgur.com/NBVWzo6.png" height="80%" width="80%"/>
<br />
<br />
6. Active Directory Domain Services installed:  <br/>
<img src="https://imgur.com/sK4yZzz.png" height="80%" width="80%"/>
<br />
<br />
7. Domain created (mydomain.com):  <br/>
<img src="https://imgur.com/9V1y1cH.png" height="80%" width="80%"/>
<br />
<br />
8. Dedicated domain administrator created (James Conway):  <br/>
<img src="https://imgur.com/dX86Zqh.png" height="80%" width="80%"/>
<br />
<br />
9. Routing and remote access configured:  <br/>
<img src="https://imgur.com/N2QhmYF.png" height="80%" width="80%"/>
<br />
<br />
10. DHCP server set up on domain controller:  <br/>
<img src="https://imgur.com/vWRouAe.png" height="80%" width="80%"/>
<br />
<br />
11. PowerShell script:  <br/>
<img src="https://imgur.com/FZQjvxc.png" height="80%" width="80%"/>
<br />
<br />
12. User names created from PowerShell script for client computers:  <br/>
<img src="https://imgur.com/9YKJo0U.png" height="80%" width="80%"/>
<br />
<br />
13. Client names now under mydomain:  <br/>
<img src="https://imgur.com/Z6HESHK.png" height="80%" width="80%"/>
<br />
<br />
14. User K. Marden logged in:  <br/>
<img src="https://imgur.com/WK9r2SS.png" height="80%" width="80%"/>
<br />
<br />
15. K. Marden's command line whoami:  <br/>
<img src="https://imgur.com/98Np7G8.png" height="80%" width="80%"/>
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
