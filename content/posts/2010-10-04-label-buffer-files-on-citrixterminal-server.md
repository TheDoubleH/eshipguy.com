---
title: Label Buffer Files on Citrix/Terminal Server
author: Henrik Helgesen
type: post
date: 2010-10-04T20:54:27+00:00
url: /label-buffer-files-on-citrixterminal-server/
featured_image: /wp-content/uploads/2010/10/SNAGHTMLbf1fb3_thumb.png
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
[<img decoding="async" loading="lazy" style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border-width: 0px;" title="SNAGHTMLbf1fb3" alt="SNAGHTMLbf1fb3" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/10/SNAGHTMLbf1fb3_thumb.png?resize=244%2C196&#038;ssl=1" width="244" height="196" align="left" border="0" data-recalc-dims="1" />][1]When using eShip on a Citrix or Terminal Server, I have seen an issue, where you end up printing a different label, than you expected. This can happen, because more than one session of Navision runs on the same ‘box’, using the same directory.

There are different ways of handling this; one being creating multiple packing stations and Carrier Packing Stations (one for each PC), but if the only reason for doing this is to separate the buffer file, there is a better way!

<!--more-->

[<img decoding="async" loading="lazy" style="background-image: none; margin: 2px 0px 5px 10px; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border-width: 0px;" title="SNAGHTMLc5480b" alt="SNAGHTMLc5480b" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/10/SNAGHTMLc5480b_thumb.png?resize=244%2C178&#038;ssl=1" width="244" height="178" align="right" border="0" data-recalc-dims="1" />][2]When eShip generate the label buffer, it actually processes some code on Table 14000709 – Packing Station, that will substitute %1 and %2 with USERID and SESSIONID.

I recommend, that you use %1 (USERID), if you have different UserID’s for each station or user. The reason being, that if you use the SESSIONID the odds of you having to accept the file name daily is fairly high – USERID you should only have to accept it once.

You will need to change the buffer file name on both Packing Station and Carrier packing Station to get the full effect. The file name on the Packing Station pertains to UCC128 labels etc, where the UPS, FedEx, USPostal labels are defined on the Carrier Packing Station.

 [1]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/10/SNAGHTMLbf1fb3.png?ssl=1
 [2]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/10/SNAGHTMLc5480b.png?ssl=1