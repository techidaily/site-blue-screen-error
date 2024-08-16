---
title: Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved
date: 2024-08-15T01:19:59.894Z
updated: 2024-08-16T01:19:59.894Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved
excerpt: This Article Describes Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved
thumbnail: https://thmb.techidaily.com/45bc41dfd22bb4252a227dcc20488f6faf42f4a30eaffbfeaeadce5abdbcdc1d.png
---

## Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-36.jpg)

 Recently, you upgrade your Windows operating system to Windows 10\. Windows 10 is great but it also brings you some troubles. The Blue Screen of Death(BSOD) is one of the Windows 10 nightmares. **UNEXPECTED\_STORE\_EXCEPTION**  is one of the common BSOD errors. If you’re facing this blue screen error, rest assured. We’ve found the answer for you. Please read on the page.[](https://tools.techidaily.com/drivereasy/download/)

 Note: Due to the error, your computer probably cannot boot into Windows 10 as normal, then boot it into Safe Mode before trying the following solutions. [](https://tools.techidaily.com/drivereasy/download/)

1. **[Performing clean boot](https://tools.techidaily.com/drivereasy/download/)**
2. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your drivers](https://tools.techidaily.com/drivereasy/download/)**
4. [**Check for Windows Updates**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Solution 1\. Performing clean boot

 1) On your keyboard, press the **Windows logo key**  and **R**  (at the same time) to invoke the Run command.

 2) Type**msconfig** in the box and press **Enter** to open the System Configuration window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-40.jpg)

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

 3) Click**Yes** when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Solution 4\. Check for Windows Updates

 Either hardware or software issues can lead to blue screen error. And Windows updates can  address security flaws and bugs related to both hardware and software. Thus make sure you’ve install all the new Windows 10 updates to keep your Windows 10 healthy, stable and away from blue screen error.

1) Type **Windows Update** in the search box. Click **Check for updates** on the top result.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
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
<li><a href="https://blue-screen-error.techidaily.com/fixed-bsod-error-0x00000133-on-windows-11/"><u>[Fixed] BSOD Error 0X00000133 on Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixed-page-fault-in-nonpaged-area-error-in-windows-11/"><u>[Fixed] Page Fault In Nonpaged Area Error in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-obs-rescue-cameras-are-back-up/"><u>[New] In 2024, OBS Rescue  Cameras Are Back Up</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-the-ultimate-manual-for-extracting-hd-from-facebook/"><u>[New] The Ultimate Manual for Extracting HD From Facebook</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-breaking-barriers-with-excellent-job-interview-techniques/"><u>[Updated] Breaking Barriers with Excellent Job Interview Techniques</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-immediate-video-removal-by-facebook-an-overview-of-processes/"><u>[Updated] In 2024, Immediate Video Removal by Facebook - An Overview of Processes</u></a></li>
<li><a href="https://article-tips.techidaily.com/20-must-have-mp4-devices/"><u>20 Must-Have MP4 Devices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-earnings-unleashed-discovering-8-lucrative-tiktok-practices/"><u>2024 Approved  Earnings Unleashed  Discovering 8 Lucrative TikTok Practices</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-punchline-studio-sign-up-and-share-your-humor/"><u>2024 Approved  PunchLine Studio  Sign Up & Share Your Humor</u></a></li>
<li><a href="https://iphone-location.techidaily.com/5-ways-change-your-home-address-in-googleapple-map-on-apple-iphone-8-plusipad-drfone-by-drfone-virtual-ios/"><u>5 Ways Change Your Home Address in Google/Apple Map on Apple iPhone 8 Plus/iPad | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/conquer-your-pcs-blues-in-depth-strategies-for-dealing-with-the-stop-error-0x0000001a-on-windows-machines/"><u>Conquer Your PC's Blues: In-Depth Strategies for Dealing With the STOP Error 0X0000001A on Windows Machines</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-techniques-for-addressing-and-correcting-bad-pool-header-issues-leading-to-bsod-on-windows-10/"><u>Effective Techniques for Addressing and Correcting Bad Pool Header Issues Leading to BSOD on Windows 10</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-techniques-to-fix-memory-management-bugs-like-bad-pool-header-across-different-windows-platforms/"><u>Effective Techniques to Fix Memory Management Bugs Like Bad Pool Header Across Different Windows Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-top-5-compact-camcorders-for-adventure/"><u>Essential Top 5 Compact Camcorders for Adventure</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722868747070-explore-our-top-picked-iphone-email-applications-to-enhance-your-communication/"><u>Explore Our Top-Picked iPhone Email Applications to Enhance Your Communication !</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-the-clock-watchdog-timeout-blue-screen-error-on-windows-11/"><u>Fixing the Clock Watchdog Timeout Blue Screen Error on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/game-on-top-6-must-try-chatgpt-gaming-experiences/"><u>Game On! Top 6 Must-Try ChatGPT Gaming Experiences</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-11-data-completely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone 11 Data Completely | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/guide-to-solving-fatal-event-logging-issues-on-windows-11-computers/"><u>Guide to Solving Fatal Event Logging Issues on Windows 11 Computers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-realme-c33-2023-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Realme C33 2023</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-the-0x00000019-bad-pool-header-issue-in-windows-operating-systems-guides/"><u>How to Resolve the 0X00000019 Bad Pool Header Issue in Windows Operating Systems [GUIDES]</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-itel-s23plus-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Itel S23+ to Apple TV | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-11-pro-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 11 Pro to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-oneplus-12-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from OnePlus 12 Phones with/without a PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-how-to-engage-with-snapchat-luminaries/"><u>In 2024, How to Engage with Snapchat Luminaries</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-nubia-red-magic-8s-proplus-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Nubia Red Magic 8S Pro+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/mastering-error-resolution-correcting-syntpsys-blue-screens-on-your-windows-computer/"><u>Mastering Error Resolution: Correcting SYNTP.SYS Blue Screens on Your Windows Computer</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/mastering-fixes-for-windows-11s-system-service-exception-expert-techniques-and-advice/"><u>Mastering Fixes for Windows 11'S 'System Service Exception': Expert Techniques and Advice</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-create-stunning-animations-top-tools-for-beginners-intermediate-and-advanced-users/"><u>New In 2024, Create Stunning Animations Top Tools for Beginners, Intermediate, and Advanced Users</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/overcoming-the-challenge-of-ntoskrnlexe-and-netiosys-errors-a-how-to-for-windows-users/"><u>Overcoming the Challenge of NTOSKRNL.EXE & NETIO.SYS Errors: A How-To for Windows Users</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199728516-quick-fixes-for-device-driver-errors-on-windows-11-get-your-system-running-smoothly/"><u>Quick Fixes for Device Driver Errors on Windows 11: Get Your System Running Smoothly!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-fixing-the-issue-why-your-computer-requires-an-immediate-reboot/"><u>Resolved: Fixing the Issue - Why Your Computer Requires an Immediate Reboot</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-how-to-fix-the-fat-file-system-issue-in-windows-10/"><u>Resolved: How to Fix the FAT File System Issue in Windows 10</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-ntdlldll-and-ndissys-bsod-issues-in-windows/"><u>Resolving ntdll.dll & ndis.sys BSOD Issues in Windows</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-ntfs-file-system-issues-in-windows-11-a-comprehensive-guide/"><u>Resolving NTFS File System Issues in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-stack-buffer-overflow-errors-a-step-by-step-guide/"><u>Resolving Stack Buffer Overflow Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-win32ksys-bsod-a-step-by-step-guide/"><u>Resolving Win32K.sys BSOD: A Step-by-Step Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solving-the-syntpsys-bsod-error-on-your-windows-pc-a-step-by-step-guide/"><u>Solving the SYNTP.SYS BSOD Error on Your Windows PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/straightforward-strategies-for-managing-unexpected-thread-failures/"><u>Straightforward Strategies for Managing Unexpected Thread Failures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-best-apps-for-keeping-your-linkedin-vids-safe-and-sound-for-2024/"><u>The Best Apps for Keeping Your LinkedIn Vids Safe & Sound for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshoot-your-pcs-win3amsys-bsod-problem-easily-a-complete-guide/"><u>Troubleshoot Your PC's win3am.sys BSOD Problem Easily – A Complete Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/unraveling-the-mystery-of-0x00000050-blue-screen-troubleshooting-tips-for-windows-7-users/"><u>Unraveling the Mystery of 0X00000050 Blue Screen: Troubleshooting Tips for Windows 7 Users</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-11-blue-screen-error-a-comprehensive-guide-after-system-updates/"><u>Windows 11 Blue Screen Error: A Comprehensive Guide After System Updates</u></a></li>
</ul></div>
