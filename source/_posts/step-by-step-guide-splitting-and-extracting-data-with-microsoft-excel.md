---
title: "Step-by-Step Guide: Splitting & Extracting Data with Microsoft Excel"
date: 2024-12-09T17:06:29.431Z
updated: 2024-12-12T17:25:26.681Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a65a2d3fb958e05df694286812a1e2454a9d6c6ff463421241eb49561be7ce4c.jpg
---

## Step-by-Step Guide: Splitting & Extracting Data with Microsoft Excel

### Quick Links

* [The TEXTBEFORE Function](https://screen-sharing-recording.techidaily.com/new-2024-approved-expert-routines-for-flawless-webinar-replays/)
* [The TEXTAFTER Function](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a58-4g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [The TEXTSPLIT Function](https://facebook-video-content.techidaily.com/tutorial-transferring-youtube-videos-to-social-media-facebook-edition/)

 Microsoft Excel offers a set of [functions for working with text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/). When you want to extract part of a text string or split a string into rows or columns, there are three particular functions that get the job done.

 With TEXTBEFORE and TEXTAFTER, you can pull out text before or after a certain word or character. This makes these functions more flexible than the [LEFT, RIGHT, and MID functions](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) you might be using. For splitting a string into various cells, you can use TEXTSPLIT.

 These three functions are new to Excel as of August 2022\. They will roll out to Office Insiders and then all Excel users over time.

##  The TEXTBEFORE Function

 The syntax for the function is

        `TEXTBEFORE(text, delimiter, instance, match_mode, match_end, if_not_found)`
    
 . The first two arguments are required with `text` being either the actual text or a cell reference and `delimiter` being the point at which you want the text before.

 Here are descriptions of the three optional arguments:

* **Instance**: Use this argument if there is more than one occurrence of the `delimiter` in the string and you want a particular one.
* **Match\_mode**: Enter a 0 for case sensitive or 1 for not case sensitive. The default is 0.
* **Match\_end**: Enter 0 to not match the delimiter to the end of the text and 1 to match it. The default is 1.
* **If\_not\_found**: Use this argument If you prefer a result rather than an error for values not found.

 Now that you know the arguments, let's look at some example uses for TEXTBEFORE.

 In this first example, we'll extract all text before the word "from" in cell A2 using this formula:

=TEXTBEFORE(A2,"from")

![TEXTBEFORE function for a basic extraction](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFOREbasic-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Using this next formula, we'll extract all text before the second instance of the word "text."

=TEXTBEFORE(A2,"text",2)

![TEXTBEFORE function using an instance](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFOREinstance-ExcelExtractSplitText.png) 

 For one more example, we'll use the `match_mode` argument for a case-sensitive match.

=TEXTBEFORE(A2,"TEXT",,0)

![TEXTBEFORE function using case sensitive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTBEFORECaseSensitive-ExcelExtractSplitText.png) 

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

##  The TEXTAFTER Function

 TEXTAFTER is the exact opposite of TEXTBEFORE. The syntax for the function is `TEXTAFTER(text, delimiter, instance, match_mode, match_end, if_not_found)`.

 Like its counterpart, the first two arguments are required with `text` being either the actual text or a cell reference and `delimiter` being the point at which you want the text after.

 The three optional arguments described above also work the same as the TEXTBEFORE function.

 In this first example, we'll extract all text after the word "from" in cell A2 using this formula:

=TEXTAFTER(A2,"from")

![TEXTAFTER function for a basic extraction](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERbasic-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Using this next formula, we'll extract all text after the second instance of the word "text."

=TEXTAFTER(A2,"text",2)

![TEXTAFTER function using an instance](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERinstance-ExcelExtractSplitText.png) 

 And finally, we'll use the `match_mode` argument for a case-sensitive match.

=TEXTAFTER(A2,"TEXT",,0)

![TEXTAFTER function using case sensitive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTAFTERCaseSensitive-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The TEXTSPLIT Function

 With the TEXTSPLIT function you can [split the text](https://fox-glue.techidaily.com/new-in-2024-navigating-the-essentials-of-av1-coders/) into cells in a row or column based on the delimiter, for example, a space or period.

Related: [How to Split Data Into Multiple Columns in Excel](https://fox-glue.techidaily.com/new-in-2024-navigating-the-essentials-of-av1-coders/) 

 The syntax is `TEXTSPLIT(text, column_delimiter, row_delimiter, ignore, match_mode, pad_with)` where the first argument is required and can be actual text or a cell reference. By default, the formula splits the text into columns, but you can use rows instead with the `row_delimiter` argument.

 Here are descriptions of the remaining arguments:

* **Ignore**: Enter FALSE to create an empty cell when two delimiters are consecutive. The default is TRUE.
* **Match\_mode**: Searches the delimiter for a match with the default as case sensitive.
* **Pad\_with**: To pad the result, enter a value. Otherwise, the #N/A error displays.

 In this example, we'll split the text string in cell A2 across columns with a space as our `column_delimiter` in quotes. Here's the formula:

=TEXTSPLIT(A2," ")

![TEXTSPLIT function across columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITbasic-ExcelExtractSplitText.png) 

 Instead of splitting the string across columns, we'll split it across rows using a space as our `row_delimiter` with this formula:

=TEXTSPLIT(A2,," ")

 Notice in this formula, we leave the `column_delimiter` argument blank and only use the `row_delimiter`.

![TEXTSPLIT function across rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITRows-ExcelExtractSplitText.png) 

 For this next example, we'll split only after the semicolon into another column:

=TEXTSPLIT(A2,";")

![TEXTSPLIT function across columns with a single delimiter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITSemicolonColumn-ExcelExtractSplitText.png) 

 Next, we'll split only after the semicolon into a row instead of a column:

=TEXTSPLIT(A2,,";")

![TEXTSPLIT function across rows with a single delimiter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TEXTSPLITSemicolonRow-ExcelExtractSplitText.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The TEXTSPLIT function is a powerful one. If you're looking for more complex examples of using the optional arguments, visit the [Microsoft Support page for the TEXTSPLIT function](https://support.microsoft.com/en-us/office/textsplit-function-b1ca414e-4c21-4ca0-b1b7-bdecace8a6e7).

 The next time you want to extract text from a cell or split a long text string, keep these [Excel functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) in mind. Then, when you need to put strings back together again, learn how to easily [add text to a cell with a formula](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/).

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-equality-in-tech-easeus-experts-take/"><u>[New] Equality in Tech EaseUS Experts' Take</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-crafting-sequences-a-movie-maker-approach-to-animation/"><u>[Updated] 2024 Approved Crafting Sequences A Movie Maker Approach to Animation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-leading-ps2-emulators-unveiled-for-iphone-and-ipad/"><u>2024 Approved Leading PS2 Emulators Unveiled for iPhone and iPad</u></a></li>
<li><a href="https://win-blog.techidaily.com/6-proven-tweaks-to-minimize-resource-drain-in-baldurs-gate-3-a-step-by-step-guide-for-pc-players-2024-version/"><u>6 Proven Tweaks to Minimize Resource Drain in Baldur's Gate 3: A Step-by-Step Guide for PC Players (2024 Version)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/deciding-on-ideal-vimeo-subscription-plan-for-2024/"><u>Deciding on Ideal Vimeo Subscription Plan for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/hitman-e-game-crash-on-pc-heres-how-to-get-it-running-smoothly/"><u>Hitman E Game Crash on PC? Here's How to Get It Running Smoothly</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-screen-casting-features-in-vlc-examined/"><u>In 2024, Screen Casting Features in VLC Examined</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723003538293-master-the-art-of-stable-gaming-overcome-yakuza-6-pc-faults-easily/"><u>Master the Art of Stable Gaming: Overcome Yakuza 6 PC Faults Easily</u></a></li>
<li><a href="https://win-blog.techidaily.com/pandoras-edge-optimized-and-bug-free-avatar-gaming-on-personal-computers/"><u>Pandora's Edge: Optimized and Bug-Free Avatar Gaming on Personal Computers</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-gaming-fixes-enjoy-a-smooth-run-with-the-latest-patch-of-wrc-10-by-fia-world-rally-championship/"><u>PC Gaming Fixes: Enjoy a Smooth Run with the Latest Patch of WRC 10 by FIA World Rally Championship</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/professional-filmmaking-essentials-ideal-lenses-to-consider-for-2024/"><u>Professional Filmmaking Essentials Ideal Lenses to Consider for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-network-issues-troubleshooting-guide-for-apex-legends-players/"><u>Resolving Network Issues: Troubleshooting Guide for Apex Legends Players</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-resolving-rainbow-six-sieges-server-connectivity-issues/"><u>Troubleshooting Steps: Resolving Rainbow Six Siege's Server Connectivity Issues</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209842427-9780994072504-4k6o4kl4k6v4kn4k6v4k6u4kn/"><u>நோக்கம் | Free Book</u></a></li>
</ul></div>

