---
title: Dynamic Charting Techniques Using Dropdown Menus in Microsoft Excel
date: 2024-08-28T05:41:27.524Z
updated: 2024-08-29T05:41:27.524Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/an-excel-spreadsheet-with-a-3d-chart-and-the-excel-logo.jpg
---

## Dynamic Charting Techniques Using Dropdown Menus in Microsoft Excel

### Quick Links

* [Step 1: Create a Drop-down List](https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-oppo-reno-8t-drfone-by-drfone-reset-android-reset-android/)
* [Step 2: Create a Data Retrieval Table](https://extra-approaches.techidaily.com/maximize-viewership-with-smart-and-stylish-titles-for-2024/)
* [Step 3: Extract Data from Table 1 to Table 2](https://youtube-video-recordings.techidaily.com/new-efficient-techniques-ios-screenshots-and-youtube-content-creation/)
* [Step 4: Insert and Format Your Chart](https://video-capture.techidaily.com/2024-approved-macs-top-screen-recorders-face-off-bandicam-vs-camtasia/)
* [Step 5: Add an Average Line to Your Chart](https://easy-unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-poco-f5-pro-5g-phone-now-with-these-tips-by-drfone-android/)

 If you want to impress your friends and colleagues, you can make an Excel chart change based on a drop-down box you have added to your sheet. There are different ways you can achieve this, but we prefer the following method because it's easier to locate any issues if something goes wrong.

 We're going to use a table of data containing five soccer players' names and their game rating for five games as we talk you through the process.

##  Step 1: Create a Drop-down List

 The first step is to [create the drop-down list](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) that will make your chart dynamic. Start by typing an action word in the cell next to where your drop-down will go. In our example, we'll put the drop-down in cell B9, so we'll type our action word in cell A9\. Then, click the cell where your drop-down will go, head to the Data tab on the ribbon, and click "Data Validation" in the Data Tools group.

![An Excel worksheet. 'Choose' is typed into cell A9, cell B9 is selected, and the 'Data Validation' function is highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/data-validation-options.png) 

 In the Data Validation window, choose "List" under Allow. Then, click in the "Source" field box and highlight the column headings in your table (the data that will be shown in the drop-down list you're creating). In our example, we want to choose the game numbers, as in the chart we are going to create later, we want to see the players' ratings for each game. Then, click "OK."

![An Excel spreadsheet with the data validation window open. The Allow field contains the "List" option, and the Source field contains the column headers from the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/data-validation-list.png) 

 You will now see a drop-down list showing the data you selected when you click the arrow. We've also formatted our Choose cell to make it stand out.

![An Excel spreadsheet containing a table and a drop-down list with the options showing as the column headers in the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/drop-down-list-in-excel.png) 

##  Step 2: Create a Data Retrieval Table

 We now need to create a second table that is separate from our raw data but pulls information from it when we adjust the drop-down menu we have created. The chart we create later on will be created using the information in this data retrieval table.

 From this point, we'll call the main data table **Table 1**, and the data retrieval table **Table 2**.

 Highlight the row titles in Table 1, press Ctrl+C, and use Ctrl+V to copy the list where you want Table 2 to be.

![An Excel sheet with a table on the left, and the first column copied and pasted to the right.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/data-retrieval-table.png) 

 Select and right-click the pasted data, hover over "Sort," and click "Sort A To Z."

![An Excel spreadsheet with data in Table 2 selected, and the Sort A to Z option highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/sort-data-a-to-z.png) 

 To continue creating Table 2, you need to give the next column a heading. The data that appears in Table 2 will be dictated by what you select in your drop-down box, so in the cell where you want the heading to go, type **\=** and click the drop-down cell. In our case, we want our heading in cell I2, and in that cell, we will type **\=** and click cell B9.

![An Excel spreadsheet with a column in Table 2 referencing a drop-down cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/reference-drop-down-cell.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Press Enter to see the column heading in Table 2 adopt the drop-down selection. Try changing the drop-down selection to see the column heading in Table 2 change.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Step 3: Extract Data from Table 1 to Table 2

 We now need to extract the relevant data from Table 1 to Table 2 [using INDEX and MATCH](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/). This is the most complex part of the process, but let's break it down so that you can work through the process more easily. Here's the synax:

=INDEX(_a_,MATCH(_b_,_c_,0),MATCH(_d_,_e_,0))

 where

* _a_ is all the data in Table 1 (excluding the row and column headings),
* _b_ is the first value we're looking up in Table 2,
* _c_ is the range of values in the first column in Table 1,
* _d_ is the column heading in Table 2, and
* _e_ represents the data column headings in Table 1.

 Make sure cell references _a_, _c_, _d_, and _e_ are absolute references by pressing F4 on your keyboard after selecting each reference. Otherwise, your formula will not work when you complete the rest of the data in Table 2.

 Let's see this in action.

 In cell I3, we want to tell Excel to look in Table 1 and pull a value to Table 2 through the INDEX function.

=INDEX

 We now need to open the parenthesis and tell Excel where the data is in Table 1\. To do this, highlight all the data in Table 1, but _not_ the column and row headings. Press F4 to make this an absolute reference, and add a comma.

=INDEX**($B$3:$F$7,**

 The next step is to tell Excel to match the data in Table 2 with what we have in Table 1\. Type **MATCH**, open a new parenthesis, and click the first entry in the first column of Table 2\. In our case, that's Davies in cell H3\. Add a comma.

=INDEX($B$3:$F$7**,MATCH(H3,**

 Next, Excel needs to know what it will use as its reference to look up in Table 1\. In our case, it's the data from cell A3 to cell A7 (the names of the players), so highlight this range, press F4, and then add a comma. Then, type **0** (zero) to tell Excel that we're looking for an exact match, and close the parentheses. Add another comma.

=INDEX($B$3:$F$7,MATCH(H3,**$A$3:$A$7,0),**

 Now, we must repeat the MATCH process for the data that will change when we select a different option in the drop-down. In our case, that's the game number, so after typing MATCH into our formula for a second time, we will click I2, press F4, and add a comma.

=INDEX($B$3:$F$7,MATCH(H3,$A$3:$A$7,0),**MATCH($I$2,**

 And again, we need to tell Excel where to find that data in Table 1\. In our example, that's cells B2 to F4\. Don't forget to press F4 after you've referenced these cells. Then, add a comma, a 0, and close the two parentheses together. Finally, press Enter.

=INDEX($B$3:$F$7,MATCH(H3,$A$3:$A$7,0),MATCH($I$2,**$B$2:$F$2,0))**

 Now, click and drag the handle in the bottom-right corner of the cell where you've just typed your formula to automatically fill out the rest of the data in Table 2.

![A table in Excel being AutoFilled.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/autofill-table-2.png) 

 Try changing your drop-down option to a different value and see the data change in Table 2, and check that it aligns with the information in Table 1\. Remember that we sorted the first column in Table 2 alphabetically, so check carefully, as the first column in Table 1 will be in a different order!

![An Excel sheet with a drop-down selection changed to 'Game 3,' and Table 2 showing the data for this selection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/drop-down-with-data-in-table-2.png) 

 Now that Table 2 successfully changes depending on our drop-down selection, we're ready to create the chart.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##  Step 4: Insert and Format Your Chart

 Highlight all the data in Table 2 (including the column and row headers), open the "Insert" tab, and [choose a chart that works for you](https://technical-tips.techidaily.com/top-techniques-for-enhancing-photo-quality-on-your-ios-device/).

![An Excel spreadsheet with Table 2 selected and the charts highlighted in the Insert tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/create-chart.png) 

 We've gone with a simple 2D column chart.

![An Excel chart with the data chosen by a drop-down box, which uses Table 2 to retrieve data from Table 1.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/data-chart-based-on-drop-down-1.png) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Format the chart to appear as you wish, and again, play with your drop-down to see Table 2—and, consequently, your chart—adjust to your selection. You'll also see your chart title change.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
##  Step 5: Add an Average Line to Your Chart

 To add an average line to the chart, you need to add more data to Table 2\. Add another column heading to Table 2, and call it **Average**.

![An Excel spreadsheet with two tables and a chart. Table 2 has a new column, headed 'Average.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/table-2-average-column.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 Now, [use the AVERAGE function](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) to capture the average of the selected data. In our case, we've selected game 4, so we want to find the average rating among all five players for this game. To do this, type

​​​​​​​=AVERAGE

 ​​​​​​​in the first cell of this new column, and then select the data in the previous column. Press F4 to make this an absolute reference, and then close the parentheses and press Enter.

![An Excel table with the average of the first data column being calculated in the second data column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/average-data.png) 

 Then, [use the AutoFill handle to click and drag the formula down to the bottom of the column](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/).

 We now want to add the average data to our chart.

 Click anywhere towards the edge of your chart and click "Chart Design" on the ribbon. Then, head to the Data group and click "Select Data."

![An Excel chart selected with the 'Select Data' icon in the Chart Design group selected.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/select-data-for-chart.png) 

 In the Select Data Source window, click "Add."

![Excel's Select Data Source window with 'Add' highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/add-data.png) 

 Then, in the Edit Series window, clear the Series Values field, and then select the data in the Average column of Table 2\. Click "OK," and you will see the average appear as an additional bar in your chart.

![An Excel sheet showing the Edit Series dialog box, the data in 'Series Values' is taken from Table 2, and the chart shows the average value as a column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/add-data-source-2.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To change this average data to a line over your existing bars, right-click one of the new bars and click "Change Series Chart Type."

![An Excel chart with an average column selected through a right-click, and 'Change Series Chart Type' selected.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/change-series-chart-type.png) 

 Open the "All Charts" tab, click "Combo" in the menu on the left, and change the average data series to "Line."

![The Change Chart Type window in Excel, with the 'All Charts' tab opened, the 'Combo' menu selected, and Series 2 changed to 'Line.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/change-data-to-line.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 Click OK to see the outcome, and change the drop-down choice to see your chart change dynamically!

![An Excel chart reflecting the drop-down choice and with an average line included as an additional data set.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/dynamic-chart-with-average-line.png) 

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can then format your line so that it stands out in the way that you want it to.

---

 Now that you've achieved that impressive, dynamic chart, check out some [ways to make it stand out even more](https://vp-tips.techidaily.com/2024-approved-capture-breathtaking-scenes-on-iphone-with-ease/).

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


