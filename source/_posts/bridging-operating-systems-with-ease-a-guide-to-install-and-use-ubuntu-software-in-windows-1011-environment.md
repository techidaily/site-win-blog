---
title: "Bridging Operating Systems with Ease: A Guide to Install and Use Ubuntu Software in Windows 10/11 Environment"
date: 2024-08-28T05:39:53.700Z
updated: 2024-08-29T05:39:53.700Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5b77fd5a0fde79a2c2eb70c6784e4159441548e492bf849faab165ff42ddbd19.jpg
---

## Bridging Operating Systems with Ease: A Guide to Install and Use Ubuntu Software in Windows 10/11 Environment

### Key Takeaways

* Install WSL2 Kernel, activate Virtual Machine Platform, and make sure you have Admin rights before getting Ubuntu on Windows 11.
* Enable Windows Subsystem for Linux, then download and install Ubuntu for WSL via Microsoft Store to run Linux apps on Windows 11.

 Did you know using Ubuntu-exclusive apps doesn't require overwriting your operating system? Unlock the true potential of your Windows desktop by using Ubuntu apps on Windows 11, enhancing your PC experience by blending the power of Linux and Windows.

##  Why Use Ubuntu Apps on Windows 11?

 Adding Ubuntu to Windows 11 enables access to a wide variety of free applications unavailable on Windows alone. These aren't just ordinary programs either; they can accomplish nearly any task on your computer, from enhancing your file management to creative projects. For example, if you're looking for a great photo management tool not found on Windows 11, you might try [Shotwell](https://shotwell-project.org/doc/html/) with WSL. Or, if you're not a fan of the email apps available on Windows, you can install the Ubuntu-native [Geary](https://wiki.gnome.org/Apps/Geary) email client. There are many great exclusive applications for Ubuntu that can level up your Windows PC.

 Furthermore, if you enjoy crafting and coding, the combination of Windows and Ubuntu significantly benefits you. It simplifies the process of working on Linux-oriented projects without the need to leave the Windows environment. This integration reduces complications and amplifies productivity, whether your pursuits involve coding for enjoyment or constructing significant projects.

 Imagine you're a developer working on a cross-platform project. Using Ubuntu apps on Windows means you can quickly and effectively test your new project on Linux and Windows with ease. Take it from me: I write programs in the Go programming language, and being able to test out my code and run it on both Ubuntu and Windows 11 seamlessly is very powerful.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Requirements Before You Begin

 Before you can start using Ubuntu on your Windows 11 system, a few requirements must be met to ensure a smooth process. During my testing, WSL wouldn't work until I installed the latest WSL2 Kernel package installed on Windows 11\. If you're having issues with WSL running on Windows 11 like I did, install this kernel package. It will ensure that WSL v2 operating systems run correctly. You can download and install the EXE file [directly from Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package).

 In addition to the WSL2 Kernel EXE package, you'll need to enable the "Virtual Machine Platform" feature in the "Windows Features" area of Windows 11\. WSL runs with the help of virtualization, and this feature is a requirement to get the most out of Ubuntu in Windows 11.

 Lastly, ensure you have Administrator rights on your Windows 11 system. Using WSL requires modifying Windows features, and it won't work if you don't have Administrator privileges.

##  Enabling Windows Subsystem for Linux (WSL)

 Windows Subsystem for Linux is not enabled by default on Windows 11\. You'll need to activate this feature on Windows before you can use it to run Ubuntu apps on your Windows PC.

 To start, open the Windows Start Menu on the desktop. Once it is open, type "Turn Windows Features on or off" into the search box. Launch the icon labeled "Control Panel" beneath it to access the "Add/Remove Features" area of Windows 11.

 Inside the "Windows Features" window, scroll down and locate "Windows Subsystem for Linux." After finding it, click on the empty box next to it to activate this feature. Select "OK" after making your selection.

![WSL feature being turned on in Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/flameshot-wsl-check-box.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that the "OK" button has been selected, Windows 11 will begin setting up WSL on your system. This setup process should take a few minutes to complete. When the setup is complete, you must reboot your Windows PC. Select the "Restart now" button to reboot.

 Upon rebooting, log back into your Windows 11 desktop. Once you've logged back in, the Windows Subsystem for Linux will be enabled on Windows 11.

##  Installing Ubuntu

 Ubuntu for WSL is available for Windows 11 via the Microsoft Store, enabling the installation of Ubuntu on your system to run Linux apps within Windows 11.

 To initiate the installation of Ubuntu for WSL, open the Microsoft Store from the Windows 11 desktop. Once open, locate the "Search apps, games, movies, and more" box and click on it.

 In the search box, type "Ubuntu." Upon entering "Ubuntu," the Microsoft Store will display various versions of the Ubuntu app. Select "Ubuntu 22.04.3 LTS" using the mouse.

![The user is searching for Ubuntu WSL 22.04.3 LTS in the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-ubuntu-22.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After selecting "Ubuntu 22.04.3 LTS," you will be directed to its feature page in the Microsoft Store. Locate the "Get" button and click on it. Selecting the "Get" button will initiate the Ubuntu download for Windows 11.

 Downloading Ubuntu 22.04.3 LTS on Windows 11 should be swift, given the program's size is only about 560 MB. Once the download is complete, Ubuntu will be accessible in the Windows Start Menu.

 After Ubuntu 22.04.3 LTS has finished installing on Windows 11, access the Windows Start Menu, search for "Ubuntu 22.04.3 LTS," and launch it. Upon its first launch, Ubuntu will automatically configure itself and prepare for use.

![Ubuntu WSL is installing itself to Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-ubuntu-is-installing.png) 

 Once Ubuntu has finished its setup on Windows 11, you will see an empty terminal window, ready for you to interact with Ubuntu on your Windows 11 system.

##  Basic Configuration Tips

 Here are some basic configuration tips to improve the WSL experience on Windows 11.

###  Windows and Linux File System Integration

 Windows and Linux File System Integration simplifies moving files between your Ubuntu WSL setup and your Windows 11 desktop. Here's how to utilize this feature.

 To access your Ubuntu files from Windows 11, begin by opening Windows Explorer. Once opened, locate the "Linux" penguin icon in the sidebar and select it.

 Upon selecting "Linux," a folder named "Ubuntu-22.04" will appear. Right-click this folder and choose "Pin to Quick access." This action allows you to effortlessly access your Ubuntu files from Windows.

![Ubuntu WSL's file access in the Windows 11 Explorer app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-selecting-ub.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 To access Windows files from Ubuntu, navigate to the **/mnt/c** folder using the cd command. This method provides interaction with the Windows 11 **C:/** drive.

cd /mnt/c

###  Update your Ubuntu WSL app

 It is good practice to update your Ubuntu WSL app from time to time, otherwise programs will stop working. Here's how to do it on Windows 11.

 First, open up the Ubuntu app from the Windows Start Menu. Once it is open, run the apt update command to check for Ubuntu software updates.

sudo apt update

 When you've finished checking for updates, you can use the apt upgrade command to install them.

sudo apt upgrade

![Ubuntu WSL is being updated.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-installing-kdenlive.png) 

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
##  Starting and Using Ubuntu

 Ubuntu in Windows 11 has a terminal interface with WSL. WSL is a Linux system layer that is accessible directly from Windows, rather than a Linux desktop on top of the Windows Desktop.

 Using Ubuntu means installing packages to use on Windows 11\. To start Ubuntu, search for "Ubuntu 22.04.3 LTS" in the Windows Start Menu. Once it is opened, it'll be ready to use.

 From here, you can install any app you like. To install an Ubuntu app on your Windows 11 system, start by searching for the name of the app. You can search using the apt search command. For example, to find "wireshark," do:

apt search wireshark

 Look through the search results for the program you wish to install. Then, use the "apt install programname" command. To install Wireshark, for example, it's:

sudo apt install wireshark

 When your program is installed, you can launch it directly from the terminal with the following command:

nohup program_name & disown

![Linux apps Kdenlive and Wireshark are running inside of Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-kdenlive-and-wireshark-open.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 Alternatively, applications can be started from the Windows 11 start menu.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Integration with Windows 11

 When apps are installed through WSL, they integrate into Windows 11 quite well by installing themselves into the Windows 11 Start menu. To access your installed WSL programs from Windows 11, look through your programs. Each integrated application will have a Linux icon.

 The WSL integration with Windows 11 is quite good. However, keep in mind that not every single application is going to create a desktop icon. Sometimes, you may need to launch your Ubuntu programs directly from the terminal. You typically do this by typing its package name and hitting Enter.

##  Troubleshooting Common Setup Issues

 WSL usually installs without a hitch on Windows 11\. However, if you're having issues, there is a quick and easy fix. First, open up PowerShell in Windows 11\. Once it is open, use the update command for WSL. Updating WSL will install various patches and fixes that are sure to alleviate the issues you're experiencing.

wsl --update

 Alternatively, if updating doesn't help, consider re-installing Ubuntu WSL again by following the installation instructions in the "Setup" portion of this guide.

---

 WSL upgrades your Windows 11 experience by bringing Ubuntu apps to your desktop without the hassle of virtualization. Jump into Ubuntu and WSL to enhance the power of your Windows 11 PC and discover new possibilities in computing.

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
<li><a href="https://extra-approaches.techidaily.com/new-picsart-mastery-in-depth-look-at-the-2024-version/"><u>[New] PicsArt Mastery  In-Depth Look at the 2024 Version</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-overwatch-black-screen-on-launch/"><u>[Solved] Overwatch Black Screen on Launch</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722996612370-solved-titanfall-2-fps-drops-quickly-and-easily/"><u>[SOLVED] Titanfall 2 FPS Drops | Quickly & Easily!</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-bold-bio-brilliance-groundbreaking-ideas-for-increasing-follower-count-on-tiktok-through-filmora/"><u>[Updated] 2024 Approved  Bold Bio Brilliance  Groundbreaking Ideas for Increasing Follower Count on TikTok Through Filmora</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-smartphone-to-screen-uploading-pics-on-youtube/"><u>[Updated] From Smartphone to Screen  Uploading Pics on YouTube</u></a></li>
<li><a href="https://win-blog.techidaily.com/addressed-notice-itunes-detected-a-glitch-with-your-speaker-configuration/"><u>Addressed Notice: ITunes Detected a Glitch with Your Speaker Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-black-ops-cold-war-error-code-887a0005-ultimate-fix-guide-for-gamers/"><u>Beat Black Ops Cold War Error Code 887A0005 - Ultimate Fix Guide for Gamers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-ip110-driver-download-for-windows-111087/"><u>Canon iP110 Driver Download for Windows 11/10/8/7</u></a></li>
<li><a href="https://win-blog.techidaily.com/cs-go-boot-problem-fixes-how-to-get-your-game-running-smoothly/"><u>CS GO Boot Problem Fixes - How to Get Your Game Running Smoothly</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-techniques-to-repair-pacific-drive-malfunctions-on-your-computer/"><u>Effective Techniques to Repair Pacific Drive Malfunctions on Your Computer</u></a></li>
<li><a href="https://win-blog.techidaily.com/elite-dangerous-stability-fixes-handling-sudden-shutdowns-on-pc/"><u>Elite Dangerous Stability Fixes: Handling Sudden Shutdowns on PC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/engaging-audiences-on-instagram-the-power-of-creative-puzzles-for-2024/"><u>Engaging Audiences on Instagram  The Power of Creative Puzzles for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723013381433-fall-guys-for-pc-resolve-freezing-problems-quickly/"><u>Fall Guys for PC - Resolve Freezing Problems Quickly!</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-guide-how-to-resolve-steam-games-wont-start-on-windows-11/"><u>Fix Guide: How to Resolve 'Steam Games Won't Start on Windows 11'</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixed-and-mastered-top-strategies-for-seamless-play-in-helldivers-2-pc/"><u>Fixed & Mastered! Top Strategies for Seamless Play in Helldivers 2 (PC)</u></a></li>
<li><a href="https://win-blog.techidaily.com/fps-drop-resolved-latest-patch-for-call-of-duty-modern-warfare-now-live/"><u>FPS Drop Resolved: Latest Patch for Call of Duty: Modern Warfare Now Live</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Honor Magic5 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-a-crashing-problem-in-frostpunk-a-comprehensive-guide/"><u>How to Fix a Crashing Problem in Frostpunk: A Comprehensive Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-from-apple-iphone-x-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working From Apple iPhone X</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-the-destiny-warzone-memory-glitch-error-code-0-1766-on-your-console-and-pc/"><u>How to Fix the Destiny Warzone Memory Glitch (Error Code 0-1766) on Your Console & PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723001415615-how-to-overcome-sea-of-thieves-start-up-errors-and-play-today/"><u>How to Overcome Sea of Thieves Start-Up Errors and Play Today</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-the-persistent-crashing-issue-in-subnautica-below-zero-for-windows-users/"><u>How to Resolve the Persistent Crashing Issue in Subnautica: Below Zero for Windows Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-sea-of-thieves-from-keeping-on-crashing-a-complete-guide/"><u>How to Stop Sea of Thieves From Keeping on Crashing: A Complete Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-tecno-pova-5-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Tecno Pova 5 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-discarding-virtual-gatherings-on-fb-pcsmartphones/"><u>In 2024, Discarding Virtual Gatherings on FB, PC/Smartphones</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-optimal-environmental-film-tech-roundup/"><u>In 2024, Optimal Environmental Film Tech Roundup</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-penning-parting-prose-for-press/"><u>In 2024, Penning Parting Prose for Press</u></a></li>
<li><a href="https://win-blog.techidaily.com/navigating-through-exception-access-violation-a-guide-for-civic-enthusiasts/"><u>Navigating Through 'Exception Access Violation' - A Guide for Civic Enthusiasts</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723010588544-overcoming-call-of-duty-wwiis-windows-black-screen-fault-expert-solutions-unlocked/"><u>Overcoming Call of Duty WWII's Windows Black Screen Fault - Expert Solutions Unlocked!</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-delays-on-spotifys-online-platform-fixing-performance-issues-in-202e/"><u>Overcoming Delays on Spotify's Online Platform – Fixing Performance Issues in 202E</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-rusts-display-flaw-solutions-and-tips/"><u>Overcoming Rust's Display Flaw - Solutions and Tips</u></a></li>
<li><a href="https://win-blog.techidaily.com/persona-amo-4-golden-troubleshooting-and-crash-fixes/"><u>Persona Amo 4 Golden Troubleshooting & Crash Fixes</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-error-enjoy-payday-2-gameplay-on-personal-computers-today/"><u>Resolved Error - Enjoy Payday 2 Gameplay on Personal Computers Today</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-issue-tf2-frequent-crashes-how-to-fix-them/"><u>Resolved Issue: TF2 Frequent Crashes - How to Fix Them</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/resolving-common-instagram-video-glitches-for-2024/"><u>Resolving Common Instagram Video Glitches for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-far-cry-6s-persistent-black-screen-glitches-efficiently/"><u>Resolving Far Cry 6'S Persistent Black Screen Glitches Efficiently</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-the-issue-why-your-pc-crashes-when-playing-fallout-3-on-windows-11/"><u>Resolving the Issue: Why Your PC Crashes When Playing Fallout 3 on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sd-unheard-of-find-the-way-out/"><u>SD Unheard Of? Find the Way Out</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/sparking-social-media-stories-facebook-fame-techniques/"><u>Sparking Social Media Stories  Facebook Fame Techniques</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-fixes-for-players-facing-problems-with-palworld-startup/"><u>Step-by-Step Fixes for Players Facing Problems with Palworld Startup</u></a></li>
<li><a href="https://win-blog.techidaily.com/steps-to-correct-continuous-halt-in-deathloop-performance-for-playstation-5-and-pc-users/"><u>Steps to Correct Continuous Halt in Deathloop Performance for PlayStation 5 and PC Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-preservation-digitizing-and-safeguarding-faded-family-memories-for-2024/"><u>The Art of Preservation  Digitizing & Safeguarding Faded Family Memories for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/top-strategies-to-eliminate-latency-in-your-dota-2-gameplay-this-year/"><u>Top Strategies to Eliminate Latency in Your Dota 2 Gameplay This Year</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshoot-and-repair-discord-js-errors-with-ease/"><u>Troubleshoot and Repair Discord JS Errors with Ease</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-resolving-issues-with-pacifica-drives-that-wont-start/"><u>Troubleshooting Guide: Resolving Issues with Pacifica Drives That Won't Start</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-solving-issues-with-non-responsive-amd-radeon-software/"><u>Troubleshooting Tips: Solving Issues with Non-Responsive AMD Radeon Software</u></a></li>
<li><a href="https://win-blog.techidaily.com/understanding-and-resolving-the-causes-behind-dragon-age-origins-unstable-performance-in-windows-n-based-computers/"><u>Understanding and Resolving the Causes Behind Dragon Age: Origins' Unstable Performance in Windows N-Based Computers</u></a></li>
</ul></div>
