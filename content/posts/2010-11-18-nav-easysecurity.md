---
title: NAV EasySecurity
author: Henrik Helgesen
type: post
date: 2010-11-18T20:09:50+00:00
url: /nav-easysecurity/
image: images/easysecurity.png
dsq_thread_id:
  - 175224413
categories:
  - Dynamics NAV
tags:
  - NAV EasySecurity
  - Off-Topic

---
I just want to let you know, that I am still breathing! I have for the past couple of weeks been doing an implementation of [EasySecurity](http://mergetool.com/products/easysecurity.html), that has taken up all my time.

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
