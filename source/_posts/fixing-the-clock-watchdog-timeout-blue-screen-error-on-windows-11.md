---
title: Fixing the Clock Watchdog Timeout Blue Screen Error on Windows 11
date: 2024-12-21T20:10:46.143Z
updated: 2024-12-24T19:30:38.345Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Fixing the Clock Watchdog Timeout Blue Screen Error on Windows 11
excerpt: This Article Describes Fixing the Clock Watchdog Timeout Blue Screen Error on Windows 11
thumbnail: https://thmb.techidaily.com/8b80e339dbd0915bb63a5c4ef4dc3b35128d5a8fefa5d8cd2d10ef2a2fa6ce03.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click**Yes** when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/11-10.jpg)

 4) Reboot your Windows 10 into normal mode. See if the Blue screen has gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/2024-approved-splendid-review-and-different-selections/"><u>2024 Approved Splendid Review & Different Selections</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-hal-initialization-issues-on-windows-11-a-comprehensive-guide/"><u>Fixing HAL Initialization Issues on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-file-is-locked-issue-on-steam-a-comprehensive-guide/"><u>Fixing the 'File Is Locked' Issue on Steam: A Comprehensive Guide</u></a></li>
<li><a href="https://discover-data.techidaily.com/intelligent-recording-tools-explore-the-latest-in-samsungs-screen-capture-technology/"><u>Intelligent Recording Tools: Explore the Latest in Samsung's Screen Capture Technology</u></a></li>
<li><a href="https://win-net.techidaily.com/quick-and-simple-steps-for-snapping-screenshots-of-any-webpage/"><u>Quick and Simple Steps for Snapping Screenshots of Any Webpage!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-critical-fatal-error-pnp-detected-in-windows-10-devices/"><u>Resolved: Critical Fatal Error 'PNP Detected' In Windows 10 Devices</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-fat32-file-system-glitch-in-windows-10/"><u>Resolving the FAT32 File System Glitch in Windows 10</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/simple-solutions-to-unstick-device-driver-related-bugs-in-windows-10/"><u>Simple Solutions to Unstick Device Driver-Related Bugs in Windows 10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-essential-blueprint-for-obtaining-premium-visuals-for-free/"><u>The Essential Blueprint for Obtaining Premium Visuals for Free</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-ultimate-mac-video-editor-adobe-premiere-pro-for-pros-for-2024/"><u>The Ultimate Mac Video Editor Adobe Premiere Pro for Pros for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshoot-driver-corrupted-exception-pool-failures-in-windows-11-effective-remedies-and-advice/"><u>Troubleshoot DRIVER CORRUPTED EXCEPTION POOL Failures in Windows 11 - Effective Remedies and Advice</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/visual-capture-specialists-top-10-tools/"><u>Visual Capture Specialists' Top 10 Tools</u></a></li>
</ul></div>

