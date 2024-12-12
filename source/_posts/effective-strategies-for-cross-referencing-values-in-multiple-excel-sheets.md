---
title: Effective Strategies for Cross-Referencing Values in Multiple Excel Sheets
date: 2024-12-10T17:37:23.140Z
updated: 2024-12-12T18:43:22.723Z
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

 In this example, you can see dollar signs ($) amongst the cell address. This is an absolute cell reference ([Find out more about absolute cell references](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/)).

 When referencing cells and ranges on different Excel files, the references are made absolute by default. You can change this to a relative reference if required.

 If you look at the formula when the referenced workbook is closed, it will contain the entire path to that file.

![Full file path of workbook in the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/closed-workbook.png) 

 Although creating references to other workbooks is straightforward, they are more susceptible to issues. Users creating or renaming folders and moving files can break these references and cause errors.

 Keeping data in one workbook, if possible, is more reliable.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Cross Reference a Cell Range in a Function

 Referencing a single cell is useful enough. But you might want to write a function (such as SUM) that references a range of cells on another worksheet or workbook.

 Start the function as usual and then click on the sheet and the range of cells---the same way you did in the previous examples.

 In the following example, a SUM function is summing the values from range B2:B6 on a worksheet named Sales.

=SUM(Sales!B2:B6)

![Sheet cross reference in sum function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/range-in-function.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 You can then use the buttons along the top to edit and delete these defined names.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Format Data as a Table

 When working with an extensive list of related data, using Excel's Format as Table feature can simplify the way that you reference data in it.

 Take the following simple table.

![Small list of product sales data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/small-list.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This could be formatted as a table.

 Click on a cell in the list, switch to the "Home" tab, click the "Format as Table" button, and then select a style.

![Format a range as a table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/format-as-table.png) 

 Confirm that the range of cells is correct and that your table has headers.

![Confirm the range to use for the table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/confirm-range.png) 

 You can then assign a meaningful name to your table from the "Design" tab.

![Assign a name to your Excel table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/table-name.png) 

 Then, if we needed to sum the sales of Chicago, we could refer to the table by its name (from any sheet), followed by a square bracket (\[) to see a list of the table's columns.

![Using structured references in formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/structured-references.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select the column by double-clicking it in the list and enter a closing square bracket. The resulting formula would look something like this:

=SUM(Sales[Chicago])

 You can see how tables can make referencing data for aggregation functions such as SUM and AVERAGE easier than standard sheet references.

 This table is small for the purposes of demonstration. The larger the table and the more sheets you have in a workbook, the more benefits you'll see.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Below is an illustration of how this formula searches the list and returns the correct information.

![The VLOOKUP function and how it works](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/found-1282.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-approaches.techidaily.com/new-lut-techniques-for-professional-color-grading-and-correction/"><u>[New] LUT Techniques for Professional Color Grading and Correction</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-hurry-up-screen-record-with-audio/"><u>[Updated] Hurry-Up Screen Record, With Audio</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-elevating-your-video-with-expert-gopro-studio-techniques/"><u>[Updated] In 2024, Elevating Your Video with Expert GoPro Studio Techniques</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-pro-convertors-guide-top-10-online-free-transformers-listed/"><u>2024 Approved Pro Convertors Guide Top 10 Online, Free Transformers Listed</u></a></li>
<li><a href="https://fake-location.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhanced-fix-for-crashing-issue-in-software-name-on-pc/"><u>Enhanced Fix for 'Crashing' Issue in [Software Name] on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-xiaomi-civi-3-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Xiaomi Civi 3</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-asus-rog-phone-7-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Asus ROG Phone 7 Screen | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leveraging-hashtags-for-a-huge-impact-on-your-youtube-views-for-2024/"><u>Leveraging #Hashtags for a Huge Impact on Your YouTube Views for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-imessage-authentication-problems-on-iphone-expert-tips-and-tricks/"><u>Overcoming iMessage Authentication Problems on iPhone – Expert Tips and Tricks</u></a></li>
<li><a href="https://win-blog.techidaily.com/tech-tips-for-a-lag-free-adventure-in-forza-horizon-5-racing-game/"><u>Tech Tips for a Lag-Free Adventure in Forza Horizon 5 Racing Game</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723012877521-troubleshoot-and-repair-your-game-fast-fixes-for-league-of-legends-crashes/"><u>Troubleshoot & Repair Your Game: Fast Fixes for League of Legends Crashes!</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-gpeditmsc-access-issues-in-windows-home-edition/"><u>Troubleshooting 'gpedit.msc' Access Issues in Windows Home Edition</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-for-fixing-memory-error-12707-on-modern-warfare-3/"><u>Troubleshooting Steps for Fixing Memory Error 12707 on Modern Warfare 3</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-stop-frequent-pc-shutdowns-the-super-solution/"><u>Troubleshooting Steps: Stop Frequent PC Shutdowns - The Super Solution</u></a></li>
<li><a href="https://win-blog.techidaily.com/winning-over-the-dark-side-troubleshooting-fortnites-windowed-woes/"><u>Winning Over The Dark Side: Troubleshooting Fortnite's Windowed Woes</u></a></li>
</ul></div>

