---
title: How to Correctly Update or Replace acpi.sys in Your Windows 10 Device
date: 2024-08-30T12:24:09.550Z
updated: 2024-08-31T12:24:09.550Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes How to Correctly Update or Replace acpi.sys in Your Windows 10 Device
excerpt: This Article Describes How to Correctly Update or Replace acpi.sys in Your Windows 10 Device
thumbnail: https://thmb.techidaily.com/c196f6b4394e95f28b75708e950be08411857a7cc6fdf0b1b999475eb2576da4.jpg
---

## Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved

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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

 3) Click**Yes** when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Solution 4\. Check for Windows Updates

 Either hardware or software issues can lead to blue screen error. And Windows updates can  address security flaws and bugs related to both hardware and software. Thus make sure you’ve install all the new Windows 10 updates to keep your Windows 10 healthy, stable and away from blue screen error.

1) Type **Windows Update** in the search box. Click **Check for updates** on the top result.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/13-2.jpg)

2) Click **Check for updates** on the right pane of pop-up window.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://blue-screen-error.techidaily.com/fixed-tcpipsys-blue-screen-of-death-on-windows-1178/"><u>[Fixed] tcpip.sys Blue Screen of Death on Windows 11/7/8</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-online-retrobing-navigating-youtubes-deleted-content/"><u>[New] 2024 Approved  Online Retrobing  Navigating YouTube’s Deleted Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-comparing-profits-from-high-ranking-youtube-videos/"><u>[New] In 2024, Comparing Profits From High-Ranking YouTube Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-discover-the-full-screen-fusion-potential-with-sierras-multimedia-capabilities/"><u>[Updated] In 2024, Discover the Full-Screen Fusion Potential with Sierra's Multimedia Capabilities</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unveiling-frames-5-effective-charge-free-youtube-techniques/"><u>[Updated] Unveiling Frames  5 Effective, Charge-Free YouTube Techniques</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-how-to-optimize-video-production-with-adobe-presenter/"><u>2024 Approved  How to Optimize Video Production with Adobe Presenter</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/critical-service-crash-to-blue-screen-of-death-solving-windows-11-issues-with-ease/"><u>Critical Service Crash to Blue Screen of Death? Solving Windows 11 Issues with Ease</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/deciphering-and-repairing-kernel-mode-violation-0x0000009f/"><u>Deciphering and Repairing Kernel-Mode Violation 0X0000009F</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/definitive-fix-for-the-dreaded-ntkrnlmpexe-bsod-tips-and-techniques/"><u>Definitive Fix for the Dreaded ntkrnlmp.exe BSOD: Tips and Techniques</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/diagnosing-and-repairing-the-blue-screen-error-0x00000124-on-your-windows-pc/"><u>Diagnosing & Repairing the Blue Screen Error (0X00000124) on Your Windows PC</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/eads-eadsbpa/"><u>EADS EADSB.PA</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-fixes-for-overcoming-syntpsys-blue-screens-of-death-on-windows-machines/"><u>Effective Fixes for Overcoming SYNTP.SYS Blue Screens of Death on Windows Machines</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-fixes-for-the-notorious-ntfs-file-system-complications-in-windows-11-devices/"><u>Effective Fixes for the Notorious NTFS File System Complications in Windows 11 Devices</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/eliminate-unexpected-shutdowns-in-depth-strategies-for-fixing-windows-seven/"><u>Eliminate Unexpected Shutdowns: In-Depth Strategies for Fixing Windows ˈseven</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-0xc000021a-blue-screen-of-death-on-windows-10-and-8-solved/"><u>Error 0xC000021A Blue Screen of Death on Windows 10 & 8 [Solved]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-code-decoded-understanding-and-fixing-stop-0x00000am-a/"><u>Error Code Decoded - Understanding and Fixing Stop 0X00000am A</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-elimination-handling-the-infamous-blue-screen-and-apc-index-mismatch/"><u>Error Elimination: Handling the Infamous Blue Screen and APC Index Mismatch</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-guide-to-troubleshooting-bsod-error-with-tcpipsys-on-different-windows-oss/"><u>Expert Guide to Troubleshooting BSOD Error with tcpip.sys on Different Windows OSs</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-solutions-to-overcome-ntfs-storage-problems-in-windows-10/"><u>Expert Solutions to Overcome NTFS Storage Problems in Windows 10</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-tips-for-triggering-windows-11-startup-repair-effortlessly/"><u>Expert Tips for Triggering Windows 11 Startup Repair Effortlessly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-latest-in-computing-gear-with-tom-a-comprehensive-guide/"><u>Exploring the Latest in Computing Gear with Tom - A Comprehensive Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/guide-to-correcting-the-tdr-failure-in-windows-nk-caused-by-atikmpagsys/"><u>Guide to Correcting the TDR Failure in Windows Nk Caused by atikmpag.sys</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199699843-how-to-address-a-dpc-watchdog-breach-without-delay-solutions-inside/"><u>How to Address a DPC Watchdog Breach Without Delay - Solutions Inside</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-page-fault-in-nonpaged-area-errors-for-a-smoother-windows-11-experience/"><u>How to Fix 'Page Fault in Nonpaged Area' Errors for a Smoother Windows 11 Experience</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-overcome-a-blue-screen-of-death-with-stop-code-0x0000007b/"><u>How to Overcome a Blue Screen of Death with STOP Code 0X0000007B</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-prevent-and-repair-the-watchdogsys-crashes-causing-bsod-on-your-pc/"><u>How to Prevent and Repair the Watchdog.sys Crashes Causing BSOD on Your PC</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-video-scheduler-internal-error-issues-on-your-pc-with-windows-10/"><u>How to Resolve Video Scheduler Internal Error Issues on Your PC with Windows 10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-guide-to-sustaining-longer-gopro-battery-life/"><u>In 2024, A Guide to Sustaining Longer GoPro Battery Life</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XS with IMEI Code?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-title-your-photos-quickly-captioning-techniques-in-photos-app-win-11/"><u>In 2024, Title Your Photos Quickly  Captioning Techniques in Photos App Win 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/master-the-troubleshooting-of-device-driver-problems-halting-windows-10-performance/"><u>Master the Troubleshooting of 'Device Driver' Problems Halting Windows 10 Performance</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/metro-ag/"><u>Metro AG</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/ntfs-errors-resolved-a-step-by-step-repair-tutorial-for-windows-10-users/"><u>NTFS Errors Resolved: A Step-by-Step Repair Tutorial for Windows 10 Users</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/quick-fixes-for-device-driver-errors-on-windows-11-get-your-system-running-smoothly/"><u>Quick Fixes for Device Driver Errors on Windows 11: Get Your System Running Smoothly</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolve-your-pc-crisis-with-error-0x000000ea-in-depth-analysis-and-solutions/"><u>Resolve Your PC Crisis with Error 0X000000EA - In-Depth Analysis & Solutions</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-winodws-7-stop-error-0x00000050-a-comprehensive-guide/"><u>Resolving the Winodws 7 Stop Error: 0X00000050 - A Comprehensive Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-solutions-for-the-kmodeexceptionnothandled-bugs-on-windows-10-and-11-platforms/"><u>Step-by-Step Solutions for the 'kMODE_Exception_Not_Handled' Bugs on Windows 10 & 11 Platforms</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-solutions-to-deal-with-stop-code-0x0000009f-on-your-pc/"><u>Step-by-Step Solutions to Deal with STOP Code 0X0000009F on Your PC</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-techniques-for-fixing-bsod-bad-pool-header-problems-on-microsofts-latest-os/"><u>Step-by-Step Techniques for Fixing BSOD: Bad Pool Header Problems on Microsoft's Latest OS</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/stop-blue-screens-expert-tips-for-fixing-0x000ptr00000124-on-windows-pcs-win10win7/"><u>Stop Blue Screens: Expert Tips for Fixing 0X000ptr_00000124 on Windows PCs (Win10/Win7)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723964462424-thrilling-breakthrough-in-pc-performance-ddr5-memory-hit-9058mhz-with-ryzen-clockwork-latest-bios-update-secrets-revealed/"><u>Thrilling Breakthrough in PC Performance: DDR5 Memory Hit 9058MHz with Ryzen Clockwork - Latest BIOS Update Secrets Revealed</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-and-solving-bad-memory-allocation-issues-in-windows-operating-systems/"><u>Troubleshooting and Solving Bad Memory Allocation Issues in Windows Operating Systems</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/ultimate-guide-resolving-the-windows-7-blue-screen-error/"><u>Ultimate Guide: Resolving the Windows 7 'Blue Screen' Error</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/ultimate-solution-for-driver-corruptedexpool-errors-in-windows-10-systems/"><u>Ultimate Solution for 'DRIVER CORRUPTED_EXPOOL' Errors in Windows 10 Systems</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/understanding-and-repairing-the-netwtw04sys-bsod-on-your-windows-amoled-device/"><u>Understanding & Repairing the 'netwtw04.sys' BSOD on Your Windows Amoled Device</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-realme-c33-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-10-blue-screen-error-resolving-pfn-list-corruption-issues/"><u>Windows 10 Blue Screen Error: Resolving PFN List Corruption Issues</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-security-enhanced-preventing-nxmemory-execution-problems/"><u>Windows Security Enhanced: Preventing NXMemory Execution Problems</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/winning-against-0x0000000a-your-ultimate-guide-to-resolving-blue-screens/"><u>Winning Against 0X0000000A: Your Ultimate Guide to Resolving Blue Screens</u></a></li>
</ul></div>
