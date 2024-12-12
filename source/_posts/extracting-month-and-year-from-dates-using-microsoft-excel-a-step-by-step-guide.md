---
title: "Extracting Month and Year From Dates Using Microsoft Excel: A Step-by-Step Guide"
date: 2024-12-05T19:11:24.916Z
updated: 2024-12-12T17:48:53.521Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b707c0511382e78c7bbc2631c8c2ac749bfdb8b7dcef137c48ff3983d7a66e67.jpg
---

## Extracting Month and Year From Dates Using Microsoft Excel: A Step-by-Step Guide

### Quick Links

* [Get the Month or Year With Date Functions](https://youtube-help.techidaily.com/2024-approved-global-gross-earnings-of-youtube-luminaries/)
* [Get the Month or Year With the TEXT Function](https://extra-tips.techidaily.com/new-blending-binaries-digital-photographic-techniques/)

 Dates in Microsoft Excel are useful for tracking finances, orders, and sales. So, there may come a time when you want to pull a month or year out of a date entry. [Functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) make this an easy task.

 There are a couple of ways to get a month from a [date in Excel](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/), depending on if you want to display the result as a number, word, or abbreviation. And luckily, you can use these same methods to get the year from your date entry.

##  Get the Month or Year With Date Functions

 If you want to get the numeric value for a month such as 10 for October, 11 for November, and so on, the MONTH function gets the job done quickly. For years, you can simply use the [YEAR function](https://tech-revival.techidaily.com/integrate-bing-ai-into-your-android-phone-tips-and-tricks-for-seamless-communication/) and a reference.

 The syntax for each function is the same: 

        `MONTH(reference)`
    
 and 

        `YEAR(reference)`
    
 where you refer to the cell containing the date.

 You can use the following formulas to get the month and then the year from the date in cell A2:

=MONTH(A2)

=YEAR(A2)

 You'll then see the result in the cell containing the formula.

![YEAR function to obtain the year from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullYear-ExcelMonthYearFromDate.png) 

 Remember, the month is formatted as its numeric value.

![MONTH function to obtain the month from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/MonthNumber-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you have a list of dates where you want to grab the month and/or year for each entry, use the fill handle to drag the formula(s) down to the remaining cells.

![Copy formula to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyFullFormulas-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Get the Month or Year With the TEXT Function

 Maybe you prefer to see the name of the month or an abbreviation rather than the number. You can do this for the month using the [TEXT function](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/). You can also get the two-digit number for the year with this method.

Related: [How to Find the Day of the Week From a Date in Microsoft Excel](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) 

 The syntax for the function is `TEXT(value, format_code)` where you'll need both arguments to display the month. The `value` is the cell containing the date and the `format_code` is how you want to display the result.

 Here, we'll get the month for the date in cell A2 as a full word using the letter M for month as the `format_code`:

=TEXT(A2,"mmmm")

 Note, you need at least four M's within quotation marks to get the full month name. The number of letters in the month's name does not correspond to the number of M's in the argument; just enter at least four of them.

![Full month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullMonth-ExcelMonthYearFromDate.png) 

 To get the three-letter abbreviation for a month instead of the full name, just use three M's:

=TEXT(A3,"mmm")

![Abbreviation for month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortMonth-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also use the TEXT function if you only want two digits for the year rather than all four. You'll use the letter Y for year as the `format_code`:

=TEXT(A2,"yy")

![Two digits for the year using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortYear-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Again, you can use the fill handle to [copy the formula(s)](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) down to your remaining cells if you like.

![Copied formulas to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyShortFormulas-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Pulling a month or year out of a full date in Excel takes only a minute with these methods. For more, check out these additional [date and time functions in Excel](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/) you might find useful.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-social-media-sync-integrating-multiple-photographsvideos-into-your-ig-feed/"><u>[New] 2024 Approved Social Media Sync Integrating Multiple Photographs/Videos Into Your IG Feed</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-mastering-your-iphone-lens-essential-techniques-for-nature-pics/"><u>[Updated] In 2024, Mastering Your iPhone Lens Essential Techniques for Nature Pics</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-amplify-engagement-essential-tips-for-tiktok-unbox-videos/"><u>2024 Approved Amplify Engagement Essential Tips for TikTok Unbox Videos</u></a></li>
<li><a href="https://discover-data.techidaily.com/complete-guide-restoring-irreversibly-lost-sms-messages-on-your-iphone/"><u>Complete Guide: Restoring Irreversibly Lost SMS Messages on Your iPhone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/create-a-stunning-rainbow-pc-using-hytes-nexus-link-a-game-changer-in-rgb-device-integration/"><u>Create a Stunning Rainbow PC Using Hyte's Nexus Link - A Game Changer in RGB Device Integration</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-for-resolving-roblox-error-code-277-on-desktop-ultimate-tips-and-tricks/"><u>Guide for Resolving Roblox Error Code 277 on Desktop: Ultimate Tips and Tricks</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-honor-x50i-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Honor X50i Without Password | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-inside-look-at-whatsapps-voice-communication-design/"><u>In 2024, Inside Look at WhatsApp's Voice Communication Design</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/july-28th-insights-unveiling-the-secrets-in-the-new-york-times-connecting-topics-and-answers-413/"><u>July 28Th Insights: Unveiling the Secrets in 'The New York Times' - Connecting Topics & Answers #413</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/mastering-ssd-data-restoration-with-ifind-expert-guidelnce-and-easy-to-follow-strategies/"><u>Mastering SSD Data Restoration with iFind - Expert Guidelnce & Easy-to-Follow Strategies</u></a></li>
<li><a href="https://win-blog.techidaily.com/navigating-through-and-correcting-palworlds-session-based-search-malfunctions/"><u>Navigating Through and Correcting Palworld's Session-Based Search Malfunctions</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-limited-memory-challenges-for-a-smooth-god-of-war-experience/"><u>Overcoming Limited Memory Challenges for a Smooth God of War Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-cyberpunk-2077-performance-issues-smooth-gameplay-achieved/"><u>Resolved: Cyberpunk 2077 Performance Issues - Smooth Gameplay Achieved</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-fixing-your-ps4-when-its-stuck-on-black-screen/"><u>Step-by-Step Guide: Fixing Your PS4 When It's Stuck on Black Screen</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-to-preventing-crashes-in-forza-horizon-5-for-pc-users/"><u>Ultimate Guide to Preventing Crashes in Forza Horizon 5 for PC Users</u></a></li>
</ul></div>

