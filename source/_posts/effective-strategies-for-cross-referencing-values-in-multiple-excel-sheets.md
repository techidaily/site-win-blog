---
title: Effective Strategies for Cross-Referencing Values in Multiple Excel Sheets
date: 2024-08-28T05:42:04.990Z
updated: 2024-08-29T05:42:04.990Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel.png
---

## Effective Strategies for Cross-Referencing Values in Multiple Excel Sheets

### Quick Links

* [How to Reference Another Sheet in the Same Excel File](https://sound-tweaking.techidaily.com/updated-the-ultimate-selection-of-six-compelling-chrome-talk-transformers-to-experience-moviemagicsuite-for-2024/)
* [How to Reference Another Excel File](https://technical-tips.techidaily.com/handling-msvbvm50dll-cannot-be-found-a-comprehensive-tutorial-for-quick-fixes/)
* [How to Cross Reference a Cell Range in a Function](https://facebook-video-content.techidaily.com/new-2024-approved-secure-your-social-media-experience-from-ad-interruptions/)
* [How to Use Defined Names for Simple Cross References](https://tech-revival.techidaily.com/the-efficient-approach-to-persona-creation-with-chatgpt/)
* [How to Format Data as a Table](https://screen-sharing-recording.techidaily.com/updated-master-classic-ps2-games-on-android-with-our-top-picks-for-2024/)
* [How to Use the VLOOKUP Function for Dynamic References](https://snapchat-videos.techidaily.com/2024-approved-ensuring-every-snapchatter-friendly-footage-via-mac/)

 In Microsoft Excel, it's a common task to refer to cells on other worksheets or even in different Excel files. At first, this can seem a little daunting and confusing, but once you understand how it works, it's not so hard.

 In this article, we'll look at how to reference another sheet in the same Excel file and how to reference a different Excel file. We'll also cover things like how to reference a cell range in a function, how to make things simpler with defined names, and how to use VLOOKUP for dynamic references.

##  How to Reference Another Sheet in the Same Excel File

 A basic cell reference is written as the column letter followed by the row number.

 So the cell reference B3 refers to the cell at the intersection of column B and row 3.

 When referring to cells on other sheets, this cell reference is preceded with the other sheet's name. For example, below is a reference to cell B3 on a sheet name "January."

=January!B3

 The exclamation point (!) separates the sheet name from the cell address.

 If the sheet name contains spaces, then you must enclose the name with single quotation marks in the reference.

='January Sales'!B3

 To create these references, you can type them directly into the cell. However, it is easier and more reliable to let Excel write the reference for you.

 Type an equal sign (=) into a cell, click on the Sheet tab, and then click the cell that you want to cross-reference.

 As you do this, Excel writes the reference for you in the Formula Bar.

![Sheet reference in formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/sheet-reference-2.png) 

 Press Enter to complete the formula.

##  How to Reference Another Excel File

 You can refer to cells of another workbook using the same method. Just be sure that you have the other Excel file open before you begin typing the formula.

 Type an equal sign (=), switch to the other file, and then click the cell in that file you want to reference. Press Enter when you're done.

 The completed cross-reference contains the other workbook name enclosed in square brackets, followed by the sheet name and cell number.

=[Chicago.xlsx]January!B3

 If the file or sheet name contains spaces, then you'll need to enclose the file reference (including the square brackets) in single quotation marks.

='[New York.xlsx]January'!B3

![Formula that references another workbook](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/workbook-reference.png) 

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In this example, you can see dollar signs ($) amongst the cell address. This is an absolute cell reference ([Find out more about absolute cell references](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/)).

 When referencing cells and ranges on different Excel files, the references are made absolute by default. You can change this to a relative reference if required.

 If you look at the formula when the referenced workbook is closed, it will contain the entire path to that file.

![Full file path of workbook in the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/closed-workbook.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Although creating references to other workbooks is straightforward, they are more susceptible to issues. Users creating or renaming folders and moving files can break these references and cause errors.

 Keeping data in one workbook, if possible, is more reliable.

##  How to Cross Reference a Cell Range in a Function

 Referencing a single cell is useful enough. But you might want to write a function (such as SUM) that references a range of cells on another worksheet or workbook.

 Start the function as usual and then click on the sheet and the range of cells---the same way you did in the previous examples.

 In the following example, a SUM function is summing the values from range B2:B6 on a worksheet named Sales.

=SUM(Sales!B2:B6)

![Sheet cross reference in sum function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/range-in-function.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use Defined Names for Simple Cross References

 In Excel, you can assign a name to a cell or range of cells. This is more meaningful than a cell or range address when you look back at them. If you use a lot of references in your spreadsheet, naming those references can make it much easier to see what you've done.

 Even better, this name is unique for all the worksheets in that Excel file.

 For example, we could name a cell 'ChicagoTotal' and then the cross-reference would read:

=ChicagoTotal

 This is a more meaningful alternative to a standard reference like this:

=Sales!B2

 It's easy to create a defined name. Start by selecting the cell or range of cells that you want to name.

 Click in the Name Box in the top left corner, type the name you want to assign, and then press Enter.

![Defining a name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/defined-name.png) 

 When creating defined names, you cannot use spaces. Therefore, in this example, the words have been joined in the name and separated by a capital letter. You could also separate words with characters like a hyphen (-) or underscore (\_).

 Excel also has a Name Manager that makes monitoring these names in the future easy. Click Formulas > Name Manager. In the Name Manager window, you can see a list of all of the defined names in the workbook, where they are, and what values they currently store.

![Name Manager to manage the defined names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/name-manager.png) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can then use the buttons along the top to edit and delete these defined names.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Format Data as a Table

 When working with an extensive list of related data, using Excel's Format as Table feature can simplify the way that you reference data in it.

 Take the following simple table.

![Small list of product sales data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/small-list.png) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This could be formatted as a table.

 Click on a cell in the list, switch to the "Home" tab, click the "Format as Table" button, and then select a style.

![Format a range as a table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/format-as-table.png) 

 Confirm that the range of cells is correct and that your table has headers.

![Confirm the range to use for the table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/confirm-range.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 You can then assign a meaningful name to your table from the "Design" tab.

![Assign a name to your Excel table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/table-name.png) 

 Then, if we needed to sum the sales of Chicago, we could refer to the table by its name (from any sheet), followed by a square bracket (\[) to see a list of the table's columns.

![Using structured references in formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/structured-references.png) 

 Select the column by double-clicking it in the list and enter a closing square bracket. The resulting formula would look something like this:

=SUM(Sales[Chicago])

 You can see how tables can make referencing data for aggregation functions such as SUM and AVERAGE easier than standard sheet references.

 This table is small for the purposes of demonstration. The larger the table and the more sheets you have in a workbook, the more benefits you'll see.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
##  How to Use the VLOOKUP Function for Dynamic References

 The references used in the examples thus far have all been fixed to a specific cell or range of cells. That's great and is often sufficient for your needs.

 However, what if the cell you are referencing has the potential to change when new rows are inserted, or somebody sorts the list?

 In those scenarios, you could not guarantee the value you want will still be in the same cell that you initially referenced.

 An alternative in these scenarios is to use a lookup function within Excel to search for the value in a list. This makes it more durable against changes to the sheet.

 In the following example, we use the VLOOKUP function to look up an employee on another sheet by their employee ID and then return their start date.

 Below is the example list of employees.

![List of employees](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/employees.png) 

 The VLOOKUP function looks down the first column of a table and then returns information from a specified column to the right.

 The following VLOOKUP function searches for the employee ID entered into cell A2 in the list shown above and returns the date joined from column 4 (fourth column of the table).

=VLOOKUP(A2,Employees!A:E,4,FALSE)

![The VLOOKUP function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/vlookup.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 Below is an illustration of how this formula searches the list and returns the correct information.

![The VLOOKUP function and how it works](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/found-1282.png) 

 The great thing about this VLOOKUP over the previous examples is that the employee will be found even if the list changes in order.

**Note:** VLOOKUP is an incredibly useful formula, and we've only scratched the surface of its value in this article. You can find out more about how to use VLOOKUP from [our article on the subject](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/).

---

 In this article, we have looked at multiple ways to cross-reference between Excel spreadsheets and workbooks. Choose the approach that works for your task at hand, and that you feel comfortable working with.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-crafting-connection-tips-and-tricks-for-sharing-content-via-facebook/"><u>[New] In 2024, Crafting Connection  Tips and Tricks for Sharing Content via Facebook</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-parrots-drone-redesign-advanced-edition-review/"><u>[New] Parrot's Drone Redesign - Advanced Edition Review</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-tranquil-escapes-top-12-pc-titles/"><u>[New] Tranquil Escapes  Top 12 PC Titles</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-brand-differentiation-with-powerful-youtube-names-for-2024/"><u>[Updated] Brand Differentiation with Powerful YouTube Names for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-chart-toppers-on-screen-uploading-songs-methodically/"><u>[Updated] In 2024, Chart-Toppers on Screen  Uploading Songs Methodically</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-tunetruthseeker-reaction-to-songs-and-speech/"><u>2024 Approved  TuneTruthseeker  Reaction to Songs and Speech</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unlocking-visual-storytelling-the-20-key-strategies-for-powerful-fb-video-marketing/"><u>2024 Approved  Unlocking Visual Storytelling  The 20 Key Strategies for Powerful FB Video Marketing</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722971118913-aircraft-engaged-in-parachute-landing-aircraft-activities/"><u>Aircraft Engaged in Parachute Landing Aircraft Activities</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/best-mac-screen-clips-roundup-under-156-chars/"><u>Best Mac Screen Clips Roundup (Under 156 Chars)</u></a></li>
<li><a href="https://win-forum.techidaily.com/boost-your-pcs-performance-on-windows-11-by-securing-extra-disk-space-with-proven-techniques/"><u>Boost Your PC's Performance on Windows 11 by Securing Extra Disk Space with Proven Techniques</u></a></li>
<li><a href="https://win-blog.techidaily.com/cracking-down-on-cyberpunk-2077s-troubles-an-in-depth-look-at-error-2024/"><u>Cracking Down on Cyberpunk 2077'S Troubles: An In-Depth Look at Error #2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/crusader-kings-ii-wont-start-troubleshooting-solutions-inside/"><u>Crusader Kings II Won't Start? Troubleshooting Solutions Inside</u></a></li>
<li><a href="https://win-blog.techidaily.com/dead-by-daylight-crash-troubleshooting-expert-hacks-for-steady-performance/"><u>Dead by Daylight Crash Troubleshooting: Expert Hacks for Steady Performance</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-strategies-to-fix-gtfo-app-crashes/"><u>Effective Strategies to Fix GTFO App Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-ways-to-address-fallout-3-stability-problems-on-windows-11/"><u>Effective Ways to Address Fallout 3 Stability Problems on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722991513223-fix-for-when-warzone-ignores-your-gpu-on-windows-10-devices-now-solved/"><u>Fix for When Warzone Ignores Your GPU on Windows 10 Devices - Now Solved!</u></a></li>
<li><a href="https://win-blog.techidaily.com/game-saving-tips-overcoming-crashes-and-bugs-in-final-fantasy-xv-on-pc-platforms/"><u>Game-Saving Tips: Overcoming Crashes and Bugs in Final Fantasy XV on PC Platforms</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-common-problems-with-twitch-livestreams-discover-our-top-7-tips/"><u>How to Fix Common Problems With Twitch Livestreams - Discover Our Top 7 Tips</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-repair-palworld-session-search-glitches-quickly/"><u>How to Repair Palworld Session Search Glitches Quickly</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-age-of-wonders-planetfall-from-crashing-on-your-windows-computer/"><u>How to Stop Age of Wonders: Planetfall From Crashing on Your Windows Computer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-reimagine-reality-techniques-for-astonishing-image-distortions/"><u>In 2024, Reimagine Reality  Techniques for Astonishing Image Distortions</u></a></li>
<li><a href="https://win-blog.techidaily.com/league-of-legends-solved-network-troubles-and-how-to-fix-them/"><u>League of Legends: Solved Network Troubles & How To Fix Them</u></a></li>
<li><a href="https://win-blog.techidaily.com/light-up-your-video-chats-avoiding-and-resolving-zooms-notorious-pc-black-screen/"><u>Light Up Your Video Chats: Avoiding and Resolving Zoom's Notorious PC Black Screen</u></a></li>
<li><a href="https://win-blog.techidaily.com/login-to-your-origin-account-is-now-fully-operational/"><u>Login to Your Origin Account Is Now Fully Operational</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-troubleshooting-solving-assassins-creed-odyssey-pc-game-crashes/"><u>Master Troubleshooting: Solving Assassin's Creed Odyssey PC Game Crashes</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-lan-party-hurdles-in-rainbow-six-siege-solving-server-link-up-challenges/"><u>Overcoming LAN Party Hurdles in Rainbow Six Siege: Solving Server Link-Up Challenges</u></a></li>
<li><a href="https://win-blog.techidaily.com/play-the-exciting-days-gone-first-person-shooter-on-your-personal-computer/"><u>Play the Exciting 'Days Gone' First-Person Shooter on Your Personal Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-persistent-system-failures-in-watch-dogs-legion-for-windows-users/"><u>Resolving Persistent System Failures in Watch Dogs: Legion for Windows Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-tips-for-updating-outdated-drivers-in-minecraft-get-back-to-playing/"><u>Solution Tips for Updating Outdated Drivers in Minecraft – Get Back to Playing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/solved-move-from-honor-play-8t-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Solved Move from Honor Play 8T to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-the-error-code-0xc19001e1-on-windows-11-a-comprehensive-guide/"><u>Solving the 'Error Code 0xC19001E1' On Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-how-to-fix-lagging-or-frozen-pubg-games-on-your-computer/"><u>Step-by-Step Guide: How to Fix Lagging or Frozen PUBG Games on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-solution-addressing-non-functional-content-warnings-during-voice-chats/"><u>Step-by-Step Solution: Addressing Non-Functional Content Warnings During Voice Chats</u></a></li>
<li><a href="https://win-blog.techidaily.com/steps-to-rectify-problems-with-non-responsive-msi-gt80-laptops/"><u>Steps to Rectify Problems with Non-Responsive MSI GT80 Laptops</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-when-amd-radeon-software-fails-to-launch/"><u>Troubleshooting Steps When AMD Radeon Software Fails to Launch</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-troubleshooting-tips-to-resolve-slime-rancher-amidst-pc-system-crashes/"><u>Ultimate Troubleshooting Tips to Resolve Slime Rancher Amidst PC System Crashes</u></a></li>
<li><a href="https://techidaily.com/update-your-drivers-with-device-manager-on-windows-10-by-drivereasy-guide/"><u>Update your drivers with Device Manager on Windows 10</u></a></li>
<li><a href="https://win-blog.techidaily.com/xcom-2-stability-enhancements-for-windows-users-no-more-crashes/"><u>XCOM 2 Stability Enhancements for Windows Users - No More Crashes</u></a></li>
</ul></div>
