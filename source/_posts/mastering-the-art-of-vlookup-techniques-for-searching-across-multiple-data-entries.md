---
title: "Mastering the Art of VLOOKUP: Techniques for Searching Across Multiple Data Entries"
date: 2024-08-28T05:42:58.213Z
updated: 2024-08-29T05:42:58.213Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/162b2aac03e354d0551440e420920822fdecda6764b32f863c3da9da1ce561fb.jpg
---

## Mastering the Art of VLOOKUP: Techniques for Searching Across Multiple Data Entries

### Quick Links

* [Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores](https://hardware-updates.techidaily.com/1722963330919-newly-released-geforce-nvidia-210-drivers-compatible-with-windows-11-get-them-now/)
* [Example Two: Providing a Discount Based on How Much a Customer Spends](https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-g310-drfone-by-drfone-virtual-android/)

 VLOOKUP is one of Excel's most well-known functions. You'll typically use it to look up exact matches, such as the ID of products or customers, but in this article, we'll explore how to use VLOOKUP with a range of values.

##  Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores

 As an example, say we have a list of exam scores, and we want to assign a grade to each score. In our table, column A shows the actual exam scores and column B will be used to show the letter grades we calculate. We've also created a table off to the right (the D and E columns) that show the score necessary to achieve each letter grade.

![Grade score sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/grades-lookup-1.png) 

 With VLOOKUP, we can use the range values in column D to assign the letter grades in column E to all the actual exam scores.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  The VLOOKUP Formula

 Before we get into applying the formula to our example, let's have a quick reminder of the VLOOKUP syntax:

=VLOOKUP(lookup_value, table_array, col_index_num, range_lookup)

 In that formula, the variables work like this:

* lookup\_value: This is the value for which you are looking. For us, this is the score in column A, starting with cell A2.
* table\_array: This is often referred to unofficially as the lookup table. For us, this is the table containing the scores and associated grades (range D2:E7).
* col\_index\_num: This is the column number where the results will be placed. In our example, this is column B, but since the VLOOKUP command requires a number, it's column 2.
* range\_lookup> This is a logical value question, so the answer is either true or false. Are you performing a range lookup? For us, the answer is yes (or "TRUE" in VLOOKUP terms).

 The completed formula for our example is shown below:

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![Results of our VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-results.png) 

 The table array has been fixed to stop it changing when the formula is copied down the cells of column B.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It is important to be clear that the order is only essential with range lookups. When you put False on the end of a VLOOKUP function, the order is not so important.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Example Two: Providing a Discount Based on How Much a Customer Spends

 In this example, we have some sales data. We would like to provide a discount on the sales amount, and the percentage of that discount is dependent upon the amount spent.

 A lookup table (columns D and E) contains the discounts at each spending bracket.

![Second VLOOKUP example data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/VLOOKUP-second-example.png) 

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The VLOOKUP formula below can be used to return the correct discount from the table.

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

 This example is interesting because we can use it in a formula to subtract the discount.

 You will often see Excel users writing complicated formulas for this type of conditional logic, but this VLOOKUP provides a concise way of achieving it.

 Below, the VLOOKUP is added to a formula to subtract the discount returned from the sales amount in column A.

=A2-A2*VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![VLOOKUP returning conditional discounts](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-discounted-price.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
---

 VLOOKUP is not just useful for when looking for specific records such as employees and products. It's more versatile than many people know, and having it return from a range of values is an example of that. You can also use it as an alternative to otherwise complicated formulas.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-the-compreeved-compendium-downloading-vimeo-content-pros-way/"><u>[New] 2024 Approved  The Compreeved Compendium  Downloading Vimeo Content Pro's Way</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-videography-101-editing-essentials-taught/"><u>[New] YouTube Videography 101  Editing Essentials Taught</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-explore-leading-platforms-offering-premium-vectr-art-resources/"><u>[Updated] 2024 Approved  Explore Leading Platforms Offering Premium Vectr Art Resources</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-expert-hashtag-analyzers-for-social-media-giants-fbtweetig/"><u>[Updated] In 2024, Expert Hashtag Analyzers for Social Media Giants (FB/Tweet/IG)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-gain-traction-with-effective-video-descriptions-and-tagging/"><u>[Updated] In 2024, Gain Traction with Effective Video Descriptions and Tagging</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-transform-your-footage-a-complete-youtube-studio-editing-course/"><u>[Updated] In 2024, Transform Your Footage  A Complete YouTube Studio Editing Course</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-harnessing-altitude-live-streaming-with-dji-drones/"><u>2024 Approved  Harnessing Altitude  Live-Streaming with DJI Drones</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-yourwebcamunlocked-astep-by-steprecordingpath/"><u>2024 Approved  YourWebcamUnlocked  AStep-by-StepRecordingPath</u></a></li>
<li><a href="https://win-blog.techidaily.com/among-us-loading-loop-solutions-to-get-past-the-sticky-start/"><u>Among Us Loading Loop - Solutions to Get Past the Sticky Start</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722999664695-beat-zooms-heavy-cpu-usage-with-these-effective-fixes/"><u>Beat Zoom's Heavy CPU Usage with These Effective Fixes!</u></a></li>
<li><a href="https://win-blog.techidaily.com/bridging-the-gap-correcting-astro-a50-and-command-center-detection-issues/"><u>Bridging the Gap: Correcting Astro A50 and Command Center Detection Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/complete-guide-fixing-error-0xc1901e3-in-windows-11-for-smooth-operations/"><u>Complete Guide: Fixing Error 0Xc1901e3 in Windows 11 for Smooth Operations</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-and-troubleshoot-steam-titles-wont-start-on-windows-10/"><u>Fix & Troubleshoot: Steam Titles Won't Start on Windows 10</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-the-issue-how-to-stop-microsoft-flight-simulator-202n-from-continuously-crashing/"><u>Fixing the Issue: How to Stop Microsoft Flight Simulator 202N From Continuously Crashing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-confusion-to-clarity-excel-made-simple-by-chatgpt/"><u>From Confusion to Clarity: Excel Made Simple by ChatGPT</u></a></li>
<li><a href="https://win-blog.techidaily.com/get-back-to-the-action-fast-solving-division-2s-game-crashing-woes/"><u>Get Back to the Action Fast: Solving Division 2'S Game Crashing Woes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-innovations-potential-se-engine-counterparts/"><u>GPT Innovations: Potential SE Engine Counterparts</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-to-diagnosing-and-repairing-a-non-responsive-paradox-launcher/"><u>Guide to Diagnosing & Repairing a Non-Responsive Paradox Launcher</u></a></li>
<li><a href="https://win-blog.techidaily.com/guilty-gear-strive-postponed-heres-everything-you-need-to-know-about-its-new-release-date/"><u>Guilty Gear Strive Postponed? Here's Everything You Need to Know About Its New Release Date</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-cod-vanguard-error-0x00001338-on-pc-a-comprehensive-guide/"><u>How to Fix CoD: Vanguard Error 0X00001338 on PC – A Comprehensive Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-sony-xperia-1-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-n53-phone-without-pin-by-drfone-android/"><u>How to Unlock Realme Narzo N53 Phone without PIN</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-newcomers-elite-entryway-list-for-zooids/"><u>In 2024, Newcomers’ Elite Entryway List for Zooids</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-the-2024-update-a-step-by-step-fix-for-path-of-exiles-failed-connections/"><u>Mastering the 2024 Update: A Step-by-Step Fix for Path of Exile's Failed Connections</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-honor-play-7t-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Honor Play 7T – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimizing-gameplay-smoothness-for-the-mass-effect-legendary-collection/"><u>Optimizing Gameplay Smoothness for the Mass Effect Legendary Collection</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimizing-your-pc-for-smooth-playthrough-of-half-life-alyx-no-more-lag-or-stuttering/"><u>Optimizing Your PC for Smooth Playthrough of Half-Life: Alyx - No More Lag or Stuttering</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722981907974-preventing-star-wars-battlefront-ii-from-crashing-on-your-computer-solutions-inside/"><u>Preventing Star Wars Battlefront II From Crashing on Your Computer - Solutions Inside</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-errors-dragon-quest-xi-crash-issues-now-solved/"><u>Say Goodbye to Errors: Dragon Quest XI Crash Issues Now Solved</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-blaze-curve-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Blaze Curve 5G</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-complete-guide-to-scheduling-and-recording-online-meetings-with-slack-and-filmora/"><u>The Complete Guide to Scheduling & Recording Online Meetings with Slack & Filmora</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-little-giant-among-iphones-a-detailed-look-into-iphone-12-mini-excellence/"><u>The Little Giant Among iPhones: A Detailed Look Into iPhone ^12 Mini Excellence</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-itel-p40-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Itel P40? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-high-frame-rates-in-valheim-pc-version/"><u>Troubleshooting High Frame Rates in Valheim PC Version</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-fixing-error-0xc19001e1-in-your-windows-10-pc/"><u>Troubleshooting Tips: Fixing Error 0XC19001E1 in Your Windows 10 PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-xbox-live-confirming-service-interruptions-and-accessibility-status/"><u>Troubleshooting Xbox Live: Confirming Service Interruptions and Accessibility Status</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-fixes-to-combat-freezing-and-increase-frames-per-second-in-fortnites-battle-royale-mode-warzone-edition/"><u>Ultimate Fixes to Combat Freezing and Increase Frames Per Second in Fortnite's Battle Royale Mode - Warzone Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-list-most-compelling-zombie-themed-video-games/"><u>Ultimate List  Most Compelling Zombie-Themed Video Games</u></a></li>
<li><a href="https://win-blog.techidaily.com/victory-over-steam-sign-in-troubles-tips-and-techniques-applied/"><u>Victory over Steam Sign-In Troubles - Tips and Techniques Applied!</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-cant-i-play-detailed-steps-for-when-tf2-refuses-to-open/"><u>Why Can't I Play? Detailed Steps for When TF2 Refuses to Open</u></a></li>
</ul></div>
