---
title: "Resolving the Issue: Excessive CPU Usage by Windows Modules Installer on Windows 10"
date: 2024-08-18T21:12:37.272Z
updated: 2024-08-19T21:12:37.272Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Resolving the Issue: Excessive CPU Usage by Windows Modules Installer on Windows 10"
excerpt: "This Article Describes Resolving the Issue: Excessive CPU Usage by Windows Modules Installer on Windows 10"
thumbnail: https://thmb.techidaily.com/7dd749384e650dd30b462267307e8e4df40b220cb06bb407dea1434bb08c1a07.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-converting-imovie-edits-for-online-exhibition-youtube-edition/"><u>[New] 2024 Approved  Converting iMovie Edits for Online Exhibition - YouTube Edition</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-seamlessly-blend-apple-music-and-videos/"><u>[New] 2024 Approved  Seamlessly Blend Apple Music & Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-building-connections-with-your-channels-audience/"><u>[New] Building Connections with Your Channel's Audience</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-cutting-edge-strategies-for-recording-slideshows-for-2024/"><u>[New] Cutting-Edge Strategies for Recording Slideshows for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-enhancing-viewer-attention-igtv-cover-tips/"><u>[Updated] 2024 Approved  Enhancing Viewer Attention  IGTV Cover Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-powerpoint-and-voice-a-seamless-journey-explored/"><u>[Updated] 2024 Approved  PowerPoint and Voice  A Seamless Journey Explored</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-unlock-content-potential-with-the-right-vimeo-membership-choice/"><u>[Updated] 2024 Approved  Unlock Content Potential with the Right Vimeo Membership Choice</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-effortless-win-11-screen-captures-here-for-2024/"><u>[Updated] Effortless Win 11 Screen Captures Here for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-scrutinizing-the-functionality-of-pixelrecorder-12/"><u>[Updated] In 2024, Scrutinizing the Functionality of PixelRecorder 12</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-seamless-twitch-content-upload-to-youtube-ready/"><u>[Updated] Seamless Twitch Content Upload to YouTube Ready</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-itel-p55-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-samsung-galaxy-a25-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-dj-beats-unleashed-high-fidelity-templates-downloaded-easily/"><u>2024 Approved  DJ Beats Unleashed  High-Fidelity Templates Downloaded Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-reaching-into-shared-snippets-of-life-on-messenger/"><u>2024 Approved  Reaching Into Shared Snippets of Life on Messenger</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-secure-extraction-converting-youtube-to-trusted-mp4/"><u>2024 Approved  Secure Extraction  Converting YouTube to Trusted MP4</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-synthesizing-worlds-latest-trends-in-virtual-tech/"><u>2024 Approved  Synthesizing Worlds  Latest Trends in Virtual Tech</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-itel-s23-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Itel S23 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/advancing-towards-tomorrow-the-impacts-of-verizons-5g-expansion/"><u>Advancing Towards Tomorrow: The Impacts of Verizon's 5G Expansion</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-your-website-interactivity-instructions-for-activating-cookies-in-your-web-browser/"><u>Boost Your Website Interactivity: Instructions for Activating Cookies in Your Web Browser</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-oppo-a56s-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/comparing-electric-and-gasoline-vehicle-durability-how-does-ev-longevity-stack-up/"><u>Comparing Electric and Gasoline Vehicle Durability - How Does EV Longevity Stack Up?</u></a></li>
<li><a href="https://techtrends.techidaily.com/connecting-your-airpods-a-step-by-step-guide-for-hp-laptop-users/"><u>Connecting Your AirPods: A Step-by-Step Guide for HP Laptop Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/convert-your-social-feeds-videos-into-listenable-audio-for-2024/"><u>Convert Your Social Feed's Videos Into Listenable Audio for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-the-newest-macos-update-an-in-depth-versions-compendium/"><u>Discovering the Newest macOS Update: An In-Depth Versions Compendium</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-your-email-steps-to-locate-your-account/"><u>Discovering Your Email: Steps to Locate Your Account</u></a></li>
<li><a href="https://techtrends.techidaily.com/eliminate-code-groovyerrors-with-these-proven-repair-methods-and-hacks/"><u>Eliminate Code groovyErrors with These Proven Repair Methods and Hacks.</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-advice-for-repairing-a-nonfunctional-or-absent-ocidll-file-on-your-pc/"><u>Expert Advice for Repairing a Nonfunctional or Absent Oci.dll File on Your PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/fix-propsydll-not-detected-or-absent-issues-a-comprehensive-solution-guide/"><u>Fix PropsyDll Not Detected or Absent Issues: A Comprehensive Solution Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/freshly-updated-netgear-default-passwords-for-july-202n4-essential-list/"><u>Freshly Updated NETGEAR Default Passwords for July 202N4 - Essential List</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-to-keeping-your-windows-11-devices-current-with-driver-updates/"><u>Guide to Keeping Your Windows 11 Devices Current with Driver Updates</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hit-the-mark-video-that-skyrockets-in-popularity-for-2024/"><u>Hit the Mark  Video that Skyrockets in Popularity for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-ideal-ringtone-hunt-prime-downloads/"><u>In 2024, Ideal Ringtone Hunt  Prime Downloads</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-oppo-a78-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Oppo A78 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-or-android-finding-the-perfect-match-for-your-lifestyle/"><u>IPhone or Android – Finding the Perfect Match for Your Lifestyle!</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722888805182-jiri-voblizka-founder-crystal-microphone-for-his-contribution-to-czech-culture-by-radio-prague/"><u>Jiří Vobližka (Founder) – Crystal Microphone for His Contribution to Czech Culture by Radio Prague;</u></a></li>
<li><a href="https://techtrends.techidaily.com/key-factors-of-lg-channels-for-effective-brand-messaging/"><u>Key Factors of LG Channels for Effective Brand Messaging</u></a></li>
<li><a href="https://techtrends.techidaily.com/macbook-air-multi-tasking-made-easy-master-the-art-of-split-screen-display/"><u>MacBook Air Multi-Tasking Made Easy: Master the Art of Split Screen Display</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-game-design-with-helldivers-2/"><u>Mastering the Art of Game Design with Helldivers 2</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-timed-texts-a-comprehensive-tutorial-for-iphones/"><u>Mastering Timed Texts: A Comprehensive Tutorial for iPhones</u></a></li>
<li><a href="https://techtrends.techidaily.com/quest-3-lite-unveiled-anticipated-cost-and-launch-timeline-alongside-key-features/"><u>Quest 3 Lite Unveiled: Anticipated Cost & Launch Timeline Alongside Key Features</u></a></li>
<li><a href="https://tech-haven.techidaily.com/seamless-integration-of-chatgpt-into-your-google-docs-and-sheets-workflow/"><u>Seamless Integration of ChatGPT Into Your Google Docs and Sheets Workflow</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-dll-file-not-found-issues-a-step-by-step-guide/"><u>Solving 'DLL File Not Found' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-restoring-defaults-by-flushing-the-cmos/"><u>Step-by-Step Guide: Restoring Defaults by Flushing the CMOS</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-setting-up-windows-11-on-a-brand-new-hard-drive/"><u>Step-by-Step Guide: Setting Up Windows 11 on a Brand New Hard Drive</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-beginners-guide-to-timed-photography-on-iphones-setting-a-countdown-before-every-snap/"><u>The Beginner’s Guide to Timed Photography on iPhones - Setting a Countdown Before Every Snap</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-honor-90-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Honor 90 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-strategies-to-enhance-your-broadband-connection-speed/"><u>Top Strategies to Enhance Your Broadband Connection Speed</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-windows-11-search-issues-top-solutions/"><u>Troubleshooting Windows 11 Search Issues: Top Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-eliminating-horizontal-line-distortions-from-your-monitor/"><u>Ultimate Guide: Eliminating Horizontal Line Distortions From Your Monitor</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-the-secrets-10-expert-hacks-for-successful-subway-surfers-playing/"><u>Unlock the Secrets: 10 Expert Hacks for Successful Subway Surfers Playing</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-your-androids-potential-a-comprehensive-solution-to-call-function-failures/"><u>Unlock Your Android’s Potential: A Comprehensive Solution to Call Function Failures</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-instagrams-secrets-to-widespread-sharing-10-proven-viral-tactics/"><u>Unlocking Instagram's Secrets to Widespread Sharing: 10 Proven Viral Tactics</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-the-secrets-of-net-neutrality-a-detailed-overview/"><u>Unlocking the Secrets of Net Neutrality: A Detailed Overview</u></a></li>
<li><a href="https://techtrends.techidaily.com/upgrading-your-entertainment-why-or-why-not-to-get-a-blu-ray-player/"><u>Upgrading Your Entertainment: Why or Why Not to Get a Blu-Ray Player</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-do-when-your-automobile-audio-goes-silent/"><u>What to Do When Your Automobile Audio Goes Silent?</u></a></li>
<li><a href="https://techtrends.techidaily.com/whatsapp-vs-signal-a-comprehensive-comparison/"><u>WhatsApp vs Signal: A Comprehensive Comparison</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->