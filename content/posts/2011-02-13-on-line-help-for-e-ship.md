---
title: On-Line Help for E-Ship
description: Want on-line help for E-Ship? Follow this step-by-step guide how You can get the help to Your users.
author: Henrik Helgesen
type: post
date: 2011-02-14T02:04:10+00:00
url: /on-line-help-for-e-ship/
image: images/help.jpg
dsq_thread_id:
  - 229768273
categories:
  - Dynamics NAV
  - E-Ship
tags:
  - Online Help

---
When you implement the E-Ship/EDI functionality in your database, you get a lot of new fields added also. A lot of those fields are added in places users already interact and as such questions often come up, as to the functionality of certain fields.

The good thing is, that Lanham & Associates over the years have developed some help text, which is a good start – and it is getting better and better.

<!--more-->

In order to get the latest On-line help, open the Shipping Setup (Shipping & Receiving –> Shipping –> Setup –> Shipping Setup.

![Shipping Station](/images/110213Shipping-Station.png)

When selecting Functions –> Online Help –> Utility Setup you may see an error:

![Error Message](/images/110213UtilError1.png)

This Error tells you that you do not have the tool installed. Unfortunately Lanham & Associates does not provide the download directly for end-users (I asked to host a copy here), so you will need to get your Partner involved. Partners should have done this at the initial implementation, but some of them tend to forget, maybe not even knowing it exist – I’ve known to forget it myself – just Say’in.

Anyways – your partner can download the LAUtil package from Lanham (I am using LAUtil1.01)

If a window open, you have the tool installed! Make sure the directory specified exists, and then go download the help files:

![110213UtilSetup](/images/110213UtilSetup.png)

Downloading will take a while, so now would be a good time to get get another coke [pfsssst…  Arhh]

PS – you have to say yes to the error message, if you get this one:

![110213DOSError](/images/110213DOSError.png)

After the files have been downloaded you will be asked if you want to import the help file. Say YES to that – That will store the help-files inside the Navision database and will help when exporting the objects.

After the help-files have been imported, it will ask you if you want to export – Say YES to that also. This will scan you hard-drive for every directory where standard NAV help files are located, and place a copy of the E-Ship/EDI help files.

So now, in stead of getting this when asking for help

![SNAGHTML128e9e81.png](/images/SNAGHTML128e9e81.png)

you will now get this:

![SNAGHTML128fd884](/images/SNAGHTML128fd884.png)

Finally &#8211; you need someone to go to each workstation and to to the Shipping Setup, and do the Export only!
