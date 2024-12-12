---
title: "Mastering Quick Network Latency Checks: Cross-Platform Guide for Windows, MacOS & Linux"
date: 2024-12-11T16:10:21.463Z
updated: 2024-12-12T17:16:05.514Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-discover-the-best-video-capture-tools-for-windows-users/"><u>[New] 2024 Approved Discover the Best Video Capture Tools for Windows Users</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-authenticating-a-step-by-step-for-youtube-users/"><u>[New] In 2024, Authenticating A Step-by-Step for Youtube Users</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-tune-into-the-beats-with-these-free-online-scanners/"><u>[Updated] In 2024, Tune Into the Beats with These Free Online Scanners</u></a></li>
<li><a href="https://tech-hub.techidaily.com/beyond-human-intelligence-surpassing-the-turing-scale/"><u>Beyond Human Intelligence: Surpassing the Turing Scale</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-fixes-for-call-of-duty-modern-warfare-3-sudden-crash-issues/"><u>Effective Fixes for Call of Duty Modern Warfare 3 Sudden Crash Issues</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/how-to-use-idvd-on-your-mac-accepted-video-sound-and-picture-formats-explained/"><u>How to Use iDVD on Your Mac: Accepted Video, Sound, and Picture Formats Explained</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-s17e-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo S17e Is Unlocked</u></a></li>
<li><a href="https://win-blog.techidaily.com/insider-tips-for-dealing-with-fifa-21-not-launching-situations/"><u>Insider Tips for Dealing with FIFA 21 Not Launching Situations</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-gaming-troubleshooting-eliminate-lag-in-your-favorite-games/"><u>PC Gaming Troubleshooting: Eliminate Lag in Your Favorite Games</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolve-your-gaming-woes-steps-for-fixing-a-failed-ds4-windows-installation/"><u>Resolve Your Gaming Woes: Steps for Fixing a Failed DS4 Windows Installation</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-tormented-souls-pc-glitches-crash-free-gaming-experience-guaranteed/"><u>Say Goodbye to Tormented Souls PC Glitches - Crash-Free Gaming Experience Guaranteed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-5-gif-making-software-with-the-highest-ratings-for-2024/"><u>Top 5 GIF Making Software with the Highest Ratings for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshoot-and-resolve-a-malfunctioning-msi-mystic-light-in-the-windows-environment/"><u>Troubleshoot and Resolve a Malfunctioning MSI Mystic Light in the Windows Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-code-0x80-windows-1110-expert-tips-and-solutions/"><u>Troubleshooting Error Code 0X80^ (Windows 11/10): Expert Tips & Solutions</u></a></li>
</ul></div>

