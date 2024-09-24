---
layout: single
title: Directions IP - IPV4/IPV6
excerpt: "What's an IP? well here we are going to explain and show what is an IP and the differences between IPV4 and IPV6."
date: 2024-06-20
classes: wide
header:
  teaser: /assets/images/ip.jpg
  teaser_home_page: true
  icon: #/assets/images/hackthebox.webp
categories:
  - IP
  - IPV4
  - IPV6
  - Info
  - linux
#tags:  
#  - osticket
#  - mysql
#  - mattermost
#  - hashcat
#  - rules
---

![](/assets/images/ip.jpg)

What's an IP? well here we are going to explain and show what is an IP and the differences between IPV4 and IPV6.

## How to see your IP and what it is

![](/assets/images/ifconfig2.png)

This is a private IP (Internet Protocol); what is an IP? Well, an IP it's like a numeric label that's identifies me in a logical and hierarchical in an net interface in a dispositive >

![](/assets/images/hostname.png)

If you do "hostname -I" it will show you your IP as well

The IPs are conformed by bits, where in a IPV4 there's 32 bits are divided into four octets.

![](/assets/images/bits.png)

And how many IP do we have in the world with IPV4? we do have 2^32 = 4,294,967,296 , and humans in the world are 7.951 billion, that means that we don't have IPs for everybody. This is the reason why NAT (Network Address Translation) and Public an Private IPs where created. 
Public IPs kinda identifies you to the internet. This type of IPs are unique, meaning there can't be two hosts with the same public IP.
On the other hand, private IPs can be repeated, because they identify devices inside your local network (behind your router).
For example, when we connect to Hack the Box, the VPN targets the Public IP, so we can access the HTB private network, inside which we can then target machines.



There's another implementation, IPV6, that has more possibilities: 2^128 = 3.4028237e+38.
