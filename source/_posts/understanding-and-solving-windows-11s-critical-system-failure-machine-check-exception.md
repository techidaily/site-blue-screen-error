---
title: Understanding and Solving Windows 11'S Critical System Failure (Machine Check Exception)
date: 2024-08-15T01:22:48.834Z
updated: 2024-08-16T01:22:48.834Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Understanding and Solving Windows 11'S Critical System Failure (Machine Check Exception)
excerpt: This Article Describes Understanding and Solving Windows 11'S Critical System Failure (Machine Check Exception)
thumbnail: https://thmb.techidaily.com/3ad0b37de8405ddff0a5f39b812ec8d893ee35987fd8e7537df266174c877eec.jpg
---

## Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-36.jpg)

 Recently, you upgrade your Windows operating system to Windows 10\. Windows 10 is great but it also brings you some troubles. The Blue Screen of Death(BSOD) is one of the Windows 10 nightmares. **UNEXPECTED\_STORE\_EXCEPTION**  is one of the common BSOD errors. If you’re facing this blue screen error, rest assured. We’ve found the answer for you. Please read on the page.[](https://tools.techidaily.com/drivereasy/download/)

 Note: Due to the error, your computer probably cannot boot into Windows 10 as normal, then boot it into Safe Mode before trying the following solutions. [](https://tools.techidaily.com/drivereasy/download/)

1. **[Performing clean boot](https://tools.techidaily.com/drivereasy/download/)**
2. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your drivers](https://tools.techidaily.com/drivereasy/download/)**
4. [**Check for Windows Updates**](https://tools.techidaily.com/drivereasy/download/)

## Solution 1\. Performing clean boot

 1) On your keyboard, press the **Windows logo key**  and **R**  (at the same time) to invoke the Run command.

 2) Type**msconfig** in the box and press **Enter** to open the System Configuration window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-40.jpg)

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

 3) Click**Yes** when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/11-10.jpg)

 4) Reboot your Windows 10 into normal mode. See if the Blue screen has gone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Solution 3\. Update your drivers**

 The blue screen errors are always caused by the incompatible, outdated or corrupted drivers. Therefore, we highly recommend updating device drivers on your Windows to ensure your system run properly whenever the blue screen shows on your computer.

 There are two ways you can update your device drivers: manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your variant of Windows versions. In this way, y ou will need to check the update for your devices one by one.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find all the available correct drivers, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a2e56ed6c56f.jpg)

 3) Click the **Update**  button next to any flagged driver to automatically download and install the correct version of that driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money-back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a2e574b9b9f3.jpg)

 4) After updating drivers, please restart your computer to make the new drivers take effect. Check to see if the blue screen is gone.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Solution 4\. Check for Windows Updates

 Either hardware or software issues can lead to blue screen error. And Windows updates can  address security flaws and bugs related to both hardware and software. Thus make sure you’ve install all the new Windows 10 updates to keep your Windows 10 healthy, stable and away from blue screen error.

1) Type **Windows Update** in the search box. Click **Check for updates** on the top result.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/13-2.jpg)

2) Click **Check for updates** on the right pane of pop-up window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/12-3.jpg)

 Go on to follow the on-screen instructions to install the updates.

That’s all there is to it.

Your any comment or feedback is welcomed coming below, thanks.

* [BSOD](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-views-and-subscribers-a-list-of-proven-youtube-techniques-for-2024/"><u>[New] Elevate Views and Subscribers  A List of Proven YouTube Techniques for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-funimate-masterclass-quick-video-access/"><u>[New] Funimate Masterclass  Quick Video Access</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-essentials-of-cinematic-dialogue-design/"><u>[New] In 2024, Essentials of Cinematic Dialogue Design</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-spotlight-series-the-best-gamers-on-tiktok/"><u>[New] Spotlight Series  The Best Gamers on TikTok</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-create-effective-fb-video-ads-with-free-kit/"><u>[Updated] 2024 Approved  Create Effective FB Video Ads with FREE Kit</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-crafting-perfect-instagram-story-cover-pages/"><u>[Updated] In 2024, Crafting Perfect Instagram Story Cover Pages</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-streamlining-lecture-recordings-on-imac/"><u>[Updated] In 2024, Streamlining Lecture Recordings on iMac</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-techniques-to-enhance-your-slow-motion-photos-for-instagram-audiences/"><u>[Updated] In 2024, Techniques to Enhance Your Slow Motion Photos for Instagram Audiences</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-top-10-igtv-channels-you-should-start-following/"><u>2024 Approved  Top 10 IGTV Channels You Should Start Following</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/adding-captions-and-text-a-guide-for-photo-titles-in-microsoft-photos-for-2024/"><u>Adding Captions and Text  A Guide for Photo Titles in Microsoft Photos for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-free-apple-iphone-12-mini-imei-checker-by-drfone-ios/"><u>Best Free Apple iPhone 12 mini IMEI Checker</u></a></li>
<li><a href="https://vp-tips.techidaily.com/budget-blueprint-for-creating-musical-cinematic-pieces/"><u>Budget Blueprint for Creating Musical Cinematic Pieces</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/compliant-driver-management-after-resolving-iomgr-non-conformity/"><u>Compliant Driver Management After Resolving Iomgr Non-Conformity</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/comprehensive-guide-to-curing-bsod-handling-the-0x00000050-error-in-windows-7/"><u>Comprehensive Guide to Curing BSOD: Handling the 0X00000050 Error in Windows 7</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/comprehensive-guide-to-diagnose-and-resolve-fat-drive-issues-on-your-windows-10-pc/"><u>Comprehensive Guide to Diagnose and Resolve FAT Drive Issues on Your Windows 10 PC</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/easy-steps-to-access-windows-10-advanced-startup-settings/"><u>Easy Steps to Access Windows 10 Advanced Startup Settings</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-solutions-for-kernal-security-check-errors-in-windows-10-a-step-by-step-fix/"><u>Effective Solutions for Kernal Security Check Errors in Windows 10 - A Step-by-Step Fix</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/end-the-nightmare-comprehensive-troubleshooting-of-rtkvhd64sys-blue-screen-errors/"><u>End the Nightmare: Comprehensive Troubleshooting of RTKVHD64.sys Blue Screen Errors</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-code-0x00000019-explained-effective-remedies-for-bad-pool-headers-on-windows-systems-resolved/"><u>Error Code 0X00000019 Explained: Effective Remedies for Bad Pool Headers on Windows Systems [RESOLVED]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-solutions-to-overcome-netwtw10sys-bsod-error-on-your-computer/"><u>Expert Solutions to Overcome 'Netwtw10.sys' BSoD Error on Your Computer</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-the-clock-watchdog-timeout-bluescreen-issue-on-windows-10/"><u>Fixing the Clock Watchdog Timeout Bluescreen Issue on Windows 10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-dfu-mode-on-iphone-14-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-repair-a-crashed-pc-with-bugcodeusbdriver-error-on-windows-10-system/"><u>How to Repair a Crashed PC with 'BUGCODE_USB_DRIVER' Error on Windows 10 System</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-inaccessible-boot-device-blue-screen-error-on-windows-11-with-illustrative-images/"><u>How to Resolve 'Inaccessible Boot Device' Blue Screen Error on Windows 11 with Illustrative Images</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-essential-audio-enhancement-apps-for-youtubers-videos/"><u>In 2024, Essential Audio Enhancement Apps for YouTubers' Videos</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-zero-30-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Zero 30 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-strategizing-against-the-phantom-follower-phenomenon/"><u>In 2024, Strategizing Against the Phantom Follower Phenomenon</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-audiophiles-companion-to-top-tier-audio-equipment/"><u>In 2024, The Audiophile's Companion to Top-Tier Audio Equipment</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-top-10-screenrecord-tips-and-tricks-on-a-laptop/"><u>In 2024, Top 10 ScreenRecord Tips and Tricks on a Laptop</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/mastering-windows-tdr-troubleshooting-fixes-and-explanations-for-atikmpagsys-failures/"><u>Mastering Windows # TDR Troubleshooting: Fixes and Explanations for Atikmpag.sys Failures</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/no-more-freezes-a-step-by-step-guide-to-stabilize-your-windows-7-system/"><u>No More Freezes: A Step-by-Step Guide to Stabilize Your Windows 7 System</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/overcoming-driver-verifier-errors-bsod-fixes-for-windows-10-users-complete-guide/"><u>Overcoming Driver Verifier Errors: BSOD Fixes for Windows 10 Users [COMPLETE GUIDE]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/overcoming-windows-blue-screen-of-death-bsod-with-win32ksys-errors/"><u>Overcoming Windows Blue Screen of Death (BSOD) with Win32K.sys Errors</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/quick-remedies-for-exception-in-thread-issues/"><u>Quick Remedies for 'Exception in Thread' Issues</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-blue-screen-of-death-read-only-memory-write-error-fixes/"><u>Resolving the Blue Screen of Death: Read-Only Memory Write Error Fixes</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solving-the-0x0000000a-bsod-dilemma-a-step-by-step-guide/"><u>Solving the 0X0000000A BSOD Dilemma: A Step-by-Step Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/trouble-with-rtkvhd64sys-heres-how-you-can-resolve-the-bsod-problem/"><u>Trouble with rtkvhd64.sys? Here's How You Can Resolve the BSOD Problem</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-successful-how-to-fix-blue-screen-caused-by-kernel-memory-issues-within-pages/"><u>Troubleshooting Successful: How to Fix 'Blue Screen' Caused by Kernel Memory Issues Within Pages</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-windows-crashes-resolving-stop-code-0x0000009f/"><u>Troubleshooting Windows Crashes: Resolving Stop Code 0X0000009F</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-7-troubleshooting-fixing-the-stop-code-0x0000007e-bsod/"><u>Windows 7 Troubleshooting: Fixing the STOP Code 0X0000007E BSOD</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/winning-against-windows-10-crashes-solve-your-critical-process-died-bsod-errors-permanently/"><u>Winning Against Windows 10 Crashes: Solve Your 'Critical Process Died' BSOD Errors Permanently!</u></a></li>
</ul></div>
