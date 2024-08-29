---
title: The Ultimate Tutorial on Combining INDEX with MATCH in Excel Spreadsheets
date: 2024-08-28T05:43:08.958Z
updated: 2024-08-29T05:43:08.958Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## The Ultimate Tutorial on Combining INDEX with MATCH in Excel Spreadsheets

### Quick Links

* [VLOOKUP Versus INDEX and MATCH](https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-f54-5g-location-on-viber-drfone-by-drfone-virtual-android/)
* [INDEX and MATCH Function Basics](https://extra-support.techidaily.com/updated-premium-steadicam-options-for-high-quality-dslr-shoots/)
* [How to Use INDEX and MATCH in Excel](https://extra-approaches.techidaily.com/prime-gold-toned-text-interactive-3d-sites-reviewed-for-2024/)

 While the [VLOOKUP function](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) is good for finding values in Excel, it has its limitations. With a combination of the INDEX and MATCH functions instead, you can look up values in any location or direction in your spreadsheet.

 The INDEX function returns a value based on a location you enter in the formula while MATCH does the reverse and returns a location based on the value you enter. When you combine these functions, you can find any number or text you need.

##  VLOOKUP Versus INDEX and MATCH

 The difference between these functions and VLOOKUP is that VLOOKUP finds values from left to right. Hence the function's name; VLOOKUP performs a vertical lookup.

 Microsoft best explains [the way VLOOKUP works](https://support.microsoft.com/en-us/office/look-up-values-with-vlookup-index-or-match-68297403-7c3c-4150-9e3c-4d348188976b):

> There are certain limitations with using VLOOKUP---the VLOOKUP function can only look up a value from left to right. This means that the column containing the value you look up should always be located to the left of the column containing the return value.

 Microsoft goes on to say that if your sheet isn't set up in a way where VLOOKUP can help you find what you need, you can use INDEX and MATCH instead. So let's look at how to use INDEX and MATCH in Excel.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
##  INDEX and MATCH Function Basics

 To use these functions together, it's important to understand their purpose and structure.

 The syntax for INDEX in Array Form is

        `INDEX(array, row_number, column_number)`
    
 with the first two arguments required and the third optional.

 INDEX looks up a position and returns its value. To find the value in the fourth row in the cell range D2 through D8, you would enter the following formula:

=INDEX(D2:D8,4)

![INDEX function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEX-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 The result is 20,745 because that's the value in the fourth position of our cell range.

 For more details on the Array and Reference Forms of INDEX as well as other ways to use this function, take a look at our how-to for [INDEX in Excel](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/).

 The syntax for MATCH is `MATCH(value, array, match_type)` with the first two arguments required and the third optional.

 MATCH looks up a value and returns its position. To find the value in cell G2 in the range A2 through A8, you would enter the following formula:

=MATCH(G2,A2:A8)

![MATCH function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MATCH-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 The result is 4 because the value in cell G2 is in the fourth position in our cell range.

 For additional details on the `match_type` argument and other ways to use this function, take a look at our tutorial for [MATCH in Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/).

Related: [How to Find a Value's Position With MATCH in Microsoft Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use INDEX and MATCH in Excel

 Now that you know what each function does and its syntax, it's time to put this dynamic duo to work. Below, we'll use the same data as above for INDEX and MATCH individually.

 You'll place the formula for the MATCH function inside the formula of the INDEX function in place of the position to look up.

 To find the value (sales) based on the location ID, you would use this formula:

=INDEX(D2:D8,MATCH(G2,A2:A8))

 The result is 20,745\. MATCH finds the value in cell G2 within the range A2 through A8 and provides that to INDEX which looks to cells D2 through D8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG2-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Let's look at another example. We want to know which city has sales that match a certain amount. Using our sheet, you would enter this formula:

=INDEX(B2:B8,MATCH(G5,D2:D8))

 The result is Houston. MATCH finds the value in cell G5 within the range D2 through D8 and provides that to INDEX which looks to cells B2 through B8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG5-ExcelINDEXandMATCH.png) 

 Here's an example using an actual value instead of a cell reference. We'll look for the value (sales) for a specific city with this formula:

=INDEX(D2:D8,MATCH("Houston",B2:B8))

 In the MATCH formula, we replaced the cell reference containing the lookup value with the actual lookup value of "Houston" from B2 through B8 which gives us the result 20,745 from D2 through D8.

 Be sure when you use the actual value to look up, rather than a cell reference, that you enclose it in quotes as shown here.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHHouston-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 To obtain that same result by using the location ID instead of the city, we simply change the formula to this:

=INDEX(D2:D8,MATCH("2B",A2:A8))

 Here we changed the MATCH formula to look up "2B" in the cell range A2 through A8 and provide that result to INDEX which then returns 20,745.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCH2B-ExcelINDEXandMATCH.png) 

[Basic functions in Excel](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) like those that help you [add numbers](https://instagram-clips.techidaily.com/updated-2024-approved-unveiling-instagrams-policies-a-musicians-legal-primer/) in cells or [enter the current date](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) are certainly helpful. But when you start adding more data and advancing your data entry or analysis needs, lookup functions like INDEX and MATCH in Excel can be quite useful.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/)

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
<li><a href="https://youtube-sure.techidaily.com/iscover-keyword-power-30-must-use-hashtags-for-freegame-content/"><u>[New] Discover Keyword Power  30 Must-Use Hashtags for FreeGame Content</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-driving-engagement-the-art-of-building-a-buzz/"><u>[New] Driving Engagement  The Art of Building a Buzz</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-15-high-performing-instagram-content-extractors/"><u>[New] In 2024, 15 High-Performing Instagram Content Extractors</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-streamlining-minecraft-by-boosting-ram-capacity/"><u>[New] Streamlining Minecraft by Boosting RAM Capacity</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-transform-screen-shots-to-videos-mastery-in-aiseesofts-screencast-tools/"><u>[New] Transform Screen Shots to Videos  Mastery in Aiseesoft's Screencast Tools</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-enabling-dynamic-hdr-in-windows-11-os-for-2024/"><u>[Updated] Enabling Dynamic HDR in Windows 11 OS for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-quick-transition-from-original-pictures-to-standout-youtube-thumbnails/"><u>[Updated] In 2024, Quick Transition  From Original Pictures To Standout YouTube Thumbnails</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-dji-drone-visor-revolution-an-in-depth-review/"><u>[Updated] The DJI Drone Visor Revolution  An In-Depth Review</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/11-audiophiles-choice-for-sound-capture/"><u>11 Audiophile's Choice for Sound Capture</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-your-online-video-quality-mastery-in-finalcut-for-youtube/"><u>2024 Approved  Elevate Your Online Video Quality  Mastery in FinalCut for YouTube</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-how-to-screen-capture-snapchat-stories-effectively/"><u>2024 Approved  How to Screen Capture Snapchat Stories Effectively</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-navigating-the-360-streaming-landscape-with-ease-on-youtube/"><u>2024 Approved  Navigating the 360° Streaming Landscape with Ease on Youtube</u></a></li>
<li><a href="https://win-blog.techidaily.com/age-of-empires-4-playthrough-perfected-a-comprehensive-guide-to-resolving-in-game-stutters/"><u>Age of Empires 4 Playthrough Perfected: A Comprehensive Guide to Resolving In-Game Stutters</u></a></li>
<li><a href="https://win-blog.techidaily.com/avoid-obs-collapsing-in-windows-1110-latest-troubleshooting-steps-for-a-smooth-stream/"><u>Avoid OBS Collapsing in Windows 11/10: Latest Troubleshooting Steps for a Smooth Stream</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-launch-glitches-unlock-warzone-20-pc-success-with-these-proven-fixes/"><u>Beat Launch Glitches: Unlock Warzone 2.0 PC Success with These Proven Fixes</u></a></li>
<li><a href="https://win-blog.techidaily.com/bug-free-gaming-solutions-for-recurrent-samurai-warriors-5-pc-game-crashes/"><u>Bug Free Gaming: Solutions for Recurrent Samurai Warriors 5 PC Game Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypass-the-hurdle-5-proven-methods-when-zoom-starts-up-without-video/"><u>Bypass the Hurdle: 5 Proven Methods When Zoom Starts Up Without Video</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-mx-series-driver-update-get-enhanced-performance-with-fresh-mx492-software-for-windows/"><u>Canon MX Series Driver Update: Get Enhanced Performance with Fresh MX492 Software for Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/centipede-bug-in-destiny-2-heres-how-to-resolve-the-game-glitch-successfully/"><u>Centipede Bug in Destiny 2? Here's How to Resolve the Game Glitch Successfully</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723011127680-continuous-youtube-audios-intermittent-videos-fix-playback-hiccups-on-chrome-and-firefox/"><u>Continuous YouTube Audios, Intermittent Videos? Fix Playback Hiccups on Chrome and Firefox</u></a></li>
<li><a href="https://tech-revival.techidaily.com/countdown-to-gpt-5-insights-into-its-potential-release-timeline/"><u>Countdown to GPT-5: Insights Into Its Potential Release Timeline</u></a></li>
<li><a href="https://win-blog.techidaily.com/diy-repairing-directx-errors-in-ea-sports-fifa-20-a-comprehensive-fix-guide/"><u>DIY: Repairing DirectX Errors in EA Sports' FIFA 20 - A Comprehensive Fix Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/download-free-mcb-logo-templates/"><u>Download Free MCB Logo Templates</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-techniques-to-stop-kurtzpel-from-crashing-an-experts-advice/"><u>Effective Techniques to Stop KurtzPel From Crashing: An Expert's Advice</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723002539333-enhancing-pc-gaming-experience-addressing-the-dip-in-frames-per-second-for-forza-horizon-amoons/"><u>Enhancing PC Gaming Experience: Addressing the Dip in Frames per Second for Forza Horizon Amoons.</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-fixing-persistent-lagging-in-the-dying-light-gaming-experience/"><u>Expert Advice: Fixing Persistent Lagging in the Dying Light Gaming Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-your-pacific-drive-failure-comprehensive-repair-steps-inside/"><u>Fix Your Pacific Drive Failure – Comprehensive Repair Steps Inside!</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-cyberpunk-2077-gpu-handling-issues-on-your-windows/"><u>Fixing Cyberpunk 2077 GPU Handling Issues on Your Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-total-war-warhammer-ii-stability-problems-solutions-and-tips/"><u>Fixing Total War: Warhammer II Stability Problems - Solutions & Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-xs-max-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone XS Max System? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-frequent-rust-program-termination-issues-effectively/"><u>How to Resolve Frequent Rust Program Termination Issues Effectively</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-resident-evil-4-reboot-from-freezing-and-crashing/"><u>How to Stop Resident Evil 4 Reboot From Freezing and Crashing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-audit-your-finances-establishing-podcast-expenses/"><u>In 2024, Audit Your Finances  Establishing Podcast Expenses</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-nubia-z50s-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Nubia Z50S Pro Devices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-honor-x9b-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Honor X9b Device</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-downloads-for-amd-ryzen-5-2600-top-graphic-drivers/"><u>Instant Downloads for AMD Ryzen 5 2600 - Top Graphic Drivers</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-gamer-hacks-how-to-overcome-persistent-among-us-crashes-in-202n4-fixed/"><u>Master Gamer Hacks: How to Overcome Persistent Among Us Crashes in 202N4 [FIXED]</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-excessive-cpu-use-in-phasmophobia-tips-and-tricks-for-smooth-gameplay/"><u>Overcoming Excessive CPU Use in Phasmophobia - Tips and Tricks for Smooth Gameplay</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-startup-difficulties-for-armored-core-vi-fires-of-rubicon-on-pc-or-console/"><u>Overcoming Startup Difficulties for Armored Core VI: Fires of Rubicon on PC or Console</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723002622515-path-of-exile-stuttering-heres-how-you-can-stop-it/"><u>Path of Exile Stuttering? Here's How You Can Stop It!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/perfect-snapchat-video-maximizing-mac-capabilities-for-2024/"><u>Perfect Snapchat Video  Maximizing Mac Capabilities for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-dota-2-fixes-stuck-at-launch-issue/"><u>Resolved: Dota 2 Fixes 'Stuck at Launch' Issue</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-how-to-fix-battlefield-v-crashes-on-your-computer/"><u>Resolved: How to Fix Battlefield V Crashes on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-geforce-experience-errors-a-complete-guide/"><u>Resolving GeForce Experience Errors: A Complete Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-the-issue-why-doesnt-my-rust-application-keep-closing-unexpectedly/"><u>Resolving the Issue: Why Doesn't My Rust Application Keep Closing Unexpectedly?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/simplified-guide-to-recording-pc-screens-for-hp-users-for-2024/"><u>Simplified Guide to Recording PC Screens for HP Users for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smooth-panoramas-state-of-the-art-tracker-tech-for-2024/"><u>Smooth Panoramas  State-of-the-Art Tracker Tech for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-monster-hunter-rise-wont-start-issue-a-step-by-step-fix/"><u>Solving Monster Hunter Rise Won't Start Issue: A Step-by-Step Fix</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-stability-problems-with-classic-chinese-rpg-sword-of-virtue-7-for-pc-users/"><u>Solving Stability Problems with Classic Chinese RPG, 'Sword of Virtue 7' For PC Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-the-problem-of-non-launchable-star-wars-jedi-fallen-order/"><u>Solving the Problem of Non-Launchable Star Wars Jedi: Fallen Order</u></a></li>
<li><a href="https://fix-guide.techidaily.com/stuck-at-android-system-recovery-of-infinix-smart-8-plus-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Infinix Smart 8 Plus ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723262424809-the-hidden-power-within-an-everyday-aerosol-spray-achieving-mach-velocity/"><u>The Hidden Power Within an Everyday Aerosol Spray: Achieving Mach Velocity!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-science-behind-ai-prompt-injection-threats/"><u>The Science Behind AI Prompt Injection Threats</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-lava-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Lava Device</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-resource-for-computer-enthusiasts-toms-hardware-breakdowns/"><u>The Ultimate Resource for Computer Enthusiasts: Tom's Hardware Breakdowns</u></a></li>
<li><a href="https://win-blog.techidaily.com/top-6-tips-to-prevent-and-repair-mw2-game-crashes-on-windows-computers/"><u>Top 6 Tips to Prevent and Repair MW2 Game Crashes on Windows Computers</u></a></li>
<li><a href="https://win-blog.techidaily.com/top-7-solutions-to-overcome-the-stubbornly-loaded-forza-horizon-5-freeze/"><u>Top 7 Solutions to Overcome the Stubbornly Loaded Forza Horizon 5 Freeze</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/transforming-the-future-the-leading-5-hardware-advancements-in-ai-sector/"><u>Transforming the Future: The Leading 5 Hardware Advancements in AI Sector</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-preventing-cities-skylines-pc-malfunctions-and-crashes/"><u>Troubleshooting Tips for Preventing 'Cities: Skylines' PC Malfunctions and Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-does-dread-hunger-keeps-freezing-on-your-pc-solve-the-issue-now/"><u>Why Does Dread Hunger Keeps Freezing on Your PC? - Solve the Issue Now</u></a></li>
</ul></div>
