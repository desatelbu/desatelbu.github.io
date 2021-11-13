---
title: "HackTheBox - Conceal"
image: "https:\/\/i.ytimg.com\/vi\/1ae64CdwLHE\/hqdefault.jpg"
vid_id: "1ae64CdwLHE"
categories: "Education"
tags: ["HackTheBox","Conceal"]
date: "2021-11-13T03:38:33+03:00"
vid_date: "2019-05-18T15:07:10Z"
duration: "PT1H27M36S"
viewcount: "33062"
likeCount: "465"
dislikeCount: "6"
channel: "IppSec"
---
{% raw %}01:15 - Begin of recon<br />02:54 - Checking SNMP with snmpwalk<br />03:29 - Discovering a Hashed PSK (MD5) in SNMPWalk, searching the internet for a decrypted value<br />04:18 - Getting more SNMP Information with snmp-check<br />07:35 - Going over UDP Ports discovered by snmp-check<br />10:55 - Running ike-scan<br />11:55 - Examining ike-scan results to build a IPSEC Config<br />13:50 - Installing Strongswan (IPSEC/VPN Program)<br />14:19 - Adding the PSK Found earlier to /etc/ipsec.secrets<br />15:30 - Begin configuring /etc/ipsec.conf<br />20:08 - Starting and debugging ipsec<br />21:55 - Explaining why we add TCP to strongswan config<br />24:00 - Starting IPSEC, then using NMAP through IPSEC.<br />(You may want to run WireShark here and see all traffic is encrypted thanks to ipsec)<br />25:55 - Enumerating SMB Quickly (SMBMap/cme)<br />26:50 - Enumerating FTP, discovering we can upload files<br />27:20 - Checking HTTP, hunting for our uploaded file.  Then uploading files that may lead to code execution<br />29:44 - Grabbing an ASP Webshell from Github/tennc/webshell<br />32:08 - Webshell has been uploaded<br />32:30 - Explaining a weird MTU Issue you *may* run into due to the nested VPN's<br />35:40 - Back to playing with the web shell, getting a reverse shell with Nishang<br />38:03 - Explaining RLWRAP<br />38:40 - whoami /all shows SEImpersonation, so we run JuicyPotato to privesc<br />44:35 - JuicyPotato fails with the default CLSID, changing it up to get it working.<br />46:30 - Doing the box again with Windows<br />47:15 - Setting up the IPSEC Connection through Windows Firewall<br />50:00 - Installing a DotNet C2 (The Covenant)<br />54:20 - Covenant/Elite open, starting a Listener then a Powershell Launcher<br />01:00:10 - Grunt activated. Running Seatbelt, then compiling Watson and reflectively running it<br />01:05:00 - Grabbing the Sandbox Escaper ALPC Privesc<br />01:08:03 - Being lazy and compiling a CPP Rev Shell in Linux because it wasn't installed on Windows<br />(bunch of flailing, then reverting the machine)<br />01:25:35 - Box is reverted, trying the ALPC Exploit again{% endraw %}
