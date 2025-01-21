---
title: Fixing the [Resolved] BSOD Caused by Machine Check Exception on Windows 11
date: 2025-01-16T18:22:26.881Z
updated: 2025-01-21T16:05:22.150Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes Fixing the [Resolved] BSOD Caused by Machine Check Exception on Windows 11
excerpt: This Article Describes Fixing the [Resolved] BSOD Caused by Machine Check Exception on Windows 11
thumbnail: https://thmb.techidaily.com/3616fb63d3712b98cc05f9583f4211869f6e4c453eb6e04c1cfde40ef70bbce3.jpg
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

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

 3) Click**Yes** when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/11-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-camera-editing-showdown-hero-vs-cubes-battle-of-the-screens/"><u>[New] Camera Editing Showdown Hero Vs. Cube's Battle of the Screens</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-easeus-assessment-for-all/"><u>[New] EaseUS Assessment for All</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-lilliputscreenmugger-review-analysis/"><u>[Updated] 2024 Approved LilliputScreenMugger Review Analysis</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-best-youtube-banner-size-and-channel-art-dimension-the-ultimate-guide/"><u>[Updated] Best YouTube Banner Size and Channel Art Dimension (The Ultimate Guide)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gif-hacks-for-iphone-users-storage-tips-and-playtime-tricks/"><u>2024 Approved GIF Hacks for iPhone Users Storage Tips and Playtime Tricks</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/demystifying-and-repairing-the-notorious-0x0000000a-blue-screen-error/"><u>Demystifying and Repairing the Notorious 0X0000000A Blue Screen Error</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/deutsche-post-ag/"><u>Deutsche Post AG</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-latest-dell-network-adapter-drivers-for-windows-7/"><u>Download the Latest Dell Network Adapter Drivers for Windows 7</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-tips-overcoming-system-service-exception-errors-on-windows-7-systems/"><u>Expert Tips - Overcoming System Service Exception Errors on Windows 7 Systems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-nokia-c12-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Nokia C12?</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-the-bad-pool-caller-mistake-on-your-windows-10-machine/"><u>How to Resolve the 'Bad Pool Caller' Mistake on Your Windows 10 Machine</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/irql-not-less-or-equal-windows-7-solved/"><u>IRQL NOT LESS OR EQUAL Windows 7 [SOLVED]</u></a></li>
<li><a href="https://sound-issues.techidaily.com/january-12th-robert-oppenheimer-an-american-physicist-known-for-his-role-in-creating-the-atomic-bomb-and-contributing-to-quantum-mechanics-his-work-has-left630/"><u>January 12Th - Robert Oppenheimer, an American Physicist Known for His Role in Creating the Atomic Bomb and Contributing to Quantum Mechanics. His Work Has Left a Lasting Impact on Science and Technology.</u></a></li>
<li><a href="https://fox-glue.techidaily.com/optimize-your-gaming-with-kinemaster-usage-tips-and-comparisons-with-best-online-games/"><u>Optimize Your Gaming with KineMaster Usage Tips & Comparisons with Best Online Games</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/rectify-windows-11-booting-issue-with-inaccessible-disk-error-bsod-detailed-photo-tutorial/"><u>Rectify Windows 11 Booting Issue with Inaccessible Disk Error (BSOD): Detailed Photo Tutorial</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-guide-to-repair-the-scheduler-glitch-on-your-windows-10-device-for-smooth-video-calls/"><u>Step-by-Step Guide to Repair the Scheduler Glitch on Your Windows 10 Device for Smooth Video Calls</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-guide-for-blue-screen-of-death-error-0x00000133-in-windows-10-systems/"><u>Troubleshooting Guide for Blue Screen of Death Error 0X00000133 in Windows 10 Systems</u></a></li>
</ul></div>

