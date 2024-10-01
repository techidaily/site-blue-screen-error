---
title: "[SOLVED] ntoskrnl.exe BSOD Blue Screen Error"
date: 2024-09-25T16:45:20.140Z
updated: 2024-09-30T22:03:44.865Z
tags:
  - win11
  - win10
  - win7
categories:
  - BlueScreenError
description: This Article Describes [SOLVED] ntoskrnl.exe BSOD Blue Screen Error
excerpt: This Article Describes [SOLVED] ntoskrnl.exe BSOD Blue Screen Error
thumbnail: https://thmb.techidaily.com/9c17d408eef8eb942c240704209721146d1ae1a43ce819e245d60c114f5c5c21.jpg
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

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

## Solution 2\. Running System File Checker

 Sometimes the corrupted system files can cause the blue screen error, in such case, we advise you run system file checker to scan the system file and repair the corrupted or missing ones.

 1) On your keyboard, press the **Windows logo key**  and **X**  (at the same time) to open the quick-access menu.

 2) Click**Command Prompt (Admin)** to run it as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-37.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click**Yes** when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-13.jpg)

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Type**sfc /scannow** in pop-up window and hit Enter to run it. Wait till Verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/11-10.jpg)

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-digital-game-chronicles-snappy-screenshots-for-every-moment-for-2024/"><u>[New] Digital Game Chronicles Snappy Screenshots for Every Moment for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-curating-striking-instagram-profile-photos/"><u>[Updated] Curating Striking Instagram Profile Photos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-best-of-gopro-cameras-side-by-side/"><u>[Updated] Exploring the Best of GoPro Cameras Side by Side</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-samsung-galaxy-s24-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Samsung Galaxy S24 to iPhone | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-superiority-topmost-ai-tools-revolutionizing-your-online-searches/"><u>Explore the Superiority: Topmost AI Tools Revolutionizing Your Online Searches</u></a></li>
<li><a href="https://win-solutions.techidaily.com/firing-your-tile/"><u>Firing Your Tile</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/hapag-lloyd-ag/"><u>Hapag-Lloyd AG</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-stop-windows-crashing-with-rtwlanesys-a-comprehensive-guide/"><u>How to Stop Windows Crashing with 'rtwlane.sys': A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-downloading-facebook-videos-ultimate-5-list-ranked/"><u>In 2024, Downloading Facebook Videos Ultimate 5 List Ranked</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-failed-to-change-from-dpc-mistake-on-your-pc-a-complete-walkthrough/"><u>Resolving the 'Failed to Change From DPC' Mistake on Your PC: A Complete Walkthrough</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/stop-the-crash-comprehensive-steps-to-fix-the-blue-screen-with-stop-code-0x00000124-in-windows-os/"><u>Stop the Crash: Comprehensive Steps to Fix the Blue Screen with Stop Code 0X00000124 in Windows OS</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199733873-the-ultimate-guide-to-cancel-free-driver-deactivation-during-active-tasks-problem-solved/"><u>The Ultimate Guide to Cancel-Free Driver Deactivation During Active Tasks - Problem Solved</u></a></li>
</ul></div>

