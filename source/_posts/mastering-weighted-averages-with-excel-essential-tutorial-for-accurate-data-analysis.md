---
title: "Mastering Weighted Averages with Excel: Essential Tutorial for Accurate Data Analysis"
date: 2024-12-07T18:42:44.233Z
updated: 2024-12-12T19:17:37.021Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What is a Weighted Average?

 A weighted average is an average that takes into account the importance, or weight, of each value. A good example would be calculating a student's final grade based on their performance on a variety of different assignments and tests. Individual assignments usually don't count as much towards a final grade as the final exam---things like quizzes, tests, and final exams will all have different weights. The weighted average is calculated as the sum of all of the values multiplied by their weights divided by the sum of all of the weights.

 The following example will demonstrate how to use Excel's SUMPRODUCT and SUM functions to calculate a weighted average.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Let's Look at an Example

 For our example, let's look at a student's quiz and exam scores. There are six quizzes each worth 5% of the total grade, two exams each worth 20% of the total grade, and one final exam worth 30% of the total grade. The student's final grade will be a weighted average, and we will use the SUMPRODUCT and SUM functions to calculate it.

 As you can see in our table below, we've already assigned the relative weights to each quiz and exam in the D column.

![Excel table showing scores and weights assigned to several quizzes and exams](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-01.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Step One: Calculate the SUMPRODUCT

 First, let's look at how the SUMPRODUCT function works. Start by selecting the cell where you want the result to appear (in our example, that's cell D13). Next, navigate to the "Formulas" menu, select the "Math & Trig" drop-down, scroll to the bottom, and click on the "SUMPRODUCT" function.

![On the Formulas tab, click Math &amp; Trig, then select SUMPRODUCT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-02.png) 

 The "Function Arguments" window will appear.

![the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-03.png) 

 For the "Array1" box, select the student's scores. Here, we're selecting all the cells with actual scores in the C column.

![In the Array1 box, select the cells with the grades](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-04.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, use the "Array2" box to select the weights of the quizzes and exams. For us, those are in the D column.

![In the Array2 box, select the cells with the weights](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-05.png) 

 Click "OK" when you're done.

![Click OK in the Function Arguments window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-06.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The SUMPRODUCT function will multiply each score by its corresponding weight and then return the sum of all of those products.

![The Excel table now shows the SUMPRODUCT value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-07.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 The SUM function will add all of the values together.

![The Excel table now shows the SUM value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-12.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Step Three: Combine the SUMPRODUCT and SUM to Calculate the Weighted Average

 Now we can combine the two functions to determine the student's final grade based on their scores and the weights of each score. Select the cell where the weighted average should go (for us that's cell D15) and then type the following formula into the function bar.

=SUMPRODUCT(C3:C11,D3:D11)/SUM(D3:D11)

![select the weighted average cell and then type the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-13.png) 

 Press "Enter" after typing the formula to view the weighted average.

![The table now shows the weighted average](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/excel-weighted-average-14.png) 

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-top-30-pro-windows-10-mastery-hacks/"><u>[New] Top 30 Pro Windows 10 Mastery Hacks</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-ultimate-blueprint-for-successful-discord-live-streams/"><u>[Updated] The Ultimate Blueprint for Successful Discord Live Streams</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-are-feedbacks-on-items-monetized-in-videos/"><u>2024 Approved Are Feedbacks on Items Monetized in Videos?</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypassing-problems-successfully-starting-up-the-ascent-application/"><u>Bypassing Problems: Successfully Starting Up 'The Ascent' Application</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-to-combat-mir4-crashing-problems-on-pc-platforms/"><u>Effective Solutions to Combat MIR4 Crashing Problems on PC Platforms</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/efficient-data-capture-with-abbyy-integrating-flexicapture-and-laserfiche-technologies/"><u>Efficient Data Capture with ABBYY: Integrating FlexiCapture and Laserfiche Technologies</u></a></li>
<li><a href="https://extra-information.techidaily.com/excellent-websites-for-3d-metallic-type-imagery/"><u>Excellent Websites for 3D Metallic Type Imagery</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722993739529-fixes-for-nier-automata-software-crash-solved/"><u>Fixes For Nier Automata Software Crash - Solved</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-experts-insight-efficiently-using-mobizen-for-capturing-screens/"><u>In 2024, Expert's Insight Efficiently Using Mobizen for Capturing Screens</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/mass-effect-legendary-edition-woes-overcoming-the-non-launching-challenge/"><u>Mass Effect Legendary Edition Woes: Overcoming the Non-Launching Challenge</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-multiversus-launch-problems-expert-advice-for-windows-users/"><u>Mastering MultiVersus Launch Problems: Expert Advice for Windows Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722997318474-modern-warfare-2-wont-open-follow-these-steps-to-resolve-the-issue/"><u>Modern Warfare ^2 Won't Open? Follow These Steps to Resolve the Issue!</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/top-ranked-aomei-backupper-the-premier-windows-server-201n2-backup-solution/"><u>Top-Ranked AOMEI Backupper: The Premier Windows Server 201N2 Backup Solution</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-is-my-battlefield-talkie-crashing-overcoming-common-compatibility-issues-on-pcs/"><u>Why Is My Battlefield Talkie-Crashing? Overcoming Common Compatibility Issues on PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/winning-against-the-stray-crash-glitch-6-proven-repairs-for-your-gaming-pc/"><u>Winning Against the Stray Crash Glitch: 6 Proven Repairs for Your Gaming PC</u></a></li>
</ul></div>

