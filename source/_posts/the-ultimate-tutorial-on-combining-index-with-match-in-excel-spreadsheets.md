---
title: The Ultimate Tutorial on Combining INDEX with MATCH in Excel Spreadsheets
date: 2024-08-28T05:43:08.958Z
updated: 2024-08-29T05:43:08.958Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## The Ultimate Tutorial on Combining INDEX with MATCH in Excel Spreadsheets

### Quick Links

* [VLOOKUP Versus INDEX and MATCH](https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-f54-5g-location-on-viber-drfone-by-drfone-virtual-android/)
* [INDEX and MATCH Function Basics](https://extra-support.techidaily.com/updated-premium-steadicam-options-for-high-quality-dslr-shoots/)
* [How to Use INDEX and MATCH in Excel](https://extra-approaches.techidaily.com/prime-gold-toned-text-interactive-3d-sites-reviewed-for-2024/)

 While the [VLOOKUP function](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) is good for finding values in Excel, it has its limitations. With a combination of the INDEX and MATCH functions instead, you can look up values in any location or direction in your spreadsheet.

 The INDEX function returns a value based on a location you enter in the formula while MATCH does the reverse and returns a location based on the value you enter. When you combine these functions, you can find any number or text you need.

##  VLOOKUP Versus INDEX and MATCH

 The difference between these functions and VLOOKUP is that VLOOKUP finds values from left to right. Hence the function's name; VLOOKUP performs a vertical lookup.

 Microsoft best explains [the way VLOOKUP works](https://support.microsoft.com/en-us/office/look-up-values-with-vlookup-index-or-match-68297403-7c3c-4150-9e3c-4d348188976b):

> There are certain limitations with using VLOOKUP---the VLOOKUP function can only look up a value from left to right. This means that the column containing the value you look up should always be located to the left of the column containing the return value.

 Microsoft goes on to say that if your sheet isn't set up in a way where VLOOKUP can help you find what you need, you can use INDEX and MATCH instead. So let's look at how to use INDEX and MATCH in Excel.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
##  INDEX and MATCH Function Basics

 To use these functions together, it's important to understand their purpose and structure.

 The syntax for INDEX in Array Form is

        `INDEX(array, row_number, column_number)`
    
 with the first two arguments required and the third optional.

 INDEX looks up a position and returns its value. To find the value in the fourth row in the cell range D2 through D8, you would enter the following formula:

=INDEX(D2:D8,4)

![INDEX function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEX-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 The result is 20,745 because that's the value in the fourth position of our cell range.

 For more details on the Array and Reference Forms of INDEX as well as other ways to use this function, take a look at our how-to for [INDEX in Excel](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/).

 The syntax for MATCH is `MATCH(value, array, match_type)` with the first two arguments required and the third optional.

 MATCH looks up a value and returns its position. To find the value in cell G2 in the range A2 through A8, you would enter the following formula:

=MATCH(G2,A2:A8)

![MATCH function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MATCH-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 The result is 4 because the value in cell G2 is in the fourth position in our cell range.

 For additional details on the `match_type` argument and other ways to use this function, take a look at our tutorial for [MATCH in Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/).

Related: [How to Find a Value's Position With MATCH in Microsoft Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use INDEX and MATCH in Excel

 Now that you know what each function does and its syntax, it's time to put this dynamic duo to work. Below, we'll use the same data as above for INDEX and MATCH individually.

 You'll place the formula for the MATCH function inside the formula of the INDEX function in place of the position to look up.

 To find the value (sales) based on the location ID, you would use this formula:

=INDEX(D2:D8,MATCH(G2,A2:A8))

 The result is 20,745\. MATCH finds the value in cell G2 within the range A2 through A8 and provides that to INDEX which looks to cells D2 through D8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG2-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Let's look at another example. We want to know which city has sales that match a certain amount. Using our sheet, you would enter this formula:

=INDEX(B2:B8,MATCH(G5,D2:D8))

 The result is Houston. MATCH finds the value in cell G5 within the range D2 through D8 and provides that to INDEX which looks to cells B2 through B8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG5-ExcelINDEXandMATCH.png) 

 Here's an example using an actual value instead of a cell reference. We'll look for the value (sales) for a specific city with this formula:

=INDEX(D2:D8,MATCH("Houston",B2:B8))

 In the MATCH formula, we replaced the cell reference containing the lookup value with the actual lookup value of "Houston" from B2 through B8 which gives us the result 20,745 from D2 through D8.

 Be sure when you use the actual value to look up, rather than a cell reference, that you enclose it in quotes as shown here.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHHouston-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 To obtain that same result by using the location ID instead of the city, we simply change the formula to this:

=INDEX(D2:D8,MATCH("2B",A2:A8))

 Here we changed the MATCH formula to look up "2B" in the cell range A2 through A8 and provide that result to INDEX which then returns 20,745.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCH2B-ExcelINDEXandMATCH.png) 

[Basic functions in Excel](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) like those that help you [add numbers](https://instagram-clips.techidaily.com/updated-2024-approved-unveiling-instagrams-policies-a-musicians-legal-primer/) in cells or [enter the current date](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) are certainly helpful. But when you start adding more data and advancing your data entry or analysis needs, lookup functions like INDEX and MATCH in Excel can be quite useful.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/)

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


