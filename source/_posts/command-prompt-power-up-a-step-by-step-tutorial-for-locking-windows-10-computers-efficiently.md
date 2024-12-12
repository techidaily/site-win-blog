---
title: "Command Prompt Power-Up: A Step-by-Step Tutorial for Locking Windows 10 Computers Efficiently"
date: 2024-12-05T18:56:40.351Z
updated: 2024-12-12T18:15:26.980Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6037bb9c2891cc5de7a061886dcf26fb2fd27c5d5408d3641e03d7db63a65dce.jpg
---

## Command Prompt Power-Up: A Step-by-Step Tutorial for Locking Windows 10 Computers Efficiently

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-infusing-audio-from-yt-into-video-artistry/"><u>[New] 2024 Approved Infusing Audio From YT Into Video Artistry</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-larger-visuals-elevating-your-youtube-footage/"><u>[Updated] 2024 Approved Larger Visuals Elevating Your YouTube Footage</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-humorous-vines-the-ultimate-10-list/"><u>2024 Approved Humorous Vines The Ultimate 10 List</u></a></li>
<li><a href="https://win-blog.techidaily.com/boosting-sifu-techniques-to-prevent-stuttering-and-dropped-frames-in-pc-gaming/"><u>Boosting 'Sifu': Techniques to Prevent Stuttering and Dropped Frames in PC Gaming</u></a></li>
<li><a href="https://win-blog.techidaily.com/call-of-duty-fans-rejoice-solve-the-unforeseen-stoppages-in-cod-mw3-for-a-better-gaming-experience/"><u>Call of Duty Fans Rejoice! Solve the Unforeseen Stoppages in COD MW3 for a Better Gaming Experience</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixed-issue-warzone-game-images-failing-to-appear/"><u>Fixed Issue: Warzone Game Images Failing to Appear</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-methods-to-turn-off-life-360-on-xiaomi-redmi-note-13-proplus-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Methods to Turn off Life 360 On Xiaomi Redmi Note 13 Pro+ 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-wireless-hotspot-configuration-in-windows-11/"><u>Navigating the Wireless Hotspot Configuration in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/resident-evil-village-and-pc-lag-here-are-the-ultimate-fixes-you-need-to-try/"><u>Resident Evil Village and PC Lag? Here Are the Ultimate Fixes You Need to Try!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/simplify-tech-sharing-effective-use-of-the-ezvide-toolkit/"><u>Simplify Tech Sharing Effective Use of the Ezvide Toolkit</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-battle-royale-bugs-fixing-call-of-duty-warzone-disc-reading-issues-5031-for-pc/"><u>Solving Battle Royale Bugs: Fixing Call of Duty Warzone Disc Reading Issues (5.0/3.1) for PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-not-found-dll-file-fixes-for-d3dx924dll-issues/"><u>Troubleshooting Not Found Dll File: Fixes for d3dx9_24.dll Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-resolving-gta-v-gears-game-crashing-issues/"><u>Ultimate Guide: Resolving GTA V Gear's Game-Crashing Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/understanding-and-solving-noticeable-frame-rate-reductions-a-step-by-step-guide/"><u>Understanding and Solving Noticeable Frame Rate Reductions: A Step-by-Step Guide</u></a></li>
</ul></div>

