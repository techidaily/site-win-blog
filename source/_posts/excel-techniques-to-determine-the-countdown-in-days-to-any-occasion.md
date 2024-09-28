---
title: Excel Techniques to Determine the Countdown in Days to Any Occasion
date: 2024-08-28T05:41:31.231Z
updated: 2024-08-29T05:41:31.231Z
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
###  TODAY

 Syntax: =TODAY()

 Result: The current date

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  DATE

 Syntax: =DATE(year,month,day)

 Result: The date designated by the year, month, and day entered

###  YEAR

 Syntax: =YEAR(date)

 Result: The year of the date entered

###  MONTH

 Syntax: =MONTH(date)

 Result: The numerical month of the date entered (1 through 12)

###  DAY

 Syntax: =DAY(date)

 Result: The day of the month of the date entered

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
##  Some Example Calculations

 We will look at three events that occur annually on the same day, calculate the date of their next occurrence, and determine the number of days between now and their next occurrence.

 Here is our sample data. We've got four columns set up: Event, Date, Next\_Occurrence, and Days\_Until\_Next. We have entered the dates of a random birth date, the date taxes are due in the U.S., and Halloween. Dates like birthdays, anniversaries, and some holidays occur on specific days each year and work well with this example. Other holidays---like Thanksgiving---occur on a particular weekday in a specific month; this example does not cover those types of events.

![Example Data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-01.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
 Hit Enter to see the result. (This article was written in late January 2019, so the dates will be...well...dated.)

 Fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Next Occurrence Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-03.png) 

 Now we can easily determine the number of days until the next occurrence by subtracting the result of the TODAY() function from the Next\_Occurrence results we just calculated. Enter the following formula into cell H3:

=G3-TODAY()

![Enter "=G3-TODAY()" into cell H3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-04.png) 

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
 Press Enter to see the result and then fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Days_Until_Next Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-05.png) 

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


