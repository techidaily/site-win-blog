---
title: "Unlocking Efficiency with Excel's Subtotal Feature: An In-Depth Tutorial for Professionals and Students Alike"
date: 2024-08-26 19:41:16
updated: 2024-08-29 11:58:54
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f0d0c2a077419838d019249854e895427fabffcbae9e8b50e548bd608d26f443.PNG
---

## Unlocking Efficiency with Excel's Subtotal Feature: An In-Depth Tutorial for Professionals and Students Alike

### Quick Links

* [What Is a Subtotal in Excel?](https://extra-guidance.techidaily.com/2024-approved-masterclass-in-minimal-photoshop-alterations/)
* [Use the Excel SUBTOTAL Function](https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-s17e-drfone-by-drfone-virtual-android/)
* [Use the Subtotal Feature](https://data-safeguard.techidaily.com/cookiebot-enabled-enhance-your-sites-analytics-and-personalization/)

### Key Takeaways

 To use the SUBTOTAL function, create a formula using the syntax: SUBTOTAL(function\_number, reference 1, reference 2,...). You can also use the Subtotal feature by selecting your rows, then clicking the "Data" tab. In the Outline drop-down menu, select "Subtotal."

 Obtaining subtotals for groups of related items is easy in Microsoft Excel. In fact, you have two ways to do this. You can either use the SUBTOTAL function or the Subtotal feature, whichever works best. We'll show you how.

##  What Is a Subtotal in Excel?

 As mentioned, SUBTOTAL in Excel allows you to group the same or related items in a list and use a function to calculate the values. For example, you can use it to sum sales by month or average grades by student. You could also add inventory by product or [count the number](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) of bills due next week.

 Using the SUBTOTAL function by creating a formula or using the Subtotal feature, you can get the calculations you need in just a few steps.

##  Use the Excel SUBTOTAL Function

 You can create a formula using the Excel SUBTOTAL function with the flexibility to include or exclude rows you've hidden.

 The syntax for the formula is

        `SUBTOTAL(function_number, reference 1, reference 2,...)`
    
 where the first two arguments are required. You can use additional cell references or [named ranges](https://some-skills.techidaily.com/new-the-impact-of-testimonial-videos-today/) for the remaining arguments as needed.

 The

        `function_number`
    
 argument allows you to insert one of 11 functions using its corresponding number. The first 11 include hidden rows, while the second 11 exclude them. So, simply insert the number for [the function you need](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) and how you want to handle the hidden rows.

| Function | Include Hidden Rows | Exclude Hidden Rows |
| -------- | ------------------- | ------------------- |
| AVERAGE  | 1                   | 101                 |
| COUNT    | 2                   | 102                 |
| COUNTA   | 3                   | 103                 |
| MAX      | 4                   | 104                 |
| MIN      | 5                   | 105                 |
| PRODUCT  | 6                   | 106                 |
| STDEV    | 7                   | 107                 |
| STDEVP   | 8                   | 108                 |
| SUM      | 9                   | 109                 |
| VAR      | 10                  | 110                 |
| VARP     | 11                  | 111                 |

 As an example of the SUBTOTAL function, we'll sum the total of sales in the cell range B2 through B4 using this formula:

=SUBTOTAL(9,B2:B4)

![Basic subtotal formula in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/BasicFormula-ExcelSubtotal.png) 

 For this next example, we hid rows 4 and 5\. Using this first formula, we can obtain our sum using the number 9 for the first argument to include the hidden data.

=SUBTOTAL(9,B2:B6)

![SUBTOTAL function including hidden rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SumIncludeHidden-ExcelSubtotal.png) 

 Now, we'll exclude those hidden rows from our total, using the number 109 for our first argument.

=SUBTOTAL(109,B2:B6)

![SUBTOTAL function excluding hidden rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SumExcludeHidden-ExcelSubtotal.png) 

 Once you have your subtotals, you can use the SUBTOTAL function once more for a grand total at the bottom. Alternatively, you can use [the SUM function](https://techtrends.techidaily.com/your-guide-to-securing-great-deals-on-apple-watch-models-this-month/) to add the subtotals.

Related: [How to Sum a Column in Microsoft Excel](https://techtrends.techidaily.com/your-guide-to-securing-great-deals-on-apple-watch-models-this-month/) 

 For another example, we'll use the [average function](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) to include hidden rows 3 and 4 with this formula:

=SUBTOTAL(1,C2:C6)

![SUBTOTAL function including hidden rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/AverageIncludeHidden-ExcelSubtotal.png) 

 And next, we'll exclude the hidden rows with this formula:

=SUBTOTAL(101,C2:C6)

![SUBTOTAL function excluding hidden rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/AverageExcludeHidden-ExcelSubtotal.png) 

###  Notes on the SUBTOTAL Function

 Here are a few things to keep in mind when using the SUBTOTAL function in Excel:

* The function works for columns or vertical ranges, not rows or horizontal ranges.
* If you have nested subtotals in the reference argument area, Excel ignores these in the subtotal result.
* When you [use a filter](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/), the data filtered out is excluded from the subtotal result.

##  Use the Subtotal Feature

 Another way to use the SUBTOTAL function in Excel is by using the Subtotal feature. This way, you can automatically [add calculations](https://fox-http.techidaily.com/updated-expert-guide-windows-movie-maker-60-configuration-for-2024/) and group the items at the same time. Excel uses the SUBTOTAL function to accomplish this for you. Let's look at a couple of examples.

Related: [How to Calculate Workdays With a Function in Microsoft Excel](https://fox-http.techidaily.com/updated-expert-guide-windows-movie-maker-60-configuration-for-2024/) 

 Using the Subtotal feature for our sales by month, we can group the data per month and sum each group with a grand total at the bottom.

 Select all of the rows you want to group and subtotal. Go to the Data tab and pick "Subtotal" in the Outline drop-down menu.

![Subtotal in the Outline menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/OutlineSubtotal-ExcelSubtotal.png) 

 When the Subtotal box opens, choose how you want to add the subtotals.

* **At Each Change In** **:** Select the column you want to use for the grouping. Here, we picked Month so that a new group is created when the Month changes in the sheet.
* **Use Function** **:** Select the function you want to use, such as sum, average, minimum, maximum, or another option. For our example, we selected Sum.
* **Add Subtotal to** **:** Check the box for where you want the subtotal to calculate. For our example, we picked Sales.

 Optionally check the boxes at the bottom for the additional items as you like. Click "OK."

![Subtotal settings for the Sum function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SubtotalSettingsSum-ExcelSubtotal.png) 

 You'll then see your data update to group _and_ subtotal the rows and create a grand total at the bottom. Use the plus, minus, and number buttons to collapse or expand the groups for easier viewing.

![Subtotal for the Sum function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SubtotalSum-ExcelSubtotal.png) 

 As another example, we'll use student grades. We'll use the Subtotal and Group features to display an average grade for each student. Here's the process.

 Select the rows, go to Data, and pick "Subtotal" in the Outline drop-down menu.

 In the Subtotal box, we'll choose Student in the change drop-down list and Average in the function list. We'll then check the box for Grade. Click "OK."

![Subtotal settings for the Average function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SubtotalSettingsAverage-ExcelSubtotal.png) 

 We now have our rows grouped by student with an average grade for each and an overall average at the bottom. Again, you can use the buttons on the left to collapse and expand the groups.

![Subtotal for the Average function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SubtotalAverage-ExcelSubtotal.png) 

 If you decide to ungroup the rows after you use the Subtotal feature, the rows return to normal. However, those containing the SUBTOTAL function used by Excel remain for you to continue using or simply delete if you prefer.

![Subtotal average for ungrouped rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/SubtotalAverageUngrouped-ExcelSubtotal.png) 

 The Subtotal feature can become complex if you plan to use many groups. However, these basic examples should help get you started if you're interested in this function.

 One thing to note is that you can't [add an Excel table](https://instagram-videos.techidaily.com/updated-2024-approved-how-to-convert-your-best-videography-into-melodic-mp3s-insta/) subtotal with this feature. If you have your data in a table, you can either insert the Excel formula for SUBTOTAL as described earlier or [convert your table to a cell range](https://video-capture.techidaily.com/new-2024-approved-revolutionize-your-laptop-experience-innovative-methods-for-screen-capture/) to use the feature. If you choose the latter, you'll lose the table functionality.

 Now that you know how to insert subtotals in Excel, check out [how to remove duplicate rows](https://visual-screen-recording.techidaily.com/new-precision-in-capturing-androids-best-techniques-for-2024/).

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·** [MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  |

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
