---
title: "Local Broadcast and Directed Broadcasts - Description and Demonstration"
image: "https:\/\/i.ytimg.com\/vi\/ZNXDbzaAM-I\/hqdefault.jpg"
vid_id: "ZNXDbzaAM-I"
categories: "Science-Technology"
tags: ["Local","Broadcast","Directed"]
date: "2021-10-20T00:16:42+03:00"
vid_date: "2020-09-02T17:38:52Z"
duration: "PT7M42S"
viewcount: "4403"
likeCount: "208"
dislikeCount: "0"
channel: "Practical Networking"
---
{% raw %}In this video we'll pick apart Broadcasts -- specifically the difference between a Local Broadcast and a Directed Broadcast (which is sometimes referred to as a Targeted Broadcast).<br /><br />This is the &quot;short version&quot; of this video. In the longer video, we'll run through the same demonstration, but I'll also show you the packet captures of what is so you can see *exactly* what is happening on the wire.<br /><br />0:00 - Start<br />0:11 - Topology<br />0:21 - Official Definition of a Broadcast message<br />0:49 - Layer 2 Broadcast vs Layer 3 Broadcast<br />1:24 - Local Broadcast<br />2:16 - Demonstration: ping 255.255.255.255<br />3:14 - Directed Broadcast - speaking to all hosts in the LOCAL subnet<br />3:54 - Demonstration: pinging the Broadcast IP of a Local Network<br />4:32 - Directed Broadcast - speaking to all hosts in a FOREIGN subnet<br />5:23 - Demonstration: pinging the Broadcast IP of a Foreign Network<br />6:20 - Summary<br />6:44 - Directed Broadcasts are a Security Risk<br /><br />The Local Broadcast IP is always 255.255.255.255. Regardless of what your Subnet IP addresses are, you can always use the specially reserved IP address of 255.255.255.255 to send a packet to everyone on the local IP subnet.<br /><br />The Directed Broadcast (also called Targeted Broadcast) is the last IP address in each Subnet (also known simply as &quot;the broadcast IP&quot;).  You can use the Directed Broadcast to speak to every host in your own local Subnet.... OR, you can send a packet to a Broadcast IP in another subnet to speak to every host in a Foreign network.<br /><br />To calculate your Broadcast IP, you'll have to do a little Subnetting. This video series will teach you everything you need to know about Subnetting:<br /><br /><a rel="nofollow" target="blank" href="https://www.youtube.com/playlist?list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE">https://www.youtube.com/playlist?list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE</a><br /><br />If you are studying for your CCNA, you'll want to check out the compendium of free CCNA study resources from Practical Networking .net:<br /><br /><a rel="nofollow" target="blank" href="https://www.practicalnetworking.net/index/ccna/">https://www.practicalnetworking.net/index/ccna/</a>{% endraw %}
