---
title: "Step-by-Step Guide: Calculating Distinct Data Points with Microsoft Excel"
date: 2024-12-05T18:50:27.277Z
updated: 2024-12-12T18:13:32.269Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the cell range you want to count contains blanks, those will be included as unique values which may cause a problem. To exclude blank cells in your range, you can add the FILTER function to the formula:

 The FILTER function is only available in the versions of Excel listed [above](https://extra-approaches.techidaily.com/updated-prime-10-converters-free-apps-for-efficient-srt-file-transformations/).

=COUNTA(UNIQUE(FILTER(A2:A5,A2:A5<>"")))

 Let's break down the FILTER portion of the formula. `A2:A5,A2:A5` represents the cell range and the criteria to filter which are the same, `<>` represents not equal to, and `""` represents blank.

 As you can see in the screenshot below, the blank cell in our array is not counted as a unique value.

![COUNTA, UNIQUE, and FILTER functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFilterFunctions-ExcelCountUnique.png) 

Related: [How to Count Cells in Microsoft Excel](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Use the SUM and COUNTIF Functions

 If you're using a version of Excel where the UNIQUE and FILTER functions are unavailable, you can use SUM and [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) instead.

 You may also use the same formulas below replacing the SUM function with SUMPRODUCT.

 The [SUM function](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) adds numbers and the COUNTIF function counts those cells containing numbers that meet specific criteria.

 To find the unique values in the cell range A2 through A5, use the following formula:

=SUM(1/COUNTIF(A2:A5,A2:A5))

 To break down this formula, the `COUNTIF` function counts the cells with numbers in our range and uses that same cell range as the criteria. That result then is [divided](https://facebook-video-share.techidaily.com/new-in-2024-breaking-through-youtubes-walls-using-advanced-creator-studio-skills/) by `1` and the `SUM` function adds the remaining values.

![SUM and COUNTIF functions in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctions-ExcelCountUnique.png) 

 Similar to the first method, you can run into issues if you have blanks in your cell range with this method. Only, you'll receive the #DIV/0![error](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) rather than an extra unique value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To eliminate this problem, you can use the following formula:

=SUM((A2:A5<>"")/COUNTIF(A2:A5,A2:A5&""))

 The additional portion for the `COUNTIF` function [concatenates](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) a blank string to prevent zeroes in the results because you cannot divide by zero. The additional portion for the `SUM` function adds the values that do not equal blank. All of this provides the count of distinct values and also does not count blanks as unique.

![SUM and COUNTIF filtered](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctionsFiltered-ExcelCountUnique.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-ultimate-instagram-captioning-hack-for-reels-and-stories/"><u>[New] 2024 Approved The Ultimate Instagram Captioning Hack for Reels and Stories</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-the-ultimate-guide-to-design-and-build-your-own-4k-editing-system/"><u>2024 Approved The Ultimate Guide to Design and Build Your Own 4K Editing System</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-xiaomi-redmi-note-12-proplus-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Xiaomi Redmi Note 12 Pro+ 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/achieving-ideal-illumination-a-guide-to-masterful-video-lighting-techniques/"><u>Achieving Ideal Illumination: A Guide to Masterful Video Lighting Techniques</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-ryzen-9x00-pricing-unveiled-by-france-eurozones-ryzen-9-9900x-listed-at-almost-680/"><u>AMD Ryzen 9X00 Pricing Unveiled by France - Eurozone's Ryzen 9 9900X Listed at Almost €680</u></a></li>
<li><a href="https://win-blog.techidaily.com/boost-your-system-proven-methods-to-curb-discords-cpu-drainage/"><u>Boost Your System: Proven Methods to Curb Discord's CPU Drainage</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1726028185887-facebook/"><u>Facebook動画再生苦情を解決する簡単方法</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-motorola-edge-40-neo-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Motorola Edge 40 Neo? Try These Fixes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-archive-snaps-from-android-plus-mac-systems-for-2024/"><u>How to Archive Snaps From Android + Mac Systems for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-cyberpunk-2077s-notorious-black-screen-problem/"><u>How to Overcome Cyberpunk 2077'S Notorious Black Screen Problem</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-league-of-legends-startup-problems-effective-solutions-for-players-year-202/"><u>Mastering League of Legends Startup Problems: Effective Solutions for Players - Year 202#</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-troubleshooting-top-5-fixes-for-world-of-warships-crashes/"><u>PC Troubleshooting: Top 5 Fixes for World of Warships Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-blurry-scenes-outriders-graphics-upgrade-successful/"><u>Say Goodbye to Blurry Scenes: Outriders' Graphics Upgrade Successful</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-art-of-color-grading-utilizing-luts-in-ae/"><u>The Art of Color Grading Utilizing LUTs in AE</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723002469327-troubleshooting-starfields-audio-glitches-no-more-skipping-sounds/"><u>Troubleshooting Starfield's Audio Glitches - No More Skipping Sounds!</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-solving-corsair-icue-compatibility-issues-with-windows-11/"><u>Troubleshooting Steps: Solving Corsair iCUE Compatibility Issues with Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlock-smooth-screenshare-troubleshooting-and-solving-shadowplay-on-windows/"><u>Unlock Smooth Screenshare: Troubleshooting and Solving ShadowPlay on Windows</u></a></li>
</ul></div>

