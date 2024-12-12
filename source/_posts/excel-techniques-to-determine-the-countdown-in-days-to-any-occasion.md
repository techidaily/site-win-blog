---
title: Excel Techniques to Determine the Countdown in Days to Any Occasion
date: 2024-12-06T16:00:24.582Z
updated: 2024-12-12T19:39:40.958Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-grey-background.png.png
---

## Excel Techniques to Determine the Countdown in Days to Any Occasion

### Quick Links

* [A Quick Summary of Date-Related Functions](https://extra-support.techidaily.com/is-there-a-business-model-for-shopping-blog-reviews-in-2024/)
* [Some Example Calculations](https://youtube-lab.techidaily.com/ed-juggling-youtube-success-and-full-time-work-a-guide-for-2024/)

 Excel treats dates as integers. This means you can add and subtract them, which can be useful for telling you how many days there are until that next deadline or event of yours. In this article, we will use Excel's DATE, YEAR, MONTH, DAY, and TODAY functions to show you how to calculate the number of days until your next birthday or any other annual event.

 Excel stores dates as integers. By default, Excel uses "1" to represent 01/01/1900 and each day after that is one greater. Type in 01/01/2000 and switch the format to "Number" and you'll see "36526" appear. If you subtract 1 from 36526, you can see that there were 36525 days in the 20th century. Alternatively, you could enter a future date and subtract the result of the TODAY function to see how many days away that date is from today.

##  A Quick Summary of Date-Related Functions

 Before we dive into some examples, we need to go over several simple date-related functions, including Excel's TODAY, DATE, YEAR, MONTH, and DAY functions.

###  TODAY

 Syntax: =TODAY()

 Result: The current date

###  DATE

 Syntax: =DATE(year,month,day)

 Result: The date designated by the year, month, and day entered

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  YEAR

 Syntax: =YEAR(date)

 Result: The year of the date entered

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  MONTH

 Syntax: =MONTH(date)

 Result: The numerical month of the date entered (1 through 12)

###  DAY

 Syntax: =DAY(date)

 Result: The day of the month of the date entered

##  Some Example Calculations

 We will look at three events that occur annually on the same day, calculate the date of their next occurrence, and determine the number of days between now and their next occurrence.

 Here is our sample data. We've got four columns set up: Event, Date, Next\_Occurrence, and Days\_Until\_Next. We have entered the dates of a random birth date, the date taxes are due in the U.S., and Halloween. Dates like birthdays, anniversaries, and some holidays occur on specific days each year and work well with this example. Other holidays---like Thanksgiving---occur on a particular weekday in a specific month; this example does not cover those types of events.

![Example Data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-01.png) 

 There are two options for filling in the 'Next\_Occurrence' column. You can hand-enter each date, but each entry will need to be manually updated in the future as the date passes. Instead, let's write an 'IF' statement formula so that Excel can do the work for you.

 Let's look at the birthday. We already know the month 

        `=MONTH(F3)`
    
 and day 

        `=DAY(F3)`
    
 of the next occurrence. That's easy, but what about the year? We need Excel to know whether the birthday has occurred in this year already or not. First, we need to calculate the date on which the birthday occurs in the present year using this formula:

=DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))

 Next, we need to know if that date has already passed and you can compare that result to `TODAY()` to find out. If it is July and the birthday occurs every September, then the next occurrence is in the current year, shown with `=YEAR(TODAY())` . If it is December and the birthday occurs every May, then the next occurrence is in the next year, so `=YEAR(TODAY())+1` would give the next year. To determine which to use, we can use an 'IF' statement:

=IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1)

 Now we can combine the results of the IF statement with the MONTH and DAY of the birthday to determine the next occurrence. Enter this formula into cell G3:

=DATE(IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1),MONTH(F3),DAY(F3))

![Entering "=DATE(IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1),MONTH(F3),DAY(F3))" into cell F3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-02.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Hit Enter to see the result. (This article was written in late January 2019, so the dates will be...well...dated.)

 Fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Next Occurrence Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-03.png) 

 Now we can easily determine the number of days until the next occurrence by subtracting the result of the TODAY() function from the Next\_Occurrence results we just calculated. Enter the following formula into cell H3:

=G3-TODAY()

![Enter "=G3-TODAY()" into cell H3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-04.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Press Enter to see the result and then fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Days_Until_Next Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-05.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can save a workbook with the formulas in this example to keep track of whose birthday is coming up next or know how many days you have left to finish your Halloween costume. Each time you use the workbook, it will recalculate the results based on the current date because you've used the `TODAY()` function.

![Example Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-06.png) 

 And yes, these are pretty specific examples that might or might not be useful to you. But, they also serve to illustrate the kinds of things you can do with date-related functions in Excel.

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
<li><a href="https://fox-helps.techidaily.com/new-engaging-audiences-the-impact-of-adding-youtube-music-to-videos/"><u>[New] Engaging Audiences The Impact of Adding YouTube Music to Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-learn-to-fine-tune-youtube-videos-for-efficient-consumption/"><u>[New] In 2024, Learn to Fine-Tune YouTube Videos for Efficient Consumption</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-virtual-producers-showdown/"><u>[New] In 2024, Virtual Producer's Showdown</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-integrating-youtube-into-your-imovie-projects/"><u>[Updated] 2024 Approved Integrating YouTube Into Your iMovie Projects</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-make-memories-not-videos-top-10-buzz-creating-tiktok-hacks/"><u>[Updated] 2024 Approved Make Memories, Not Videos! Top 10 Buzz-Creating TikTok Hacks</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-uncovering-the-secrets-of-enhancing-tiktok-profiles-with-linktree/"><u>[Updated] 2024 Approved Uncovering the Secrets of Enhancing TikTok Profiles with Linktree</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-streaming-success-youtube-broadcasts-of-google-meet/"><u>[Updated] In 2024, Streaming Success YouTube Broadcasts of Google Meet</u></a></li>
<li><a href="https://win-blog.techidaily.com/conquer-nba-2k23-pc-crashes-discover-the-7-best-strategies-to-keep-playing-seamlessly/"><u>Conquer NBA 2K23 PC Crashes: Discover the 7 Best Strategies to Keep Playing Seamlessly</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-to-keep-stardew-valley-running-smoothly-on-pc-without-interruptions/"><u>Effective Solutions to Keep Stardew Valley Running Smoothly on PC Without Interruptions</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-the-deadly-glitch-of-ghostrunner-game-on-windows-11-systems/"><u>Fixing the Deadly Glitch of Ghostrunner Game on Windows 11 Systems</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-7-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone 7 to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/navigating-through-stormy-seas-understanding-startups-akin-to-an-atomic-heart/"><u>Navigating Through Stormy Seas: Understanding Startups Akin to an 'Atomic Heart'</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-launch-problems-in-crusader-kings-2-a-comprehensive-troubleshooting-tutorial/"><u>Overcoming Launch Problems in Crusader Kings 2 - A Comprehensive Troubleshooting Tutorial</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-minecraft-freezing-issues-on-your-computer/"><u>Resolving Minecraft Freezing Issues on Your Computer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-to-downloading-specific-portions-of-youtube-footage/"><u>Step-by-Step Guide to Downloading Specific Portions of YouTube Footage</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-fix-the-issue-when-immortals-fenyx-rising-wont-start/"><u>Troubleshooting: Fix the Issue When Immortals Fenyx Rising Won't Start</u></a></li>
</ul></div>

