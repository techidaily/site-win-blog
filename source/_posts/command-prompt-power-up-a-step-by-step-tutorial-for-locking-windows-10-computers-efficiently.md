---
title: "Command Prompt Power-Up: A Step-by-Step Tutorial for Locking Windows 10 Computers Efficiently"
date: 2024-08-28T05:40:36.363Z
updated: 2024-08-29T05:40:36.363Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6037bb9c2891cc5de7a061886dcf26fb2fd27c5d5408d3641e03d7db63a65dce.jpg
---

## Command Prompt Power-Up: A Step-by-Step Tutorial for Locking Windows 10 Computers Efficiently

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-how-to-record-whatsapp-call/"><u>[Updated] 2024 Approved  How to Record WhatsApp Call</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-top-eight-video-recording-apps/"><u>[Updated] 2024 Approved  Top Eight Video Recording Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-cost-effective-video-enhancement-vimeo-edition-for-2024/"><u>[Updated] Cost-Effective Video Enhancement  Vimeo Edition for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-step-by-step-from-twitter-videosyoutube-songs-to-scribbled-mp3-files/"><u>[Updated] Step-by-Step  From Twitter Videos/YouTube Songs to Scribbled MP3 Files</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-unraveling-the-mystery-of-frame-rates-in-videos/"><u>2024 Approved  Unraveling the Mystery of Frame Rates in Videos</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/achieve-optimal-graphics-a-comprehensive-walkthrough-of-updating-ati-radeon-drivers-on-windows-pcs/"><u>Achieve Optimal Graphics: A Comprehensive Walkthrough of Updating ATI Radeon Drivers on Windows PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/achieve-smooth-gameplay-fix-splitgates-performance-problems-with-these-proven-methods/"><u>Achieve Smooth Gameplay: Fix Splitgate's Performance Problems with These Proven Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/adrevenue-on-youtube-unpacked-average-income-from-1000-viewers-engagement-for-2024/"><u>AdRevenue on YouTube Unpacked  Average Income From 1,000 Viewers' Engagement for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-startup-problems-8-crucial-solutions-to-keep-hogwarts-legacy-runnning-smoothly/"><u>Beat Startup Problems: 8 Crucial Solutions to Keep Hogwarts Legacy Runnning Smoothly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/bluetooth-sync-how-to-connect-several-speakers-with-one-source/"><u>Bluetooth Sync: How to Connect Several Speakers with One Source</u></a></li>
<li><a href="https://win-blog.techidaily.com/boost-your-warzone-performance-with-graphics-card-utilization-in-windows-10/"><u>Boost Your Warzone Performance with Graphics Card Utilization in Windows 10</u></a></li>
<li><a href="https://win-blog.techidaily.com/discover-effective-techniques-to-lower-discord-cpu-usage-guide/"><u>Discover Effective Techniques to Lower Discord CPU Usage (Guide)</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-for-resolving-the-2024-starfield-games-excessive-cpu-consumption/"><u>Effective Solutions for Resolving the 2024 Starfield Game's Excessive CPU Consumption</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722986080955-effortless-fixes-for-when-fortnite-wont-launch-get-back-to-gaming/"><u>Effortless Fixes for When Fortnite Won't Launch – Get Back to Gaming!</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722987081941-enhanced-gaming-experience-no-more-stuttering-in-starfield/"><u>Enhanced Gaming Experience - No More Stuttering in Starfield!</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhanced-horizon-zero-dawn-optimized-frame-rate-and-improved-gameplay-efficiency/"><u>Enhanced Horizon Zero Dawn: Optimized Frame Rate & Improved Gameplay Efficiency</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-your-game-eliminate-fps-drop-stutter-and-overcome-gaming-lag/"><u>Fix Your Game: Eliminate FPS Drop, Stutter, and Overcome Gaming Lag</u></a></li>
<li><a href="https://win-blog.techidaily.com/get-back-into-the-action-quick-fixes-for-modern-warfare-2-not-starting-properly/"><u>Get Back Into the Action: Quick Fixes for Modern Warfare 2 Not Starting Properly</u></a></li>
<li><a href="https://win-blog.techidaily.com/hitman-navigating-and-resolving-the-infamous-connection-error/"><u>Hitman Navigating and Resolving the Infamous Connection Error</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-and-prevent-input-lag-issues-in-valorant-april-2024/"><u>How to Fix and Prevent Input Lag Issues in Valorant - April 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-warframe-lag-and-unfreeze-your-game-a-step-by-step-guide/"><u>How to Fix Warframe Lag and Unfreeze Your Game: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-restore-the-windows-11-taskbar-when-it-stops-working/"><u>How to Restore the Windows 11 Taskbar When It Stops Working</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-solve-the-issue-when-gta-5-doesnt-open/"><u>How to Solve the Issue When GTA 5 Doesn't Open</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722991320772-hp-visuals-gone-wrong-discover-how-to-fix-your-screen-problems-here/"><u>HP Visuals Gone Wrong? Discover How To Fix Your Screen Problems Here</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-much-money-can-a-podcaster-make/"><u>In 2024, How Much Money Can a Podcaster Make?</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-game-performance-how-to-prevent-days-gone-from-crashing/"><u>Mastering Game Performance: How to Prevent 'Days Gone' From Crashing</u></a></li>
<li><a href="https://win-blog.techidaily.com/navigate-through-pc-game-lags-in-resident-evil-village-expert-solutions-for-smooth-play/"><u>Navigate Through PC Game Lags in Resident Evil Village - Expert Solutions for Smooth Play</u></a></li>
<li><a href="https://win-blog.techidaily.com/no-more-crashes-rapid-remedies-for-the-origin-application-issue/"><u>No More Crashes: Rapid Remedies for the 'Origin' Application Issue!</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-launch-obstacles-in-evil-genius-2-expert-advice/"><u>Overcoming Launch Obstacles in Evil Genius 2: Expert Advice</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723006434090-overcoming-performance-hitches-for-a-smoother-playthrough-of-dying-light-fps/"><u>Overcoming Performance Hitches for a Smoother Playthrough of Dying Light FPS.</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-the-centipede-glitch-in-destiny-2-complete-guide/"><u>Overcoming the 'Centipede' Glitch in Destiny 2 - Complete Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/quick-and-simple-troubleshooting-for-continuous-system-errors-master-the-art/"><u>Quick & Simple Troubleshooting for Continuous System Errors: Master the Art!</u></a></li>
<li><a href="https://win-blog.techidaily.com/quick-solution-dayz-fps-drop-problem-solved-with-ease/"><u>Quick Solution: DayZ FPS Drop Problem Solved with Ease</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723005215563-resolve-league-of-legends-crashes-swiftly-a-step-by-step-guide/"><u>Resolve League of Legends Crashes Swiftly: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-chrome-stuck-issues-on-windows-10-tips-and-tricks/"><u>Resolving Chrome Stuck Issues on Windows 10 - Tips & Tricks</u></a></li>
<li><a href="https://fox-that.techidaily.com/revive-your-ios-devices-emoji-predictions-with-these-7-swift-strategies/"><u>Revive Your iOS Device's Emoji Predictions with These 7 Swift Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-engagement-showdown-twitter-instagram-facebook-against-youtube-giant/"><u>Social Engagement Showdown: Twitter, Instagram, Facebook Against YouTube Giant</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722999465504-steam-vr-detection-problems-try-these-6-tricks-to-get-it-working/"><u>Steam VR Detection Problems? Try These 6 Tricks to Get It Working</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-download-of-amd-ryzen-r5-2600-chipset-drivers/"><u>Step-by-Step Download of AMD Ryzen R5 2600 Chipset Drivers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-6-recommended-websites-offering-complimentary-childrens-films/"><u>Top 6 Recommended Websites Offering Complimentary Children's Films</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-red-dead-redemption-abortionerror-errgfxstate-for-an-uninterrupted-gaming-experience/"><u>Troubleshooting Red Dead Redemption abortionError (ERR_GFX_STATE) for an Uninterrupted Gaming Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-resolving-forza-horizon-5-crashes-on-your-windows-computer/"><u>Troubleshooting Tips: Resolving 'Forza Horizon 5' Crashes on Your Windows Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-fixes-to-bypass-the-notorious-0x00001338-bug-in-call-of-duty-vanguard-on-your-computer/"><u>Ultimate Fixes to Bypass the Notorious 0X00001338 Bug in Call of Duty Vanguard on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-solve-steams-2024-black-screen-and-load-issues-in-just-7-steps/"><u>Ultimate Guide: Solve Steam's 2024 Black Screen & Load Issues in Just 7 Steps</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-solutions-how-to-prevent-mass-effect-legendary-edition-from-freezing-on-pc-and-xbox-systems/"><u>Ultimate Solutions: How to Prevent Mass Effect Legendary Edition From Freezing on PC & Xbox Systems</u></a></li>
<li><a href="https://win-blog.techidaily.com/untangling-pc-instability-for-robocop-rupture-city-essential-troubleshooting-steps/"><u>Untangling PC Instability for 'RoboCop: Rupture City': Essential Troubleshooting Steps</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-mkvtoolnix-for-macos-a-user-friendly-video-editing-solution/"><u>Updated MKVtoolnix for macOS A User-Friendly Video Editing Solution</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-modern-warfare-wont-start-pc-launch-solutions-gamers/"><u>Why Modern Warfare Won't Start? PC Launch Solutions Gamers</u></a></li>
</ul></div>
