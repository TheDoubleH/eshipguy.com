---
title: Label Print Shell Command Error
description: The file name “C:\Windows\system32\cmd.exe /c type c:\temp\buffer.txt > LPT1" contains a character that may not be used
author: Henrik Helgesen
type: post
date: 2010-09-23T06:59:01+00:00
url: /label-print-shell-command-error/
image: images/labelprintererror.png
dsq_thread_id:
  - 145755737
categories:
  - E-Ship
tags:
  - eShip
  - Label
  - Packing Station

---
If you ever receive the error message:

>The file name “C:\Windows\system32\cmd.exe /c type c:\temp\buffer.txt > LPT1" contains a character that may not be used.
>Please check the file name. You can find additional information on file names in the documentation for your operation system.

you are more than likely on a newer operating system – i.e. Vista. In the good old days where all computers had at least one parallel port and two serial ports, you could execute shell commands very easy. Nowadays, however, you have to pass the program and parameters separately.

<!--more-->

Luckily Lanham & Associates have made that easy for us, and added a field on the Packing Station: ‘Shell Command Type’ – Once you set it to With Parameters you should be good to go.

![Screen Shot](/images/SNAGHTML2543c31.png)

The first time you print a label, Windows will ask you, to confirm – you only have to confirm this the very first time you print a label.
