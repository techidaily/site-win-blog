---
title: "Mastering Weighted Averages with Excel: Essential Tutorial for Accurate Data Analysis"
date: 2024-08-28T05:42:27.169Z
updated: 2024-08-29T05:42:27.169Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Mastering Weighted Averages with Excel: Essential Tutorial for Accurate Data Analysis

### Quick Links

* [What is a Weighted Average?](https://extra-guidance.techidaily.com/new-mastering-the-ritual-of-independent-instagram-sound-creation/)
* [Let's Look at an Example](https://fox-access.techidaily.com/updated-dji-drone-artistry-unlocked-first-20-free-lutts-available/)

 A weighted average is one that takes into account the importance, or weight, of each value. This article will show you how to use Excel's SUMPRODUCT and SUM functions individually and how to combine the two to calculate a weighted average.

##  What is a Weighted Average?

 A weighted average is an average that takes into account the importance, or weight, of each value. A good example would be calculating a student's final grade based on their performance on a variety of different assignments and tests. Individual assignments usually don't count as much towards a final grade as the final exam---things like quizzes, tests, and final exams will all have different weights. The weighted average is calculated as the sum of all of the values multiplied by their weights divided by the sum of all of the weights.

 The following example will demonstrate how to use Excel's SUMPRODUCT and SUM functions to calculate a weighted average.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
##  Let's Look at an Example

 For our example, let's look at a student's quiz and exam scores. There are six quizzes each worth 5% of the total grade, two exams each worth 20% of the total grade, and one final exam worth 30% of the total grade. The student's final grade will be a weighted average, and we will use the SUMPRODUCT and SUM functions to calculate it.

 As you can see in our table below, we've already assigned the relative weights to each quiz and exam in the D column.

![Excel table showing scores and weights assigned to several quizzes and exams](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-01.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step One: Calculate the SUMPRODUCT

 First, let's look at how the SUMPRODUCT function works. Start by selecting the cell where you want the result to appear (in our example, that's cell D13). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUMPRODUCT" function.

![On the Formulas tab, click Math &amp; Trig, then select SUMPRODUCT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-02.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The "Function Arguments" window will appear.

![the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-03.png) 

 For the "Array1" box, select the student's scores. Here, we're selecting all the cells with actual scores in the C column.

![In the Array1 box, select the cells with the grades](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-04.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
 Next, use the "Array2" box to select the weights of the quizzes and exams. For us, those are in the D column.

![In the Array2 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-05.png) 

 Click "OK" when you're done.

![Click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-06.png) 

 The SUMPRODUCT function will multiply each score by its corresponding weight and then return the sum of all of those products.

![The Excel table now shows the SUMPRODUCT value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-07.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step Two: Calculate the SUM

 Now let's look at how the SUM function works. Select the cell where you want the results to appear (in our example, that's cell D14). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUM" function.

![On the Formulas tab, click Math &amp; Trig, then select SUM](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-08.png) 

 The "Function Arguments" window will appear.

![The Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-09.png) 

 For the "Number1" box, select all of the weights.

![In the Number1 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-10.png) 

 Click "OK."

![click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-11.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The SUM function will add all of the values together.

![The Excel table now shows the SUM value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-12.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
###  Step Three: Combine the SUMPRODUCT and SUM to Calculate the Weighted Average

 Now we can combine the two functions to determine the student's final grade based on their scores and the weights of each score. Select the cell where the weighted average should go (for us that's cell D15) and then type the following formula into the function bar.

=SUMPRODUCT(C3:C11,D3:D11)/SUM(D3:D11)

![select the weighted average cell and then type the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-13.png) 

 Press "Enter" after typing the formula to view the weighted average.

![The table now shows the weighted average](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-14.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And there you have it. It's a fairly simple example, but it's a good one for showing how weighted averages work.

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
<li><a href="https://win-blog.techidaily.com/fixed-modern-warfare-2-fps-drops-and-stuttering-on-windows/"><u>[Fixed] Modern Warfare 2 FPS Drops and Stuttering on Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/issue-resolved-how-to-stop-call-of-duty-black-ops-cold-war-from-crashing-on-your-computer-year-2024/"><u>[Issue Resolved] How to Stop Call of Duty: Black Ops Cold War From Crashing on Your Computer (Year 2024)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-enhance-engagement-learn-to-dim-youtube-video-backgrounds-for-2024/"><u>[New] Enhance Engagement  Learn to Dim YouTube Video Backgrounds for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-capture-attention-with-top-mobile-video-editing-software-for-snapchats/"><u>[New] In 2024, Capture Attention with Top Mobile Video Editing Software for Snapchats</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-snap-complete-web-panel/"><u>[Updated] 2024 Approved  Snap Complete Web Panel</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-beginners-guide-to-crafting-trendy-mac-video-content/"><u>[Updated] Beginner's Guide to Crafting Trendy Mac Video Content</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-clandestine-call-collectors-a-stealthy-apps-review-androidios-for-2024/"><u>[Updated] Clandestine Call Collectors  A Stealthy Apps Review (Android/iOS) for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-prime-10-mobile-movie-extractors/"><u>2024 Approved  Prime 10 Mobile Movie Extractors</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-itel-a05s-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Itel A05s to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-oppo-find-x6-pro-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Oppo Find X6 Pro without App | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-division-2-glitches-with-these-quick-and-effective-solutions/"><u>Beat Division 2 Glitches with These Quick and Effective Solutions!</u></a></li>
<li><a href="https://win-blog.techidaily.com/boost-your-warzone-performance-with-graphics-card-utilization-in-windows-10/"><u>Boost Your Warzone Performance with Graphics Card Utilization in Windows 10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/dissecting-screenflows-impact-on-mac-creatives-and-developers/"><u>Dissecting ScreenFlow's Impact on Mac Creatives and Developers</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-fixes-when-multiversus-wont-open-on-your-pc-a-user-friendly-guide/"><u>Effective Fixes When MultiVersus Won't Open on Your PC: A User-Friendly Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebook-cover-video-aspect-ratio-for-2024/"><u>Facebook Cover Video Aspect Ratio for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722991917357-fortnite-black-screen-dilemma-on-windows-discover-proven-strategies-to-restore-gameplay/"><u>Fortnite Black Screen Dilemma on Windows? Discover Proven Strategies to Restore Gameplay.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-videos-not-playing-on-huawei-p60-art-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix Videos Not Playing on Huawei P60 Art?</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-repair-error-code-0xc19001e1-in-windows-11-a-detailed-tutorial/"><u>How to Repair Error Code 0xC19001E1 in Windows 11: A Detailed Tutorial</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-non-functioning-of-steelseries-gg-software-on-your-pc/"><u>How to Resolve Non-Functioning of SteelSeries GG Software on Your PC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-share-youtube-link-on-instagram-story/"><u>How to Share YouTube Link on Instagram Story</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-essential-video-editors-to-make-your-snapchats-pop-on-phones/"><u>In 2024, Essential Video Editors to Make Your Snapchats Pop on Phones</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-6s-plus-with-7-methods-drfone-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 6s Plus With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-quality-upgrade-switch-codecs-to-av1-for-youtube-viewing/"><u>In 2024, Quality Upgrade  Switch Codecs to AV1 for YouTube Viewing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-techniques-to-avoid-blackout-issues-on-online-video-platform/"><u>In 2024, Techniques to Avoid Blackout Issues on Online Video Platform</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unexpected-vertical-tilt-in-instagram-vids-why/"><u>In 2024, Unexpected Vertical Tilt in Instagram Vids? Why?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-visionary-composer-dual-elements-conjoined/"><u>In 2024, Visionary Composer  Dual Elements Conjoined</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-tips-eliminating-game-crashes-in-fifa-20-when-played-on-pc/"><u>Master Tips: Eliminating Game Crashes in FIFA 20 When Played on PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-multiversus-pc-trouble-a-guide-for-smooth-gameplay-launches/"><u>Mastering MultiVersus PC Trouble: A Guide for Smooth Gameplay Launches</u></a></li>
<li><a href="https://win-blog.techidaily.com/nba-2k21-for-pc-stability-tips-how-to-prevent-the-game-from-crashing/"><u>NBA 2K21 for PC Stability Tips - How to Prevent the Game From Crashing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/optimal-gameplayers-for-your-androids-gb-games-for-2024/"><u>Optimal GamePlayers for Your Android's GB Games for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcome-dreamlight-valley-errors-on-your-computer-with-these-6-quick-fixes/"><u>Overcome Dreamlight Valley Errors on Your Computer with These 6 Quick Fixes</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723006434090-overcoming-performance-hitches-for-a-smoother-playthrough-of-dying-light-fps/"><u>Overcoming Performance Hitches for a Smoother Playthrough of Dying Light FPS.</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-the-centipede-glitch-in-destiny-2-complete-guide/"><u>Overcoming the 'Centipede' Glitch in Destiny 2 - Complete Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-windows/"><u>Overcoming Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/rapid-resolution-techniques-for-assassins-creed-valhalla-performance-issues/"><u>Rapid Resolution Techniques for 'Assassin's Creed: Valhalla' Performance Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723005215563-resolve-league-of-legends-crashes-swiftly-a-step-by-step-guide/"><u>Resolve League of Legends Crashes Swiftly: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-chrome-stuck-issues-on-windows-10-tips-and-tricks/"><u>Resolving Chrome Stuck Issues on Windows 10 - Tips & Tricks</u></a></li>
<li><a href="https://win-blog.techidaily.com/restore-the-soundscape-fixing-audio-glitches-in-your-lost-ark-adventure/"><u>Restore the Soundscape: Fixing Audio Glitches in Your Lost Ark Adventure</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-fixing-fall-guys-freezes-and-lag-issues-in-pc-version/"><u>Solved: Fixing 'Fall Guys' Freezes and Lag Issues in PC Version</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-audio-glitches-and-problems-in-halo-infinite-gameplay/"><u>Solving Audio Glitches and Problems in Halo Infinite Gameplay</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-tips-for-stabilizing-the-sovled-warno-experience-and-preventing-pc-issues/"><u>Step-by-Step Tips for Stabilizing the [SOVLED] Warno Experience and Preventing PC Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-and-resolving-persistent-firefox-lag-issues/"><u>Troubleshooting & Resolving Persistent Firefox Lag Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-for-overcoming-lunar-client-malfunctions-on-desktop-computers/"><u>Troubleshooting Guide for Overcoming Lunar Client Malfunctions on Desktop Computers</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-resolving-after-effects-software-crashes-in-windows-11-and-10-environments/"><u>Troubleshooting Tips for Resolving After Effects Software Crashes in Windows 11 & 10 Environments</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-solutions-for-eliminating-lag-issues-while-playing-resident-evil-village-pc/"><u>Ultimate Solutions for Eliminating Lag Issues While Playing Resident Evil Village [PC]</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723004687038-ultimate-troubleshooting-tips-for-fixing-call-of-duty-modern-warfare-dev-error-6034-play-without-glitches/"><u>Ultimate Troubleshooting Tips for Fixing Call of Duty: Modern Warfare (Dev Error 6034) - Play Without Glitches!</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlocking-victory-over-shadows-defeating-nba-2k21s-endless-black-loading-phase-2c4/"><u>Unlocking Victory Over Shadows: Defeating NBA 2K21's Endless Black Loading Phase (2C4)</u></a></li>
<li><a href="https://win-blog.techidaily.com/untangling-pc-instability-for-robocop-rupture-city-essential-troubleshooting-steps/"><u>Untangling PC Instability for 'RoboCop: Rupture City': Essential Troubleshooting Steps</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-mp4-file-editor-for-pc-quickly-trim-cut-and-merge-videos/"><u>Updated 2024 Approved MP4 File Editor for PC Quickly Trim, Cut, and Merge Videos</u></a></li>
<li><a href="https://win-blog.techidaily.com/vrchat-troubleshooting-made-easy-how-to-fix-a-non-functional-app/"><u>VRChat Troubleshooting Made Easy – How to Fix a Non-Functional App</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-modern-warfare-wont-start-pc-launch-solutions-gamers/"><u>Why Modern Warfare Won't Start? PC Launch Solutions Gamers</u></a></li>
</ul></div>
