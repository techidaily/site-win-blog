---
title: The Ultimate Guide to Calculating Text Length in MS Excel
date: 2024-08-28T05:43:07.777Z
updated: 2024-08-29T05:43:07.777Z
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

 Or, you can simply copy the content of the cell you want to get the character count of, paste it in the formula in place of the reference cell, and wrap it in quotation marks. For example:

=LEN("How many characters are in this cell?")

![Paste the content of the cell in the formula.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Paste-the-content-of-the-cell-in-the-formula..png) 

 This will return the same result.

 If you're parsing data, you may also want to [split your text across multiple columns](https://tiktok-clips.techidaily.com/2024-approved-speeding-up-tiktok-videos-made-simple/).

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
##  How to Get the Character Count of Multiple Cells

 The LEN function can also be used in combination with the SUM function to get the character count of multiple cells. First, click the cell you would like to place the word count in. Next, enter this formula:

=SUM(LEN(A1),LEN(A2))

 Replace the cell numbers with your own.

![Enter the LEN and SUM function combination.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-and-SUM-function-combination..png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click on any other cell and the character count will be returned.

![The character count of cells A1 and A2.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-character-count-of-cells-A1-and-A2..png) 

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can add as many cells as you like in the formula.

 It's also easy to [combine text](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) from these different cells into one.

Related: [How to Combine Text from Multiple Cells into One Cell in Excel](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Get the Count of a Specific Character in a Cell

 You can also use the LEN function to get the count of how many times a specific character appears in a cell. Select the cell you'd like the count to be returned in and then enter this formula:

=LEN(A1)-LEN(SUBSTITUTE(A1,"a",""))

 Replace the cell (`A1`) with your reference cell and `a` with the character you'd like to get the count of. In our case, we're searching for how many times `a` appears in cell A1.

![Enter the LEN function to get the specific character count.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-function-to-get-the-specific-character-count..png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 Click on any other cell and the count of the specified character will be returned.

![The count of the specified character.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-count-of-the-specified-character..png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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


