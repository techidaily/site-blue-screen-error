---
title: Ultimate Guide to Correcting the Fatal Exception Error on Windows
date: 2024-08-20T08:48:21.102Z
updated: 2024-08-21T08:48:21.102Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Ultimate Guide to Correcting the Fatal Exception Error on Windows
excerpt: This Article Describes Ultimate Guide to Correcting the Fatal Exception Error on Windows
thumbnail: https://thmb.techidaily.com/dbfa6019d8b3f211a2d4346989a8be20fa1fb2520363f53adb487ff9f78fd127.jpg
---

## Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-36.jpg)

 Recently, you upgrade your Windows operating system to Windows 10\. Windows 10 is great but it also brings you some troubles. The Blue Screen of Death(BSOD) is one of the Windows 10 nightmares. **UNEXPECTED\_STORE\_EXCEPTION**  is one of the common BSOD errors. If you’re facing this blue screen error, rest assured. We’ve found the answer for you. Please read on the page.[](https://tools.techidaily.com/drivereasy/download/)

 Note: Due to the error, your computer probably cannot boot into Windows 10 as normal, then boot it into Safe Mode before trying the following solutions. [](https://tools.techidaily.com/drivereasy/download/)

1. **[Performing clean boot](https://tools.techidaily.com/drivereasy/download/)**
2. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your drivers](https://tools.techidaily.com/drivereasy/download/)**
4. [**Check for Windows Updates**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Solution 1\. Performing clean boot

 1) On your keyboard, press the **Windows logo key**  and **R**  (at the same time) to invoke the Run command.

 2) Type**msconfig** in the box and press **Enter** to open the System Configuration window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-40.jpg)

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

 3) Click**Yes** when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/11-10.jpg)

 4) Reboot your Windows 10 into normal mode. See if the Blue screen has gone.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Solution 4\. Check for Windows Updates

 Either hardware or software issues can lead to blue screen error. And Windows updates can  address security flaws and bugs related to both hardware and software. Thus make sure you’ve install all the new Windows 10 updates to keep your Windows 10 healthy, stable and away from blue screen error.

1) Type **Windows Update** in the search box. Click **Check for updates** on the top result.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fast-track-the-worlds-top-8-burgeoning-video-hubs-on-youtube/"><u>[New] 2024 Approved  Fast-Track  The World's Top 8 Burgeoning Video Hubs on YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-polaroid-xs-review-capturing-life-in-full-hd/"><u>[New] Polaroid XS Review  Capturing Life in Full HD</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-androids-best-youtube-video-downloaders-reviewed/"><u>[Updated] In 2024, Android's Best YouTube Video Downloaders Reviewed</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/breaking-barriers-next-level-strategies-for-fb-video-success/"><u>Breaking Barriers  Next-Level Strategies for FB Video Success</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/complete-fix-for-hypervisor-error-causing-blue-screen-of-death-on-windows-11-expert-advice/"><u>Complete Fix for HYPERVISOR ERROR Causing Blue Screen of Death on Windows 11 - Expert Advice</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/diagnosing-and-repairing-kernel-mode-violations-the-pool-header-blue-screen-of-death-on-windows-11/"><u>Diagnosing and Repairing Kernel-Mode Violations: The Pool Header Blue Screen of Death on Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199738605-driver-protection-oversight-rectified-no-more-blue-screens-of-death/"><u>Driver Protection Oversight Rectified – No More Blue Screens of Death</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/elevate-your-console-gaming-experience-with-the-powerful-asus-vg245h-display/"><u>Elevate Your Console Gaming Experience with the Powerful Asus VG245H Display</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-free-operations-deciphering-the-causes-behind-unexpected-system-reboots/"><u>Error-Free Operations: Deciphering the Causes Behind Unexpected System Reboots</u></a></li>
<li><a href="https://buynow-info.techidaily.com/evaluating-the-cost-of-airpods-max-earpieces/"><u>Evaluating the Cost of AirPods Max Earpieces</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fix-your-windows-10-blue-screen-of-death-with-igdkmd64sys-step-by-step-solutions/"><u>Fix Your Windows 10 Blue Screen of Death with Igdkmd64.sys - Step by Step Solutions</u></a></li>
<li><a href="https://techidaily.com/fix-non-functional-headphones-on-windows-11-pc-troubleshooting-steps/"><u>Fix: Non-Functional Headphones on Windows 11 PC - Troubleshooting Steps</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-hal-initialization-failed-issues-on-windows-11-step-by-step-tutorial/"><u>Fixing 'HAL Initialization Failed' Issues on Windows 11 - Step-by-Step Tutorial</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-it-what-it-means-when-your-pc-requires-a-forced-reboot/"><u>Fixing IT: What It Means When Your PC Requires a Forced Reboot</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-correctly-address-acpisys-malfunctions-on-your-windows-11-pc/"><u>How to Correctly Address acpi.sys Malfunctions on Your Windows 11 PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-embrace-automatic-transcription-for-engaging-presentations/"><u>In 2024, How to Embrace Automatic Transcription for Engaging Presentations</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-blue-screen-error-code-0x0000003b-explained/"><u>Resolved: Blue Screen Error Code 0X0000003B Explained</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-critical-stop-error-blue-screen-with-code-0x00000133-in-windows-10/"><u>Resolving the Critical Stop Error: Blue Screen with Code 0X00000133 in Windows 10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-work-life-by-learning-about-the-power-of-chatgpt-top-6-insights/"><u>Revolutionize Your Work Life by Learning About the Power of ChatGPT - Top 6 Insights</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/rewe-group/"><u>Rewe Group</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/simple-fixes-for-the-persistent-thread-blocked-by-windows-driver-in-win-10/"><u>Simple Fixes for the Persistent Thread Blocked by Windows Driver in Win 10</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solving-non-paged-memory-problems-a-complete-fix-for-windows-10-users/"><u>Solving Non-Paged Memory Problems: A Complete Fix for Windows ‪10 Users‬</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-solution-to-stop-ntkrnlmpexe-from-causing-system-failures/"><u>Step-by-Step Solution to Stop NTKRNLMP.EXE From Causing System Failures</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-strategies-to-repair-the-syntpsys-blue-screen-error-in-windows/"><u>Step-by-Step Strategies to Repair the SYNTP.SYS Blue Screen Error in Windows</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/the-definitive-fix-guide-for-windows-elusive-error-0x0000000a-blue-screen-challenge/"><u>The Definitive Fix Guide for Windows' Elusive Error 0X0000000A Blue Screen Challenge</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-7-apps-altering-vocal-soundtracks-for-2024/"><u>Top 7 Apps Altering Vocal Soundtracks for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-and-fixing-a-failed-dpc-transition-error-in-windows-systems/"><u>Troubleshooting and Fixing a Failed DPC Transition Error in Windows Systems</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-and-resolving-blue-screen-with-error-0x0000001e/"><u>Troubleshooting and Resolving Blue Screen with Error 0X0000001E</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199733102-troubleshooting-the-fltrmgrsys-crashing-issue-in-windows-systems-solutions-inside/"><u>Troubleshooting the Fltrmgr.sys Crashing Issue in Windows Systems - Solutions Inside</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199721721-troubleshooting-the-notorious-blue-screen-error-0xc000021a-in-windows-11-and-8-solutions-proven-to-work/"><u>Troubleshooting the Notorious Blue Screen (Error 0xC000021A) in Windows 11 and 8: Solutions Proven to Work</u></a></li>
</ul></div>
