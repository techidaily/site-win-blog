---
title: Step-by-Step Tutorial on Forcing Microsoft Excel to Preserve and Display Leading Zeroes
date: 2024-08-28T05:41:48.335Z
updated: 2024-08-29T05:41:48.335Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/img_5ad9da0c2cec7.png
---

## Step-by-Step Tutorial on Forcing Microsoft Excel to Preserve and Display Leading Zeroes

By default, Excel doesn't show the leading zero in any non-decimal numerical data set. But if you need to show the leading zero --- usually because of some weird numbering system at your job, it’s easy to keep that zero in its place.

 In any individual Excel document, select one of more cells (or a whole column or row), and then Ctrl+1 to open the “Format Cells” menu. (MacOS users, use the Command+1 instead.)

![img_5ad9d9030bc9b](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/img_5ad9d9030bc9b.png) 

 In the Format Cells window, on the “Number” tab, select the “Custom” entry in the Category list. In the "Type" field on the right, type zeroes indicating the number of digits you want displayed. For example, if you always want to see four digits, type "0000" into the field.

![img_5ad9d95fc9c58](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/img_5ad9d95fc9c58.png) 

 You’ll have to manually add decimal places, too. For example, if you’re listing payments up to $500 that include cents, you need to specify your custom value as 000.00 to avoid rounding to the nearest dollar.

![img_5ad9d9996a6f6](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/img_5ad9d9996a6f6.png) 

 Formatting changes are applied to the cells you selected. Repeat this process as many times as you need in a single sheet or workbook---different cells or groups of cells can use different number formatting on the same sheet.

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



<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->