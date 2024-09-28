---
title: "Mastering Weighted Averages with Excel: Essential Tutorial for Accurate Data Analysis"
date: 2024-08-28T05:42:27.169Z
updated: 2024-08-29T05:42:27.169Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Mastering Weighted Averages with Excel: Essential Tutorial for Accurate Data Analysis

### Quick Links

* [What is a Weighted Average?](https://extra-guidance.techidaily.com/new-mastering-the-ritual-of-independent-instagram-sound-creation/)
* [Let's Look at an Example](https://fox-access.techidaily.com/updated-dji-drone-artistry-unlocked-first-20-free-lutts-available/)

 A weighted average is one that takes into account the importance, or weight, of each value. This article will show you how to use Excel's SUMPRODUCT and SUM functions individually and how to combine the two to calculate a weighted average.

##  What is a Weighted Average?

 A weighted average is an average that takes into account the importance, or weight, of each value. A good example would be calculating a student's final grade based on their performance on a variety of different assignments and tests. Individual assignments usually don't count as much towards a final grade as the final exam---things like quizzes, tests, and final exams will all have different weights. The weighted average is calculated as the sum of all of the values multiplied by their weights divided by the sum of all of the weights.

 The following example will demonstrate how to use Excel's SUMPRODUCT and SUM functions to calculate a weighted average.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
##  Let's Look at an Example

 For our example, let's look at a student's quiz and exam scores. There are six quizzes each worth 5% of the total grade, two exams each worth 20% of the total grade, and one final exam worth 30% of the total grade. The student's final grade will be a weighted average, and we will use the SUMPRODUCT and SUM functions to calculate it.

 As you can see in our table below, we've already assigned the relative weights to each quiz and exam in the D column.

![Excel table showing scores and weights assigned to several quizzes and exams](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-01.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step One: Calculate the SUMPRODUCT

 First, let's look at how the SUMPRODUCT function works. Start by selecting the cell where you want the result to appear (in our example, that's cell D13). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUMPRODUCT" function.

![On the Formulas tab, click Math &amp; Trig, then select SUMPRODUCT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-02.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The "Function Arguments" window will appear.

![the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-03.png) 

 For the "Array1" box, select the student's scores. Here, we're selecting all the cells with actual scores in the C column.

![In the Array1 box, select the cells with the grades](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-04.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
 Next, use the "Array2" box to select the weights of the quizzes and exams. For us, those are in the D column.

![In the Array2 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-05.png) 

 Click "OK" when you're done.

![Click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-06.png) 

 The SUMPRODUCT function will multiply each score by its corresponding weight and then return the sum of all of those products.

![The Excel table now shows the SUMPRODUCT value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-07.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step Two: Calculate the SUM

 Now let's look at how the SUM function works. Select the cell where you want the results to appear (in our example, that's cell D14). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUM" function.

![On the Formulas tab, click Math &amp; Trig, then select SUM](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-08.png) 

 The "Function Arguments" window will appear.

![The Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-09.png) 

 For the "Number1" box, select all of the weights.

![In the Number1 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-10.png) 

 Click "OK."

![click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-11.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The SUM function will add all of the values together.

![The Excel table now shows the SUM value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-12.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
###  Step Three: Combine the SUMPRODUCT and SUM to Calculate the Weighted Average

 Now we can combine the two functions to determine the student's final grade based on their scores and the weights of each score. Select the cell where the weighted average should go (for us that's cell D15) and then type the following formula into the function bar.

=SUMPRODUCT(C3:C11,D3:D11)/SUM(D3:D11)

![select the weighted average cell and then type the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-13.png) 

 Press "Enter" after typing the formula to view the weighted average.

![The table now shows the weighted average](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-14.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And there you have it. It's a fairly simple example, but it's a good one for showing how weighted averages work.

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


