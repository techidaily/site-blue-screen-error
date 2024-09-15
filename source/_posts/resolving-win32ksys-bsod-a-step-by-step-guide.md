---
title: "Resolving Win32K.sys BSOD: A Step-by-Step Guide"
date: 2024-09-14T02:22:06.008Z
updated: 2024-09-14T17:10:13.527Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: "This Article Describes Resolving Win32K.sys BSOD: A Step-by-Step Guide"
excerpt: "This Article Describes Resolving Win32K.sys BSOD: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/07b2aab86c7b38cc417b46120335b85009ee66f18ed61940d702b12e24cb4c65.jpg
---

## Fix 'Bad System Configuration' BSOD Fast: Simple Steps to Resolve

![](https://images.drivereasy.com/wp-content/uploads/2017/03/bad-system-config-info.png)

**BAD\_SYSTEM\_CONFIG\_INFO**  is one of the common Blue Screen of Death (BSOD) error on Windows system. If you’re experiencing this error, rest assured, you’re not alone. Many Windows users have this problem. More importantly, you can fix it through the methods below quickly & easily!

## 3 effective methods to fix BAD\_SYSYTEM\_CONFIG\_INFO

 The Bad System Config Info blue screen error could be caused by different reasons. This guide is covering 3 different effective and easy methods for your to try. You may not have to try them all; just start from the top and work your way down, till you solve your problem.

**[](https://tools.techidaily.com/drivereasy/download/)**

**IMPORTANT:** You’ll need to log into Windows on the problem computer to try any of these solutions. If you can’t log into Windows, [restart it in Safe Mode](https://tools.techidaily.com/drivereasy/download/) , then try these solutions.

1. **[Update all your available drivers](https://tools.techidaily.com/drivereasy/download/)**
2. **[Fix your BCD file](https://tools.techidaily.com/drivereasy/download/)**
3. **[Fix your Windows Registry](https://tools.techidaily.com/drivereasy/download/)**

## Method 1: Update all your available drivers

 Many blue screen errors are blamed on  outdated, corrupted or missing device drivers. BAD\_SYSTEM\_CONFIG\_INFO is no exception. Updating drivers should always be your go-to option when something goes wrong with your computer or system. Whether you choose to update the device drivers manually, using Windows Update, or you use a trusted third party product, it’s essential that you have the latest correct device drivers for your operating system at all times.

 If you’re not comfortable playing with device drivers, we recommend using **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . It’s a tool that detects, downloads and (if you go Pro) installs any driver updates your computer needs. Here is how to do it:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.
2. Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy.jpg)
3. Click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. You need the Pro version of Driver Easy to do this, so you’ll be prompted to upgrade.  

 Don’t worry; it comes with a 30-day money-back guarantee, so if you don’t like it you can get a full refund, no questions asked.  

 (Alternatively if you’re comfortable manually installing drivers, you can click ‘Update’ next to each flagged device in the free version to automatically download the correct driver. Once it’s downloaded, you can manually install it.)  
![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-update-drivers.jpg)
4. Reboot your Windows 10 to see if it works.

 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://tools.techidaily.com/drivereasy/download/)**  .

## Method 2: Fix your BCD file

 This error could be also caused by the damaged BCD (Boot Configuration Data) file . So if your Win 10 can’t enter safe mode to fix the error, be sure to try to fix the BCD file.

**NOTE:**  It needs a Win 10 installation flash drive to try this fix. If you don’t have one, you can refer to the post[How to create Win 10 installation flash drive](https://tools.techidaily.com/drivereasy/download/) to create one.

1. Insert your Windows 10 installation disk in your computer. Then restart it to boot from the disk. (if you don’t know how to do it, you can refer to the post:[How to boot from a USB drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) )
2. Click**Next** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/03/2019-10-30_11-43-48.jpg)
3. Click **Repair your computer** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/03/2019-10-30_11-45-25.jpg)
4. Click **Troubleshoot** \>**Advanced options** \>**Command Prompt** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/03/2019-10-30_11-46-49.jpg)  

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2019-10-30_11-48-00.jpg)  

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2019-10-30_11-49-04.jpg)
5. Type the following commands and press **Enter**  after each.  
 **bootrec /repairbcd**  
 **bootrec /osscan**  
 **bootrec /repairmbr**
6. Close the command prompt window.
7. Reboot your Windows 10 to see if it works.

See if this method works for you. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Fix your Windows Registry

 This problem may also be triggered by the incorrect registry settings. To fix your Windows Registry:

**NOTE:**  It needs a Win 10 installation flash drive to try this fix. If you don’t have one, click to follow the instructions in the post[How to create Win 10 installation flash drive](https://tools.techidaily.com/drivereasy/download/) to create one.

1. Repeat step 1 \~ 4 in[Method 2](https://tools.techidaily.com/drivereasy/download/) to go to**Troubleshoot** \>**Advanced options** \>**Command Prompt** .
2. Type the following commands and press **Enter**  after each.  

 **CD C:\\Windows\\System32\\config**  
 **ren C:\\Windows\\System32\\config\\DEFAULT DEFAULT.old**  
 **ren C:\\Windows\\System32\\config\\SAM SAM.old**  
 **ren C:\\Windows\\System32\\config\\SECURITY SECURITY.old**  
 **ren C:\\Windows\\System32\\config\\SOFTWARE SOFTWARE.old**  
 **ren C:\\Windows\\System32\\config\\SYSTEM SYSTEM.old**
3. After the last command in step 2 completed, then type the following commands and press Enter after each.  

 **copy C:\\Windows\\System32\\config\\RegBack\\DEFAULT C:\\Windows\\System32\\config\\**  

 **copy C:\\Windows\\System32\\config\\RegBack\\SAM C:\\Windows\\System32\\config\\**  

 **copy C:\\Windows\\System32\\config\\RegBack\\SECURITY C:\\Windows\\System32\\config\\**  

 **copy C:\\Windows\\System32\\config\\RegBack\\SYSTEM C:\\Windows\\System32\\config\\**  

 **copy C:\\Windows\\System32\\config\\RegBack\\SOFTWARE C:\\Windows\\System32\\config\\**
4. Close the command prompt window after all the command are executed.
5. Reboot Windows 10 to see if it works.

 Hopefully, one of the methods in the post helped you resolve this issue. If you have any questions or suggestions on this issue, you’re more than welcome to leave us a comment below. Thanks for reading!

* [Blue Screen](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://discord-videos.techidaily.com/updated-easy-steps-for-clearing-out-desktop-discords/"><u>[Updated] Easy Steps for Clearing Out Desktop Discords</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-vsco-photo-workflow-analysis/"><u>[Updated] The Ultimate VSCO Photo Workflow Analysis</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-mastering-the-craft-of-powerpoint-transformation-into-videos/"><u>2024 Approved Mastering the Craft of PowerPoint Transformation Into Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/bluescreen-of-death-fixing-the-asmtxhcisys-error-on-your-pc/"><u>BlueScreen of Death: Fixing the 'asmtxhci.sys' Error on Your PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-iphone-x-activation-lock-without-previous-owner-by-drfone-ios-unlock-ios-unlock/"><u>Bypass iPhone X activation lock without previous owner</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/dive-into-the-world-of-cartoon-pop-culture-with-snapchat-for-2024/"><u>Dive Into the World of Cartoon Pop Culture with Snapchat for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-unmountable-boot-volume-bsod-on-windows-10-step-by-step-solutions/"><u>Fixing 'Unmountable Boot Volume' BSOD on Windows 10 - Step by Step Solutions</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-blue-screen-of-death-solutions-for-video-memory-handling-issues/"><u>Fixing Blue Screen of Death: Solutions for Video Memory Handling Issues</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopro-hero5-black-vs-garmin-virb-ultra-30-which-one-is-better-for-2024/"><u>GoPro Hero5 Black VS Garmin Virb Ultra 30 Which One Is Better for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-ultimate-watch-list-top-10-music-clips-on-facebook/"><u>In 2024, The Ultimate Watch List Top 10 Music Clips on Facebook</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-artificial-intelligence-top-tools-and-resources-amongst-beginner-circles-top-9/"><u>Navigating Artificial Intelligence: Top Tools and Resources Amongst Beginner Circles (Top 9)</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-internal-error-issues-with-video-scheduler-on-windows-11-guide/"><u>Resolving Internal Error Issues with Video Scheduler on Windows 11 [Guide]</u></a></li>
</ul></div>

