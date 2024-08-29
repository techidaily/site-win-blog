---
title: "Step-by-Step Guide: Calculating Distinct Data Points with Microsoft Excel"
date: 2024-08-28T05:42:33.024Z
updated: 2024-08-29T05:42:33.024Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e082df8e991a0ed032e389702a1a1fbbc04b4810305a265213fc94683f22a3e9.jpg
---

## Step-by-Step Guide: Calculating Distinct Data Points with Microsoft Excel

### Quick Links

* [Use the COUNTA and UNIQUE Functions](https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/)
* [Use the SUM and COUNTIF Functions](https://tech-revival.techidaily.com/synthesizing-visuals-seamlessly-gpt-4-meets-dall-e-techniques/)

 You can use the COUNT function and variations to count cells that contain numbers. But what if you want to count only the distinct values in a cell range? We'll show you two ways to count unique values in Excel.

 Both methods we'll explain use a combination of functions and variations of [the COUNT function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/). And because your cell range could include blank cells, we're including alternative formulas to account for this.

Related: [How to Use the COUNT Function in Microsoft Excel](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) 

##  Use the COUNTA and UNIQUE Functions

 This first method is for those who use Excel for [Microsoft 365](https://games-able.techidaily.com/ultimate-console-content-psplus-or-xbox-game-pass/), Excel for the web, Excel 2021, or Excel for iPhone, iPad, or Android phones or tablets. This is because the UNIQUE function is only available in these and later versions of Excel.

 The UNIQUE function provides all distinct values in a cell range. Because you don't want to list those unique values, but count them instead, you'll add the COUNTA function. The COUNTA function [counts nonblank cells](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/).

 To list the unique values in the cell range A2 through A5, you would use this formula:

=UNIQUE(A2:A5)

 You can see here we have three distinct values listed.

![UNIQUE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UniqueFunction-ExcelCountUnique.png) 

 To count those unique values instead of listing them, you add the COUNTA function to the beginning of the formula:

=COUNTA(UNIQUE(A2:A5))

 Now you have the count for those unique values which is 3.

![COUNTA with UNIQUE in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFunctions-ExcelCountUnique.png) 

 If the cell range you want to count contains blanks, those will be included as unique values which may cause a problem. To exclude blank cells in your range, you can add the FILTER function to the formula:

 The FILTER function is only available in the versions of Excel listed [above](https://extra-approaches.techidaily.com/updated-prime-10-converters-free-apps-for-efficient-srt-file-transformations/).

=COUNTA(UNIQUE(FILTER(A2:A5,A2:A5<>"")))

 Let's break down the FILTER portion of the formula. `A2:A5,A2:A5` represents the cell range and the criteria to filter which are the same, `<>` represents not equal to, and `""` represents blank.

 As you can see in the screenshot below, the blank cell in our array is not counted as a unique value.

![COUNTA, UNIQUE, and FILTER functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFilterFunctions-ExcelCountUnique.png) 

Related: [How to Count Cells in Microsoft Excel](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) 

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Use the SUM and COUNTIF Functions

 If you're using a version of Excel where the UNIQUE and FILTER functions are unavailable, you can use SUM and [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) instead.

 You may also use the same formulas below replacing the SUM function with SUMPRODUCT.

 The [SUM function](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) adds numbers and the COUNTIF function counts those cells containing numbers that meet specific criteria.

 To find the unique values in the cell range A2 through A5, use the following formula:

=SUM(1/COUNTIF(A2:A5,A2:A5))

 To break down this formula, the `COUNTIF` function counts the cells with numbers in our range and uses that same cell range as the criteria. That result then is [divided](https://facebook-video-share.techidaily.com/new-in-2024-breaking-through-youtubes-walls-using-advanced-creator-studio-skills/) by `1` and the `SUM` function adds the remaining values.

![SUM and COUNTIF functions in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctions-ExcelCountUnique.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Similar to the first method, you can run into issues if you have blanks in your cell range with this method. Only, you'll receive the #DIV/0![error](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) rather than an extra unique value.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To eliminate this problem, you can use the following formula:

=SUM((A2:A5<>"")/COUNTIF(A2:A5,A2:A5&""))

 The additional portion for the `COUNTIF` function [concatenates](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) a blank string to prevent zeroes in the results because you cannot divide by zero. The additional portion for the `SUM` function adds the values that do not equal blank. All of this provides the count of distinct values and also does not count blanks as unique.

![SUM and COUNTIF filtered](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctionsFiltered-ExcelCountUnique.png) 

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
 Finding unique values in Excel doesn't have to be a difficult task. By using the [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) here, you should see those distinct values in no time!

Related: [Functions vs. Formulas in Microsoft Excel: What's the Difference?](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/)

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
<li><a href="https://win-blog.techidaily.com/among-us-gaming-perfection-your-ultimate-guide-to-avoid-crashes-and-glitches-2veled-by-experts-for-gamers/"><u>'Among Us' Gaming Perfection: Your Ultimate Guide to Avoid Crashes & Glitches - 2Veled by Experts for Gamers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-premium-youtube-insights-everything-you-must-know/"><u>[New] 2024 Approved  Premium YouTube Insights  Everything You Must Know</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-scrutinizing-hero5s-performance-throughout-day/"><u>[New] Scrutinizing Hero5's Performance Throughout Day</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-fixing-overencoded-obs-videos/"><u>[Updated] 2024 Approved  Fixing Overencoded OBS Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-stock-photos-free-flawless-and-legal-for-2024/"><u>[Updated] Navigating Stock Photos  Free, Flawless, and Legal for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-the-blues-comprehensive-solutions-for-stable-fifa-21-gameplay-on-pc/"><u>Beat the Blues: Comprehensive Solutions for Stable FIFA 21 Gameplay on PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mov-files-on-galaxy-s23-fe-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't play .mov files on Galaxy S23 FE</u></a></li>
<li><a href="https://win-blog.techidaily.com/civilization-vi-wont-start-fix-your-game-with-these-tips-for-windows-10-users/"><u>Civilization VI Wont Start? Fix Your Game with These Tips for Windows 10 Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/dealing-with-unexpected-closures-of-geforce-experience-expert-tips-on-error-diagnosis-and-fixes-for-enthusiast-gamers/"><u>Dealing with Unexpected Closures of GeForce Experience: Expert Tips on Error Diagnosis and Fixes for Enthusiast Gamers</u></a></li>
<li><a href="https://win-blog.techidaily.com/direct-x-errors-on-fifa-20-solutions-for-a-seamless-experience/"><u>DIRECT X Errors on FIFA 20: Solutions for a Seamless Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722998832947-elden-ring-players-rejoice-multiplayer-feature-fixed/"><u>Elden Ring Players Rejoice: Multiplayer Feature Fixed</u></a></li>
<li><a href="https://win-blog.techidaily.com/end-the-steam-error-woes-unlocking-tips-for-content-file-roadblocks/"><u>End the Steam Error Woes: Unlocking Tips for Content File Roadblocks</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhanced-performance-tweaks-overcoming-pc-lag-challenges-in-the-latest-yakuza-3-version/"><u>Enhanced Performance Tweaks: Overcoming PC Lag Challenges in the Latest Yakuza 3 Version</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/essential-tags-for-tiktok-fame-and-viral-potential-for-2024/"><u>Essential Tags for TikTok Fame and Viral Potential for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-to-resolve-the-notorious-ntdlldll-file-crash-problem-on-pcs-with-win11win10/"><u>Expert Advice to Resolve the Notorious ntdll.dll File Crash Problem on PCs with Win11/Win10</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-to-prevent-and-fix-microsoft-edge-crashing-on-your-windows-11-device/"><u>Expert Tips to Prevent and Fix Microsoft Edge Crashing on Your Windows 11 Device</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-steams-frequent-crashes-instantly-a-simple-step-by-step-guide/"><u>Fix Steam's Frequent Crashes Instantly: A Simple Step-by-Step Guide!</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-true-colors-crash-in-life-is-strange-the-complete-solution-walkthrough/"><u>Fixing 'True Colors' Crash in Life Is Strange – The Complete Solution Walkthrough</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/get-rid-of-filmora-watermark-with-or-without-subscription-for-2024/"><u>Get Rid of Filmora Watermark With or Without Subscription for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/getting-civilization-6-running-again-in-windows-10-a-step-by-step-guide-to-solving-launch-errors/"><u>Getting Civilization 6 Running Again in Windows 10 – A Step-by-Step Guide to Solving Launch Errors</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-samsung-galaxy-m14-4g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-darkest-dungeon-2-from-crashing-frequently-pc-solved/"><u>How to Stop Darkest Dungeon 2 From Crashing Frequently (PC) - Solved!</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-your-frostpunk-game-from-unexpectedly-crashing/"><u>How to Stop Your Frostpunk Game From Unexpectedly Crashing</u></a></li>
<li><a href="https://apple-account.techidaily.com/icloud-separation-how-to-disconnect-apple-iphone-6s-and-ipad-by-drfone-ios/"><u>iCloud Separation How To Disconnect Apple iPhone 6s and iPad</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-oppo-a38-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Oppo A38</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-pc-builds-with-expert-advice-from-toms-system-solutions/"><u>Navigating PC Builds with Expert Advice From Tom's System Solutions</u></a></li>
<li><a href="https://win-blog.techidaily.com/new-realm-persistent-frosts-and-chilling-dilemmas-how-to-address-them/"><u>New Realm: Persistent Frosts and Chilling Dilemmas - How to Address Them?</u></a></li>
<li><a href="https://win-blog.techidaily.com/nvidia-geforce-trouble-your-ultimate-guide-for-correcting-code-0x0003/"><u>NVIDIA GeForce Trouble? Your Ultimate Guide for Correcting Code 0X0003</u></a></li>
<li><a href="https://solve-info.techidaily.com/optimized-with-automated-tracker-discover-the-power-of-cookiebot/"><u>Optimized with Automated Tracker: Discover the Power of Cookiebot</u></a></li>
<li><a href="https://win-blog.techidaily.com/overwatch-graphic-glitch-fixed-enhanced-gaming-experience-with-updated-drivers/"><u>Overwatch Graphic Glitch Fixed: Enhanced Gaming Experience with Updated Drivers</u></a></li>
<li><a href="https://win-blog.techidaily.com/preventing-star-wars-battlefront-ii-from-crashing-on-your-computer-solutions-inside/"><u>Preventing Star Wars Battlefront II From Crashing on Your Computer - Solutions Inside!</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-issue-preventing-left-4-dead-2-from-crashing-on-your-pc/"><u>Resolved Issue: Preventing Left 4 Dead 2 From Crashing on Your PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-issues-preventing-fifa-21-from-starting/"><u>Resolved: Issues Preventing FIFA 21 From Starting</u></a></li>
<li><a href="https://win-blog.techidaily.com/restore-sound-in-evil-genius-2-a-step-by-step-guide-for-gamers/"><u>Restore Sound in 'Evil Genius 2': A Step-by-Step Guide for Gamers</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-frozen-pages-easy-steps-to-prevent-chrome-crashes-on-windows-11/"><u>Say Goodbye to Frozen Pages: Easy Steps to Prevent Chrome Crashes on Windows 11</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-honor-x50iplus-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Honor X50i+</u></a></li>
<li><a href="https://win-blog.techidaily.com/solve-your-sea-of-thieves-stuck-on-launch-dilemma-today/"><u>Solve Your Sea of Thieves Stuck on Launch Dilemma Today</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-splitgate-lags-tips-to-improve-frame-rate-and-eliminate-stutter/"><u>Solving Splitgate Lags: Tips to Improve Frame Rate and Eliminate Stutter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722996261757-the-mystery-behind-immortals-fenyx-risings-postponement-is-finally-solved/"><u>The Mystery Behind Immortals: Fenyx Rising's Postponement Is Finally Solved!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-expert-hardware-reviews/"><u>Tom's Tech Insights: Expert Hardware Reviews</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-drops-in-frames-per-second-fps-during-f1-2021-on-pc-gaming/"><u>Troubleshooting Drops in Frames Per Second (FPS) During F1 2021 on PC Gaming</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-failed-game-starts-by-verifying-integrity-of-game-data/"><u>Troubleshooting Failed Game Starts by Verifying Integrity of Game Data</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-troubleshooting-keeping-your-pcs-palworld-game-from-crashing/"><u>Ultimate Troubleshooting: Keeping Your PC's PalWorld Game From Crashing</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlock-your-palworld-eos-account-a-guide-to-resolving-the-notorious-login-failure-with-6-key-fixes/"><u>Unlock Your Palworld EOS Account: A Guide to Resolving the Notorious Login Failure with 6 Key Fixes</u></a></li>
<li><a href="https://techidaily.com/vivo-data-retrieval-tool-restore-lost-data-from-vivo-y77t-by-fonelab-android-recover-data/"><u>Vivo Data Retrieval tool – restore lost data from Vivo Y77t</u></a></li>
<li><a href="https://win-answers.techidaily.com/xbox-one-users-no-longer-face-issues-with-netflix-all-systems-go/"><u>Xbox One Users No Longer Face Issues with Netflix - All Systems Go</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-lava-yuva-2-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Lava Yuva 2 | Dr.fone</u></a></li>
</ul></div>
