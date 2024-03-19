<h1> Windows Server (Installing Active Directory) </h1>


<h2>Description</h2>
In this Lab, I installed Active Directory on the first domain controller in an Active Directory forest. I then join the remaining computers and servers to the domain. Lastly, I added the 2nd server (Server-02) virtual machine as an additional domain controller in the domain. 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Hyper-V Manager</b>

<h2>Program Screenshots:</h2>

<p align="center">
Install The Active Directory Domain Services role : <br/>
<img src="https://i.imgur.com/voyQSsh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created The Forest Root Domain:  <br/>
<img src="https://i.imgur.com/R3vPXqK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verified The Installation of Active Directory: <br/>
<img src="https://i.imgur.com/EuaoiiJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created an unprivileged user account: <br/>
<img src="https://i.imgur.com/rMGW3qs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a user account named KMWAdmin: <br/>
<img src="https://i.imgur.com/Svefo0o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Added KMWAdmin to the Domain Admins and Enterprise Admins groups: <br/>
<img src="https://i.imgur.com/uslGXqj.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Made Server-02 apart of the domain: <br/>
<img src="https://i.imgur.com/7hYrUb7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PCS and 2nd Sever added to Domain: <br/>
<img src="https://i.imgur.com/04PJp0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Active Directory as an additional domain controller:  <br/>
<img src="https://i.imgur.com/pPdKaoQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
