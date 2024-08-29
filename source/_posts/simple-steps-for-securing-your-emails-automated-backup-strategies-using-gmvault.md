---
title: "Simple Steps for Securing Your Emails: Automated Backup Strategies Using GMVault"
date: 2024-08-28T05:42:29.405Z
updated: 2024-08-29T05:42:29.405Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/99d21901c046ee167dc651651f4c0a4a5fcaa0180bc67e42c2265df29bcc90c2.png
---

## Simple Steps for Securing Your Emails: Automated Backup Strategies Using GMVault

### Quick Links

* [Gmail Setup](https://facebook-video-content.techidaily.com/new-discover-the-top-6-fb-lite-video-export-apps-of-2023/)
* [GMVault Setup](https://smart-video-editing.techidaily.com/new-2024-approved-discover-the-best-8-windows-10-photos-alternatives/)
* [Updating and Restoring Backups](https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/)
* [Creating a Scheduled Backup](https://iphone-unlock.techidaily.com/how-to-unlock-a-found-iphone-13-pro-max-drfone-by-drfone-ios/)

 We all know [backups are important](https://extra-guidance.techidaily.com/iphone-tricks-adjusting-picture-size-efficiently-for-2024/), but we rarely think about backing up our email. [GMVault](http://gmvault.org/) can automatically back up your Gmail to your computer and even restore the emails to another Gmail account -- convenient when switching Gmail addresses.

 We've also covered [using Thunderbird to back up your web-based email account](https://some-skills.techidaily.com/in-2024-the-bottom-line-how-much-do-podcasters-take-home/), but GMVault has a few advantages, including its integrated restore function and easy integration with the Windows Task Scheduler.

##  Gmail Setup

 You'll have to change a few settings in Gmail before you begin. First, on the Forwarding and POP/IMAP tab in your Gmail account's settings page, ensure IMAP is enabled.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image262.png) 

 On the Labels pane, ensure the all labels are set to Show in IMAP. Any labels that aren't visible in IMAP won't be backed up.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image263.png) 

##  GMVault Setup

 Download and install GMVault from [GMVault's website](http://gmvault.org/download.html). Once it's installed, you can launch GMVault from the gmvault-shell shortcut on your desktop or Start menu.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image264.png) 

 GMVault doesn't provide a graphical user interface, but using it is easy.

 To start syncing an account's emails to your computer, type the following command into the GMVault window, where account@gmail.com is your Gmail account address:

> gmvault sync account@gmail.com

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image265.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
 Ensure you're logged into the Gmail account you specified in your default browser and press Enter.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image266.png) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 GMVault will request an [OAuth token](https://video-screen-grab.techidaily.com/new-simplified-steps-to-documenting-fb-chats-and-calls/) \-- click the Grant access button to continue and allow GMVault access to your email account.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image267.png) 

 Go back to the GMVault window, press Enter, and GMVault will automatically back up your emails to your computer.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image268.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
##  Updating and Restoring Backups

 To update your backup in the future, just run the same command again:

> gmvault sync account@gmail.com

 You can also use the -t quick option -- when you use this option, GMVault will only check for new emails, deletions, or changes from the past week. This makes performing a backup much faster.

> gmvault sync -t quick account@gmail.com

 If you want to restore your Gmail to another Gmail account in the future, run the following command:

> gmvault restore newaccount@gmail.com

 Your authentication credentials are stored in the C:\\Users\\NAME\\.gmvault folder, while your email backups are stored in the C:\\Users\\NAME\\gmvault-db folder. You can back up the gmvault-db folder to create another backup of your emails.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image269.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
##  Creating a Scheduled Backup

 You can now run the above commands to quickly update your backup. However, if you want to perform regular backups without thinking about it, you can [create a scheduled task](https://fox-direct.techidaily.com/updated-banish-the-chaos-strategies-to-refine-overwhelming-tiktok-drafts/) that automatically backs up your email.

 First, open the Task Scheduler by typing Task Scheduler into your Start menu and pressing Enter.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/08/image395.png) 

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click the Create Basic Task link at the right side of the window.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/08/image396.png) 

 Name your task and set the trigger to Daily.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image270.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 Set the task to run every one days or every few days, whichever you like.

 (Note that GMVault's -t quick option only checks the previous week of email by default, so you'll want to have this task run at least once a week.)

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image271.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 On the Action pane, select Start a Program and navigate to the gmvault.bat file. By default, this file is installed to the following location:

> C:\\Users\\NAME\\AppData\\Local\\gmvault\\gmvault.bat

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image272.png) 

 In the Add arguments box, add the following arguments, replacing account@gmail.com with your Gmail address:

> sync -t quick account@gmail.com

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image273.png) 

 To verify that your scheduled task is working properly, you can right-click it in the Task Scheduler window and select Run. The GMVault window will appear and perform a backup.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2012/09/image274.png) 

---

 GMVault will now automatically update your back up with new emails and changes on the schedule you specified. If you want to be sure no emails or other changes are missed, you can run a full backup command (without the -t quick option) occasionally.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-android-options-10-gb-emulation-tools-for-2024/"><u>[New] Best Android Options  10 GB Emulation Tools for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sony-s6700-updated-summary-unpacked/"><u>[New] Sony S6700 Updated Summary Unpacked</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-the-eraser-guru-expert-tips-for-psx-users/"><u>[New] The Eraser Guru  Expert Tips for PSX Users</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-accelerated-sound-adjustment-apps-overview/"><u>[Updated] In 2024, Accelerated Sound Adjustment Apps Overview</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-seamless-tiktok-integration-on-your-macbook/"><u>[Updated] Seamless TikTok Integration on Your MacBook</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-5-android-emulators-for-playstation-2-gaming-for-2024/"><u>[Updated] Top 5 Android Emulators for PlayStation 2 Gaming for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-y36i-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/banish-bugs-and-boost-performance-proven-strategies-to-address-how4-stability-problems/"><u>Banish Bugs & Boost Performance: Proven Strategies to Address HOW4 Stability Problems</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/brain-benders-await-at-the-best-room-sanctuaries/"><u>Brain Benders Await at the Best Room Sanctuaries</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-to-fix-davinci-resolve-not-launching-properly-on-windows-systems/"><u>Effective Solutions to Fix DaVinci Resolve Not Launching Properly on Windows Systems</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhancing-picture-quality-fixes-for-hazy-imagery-in-outriders/"><u>Enhancing Picture Quality: Fixes for Hazy Imagery in Outriders</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-swagtrons-chic-and-modern-electric-commuting-scooter/"><u>Evaluating Swagtron’s Chic and Modern Electric Commuting Scooter</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-to-eliminate-stutter-and-freezing-in-your-deathloop-adventures-on-pc-and-ps5/"><u>Expert Tips to Eliminate Stutter & Freezing in Your Deathloop Adventures on PC and PS5</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/future-visions-10-sci-fi-metaverse-movies-explore-worlds-anew-for-2024/"><u>Future Visions  10 Sci-Fi Metaverse Movies Explore Worlds Anew for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-preventing-granblue-fantasy-from-crashing-when-re-linking-on-your-desktop/"><u>Guide: Preventing Granblue Fantasy From Crashing When Re-Linking on Your Desktop</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-sony-xperia-10-v-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Sony Xperia 10 V to Protect Your Individual Information</u></a></li>
<li><a href="https://extra-resources.techidaily.com/inside-the-innovative-world-of-intova-x/"><u>Inside the Innovative World of Intova X</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/live-video-logging-on-mac-free-in-2024/"><u>Live Video Logging on Mac, Free, In 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/mouse-conundrum-solutions-for-gamers-playing-resident-evil-village/"><u>Mouse Conundrum Solutions for Gamers Playing Resident Evil Village</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimize-your-ark-survival-fps-experience-on-computer-with-expert-advice/"><u>Optimize Your ARK Survival FPS Experience on Computer with Expert Advice</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-delays-and-stuttering-an-ultimate-fix-for-outriders-console-issues/"><u>Overcoming Delays and Stuttering - An Ultimate Fix for Outriders Console Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolve-frame-drops-in-splitgate-strategies-for-smoother-gameplay-performance/"><u>Resolve Frame Drops in Splitgate: Strategies for Smoother Gameplay Performance</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-fixes-made-to-overcome-maplestory-launch-issues/"><u>Resolved: Fixes Made to Overcome MapleStory Launch Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723001317992-sea-of-thieves-wont-open-heres-what-you-can-do/"><u>Sea of Thieves Won't Open? Here's What You Can Do!</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-guide-overcoming-launch-problems-in-team-fortress-2/"><u>Solution Guide: Overcoming Launch Problems in Team Fortress 2</u></a></li>
<li><a href="https://win-blog.techidaily.com/solve-your-epic-games-launcher-problem-in-minutes-a-simple-guide/"><u>Solve Your Epic Games Launcher Problem in Minutes - A Simple Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/stop-pc-freezes-in-hyper-scape-with-these-simple-tips/"><u>Stop PC Freezes in Hyper Scape With These Simple Tips</u></a></li>
<li><a href="https://win-blog.techidaily.com/stop-the-rampant-pc-issues-expert-fixes-for-euro-truck-simulator-2-crashes/"><u>Stop the Rampant PC Issues: Expert Fixes for Euro Truck Simulator 2 Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/the-ultimate-guide-to-resolve-continuous-loading-on-minecraft/"><u>The Ultimate Guide to Resolve Continuous Loading on Minecraft</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-preventing-rainbow-six-extraction-pc-game-crashes/"><u>Troubleshooting Tips for Preventing Rainbow Six Extraction PC Game Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723002416772-unstick-your-stuck-genshin-game-5-easy-remedies-for-quick-playtime/"><u>Unstick Your Stuck Genshin Game: 5 Easy Remedies for Quick Playtime</u></a></li>
<li><a href="https://win-blog.techidaily.com/warcraft-3-reforged-and-pc-compatibility-overcome-crashing-issues-in-the-latest-update-tips-users/"><u>Warcraft 3 Reforged and PC Compatibility: Overcome Crashing Issues in the Latest Update (Tips Users)</u></a></li>
</ul></div>
