<h1>Phishing Analysis Home Lab</h1>
- [Analyzing SMTP Headers and Email Body ]

<h2>Description</h2>
In this lab we will cover Phishing Email, a social engineering technique constantly used by attackers to trick victims to click on links in other to steal their information and penetrate networks and computers.We will Install Thunderbird email client on a Window 10 virtual machine. We will view the raw source of an email,analyze the SMPT headers and Email Body to identify malicious links,IPs and urls using various tools.
<br />

<h2>Tool Used</h2>

- <b>Message Header Analyzer</b> 
- <b>IPinfo.io</b> 
- <b>urlscan.io</b> 
- <b>VirusTotal</b> 

<h2>Environments Used </h2>

- <b>Thunderbird Email Client</b>
- <b>Windows 10</b> (21H2)

<h2>Lab walk-through:</h2>

<p align="center">
Installing ThunderBirdEmail Client on Windows 10 Host: Click Next<br/>
<img src="https://imgur.com/6exFdvr.png" height="80%" width="80%"/>
<br />
<br />
Click Next to Allow Standard Setup<br/>
<img src="https://imgur.com/mQ7nPyw.png" height="80%" width="80%" />
<br />
<br />
Click install<br/>
<img src="https://imgur.com/YeUs5PT.png" height="80%" width="80%" />
<br />
<br />
Setup Installing<br/>
<img src="https://imgur.com/GiwJdMT.png" height="80%" width="80%" />
<br />
<br />
Installation Complete: Click finish<br/>
<img src="https://imgur.com/sYhcXWr.png" height="80%" width="80%" />
<br />
<br />
ThunderBird is launch. Create an email account, just as I have done and fowarded some suspicious email into the inbox.<br/>
<img src="https://imgur.com/eOWXhff.png" height="80%" width="80%" />
<br />
<br />
I open one email, click the dropdown on "More" and click view source:Email Header<br/>
<img src="https://imgur.com/VOpNwF9.png" height="80%" width="80%" />
<br />
<br />
Email Body<br/>
<img src="https://imgur.com/JcQz4Ms.png" height="80%" width="80%" />
<br />
<br />









Watch this Video Tutorial for further Email Header and Body Analysis using various Tools <br/>
[Video Demonstration](https://youtu.be/7eJexJVCqJo)
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
