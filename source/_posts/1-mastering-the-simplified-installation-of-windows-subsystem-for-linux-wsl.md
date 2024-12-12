---
title: 1. Mastering the Simplified Installation of Windows Subsystem for Linux (WSL)
date: 2024-12-06T16:26:23.592Z
updated: 2024-12-12T16:31:54.211Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/windows-11-4.jpg
---

## 1. Mastering the Simplified Installation of Windows Subsystem for Linux (WSL)

It's been a week since the BUILD conference ended, but Microsoft has one last announcement up its sleeve. The Windows Subsystem for Linux (WSL) is gaining some new features, and it will soon offer a dedicated GUI for more convenient settings adjustments.

 Two features that were introduced in the [WSL September 2023 update](https://devblogs.microsoft.com/commandline/windows-subsystem-for-linux-september-2023-update/)—autoMemoryReclaim and dnsTunneling—are now transitioning from experimental status to default, stable settings. The autoMemoryReclaim feature aims to free unused RAM from the clutches of [WSL](https://extra-guidance.techidaily.com/2024-approved-quick-tips-to-master-free-countdown-functions/), which may improve system performance while running memory-hogging applications on some systems. And, as the name implies, dnsTunneling improves WSL's network compatibility by enabling DNS tunneling by default.

![A screenshot of the upcoming WSL Settings GUI.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/53.jpg) 

Microsoft

 This update also introduces an experimental automatic disk space reclaim setting that you can enable using _– wsl --manage --set-sparse <true/false>_. And Microsoft is taking this opportunity to remind users that the experimental mirrored networking mode, which debuted in the September 2023 update, can be enabled with _– wslconfig setting of networkingMode=mirrored_. Other experimental features introduced in the September 2023 update, such as sparseVhd, were promoted to default settings earlier this year.

 More interestingly, Microsoft is preparing to launch a WSL Settings GUI app. This saves you the trouble of manually editing the contents of the .wslconfig file or fiddling in the command line when adjusting things like memory or disk usage. Any changes made to the .wslconfig file will be immediately reflected in the WSL Settings GUI app, so you can continue doing things the old-fashioned way, if that's what you'd prefer.

 Microsoft has also announced that WSL will support the Dev Home app's new Environments feature, which makes it easier to manage and launch operating systems for development purposes. The [work in progress source code](https://github.com/WhitewaterFoundry/DevHomeWSLExtension) is currently available on GitHub. For enterprise customers, Microsoft Defender for Endpoint’s WSL 2 support is now generally available. [WSL management via Intune](https://learn.microsoft.com/en-us/windows/wsl/enterprise#configure-recommended-settings-with-intune) is also rolling out as a public preview, and Microsoft Entra Id is coming to WSL later this year.

 You can read more about the new WSL update at Microsoft's [Command Line blog](https://devblogs.microsoft.com/commandline/whats-new-in-the-windows-subsystem-for-linux-in-may-2024/). Note that you can report technical issues at the [WSL GitHub repo](https://github.com/microsoft/wsl).

 Source: [Microsoft](https://devblogs.microsoft.com/commandline/whats-new-in-the-windows-subsystem-for-linux-in-may-2024/)

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-pro-tips-configuring-stopwatches-in-obs-studio-for-2024/"><u>[New] Pro Tips Configuring Stopwatches in OBS Studio for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-saying-goodbye-a-guide-for-ending-your-discord-membership/"><u>[Updated] Saying Goodbye A Guide for Ending Your Discord Membership</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-lava-yuva-3-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Lava Yuva 3 Activity | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/acoustic-indexing-sound-and-vocal-files-for-2024/"><u>Acoustic Indexing Sound and Vocal Files for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/banish-the-bugs-troubleshooting-constant-crashes-in-new-world-for-pc-players/"><u>Banish the Bugs: Troubleshooting Constant Crashes in New World for PC Players</u></a></li>
<li><a href="https://article-files.techidaily.com/capturing-moments-like-never-before-toolwiz-apps-2023-review-for-2024/"><u>Capturing Moments Like Never Before Toolwiz App's 2023 Review for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-to-eliminate-screen-tremors-fixing-persistent-chrome-fluctuation-issues-in-windows-os-all-in-one-solution/"><u>Guide to Eliminate Screen Tremors: Fixing Persistent Chrome Fluctuation Issues in Windows OS (All-in-One Solution)</u></a></li>
<li><a href="https://win-blog.techidaily.com/helldivers-2-msvcr110dll-error-easy-fixes-to-get-you-back-in-action/"><u>HellDivers 2 MSVCR110.dll Error: Easy Fixes to Get You Back in Action!</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-prevent-baldurs-gate-iii-from-crashing-on-your-windows-machine/"><u>How to Prevent Baldur's Gate III From Crashing on Your Windows Machine</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-dark-heroity-meets-radiant-righteousness/"><u>In 2024, Dark Heroity Meets Radiant Righteousness</u></a></li>
<li><a href="https://fix-guide.techidaily.com/infinix-note-30i-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Infinix Note 30i Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-overcoming-startup-issues-in-the-popular-fall-guys-game/"><u>Step-by-Step Guide: Overcoming Startup Issues in the Popular Fall Guys Game</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-implement-autodelete-feature-in-winos/"><u>Streamline Your System: Implement AutoDelete Feature in WINOS</u></a></li>
<li><a href="https://win-blog.techidaily.com/tips-to-overcome-input-lag-challenges-in-cyberpunk-2077/"><u>Tips to Overcome Input Lag Challenges in Cyberpunk 2077</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723005175759-warzone-textures-not-appearing-here-are-the-steps-to-fix-it-quickly/"><u>Warzone Textures Not Appearing? Here Are the Steps to Fix It Quickly!</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-oppo-reno-8t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Oppo Reno 8T Hard Reset | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

