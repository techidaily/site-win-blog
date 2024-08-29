---
title: "Mastering Quick Network Latency Checks: Cross-Platform Guide for Windows, MacOS & Linux"
date: 2024-08-28T05:40:11.695Z
updated: 2024-08-29T05:40:11.695Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/031a4402ffc175410606d46c107303b712eafaa4d65eb4fb68f4c0c322106dcd.jpg
---

## Mastering Quick Network Latency Checks: Cross-Platform Guide for Windows, MacOS & Linux

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Run a Speed Test on Linux via Terminal

 Linux users have a slightly different setup process, as the steps can vary depending on the distribution. Here, we'll cover the installation process for one of the [most widely used distributions](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/): Debian/Ubuntu.

 First, open a Terminal window. Before installing the speed test CLI, you may need to install curl, a command-line tool for transferring data with URLs. If you're unsure whether curl is installed, you can install it by running:

        `sudo apt-get install curl`
    
 Next, add the Ookla repository to your list of package sources. This ensures that you get the latest version of the speed test CLI. Use the following command to do this:

        `curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash`
    
 Once the repository is added, you can install the speed test CLI with:

        `sudo apt-get install speedtest`
    
![Running Speedtest CLI on Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-on-ubuntu-1.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After installation, you can test your internet speed by typing "speedtest" in the Terminal and pressing enter. This command will run the test and display the results directly in the window.

---

 Using Ookla's CLI speed test is an efficient way to measure your internet connection speed without the distractions and slowdowns caused by browser-based tools. No matter which OS you're using, this lightweight tool provides accurate and quick results. It's particularly useful when you want to avoid ads or need to integrate speed tests into automated systems or scripts.

 With just a few commands or a shortcut workflow, you can have a reliable tool at your disposal for monitoring and diagnosing your network performance, empowering you to run a network test at the drop of a hat or a hotkey.

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
<li><a href="https://extra-information.techidaily.com/new-construct-your-dreams-with-dynamic-time-lapses-on-a-hero5/"><u>[New] Construct Your Dreams with Dynamic Time-Lapses on a Hero5</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-revolutionizing-the-market-the-leading-7-tools-to-create-digital-tokens/"><u>[New] In 2024, Revolutionizing the Market - The Leading 7 Tools to Create Digital Tokens</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-witness-humor-with-hearts-on-instagram-top-10-memes-to-admire/"><u>[Updated] 2024 Approved  Witness Humor with Hearts on Instagram  Top 10 Memes to Admire</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-beat-the-bounds-of-voice-modification-the-leading-chrome-apps-unveiled/"><u>[Updated] Beat the Bounds of Voice Modification  The Leading Chrome Apps Unveiled</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-mastering-hashtags-enhance-your-gaming-youtube-content/"><u>[Updated] In 2024, Mastering Hashtags  Enhance Your Gaming YouTube Content</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-new-era-facebooks-quintessential-features-showcased/"><u>[Updated] New Era  Facebook's Quintessential Features Showcased</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-framing-for-instagram-techniques-for-vertical-footage-in-fcpx/"><u>2024 Approved  Framing for Instagram  Techniques for Vertical Footage in FCPX</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-e-learning-titling-toolkit/"><u>2024 Approved  Leading E-Learning Titling Toolkit</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-forza-horizon-amoads-loading-screen-glitch-7-essential-fixes-for-gamers/"><u>Beat Forza Horizon Amoad's Loading Screen Glitch: 7 Essential Fixes for Gamers</u></a></li>
<li><a href="https://win-blog.techidaily.com/call-of-duty-how-to-quickly-fix-warzones-dev-error-asterisk-error-code-6634/"><u>Call of Duty: How to Quickly Fix Warzone's Dev Error Asterisk Error Code 6634</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721869684834-chatgpt-conversation-storage-learn-how-to-stop-it-now/"><u>ChatGPT Conversation Storage? Learn How to Stop It Now</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723013114752-directx-glitch-in-anno-1800-heres-your-ultimate-solution/"><u>DirectX Glitch in Anno 1800? Here's Your Ultimate Solution!</u></a></li>
<li><a href="https://win-blog.techidaily.com/diy-solutions-for-preventing-doom-eternal-from-crashing/"><u>DIY Solutions for Preventing DOOM Eternal From Crashing</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-tips-to-overcome-gta-vs-d3d-initialization-flaw-the-errgfxd3dinit-error/"><u>Expert Tips to Overcome GTA V's D3D Initialization Flaw - The ERR_GFX_D3D_INIT Error</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-inwin-f5-pc-case-features-dual-connectivity-and-aesthetic-wooden-design/"><u>Exploring the InWin F5 PC Case Features: Dual Connectivity & Aesthetic Wooden Design</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-common-issues-why-your-discord-audio-isnt-working-during-screen-shares/"><u>Fixing Common Issues: Why Your Discord Audio Isn't Working During Screen Shares</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-issues-how-to-stop-microsoft-flight-simulator-2-cuase-from-crashing-your-pc/"><u>Fixing Issues: How to Stop Microsoft Flight Simulator 2 Cuase From Crashing Your PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-the-crash-problem-a-step-by-step-solution-for-slime-rancher-2-pc-glitches/"><u>Fixing the Crash Problem: A Step-by-Step Solution for 'Slime Rancher 2' PC Glitches</u></a></li>
<li><a href="https://win-blog.techidaily.com/future-proof-your-gameplay-ps5-vs-ps4-pro-edition/"><u>Future-Proof Your Gameplay: PS5 vs PS4 Pro Edition</u></a></li>
<li><a href="https://win-blog.techidaily.com/getting-past-the-stuck-loader-expert-tips-for-madden-22-gameplay-fixes/"><u>Getting Past the Stuck Loader: Expert Tips for Madden 22 Gameplay Fixes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-among-us-freezing-issue-expert-tips-and-solutions/"><u>How to Overcome Among Us Freezing Issue: Expert Tips and Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-the-required-apple-store-verification-for-iphone-se-2020-drfone-by-drfone-ios/"><u>In 2024, How To Bypass the Required Apple Store Verification For iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-oneplus-ace-2-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On OnePlus Ace 2</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/keep-the-click-going-tips-for-automatically-backing-up-snapshots/"><u>Keep the Click Going  Tips for Automatically Backing Up Snapshots</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-realme-narzo-60-pro-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Realme Narzo 60 Pro 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-utorrent-performance-ensuring-stable-peer-connections-and-continuous-downloads/"><u>Mastering uTorrent Performance: Ensuring Stable Peer Connections and Continuous Downloads</u></a></li>
<li><a href="https://win-blog.techidaily.com/maximizing-performance-enabling-gpu-usage-in-cyberpunk-2077-on-windows-10-devices/"><u>Maximizing Performance: Enabling GPU Usage in Cyberpunk 2077 on Windows 10 Devices</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-diva-error-code-6-in-pc-version-of-call-of-duty-modern-warfare/"><u>Overcoming DIVA Error Code 6 in PC Version of Call of Duty: Modern Warfare</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-the-unable-to-locate-launch-point-hurdle-in-fortnite-for-smooth-gaming/"><u>Overcoming the 'Unable to Locate Launch Point' Hurdle in Fortnite for Smooth Gaming</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-total-vrchat-failure-a-step-by-step-guide-to-fixing-launch-problems/"><u>Overcoming Total VRChat Failure: A Step-by-Step Guide to Fixing Launch Problems</u></a></li>
<li><a href="https://win-blog.techidaily.com/path-of-exile-2024-connection-issues-solved-a-comprehensive-instance-setup-guide/"><u>Path of Exile 2024 Connection Issues Solved: A Comprehensive Instance Setup Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/star-wars-squadrons-game-issue-resolved/"><u>STAR WARS Squadrons Game Issue Resolved</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-resolving-fallout-3-stutter-and-freeze-issues-on-windows-10/"><u>Troubleshooting Guide: Resolving Fallout 3 Stutter and Freeze Issues on Windows 10</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-overcoming-the-warzone-memory-glitch-on-xbox-and-pc-error-0-1766/"><u>Troubleshooting Tips for Overcoming the Warzone Memory Glitch on Xbox and PC (Error 0-1766)</u></a></li>
<li><a href="https://some-tips.techidaily.com/unravel-the-mystery-of-scouring-exceptional-photos-on-pexels-for-2024/"><u>Unravel the Mystery of Scouring Exceptional Photos on Pexels for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/unveiling-achieving-the-ultimate-mass-effect-legendary-collection-with-epic-fps-rewards/"><u>Unveiling: Achieving the Ultimate Mass Effect Legendary Collection with Epic FPS Rewards</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723011001011-why-wont-my-game-launch-ensuring-proper-game-file-setup-is-key/"><u>Why Won't My Game Launch? Ensuring Proper Game File Setup Is Key!</u></a></li>
</ul></div>
