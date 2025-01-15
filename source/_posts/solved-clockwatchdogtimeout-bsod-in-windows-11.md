---
title: "[Solved] CLOCK_WATCHDOG_TIMEOUT BSOD in Windows 11"
date: 2025-01-13T01:01:29.643Z
updated: 2025-01-14T17:53:59.305Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 1\. Performing clean boot

 1) On your keyboard, press the **Windows logo key**  and **R**  (at the same time) to invoke the Run command.

 2) Type**msconfig** in the box and press **Enter** to open the System Configuration window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-40.jpg)

 3) Choose to view on**Services** pane. Click**Hide all Microsoft services** \>**Disable all** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-39.jpg)

 4) Go on to choose to view on**Startup** pane. Click**Open Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-32.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) On Task Manager window, tap on**Startup** pane. Then highlight the unnecessary services except Windows safe services and click**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-41.jpg)

 6） Close Task Manager window and back on Services Configuration window, tap on**Boot**  pane. Then**uncheck Safe boot** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-29.jpg)

 7) Click**Restart** if prompted by System Configuration. Then see if your computer can boot to Windows 10 normally.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-19.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Solution 4\. Check for Windows Updates

 Either hardware or software issues can lead to blue screen error. And Windows updates can  address security flaws and bugs related to both hardware and software. Thus make sure you’ve install all the new Windows 10 updates to keep your Windows 10 healthy, stable and away from blue screen error.

1) Type **Windows Update** in the search box. Click **Check for updates** on the top result.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/13-2.jpg)

2) Click **Check for updates** on the right pane of pop-up window.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/12-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://data-safeguard.techidaily.com/1721266307608-click-to-order-the-perfect-erasing-solution-for-your-iphone/"><u>Click to Order the Perfect Erasing Solution for Your iPhone!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/comprehensive-guide-to-curing-bsod-handling-the-0x00000050-error-in-windows-7/"><u>Comprehensive Guide to Curing BSOD: Handling the 0X00000050 Error in Windows 7</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/error-code-0x00000019-explained-effective-remedies-for-bad-pool-headers-on-windows-systems-resolved/"><u>Error Code 0X00000019 Explained: Effective Remedies for Bad Pool Headers on Windows Systems [RESOLVED]</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-repair-a-crashed-pc-with-bugcodeusbdriver-error-on-windows-10-system/"><u>How to Repair a Crashed PC with 'BUGCODE_USB_DRIVER' Error on Windows 10 System</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-inaccessible-boot-device-blue-screen-error-on-windows-11-with-illustrative-images/"><u>How to Resolve 'Inaccessible Boot Device' Blue Screen Error on Windows 11 with Illustrative Images</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-special-features-virtual-location-on-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Nubia Red Magic 9 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-note-30i-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Note 30i to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-6-retailers-for-high-quality-laptops-on-the-market/"><u>Top 6 Retailers for High-Quality Laptops on the Market</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-windows-crashes-resolving-stop-code-0x0000009f/"><u>Troubleshooting Windows Crashes: Resolving Stop Code 0X0000009F</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/unveiling-top-15-cost-saving-web-editors-rated-best-for-2024/"><u>Unveiling Top 15 Cost-Saving Web Editors - Rated Best for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/video-perfection-choosing-the-ultimate-5-enhancers/"><u>Video Perfection Choosing the Ultimate 5 Enhancers</u></a></li>
</ul></div>

