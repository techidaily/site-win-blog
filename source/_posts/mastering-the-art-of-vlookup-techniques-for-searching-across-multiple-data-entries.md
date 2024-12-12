---
title: "Mastering the Art of VLOOKUP: Techniques for Searching Across Multiple Data Entries"
date: 2024-12-07T16:33:54.544Z
updated: 2024-12-12T19:21:56.719Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/162b2aac03e354d0551440e420920822fdecda6764b32f863c3da9da1ce561fb.jpg
---

## Mastering the Art of VLOOKUP: Techniques for Searching Across Multiple Data Entries

### Quick Links

* [Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores](https://hardware-updates.techidaily.com/1722963330919-newly-released-geforce-nvidia-210-drivers-compatible-with-windows-11-get-them-now/)
* [Example Two: Providing a Discount Based on How Much a Customer Spends](https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-g310-drfone-by-drfone-virtual-android/)

 VLOOKUP is one of Excel's most well-known functions. You'll typically use it to look up exact matches, such as the ID of products or customers, but in this article, we'll explore how to use VLOOKUP with a range of values.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores

 As an example, say we have a list of exam scores, and we want to assign a grade to each score. In our table, column A shows the actual exam scores and column B will be used to show the letter grades we calculate. We've also created a table off to the right (the D and E columns) that show the score necessary to achieve each letter grade.

![Grade score sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/grades-lookup-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With VLOOKUP, we can use the range values in column D to assign the letter grades in column E to all the actual exam scores.

###  The VLOOKUP Formula

 Before we get into applying the formula to our example, let's have a quick reminder of the VLOOKUP syntax:

=VLOOKUP(lookup_value, table_array, col_index_num, range_lookup)

 In that formula, the variables work like this:

* lookup\_value: This is the value for which you are looking. For us, this is the score in column A, starting with cell A2.
* table\_array: This is often referred to unofficially as the lookup table. For us, this is the table containing the scores and associated grades (range D2:E7).
* col\_index\_num: This is the column number where the results will be placed. In our example, this is column B, but since the VLOOKUP command requires a number, it's column 2.
* range\_lookup> This is a logical value question, so the answer is either true or false. Are you performing a range lookup? For us, the answer is yes (or "TRUE" in VLOOKUP terms).

 The completed formula for our example is shown below:

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![Results of our VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-results.png) 

 The table array has been fixed to stop it changing when the formula is copied down the cells of column B.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

 It is important to be clear that the order is only essential with range lookups. When you put False on the end of a VLOOKUP function, the order is not so important.

##  Example Two: Providing a Discount Based on How Much a Customer Spends

 In this example, we have some sales data. We would like to provide a discount on the sales amount, and the percentage of that discount is dependent upon the amount spent.

 A lookup table (columns D and E) contains the discounts at each spending bracket.

![Second VLOOKUP example data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/VLOOKUP-second-example.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The VLOOKUP formula below can be used to return the correct discount from the table.

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

 This example is interesting because we can use it in a formula to subtract the discount.

 You will often see Excel users writing complicated formulas for this type of conditional logic, but this VLOOKUP provides a concise way of achieving it.

 Below, the VLOOKUP is added to a formula to subtract the discount returned from the sales amount in column A.

=A2-A2*VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![VLOOKUP returning conditional discounts](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-discounted-price.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

 VLOOKUP is not just useful for when looking for specific records such as employees and products. It's more versatile than many people know, and having it return from a range of values is an example of that. You can also use it as an alternative to otherwise complicated formulas.

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
<li><a href="https://youtube-zero.techidaily.com/eat-your-content-up-a-notch-music-addition-in-youtube-videos-for-2024/"><u>[New] Beat Your Content Up a Notch Music Addition in YouTube Videos for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-perfectly-pristine-photos-in-the-cloud-free-and-paid-unveiled/"><u>[Updated] Perfectly Pristine Photos in the Cloud Free & Paid Unveiled</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-next-level-thrills-with-samsungs-leading-vr-games/"><u>2024 Approved Next-Level Thrills with Samsung's Leading VR Games</u></a></li>
<li><a href="https://win-blog.techidaily.com/a-total-war-saga-troy-fixed-pc-crashing-issues-ready-to-play/"><u>A Total War Saga: Troy - Fixed PC Crashing Issues, Ready To Play!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/auroras-vision-in-home-theater-systems-evaluated/"><u>Aurora's Vision in Home Theater Systems Evaluated</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/celebration-on-the-red-planet-a-century-of-singing-machines-honors-mars-exploration/"><u>Celebration on the Red Planet: A Century of Singing Machines Honors Mars Exploration</u></a></li>
<li><a href="https://win-blog.techidaily.com/closing-the-loop-why-rainbow-six-extraction-no-longer-crashes-on-personal-computers/"><u>Closing the Loop: Why Rainbow Six Extraction No Longer Crashes on Personal Computers</u></a></li>
<li><a href="https://win-blog.techidaily.com/eliminating-delays-how-to-address-frame-rate-issues-in-forza-horizon-5/"><u>Eliminating Delays: How to Address Frame Rate Issues in Forza Horizon 5</u></a></li>
<li><a href="https://driver-download.techidaily.com/enhance-gameplay-on-dell-g3-update-essential-graphics-and-audio-drivers/"><u>Enhance Gameplay on Dell G3: Update Essential Graphics and Audio Drivers</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixed-eliminating-stutter-and-lock-ups-in-your-warframe-gameplay-experience/"><u>Fixed! Eliminating Stutter and Lock-Ups in Your Warframe Gameplay Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722995048018-fixes-and-solutions-how-to-stop-starcraft-ii-from-crashing-on-your-computer/"><u>Fixes & Solutions: How to Stop StarCraft II From Crashing on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/god-of-war-bug-fix-how-we-overcame-low-memory-problems/"><u>God of War Bug Fix: How We Overcame Low Memory Problems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-realme-narzo-60x-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Realme Narzo 60x 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-look-at-the-budget-friendly-roku-express-with-extensive-content-offering/"><u>In-Depth Look at the Budget-Friendly Roku Express with Extensive Content Offering</u></a></li>
<li><a href="https://win-blog.techidaily.com/simple-troubleshooting-steps-for-persistent-outriders-crashes/"><u>Simple Troubleshooting Steps for Persistent Outriders Crashes</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-get-your-amd-radeon-management-tool-running-again/"><u>Step by Step Guide: Get Your AMD Radeon Management Tool Running Again</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-echo-show-4th-generation-in-depth-review-and-significant-enhancements/"><u>The Echo Show 4Th Generation: In-Depth Review & Significant Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-asking-too-many-hands-at-once-errors/"><u>Troubleshoot Asking Too Many Hands at Once Errors</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlocking-fortnite-tips-for-fixing-access-not-granted-errors/"><u>Unlocking Fortnite: Tips for Fixing 'Access Not Granted' Errors</u></a></li>
</ul></div>

