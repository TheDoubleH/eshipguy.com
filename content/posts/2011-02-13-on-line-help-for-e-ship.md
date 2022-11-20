---
title: On-Line Help for E-Ship
author: Henrik Helgesen
type: post
date: 2011-02-14T02:04:10+00:00
url: /on-line-help-for-e-ship/
featured_image: /wp-content/uploads/2011/02/help.jpg
dsq_thread_id:
  - 229768273
categories:
  - Dynamics NAV
  - E-Ship
tags:
  - Online Help

---
[<img decoding="async" loading="lazy" class="alignleft" style="background-image: none; margin: 0px 15px 0px 0px; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0pt none;" title="help" alt="help" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/help_thumb.jpg?resize=244%2C185&#038;ssl=1" width="244" height="185" border="0" data-recalc-dims="1" />][1]When you implement the E-Ship/EDI functionality in your database, you get a lot of new fields added also. A lot of those fields are added in places users already interact and as such questions often come up, as to the functionality of certain fields.

The good thing is, that Lanham & Associates over the years have developed some help text, which is a good start – and it is getting better and better.

<!--more-->

In order to get the latest On-line help, open the Shipping Setup (Shipping & Receiving –> Shipping –> Setup –> Shipping Setup.

[<img decoding="async" loading="lazy" class="size-medium wp-image-127 alignnone" title="110213Shipping Station" alt="Shipping Station" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213Shipping-Station.png?resize=300%2C202&#038;ssl=1" width="300" height="202" srcset="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213Shipping-Station.png?resize=300%2C202&ssl=1 300w, https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213Shipping-Station.png?resize=768%2C518&ssl=1 768w, https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213Shipping-Station.png?w=810&ssl=1 810w" sizes="(max-width: 300px) 100vw, 300px" data-recalc-dims="1" />][2]

When selecting Functions –> Online Help –> Utility Setup you may see an error:

[<img decoding="async" loading="lazy" class="alignnone size-medium wp-image-129" title="110213UtilError" alt="Utility Error" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilError1.png?resize=300%2C106&#038;ssl=1" width="300" height="106" srcset="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilError1.png?resize=300%2C106&ssl=1 300w, https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilError1.png?w=482&ssl=1 482w" sizes="(max-width: 300px) 100vw, 300px" data-recalc-dims="1" />][3]

This Error tells you that you do not have the tool installed. Unfortunately Lanham & Associates does not provide the download directly for end-users (I asked to host a copy here), so you will need to get your Partner involved. Partners should have done this at the initial implementation, but some of them tend to forget, maybe not even knowing it exist – I’ve known to forget it myself – just Say’in.

Anyways – your partner can download the LAUtil package from Lanham (I am using LAUtil1.01)

If a window open, you have the tool installed! Make sure the directory specified exists, and then go download the help files:

[<img decoding="async" loading="lazy" class="alignnone size-medium wp-image-130" title="110213UtilSetup" alt="" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilSetup.png?resize=300%2C182&#038;ssl=1" width="300" height="182" srcset="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilSetup.png?resize=300%2C182&ssl=1 300w, https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilSetup.png?w=553&ssl=1 553w" sizes="(max-width: 300px) 100vw, 300px" data-recalc-dims="1" />][4]

Downloading will take a while, so now would be a good time to get get another coke [pfsssst…  Arhh]

PS – you have to say yes to the error message, if you get this one:

[<img decoding="async" loading="lazy" class="alignnone size-full wp-image-131" title="110213DOSError" alt="" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213DOSError.png?resize=471%2C289&#038;ssl=1" width="471" height="289" srcset="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213DOSError.png?w=471&ssl=1 471w, https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213DOSError.png?resize=300%2C184&ssl=1 300w" sizes="(max-width: 471px) 100vw, 471px" data-recalc-dims="1" />][5]

After the files have been downloaded you will be asked if you want to import the help file. Say YES to that – That will store the help-files inside the Navision database and will help when exporting the objects.

After the help-files have been imported, it will ask you if you want to export – Say YES to that also. This will scan you hard-drive for every directory where standard NAV help files are located, and place a copy of the E-Ship/EDI help files.

So now, in stead of getting this when asking for help

[<img decoding="async" loading="lazy" class="alignleft" style="background-image: none; margin: 0px 15px 0px 0px; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0pt none;" title="SNAGHTML128e9e81" alt="SNAGHTML128e9e81" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/SNAGHTML128e9e81_thumb.png?resize=244%2C204&#038;ssl=1" width="244" height="204" border="0" data-recalc-dims="1" />][6]

you will now get this:

[<img decoding="async" loading="lazy" class="alignleft" style="background-image: none; margin: 0px 15px 0px 0px; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0pt none;" title="SNAGHTML128fd884" alt="SNAGHTML128fd884" src="https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/SNAGHTML128fd884_thumb.png?resize=244%2C204&#038;ssl=1" width="244" height="204" border="0" data-recalc-dims="1" />][7]

Finally &#8211; you need someone to go to each workstation and to to the Shipping Setup, and do the Export only!

<!--Digiprove_Start-->

<span class="notranslate" lang="en" style="vertical-align: middle; display: inline; padding: 3px; line-height: normal; border: 1px solid #bbbbbb; background-color: #ffffff;" title="certified 14 February 2011 02:42:21 UTC by Digiprove certificate P101892" xml:lang="en"><a style="border: 0px; float: none; display: inline; text-decoration: none; background-color: transparent;" href="http://www.digiprove.com/show_certificate.aspx?id=P101892" target="_blank" rel="copyright"><img decoding="async" loading="lazy" style="vertical-align: middle; display: inline; border: 0px; margin: 0px; float: none; background-color: transparent;" alt="" src="https://i0.wp.com/eshipguy.com/wp-content/plugins/digiproveblog/dp_seal_trans_16x16.png?resize=12%2C12&#038;ssl=1" width="12 px" height="12 px" border="0" data-recalc-dims="1" /><span style="font-family: Tahoma, MS Sans Serif; font-size: 9px; font-weight: normal; color: #636363; border: 0px; float: none; display: inline; text-decoration: none; letter-spacing: normal;" onmouseover="this.style.color='#A35353';" onmouseout="this.style.color='#636363';">  Copyright secured by Digiprove © 2011</span></a><!--CEF53018035016B3D867E429CE229A42AFD1622E52D4997853F6FA8345C272A8--></span>

<!--Digiprove_End-->

 [1]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/help.jpg?ssl=1
 [2]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213Shipping-Station.png?ssl=1
 [3]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilError1.png?ssl=1
 [4]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213UtilSetup.png?ssl=1
 [5]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/110213DOSError.png?ssl=1
 [6]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/SNAGHTML128e9e81.png?ssl=1
 [7]: https://i0.wp.com/eshipguy.com/wp-content/uploads/2011/02/SNAGHTML128fd884.png?ssl=1