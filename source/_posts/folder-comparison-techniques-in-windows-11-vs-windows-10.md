---
title: Folder Comparison Techniques in Windows 11 Vs. Windows 10
date: 2024-08-28T05:40:01.966Z
updated: 2024-08-29T05:40:01.966Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/52846060984_17cb6c3aa6_o.jpg
---

## Folder Comparison Techniques in Windows 11 Vs. Windows 10

### Quick Links

* [Compare Folders From Properties](https://tech-recovery.techidaily.com/the-ultimate-fix-for-when-youtube-comments-wont-load/)
* [Compare Folders Using Command Prompt](https://video-capture.techidaily.com/new-in-2024-exacting-speech-recognition-via-googles-precision-tools/)
* [Compare Folders With WinMerge](https://win-howtos.techidaily.com/how-to-repair-when-your-macs-trackpad-wont-respond/)

### Key Takeaways

* One way to compare folders is to right-click your folders one at a time and choose "Properties" for each. Then compare the Properties window of each folder.
* The robocopy command is a command-line tool that can be used to view the differences between folder.
* Use WinMerge to compare the contents and details of folders if you want a graphical tool.

 Do you want to compare the number of files or folders or simply visualize the difference between two folders? If so, you have two graphical and one command line method to do that. We’ll show you how to perform the folder comparison task on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
##  Compare Folders From Properties

 To compare the number of files, subfolders, the size, and the creation date of two folders, use the Properties option in Windows File Explorer. This lets you quickly glance at the main attributes of a folder.

 To start, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E. Find the first folder, right-click it, and select "Properties."

!['Properties' highlighted for a folder in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-folder-properties.jpg) 

 Keep the first folder’s "Properties" window open. Then, find the second folder, right-click it, and select "Properties."

 You now have the "Properties" window open for both your folders. Bring these windows side-by-side by [dragging them](https://extra-resources.techidaily.com/mastering-complex-video-effects-and-transitions-in-gopro-studio/), and you can see the differences in the contents of these folders. For example, you can see how many files both folders have, what size these folders are, and so on.

!['Properties' windows for two folders in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-compare-folder-properties.jpg) 

 That gives you a general overview of the differences between your folders.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Compare Folders Using Command Prompt

 If you prefer command line methods over graphical ones, use the robocopy command in Command Prompt to see the differences between the two folders. This command is actually for [copying files from one folder to another](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/), but you can make it show the differences between two specified folders and not copy any files.

 To use robocopy, first open the Start Menu, search **Command Prompt**, and launch it.

![Command Prompt highlighted in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 In Command Prompt, type the following command. Replace "Folder1" with the path to your first folder and "Folder2" with the path to your second folder. Ensure both folder paths are enclosed in double quotes.

 To copy a folder’s full path along with double quotes around the path, hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

robocopy "Folder1" "Folder2" /L /NJH /NJS /NP /NS

![The 'robocopy' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-compare-folders-command-prompt.jpg) 

 You’ll see the differences between your folders.

 If you’re curious as to what the robocopy command does, here’s an explanation of each flag we used with the command:

* **L**: This tells the command not to copy files but show the log of the files in the specified folder.
* **NJH**: This flag excludes junctions, hard links, and reparse points from consideration. This way, the command focuses on the regular files in the specified folders.
* **NJS**: This flag excludes symbolic links from the process.
* **NP**: This flag excludes folder timestamps.
* **NS**: This flag excludes file security information.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
##  Compare Folders With WinMerge

 If you want more details about the differences in your folders, Windows doesn't have a built-in tool to help you with that. However, you can use a free third-party app called WinMerge to compare multiple folders.

 To use it, launch a web browser on your PC, head to the [WinMerge](https://winmerge.org/downloads/?lang=en) site, and download and install the app. Make sure to download the app’s executable and not the ZIP version.

 Open the WinMerge app, then select File > Open in the Menu Bar or press Ctrl+O.

![File > Open highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-folder-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 For the "1st File or Folder" field, select "Browse" and choose the first folder to compare.

!['Browse' highlighted for the '1st File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-add-first-folder-winmerge.jpg) 

 For the "2nd File or Folder" field, click the "Browse" button and choose the second folder to compare.

!['Browse' highlighted for the '2nd File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-add-second-folder-winmerge.jpg) 

 In both fields, enable the "Read-Only" option. Click the "Folder: Filter" field and type **\*.\*** if it isn’t already there. This ensures the app compares all the files in both the specified folders. Then, at the bottom, click "Compare."

![Various comparison options highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-configure-comparison-options-winmerge.jpg) 

 On the following screen, you’ll see the comparison of the specified folders. You’ll see information like identical files in both folders, files missing from one folder, and so on.

![The comparison of two folders in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-folder-comparison-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's how you know what one folder has that another doesn't. This can be really useful if you're trying to quickly compare different versions of the same folder, like you'd have when you[create a backup](https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-14-pro-max-if-youve-tried-everything-by-drfone-ios/).

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
<li><a href="https://video-screen-grab.techidaily.com/new-castcritique-report-for-2024/"><u>[New] CastCritique Report for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-expert-strategies-for-choosing-valheim-crops-for-2024/"><u>[New] Expert Strategies for Choosing Valheim Crops for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ain-more-views-beginners-guide-to-youtube-seo-for-2024/"><u>[New] Gain More Views  Beginner’s Guide to YouTube SEO for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ultimate-win10-screen-and-video-recording-tool/"><u>[New] Ultimate Win10 Screen & Video Recording Tool</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtubes-payment-system-a-monthly-breakdown/"><u>[Updated] YouTube’s Payment System  A Monthly Breakdown</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1149-off-shop-the-newly-discounted-m3-macbook-air-laptop-16gb-memory-and-13-inch-screen/"><u>$1,149 OFF! Shop the Newly Discounted M3 MacBook Air Laptop - 16GB Memory & 13-Inch Screen</u></a></li>
<li><a href="https://win-blog.techidaily.com/age-of-empires-4-playthrough-perfected-a-comprehensive-guide-to-resolving-in-game-stutters/"><u>Age of Empires 4 Playthrough Perfected: A Comprehensive Guide to Resolving In-Game Stutters</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypass-the-hurdle-5-proven-methods-when-zoom-starts-up-without-video/"><u>Bypass the Hurdle: 5 Proven Methods When Zoom Starts Up Without Video</u></a></li>
<li><a href="https://win-blog.techidaily.com/centipede-bug-in-destiny-2-heres-how-to-resolve-the-game-glitch-successfully/"><u>Centipede Bug in Destiny 2? Here's How to Resolve the Game Glitch Successfully</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723011127680-continuous-youtube-audios-intermittent-videos-fix-playback-hiccups-on-chrome-and-firefox/"><u>Continuous YouTube Audios, Intermittent Videos? Fix Playback Hiccups on Chrome and Firefox</u></a></li>
<li><a href="https://win-blog.techidaily.com/diy-repairing-directx-errors-in-ea-sports-fifa-20-a-comprehensive-fix-guide/"><u>DIY: Repairing DirectX Errors in EA Sports' FIFA 20 - A Comprehensive Fix Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effective-solutions-for-correcting-issues-in-realteks-rtl8723be-device-drivers/"><u>Effective Solutions for Correcting Issues in Realtek's RTL8723BE Device Drivers</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-fixing-persistent-lagging-in-the-dying-light-gaming-experience/"><u>Expert Advice: Fixing Persistent Lagging in the Dying Light Gaming Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-for-dragon-age-origins-stability-problems-on-windows-11-released/"><u>Fix for 'Dragon Age: Origins' Stability Problems on Windows 11 Released</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-cyberpunk-2077-gpu-handling-issues-on-your-windows/"><u>Fixing Cyberpunk 2077 GPU Handling Issues on Your Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-total-war-warhammer-ii-stability-problems-solutions-and-tips/"><u>Fixing Total War: Warhammer II Stability Problems - Solutions & Tips</u></a></li>
<li><a href="https://win-blog.techidaily.com/ghostrunner-malfunction-in-windows-10-causes-and-solutions-revealed/"><u>Ghostrunner Malfunction in Windows 10: Causes and Solutions Revealed</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-preventing-granblue-fantasy-from-crashing-when-re-linking-on-your-desktop/"><u>Guide: Preventing Granblue Fantasy From Crashing When Re-Linking on Your Desktop</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-infinix-note-30i-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Infinix Note 30i phone? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-resident-evil-4-reboot-from-freezing-and-crashing/"><u>How to Stop Resident Evil 4 Reboot From Freezing and Crashing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/mouse-conundrum-solutions-for-gamers-playing-resident-evil-village/"><u>Mouse Conundrum Solutions for Gamers Playing Resident Evil Village</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-startup-difficulties-for-armored-core-vi-fires-of-rubicon-on-pc-or-console/"><u>Overcoming Startup Difficulties for Armored Core VI: Fires of Rubicon on PC or Console</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-dota-2-fixes-stuck-at-launch-issue/"><u>Resolved: Dota 2 Fixes 'Stuck at Launch' Issue</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-how-to-fix-battlefield-v-crashes-on-your-computer/"><u>Resolved: How to Fix Battlefield V Crashes on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-geforce-experience-errors-a-complete-guide/"><u>Resolving GeForce Experience Errors: A Complete Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-guide-addressing-non-functional-msi-mystic-light-devices-under-windows/"><u>Solution Guide: Addressing Non-Functional MSI Mystic Light Devices Under Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-guide-overcoming-launch-problems-in-team-fortress-2/"><u>Solution Guide: Overcoming Launch Problems in Team Fortress 2</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-monster-hunter-rise-wont-start-issue-a-step-by-step-fix/"><u>Solving Monster Hunter Rise Won't Start Issue: A Step-by-Step Fix</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-stability-problems-with-classic-chinese-rpg-sword-of-virtue-7-for-pc-users/"><u>Solving Stability Problems with Classic Chinese RPG, 'Sword of Virtue 7' For PC Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-the-problem-of-non-launchable-star-wars-jedi-fallen-order/"><u>Solving the Problem of Non-Launchable Star Wars Jedi: Fallen Order</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-wwe-2k20s-stability-issues-on-your-computer-effortlessly/"><u>Solving WWE 2K20's Stability Issues on Your Computer Effortlessly</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-10-affordable-video-chat-for-android-users/"><u>Top 10 Affordable Video Chat for Android Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-for-resolving-google-chrome-not-opening-problems/"><u>Troubleshooting Guide for Resolving Google Chrome Not Opening Problems</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-how-to-fix-the-issue-with-robocop-rogue-city-failure-to-start-on-windows/"><u>Troubleshooting Steps: How to Fix the Issue with 'Robocop: Rogue City' Failure to Start on Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723002416772-unstick-your-stuck-genshin-game-5-easy-remedies-for-quick-playtime/"><u>Unstick Your Stuck Genshin Game: 5 Easy Remedies for Quick Playtime</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-music-blend-fundamentals-for-2024/"><u>YouTube Music Blend Fundamentals for 2024</u></a></li>
</ul></div>
