---
title: NAV EasySecurity
author: Henrik Helgesen
type: post
date: 2010-11-18T20:09:50+00:00
url: /nav-easysecurity/
featured_image: /wp-content/uploads/2010/11/image_thumb.png
dsq_thread_id:
  - 175224413
categories:
  - Dynamics NAV
tags:
  - NAV EasySecurity
  - Off-Topic

---
[<img decoding="async" loading="lazy" style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; float: left; padding-top: 0px; border: 0px;" title="image" alt="image" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/11/image_thumb.png?resize=244%2C181&#038;ssl=1" width="244" height="181" align="left" border="0" data-recalc-dims="1" />][1]Hi Folks &#8211;

I just want to let you know, that I am still breathing! I have for the past couple of weeks been doing an implementation of <a href="http://mergetool.com/products/easysecurity.html" target="_blank">NAV EasySecurity</a>, that has taken up all my time.

This customer is a public company and as such needs to adhere to SOX regulations.

&nbsp;

One thing I have learned about SOX; The US Government must be jealous – so much bureaucracy to do anything!

<!--more-->

Another thing, I have learned; If you need to go to the level we have done, you need to have your test plans ready BEFORE even starting the process. Because as cool as the Recorder is, it only record what the user do – it doesn’t care about what the test plan tells you to do.

I would also recommend, that you create micro recordings – this way you can create rolls (which you can combine into role groups) that are task specific!

For example; here, the people posting the Transfer Order Shipment does not Post the Receipt – So having a role for – _Post Transfer Order Shipment_ and _Post Transfer Order Receipt_ separately helps. Other recordings we have generated is _Print Sales Invoice_ (This customer uses AvaTax, so the amount of objects used to just print a Sales Invoice is Ridiculous.

So even if you will end up with a lot of recordings and roles, you have the benefit of being able to build a list from which you can select tasks.

I would love to hear if any of you have experience with using EasySecurity.

And – by the way – you should definitely have a phased approach  &#8212;  Do NOT implement Lanham History & Security and Easy Security at the same time. They do compliment each other – but do Easy Security first. That way you will find out what tables users have insert/modify/delete permissions and then lock them down with Lanham Security afterwards.

<!--Digiprove_Start-->

<span lang="en" style="vertical-align: middle; display: inline; padding: 3px; line-height: normal; border: 1px solid #bbbbbb; background-color: #ffffff;" title="certified 18 November 2010 20:09:51 UTC by Digiprove certificate P64953" xml:lang="en"><a style="border: 0px; float: none; display: inline; text-decoration: none; background-color: transparent;" href="http://www.digiprove.com/show_certificate.aspx?id=P64953" target="_blank" rel="copyright"><img decoding="async" loading="lazy" style="vertical-align: middle; display: inline; border: 0px; margin: 0px; float: none; background-color: transparent;" alt="" src="https://i0.wp.com/www.digiprove.com/images/dp_seal_trans_16x16.png?resize=12%2C12" width="12 px" height="12 px" border="0" data-recalc-dims="1" /><span style="font-family: Tahoma, MS Sans Serif; font-size: 9px; font-weight: normal; color: #636363; border: 0px; float: none; display: inline; text-decoration: none; letter-spacing: normal;" onmouseover="this.style.color='#A35353';" onmouseout="this.style.color='#636363';">  Copyright secured by Digiprove © 2010</span></a><!--CCAB77CB5FF299716DC839A906DDF089B11F173EF5A760AD6B55CF6B82632CA9--></span>

<!--Digiprove_End-->

 [1]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/11/image.png?ssl=1