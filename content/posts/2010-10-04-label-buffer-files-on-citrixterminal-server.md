---
title: Label Buffer Files on Citrix/Terminal Server
description: Citrix and E-Ship can cause a few challenges - Here is a few tips to fix those
author: Henrik Helgesen
type: post
date: 2010-10-04T20:54:27+00:00
url: /label-buffer-files-on-citrixterminal-server/
image: images/SNAGHTMLbf1fb3.png
dsq_thread_id:
  - 151184152
dsq_needs_sync:
  - 1
categories:
  - E-Ship
tags:
  - Citrix
  - FedEx
  - Label
  - Packing Station
  - Terminal Server
  - UPS

---
There are different ways of handling this; one being creating multiple packing stations and Carrier Packing Stations (one for each PC), but if the only reason for doing this is to separate the buffer file, there is a better way!

<!--more-->

![SNAGHTMLc5480b](/images/SNAGHTMLc5480b.png)

When eShip generate the label buffer, it actually processes some code on Table 14000709 – Packing Station, that will substitute %1 and %2 with USERID and SESSIONID.

I recommend, that you use %1 (USERID), if you have different UserID’s for each station or user. The reason being, that if you use the SESSIONID the odds of you having to accept the file name daily is fairly high – USERID you should only have to accept it once.

You will need to change the buffer file name on both Packing Station and Carrier packing Station to get the full effect. The file name on the Packing Station pertains to UCC128 labels etc, where the UPS, FedEx, USPostal labels are defined on the Carrier Packing Station.
