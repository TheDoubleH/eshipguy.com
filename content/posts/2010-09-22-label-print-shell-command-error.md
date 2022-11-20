---
title: Label Print Shell Command Error
author: Henrik Helgesen
type: post
date: 2010-09-23T06:59:01+00:00
url: /label-print-shell-command-error/
featured_image: /wp-content/uploads/2010/09/labelprintererror.png
dsq_thread_id:
  - 145755737
categories:
  - E-Ship
tags:
  - eShip
  - Label
  - Packing Station

---
[<img decoding="async" loading="lazy" style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0px;" title="labelprintererror" alt="labelprintererror" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/09/labelprintererror_thumb.png?resize=412%2C174&#038;ssl=1" width="412" height="174" border="0" data-recalc-dims="1" />][1]

If you ever receive the error message:

The file name “C:Windowssystem32cmd.exe /c type

\[c 1=&#8221;>&#8221; 2=&#8221;LPT1&#8243; language=&#8221;:eShipLabeluffer.txt&#8221;\]\[/c\]

” contains a character that may not be used.

Please check the file name. You can find additional information on file names in the documentation for your operation system.

you are more than likely on a newer operating system – i.e. Vista. In the good old days where all computers had at least one parallel port and two serial ports, you could execute shell commands very easy. Nowadays, however, you have to pass the program and parameters separately.

<!--more-->

Luckily Lanham & Associates have made that easy for us, and added a field on the Packing Station: ‘Shell Command Type’ – Once you set it to With Parameters you should be good to go.

[<img decoding="async" loading="lazy" style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0px;" title="SNAGHTML2543c31" alt="SNAGHTML2543c31" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/09/SNAGHTML2543c31_thumb.png?resize=429%2C312&#038;ssl=1" width="429" height="312" border="0" data-recalc-dims="1" />][2]

The first time you print a label, Windows will ask you, to confirm – you only have to confirm this the very first time you print a label.

 [1]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/09/labelprintererror.png?ssl=1
 [2]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2010/09/SNAGHTML2543c31.png?ssl=1