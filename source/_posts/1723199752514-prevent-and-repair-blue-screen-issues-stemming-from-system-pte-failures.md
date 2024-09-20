---
title: Prevent and Repair Blue Screen Issues Stemming From System PTE Failures.
date: 2024-09-16T06:45:13.311Z
updated: 2024-09-19T22:51:03.332Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Prevent and Repair Blue Screen Issues Stemming From System PTE Failures.
excerpt: This Article Describes Prevent and Repair Blue Screen Issues Stemming From System PTE Failures.
thumbnail: https://thmb.techidaily.com/0afe01c2e0f6b1c3ba9a8b87db7e0159921da64d28f55d619b92fd6d20b9c57c.jpg
---

## Blue Screen of Death? Eliminate 'Bad System Config' Issues in Minutes

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
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-skills.techidaily.com/new-the-perfect-blend-of-relaxation-and-growth-podcast-multi-tasking-tips/"><u>[New] The Perfect Blend of Relaxation and Growth Podcast Multi-Tasking Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-discover-8-youtube-thumbnail-generators-online/"><u>[Updated] 2024 Approved Discover 8 YouTube Thumbnail Generators Online</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-upgrade-your-whatsapp-experience-with-a-bespokel-ringtones-design/"><u>2024 Approved Upgrade Your WhatsApp Experience with a Bespokel Ringtones Design</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-viral-hits-top-10-video-watches-in-an-hour/"><u>2024 Approved Viral Hits Top 10 Video Watches in an Hour</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199746265-comprehensive-solutions-to-the-bsod-error-0xc00lete-on-windows-10-and-8-get-your-pc-back-online/"><u>Comprehensive Solutions to the BSOD (Error 0xC00lete) on Windows 10 and 8: Get Your PC Back Online</u></a></li>
<li><a href="https://win-able.techidaily.com/comprehensive-strategies-to-resolve-lost-arks-network-access-problem/"><u>Comprehensive Strategies to Resolve Lost Ark’s Network Access Problem</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-video-tdr-faults-caused-by-atikmpagsys-in-windows-11-solution-guide/"><u>How to Fix Video TDR Faults Caused by atikmpag.sys in Windows 11 - Solution Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-iphone-12-pro-max-device-from-icloud-by-drfone-ios/"><u>How to Remove iPhone 12 Pro Max Device from iCloud</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-image-integration-software-for-visual-enthusiasts/"><u>In 2024, Innovative Image Integration Software for Visual Enthusiasts</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-guide-seamless-audio-transitions-for-2024/"><u>Quick Guide Seamless Audio Transitions for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/system-service-exception-on-windows-10-solved/"><u>System Service Exception on Windows 10 [Solved]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/system-service-exception-on-windows-11-solved/"><u>System Service Exception on Windows 11 [Solved]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshoot-your-fix-for-inaccessible-boot-device-blue-screen-on-windows-e/"><u>Troubleshoot Your Fix for 'Inaccessible Boot Device' Blue Screen on Windows E</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-flv-editor-for-windows-8-professional-video-editing-made-easy/"><u>Updated Best FLV Editor for Windows 8 Professional Video Editing Made Easy</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-11-inaccessible-boot-device-blue-screen-troubleshooting-a-step-by-step-pictorial-guide/"><u>Windows 11 'Inaccessible Boot Device' Blue Screen Troubleshooting: A Step-by-Step Pictorial Guide</u></a></li>
</ul></div>

