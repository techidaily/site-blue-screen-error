---
title: "[Solved] CLOCK_WATCHDOG_TIMEOUT BSOD in Windows 11"
date: 2025-01-18T17:05:33.692Z
updated: 2025-01-21T16:07:29.722Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes [Solved] CLOCK_WATCHDOG_TIMEOUT BSOD in Windows 11
excerpt: This Article Describes [Solved] CLOCK_WATCHDOG_TIMEOUT BSOD in Windows 11
thumbnail: https://thmb.techidaily.com/f7c7286cd43e0a0357c0677fcf7ef7e026ec5b0c5c8fee31ed3df2a195c8af00.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 1\. Performing clean boot

 1) On your keyboard, press the **Windows logo key**  and **R**  (at the same time) to invoke the Run command.

 2) Type**msconfig** in the box and press **Enter** to open the System Configuration window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-40.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click**Yes** when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://visual-screen-recording.techidaily.com/new-android-audio-capture-techniques-rootless-options/"><u>[New] Android Audio Capture Techniques - Rootless Options</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-video-cropping-anomaly-decoding-imovies-actions/"><u>[New] In 2024, Video Cropping Anomaly Decoding iMovie's Actions</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solved-dxgkrnlsys-blue-screen-of-death-on-windows/"><u>[Solved] dxgkrnl.sys Blue Screen of Death on Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-showcasing-creativity-an-assortment-of-top-5-book-vtts/"><u>[Updated] 2024 Approved Showcasing Creativity An Assortment of Top 5 Book VTTs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-lenovo-laptop-a-complete-guide-to-recording-screens/"><u>[Updated] Lenovo Laptop A Complete Guide to Recording Screens</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015875415-apex-legends-and-voice-chat-woes-discover-simple-solutions-to-sound-off-in-the-game/"><u>Apex Legends and Voice Chat Woes? Discover Simple Solutions to Sound Off in the Game!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/easy-fixes-to-address-critical-system-info-issue-causing-your-pc-to-crash/"><u>Easy Fixes to Address Critical System Info Issue Causing Your PC to Crash</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-the-windows-10-unexpected-store-exception-error/"><u>How to Fix the Windows 10 Unexpected Store Exception Error</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-windows-ntoskrnlexe-crashes-and-stop-bsod-from-ruining-your-day/"><u>How to Resolve Windows NTOSKRNL.EXE Crashes and Stop BSoD From Ruining Your Day</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-virtual-tournament-gear-showcase-series/"><u>In 2024, Virtual Tournament Gear Showcase Series</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-courtesy-essential-when-interacting-with-voice-assistants-like-chatgpt-alexa-or-siri/"><u>Is Courtesy Essential When Interacting with Voice Assistants Like ChatGPT, Alexa, or Siri?</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-0x80070194-on-onedrive-and-windows-oses/"><u>Resolving 0X80070194 on OneDrive & Windows OSes</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199736422-step-by-step-fix-for-driver-verifier-causing-bsod-on-windows-10-problem-solved/"><u>Step-by-Step Fix for Driver Verifier Causing BSOD on Windows 10 – Problem Solved!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-steps-for-correcting-internal-power-malfunction-on-windows-11-computers/"><u>Troubleshooting Steps for Correcting Internal Power Malfunction on Windows 11 Computers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-selection-of-free-streaming-options-reviewed/"><u>Ultimate Selection of Free Streaming Options Reviewed</u></a></li>
</ul></div>

