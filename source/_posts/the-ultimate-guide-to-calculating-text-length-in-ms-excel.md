---
title: The Ultimate Guide to Calculating Text Length in MS Excel
date: 2024-12-06T17:53:28.730Z
updated: 2024-12-12T18:44:08.782Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## The Ultimate Guide to Calculating Text Length in MS Excel

### Quick Links

* [How to Get the Character Count of a Single Cell](https://extra-approaches.techidaily.com/2024-approved-prime-pictures-visuals-for-livestream-excellence/)
* [How to Get the Character Count of Multiple Cells](https://extra-lessons.techidaily.com/reviving-shadows-and-highlights-in-iphone-hdr-footage-with-premiere-pro/)
* [How to Get the Count of a Specific Character in a Cell](https://remote-screen-capture.techidaily.com/new-most-reliable-no-cost-chrome-os-recorder-tools-for-2024/)

 Unlike Word where you can easily [get the document's character count](https://tech-savvy.techidaily.com/ai-and-healthcare-how-can-chatgpt-innovate/) using a tool in the menu bar, you'll need to use the [LEN function](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) if you want to get a character count in Excel. Here's how to use it.

##  How to Get the Character Count of a Single Cell

 You can use the LEN function to quickly count the number of characters in a single cell in two different ways.

 To use the LEN function to get the character count, click the cell you would like to place the character count in. After that, type 

        `=LEN(cell)`
    
 , where cell is the actual cell you want to get the character count of. So if you want to get the character count of cell A1, you'd enter:

=LEN(A1)

![Enter the LEN function in a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-function-in-a-cell..png) 

 Click on any other cell and the character count will appear.

![The character count of cell A1.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-character-count-of-cell-A1..png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Or, you can simply copy the content of the cell you want to get the character count of, paste it in the formula in place of the reference cell, and wrap it in quotation marks. For example:

=LEN("How many characters are in this cell?")

![Paste the content of the cell in the formula.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Paste-the-content-of-the-cell-in-the-formula..png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will return the same result.

 If you're parsing data, you may also want to [split your text across multiple columns](https://tiktok-clips.techidaily.com/2024-approved-speeding-up-tiktok-videos-made-simple/).

##  How to Get the Character Count of Multiple Cells

 The LEN function can also be used in combination with the SUM function to get the character count of multiple cells. First, click the cell you would like to place the word count in. Next, enter this formula:

=SUM(LEN(A1),LEN(A2))

 Replace the cell numbers with your own.

![Enter the LEN and SUM function combination.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-and-SUM-function-combination..png) 

 Click on any other cell and the character count will be returned.

![The character count of cells A1 and A2.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-character-count-of-cells-A1-and-A2..png) 

 You can add as many cells as you like in the formula.

 It's also easy to [combine text](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) from these different cells into one.

Related: [How to Combine Text from Multiple Cells into One Cell in Excel](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Get the Count of a Specific Character in a Cell

 You can also use the LEN function to get the count of how many times a specific character appears in a cell. Select the cell you'd like the count to be returned in and then enter this formula:

=LEN(A1)-LEN(SUBSTITUTE(A1,"a",""))

 Replace the cell (`A1`) with your reference cell and `a` with the character you'd like to get the count of. In our case, we're searching for how many times `a` appears in cell A1.

![Enter the LEN function to get the specific character count.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-function-to-get-the-specific-character-count..png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on any other cell and the count of the specified character will be returned.

![The count of the specified character.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-count-of-the-specified-character..png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's all there is to it. Excel is full of [extremely useful functions](https://some-techniques.techidaily.com/new-exploring-whatsapp-voice-chat-features/), from the [COUNTIF function](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) to the [FREQUENCY function](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) to many [different Logical functions](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/), all designed to streamline your workflow.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-videography-secrets-leveraging-strikethrough-for-impactful-edits/"><u>[New] In 2024, Videography Secrets Leveraging Strikethrough for Impactful Edits</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-jokejumper-generate-share-worthy-images-quickly/"><u>[New] JokeJumper Generate Share-Worthy Images Quickly</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-peervid-grabber-fb-live/"><u>[Updated] 2024 Approved PeerVid Grabber FB Live</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-tech-solutions-overcoming-windows-driver-power-failures-easily/"><u>DIY Tech Solutions: Overcoming Windows Driver Power Failures Easily</u></a></li>
<li><a href="https://win-blog.techidaily.com/five-essential-fixes-for-a-stable-world-of-warships-gameplay-on-windowslinux-pcs/"><u>Five Essential Fixes for a Stable World of Warships Gameplay on Windows/Linux PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722994138449-fortnite-loading-screen-issue-solutions-for-getting-unstuck/"><u>Fortnite Loading Screen Issue - Solutions for Getting Unstuck</u></a></li>
<li><a href="https://win-blog.techidaily.com/get-back-to-battling-in-valorant-expert-fixes-for-pc-startup-failures-updated-for-2econd/"><u>Get Back to Battling in Valorant: Expert Fixes for PC Startup Failures (Updated for 2Econd)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-determine-if-robloxs-downtime-affects-everyone-or-just-your-connection/"><u>How to Determine if Roblox's Downtime Affects Everyone or Just Your Connection.</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-prevent-hearthstone-from-freezing-and-crashing-on-your-computer-expert-tips/"><u>How to Prevent Hearthstone From Freezing and Crashing on Your Computer - Expert Tips</u></a></li>
<li><a href="https://article-tips.techidaily.com/launching-joining-and-scheduling-zoom-calls-made-simple-for-android-users-for-2024/"><u>Launching, Joining, and Scheduling Zoom Calls Made Simple for Android Users for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-rectifying-lack-of-sound-in-pc-version-of-borderlands-3-gameplay/"><u>Solved! Rectifying Lack of Sound in PC Version of Borderlands 3 Gameplay</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steam-how-to-speed-up-a-lagging-stream/"><u>Troubleshooting Steam: How to Speed Up a Lagging Stream</u></a></li>
<li><a href="https://win-blog.techidaily.com/war-thunder-gaming-prowess-unleashed-fps-optimization-guide-and-troubleshooting-steps-to-conquer-2eep-play/"><u>War Thunder Gaming Prowess Unleashed: FPS Optimization Guide & Troubleshooting Steps to Conquer 2Eep Play</u></a></li>
</ul></div>

