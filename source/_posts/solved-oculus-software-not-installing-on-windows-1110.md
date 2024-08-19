---
title: "[SOLVED] Oculus Software Not Installing on Windows 11/10"
date: 2024-08-18T21:05:03.162Z
updated: 2024-08-19T21:05:03.162Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes [SOLVED] Oculus Software Not Installing on Windows 11/10
excerpt: This Article Describes [SOLVED] Oculus Software Not Installing on Windows 11/10
thumbnail: https://thmb.techidaily.com/cec958dbb28e58c65e080cad326f07d4e7cdd67a50648dc244def701160f50d9.png
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
<li><a href="https://fox-direct.techidaily.com/new-crafting-the-future-revolutionary-tools-for-3d-modelers/"><u>[New] Crafting the Future  Revolutionary Tools for 3D Modelers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-expert-advice-on-lighting-your-youtube-content-perfectly/"><u>[New] Expert Advice on Lighting Your YouTube Content Perfectly</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-can-i-stop-my-videos-from-flipping-on-instagram/"><u>[New] How Can I Stop My Videos From Flipping on Instagram?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-skyrocket-with-subscribers-5-proven-methods-for-igtv-success/"><u>[New] In 2024, Skyrocket with Subscribers  5 Proven Methods for IGTV Success</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-the-photographers-companion-to-master-color-correction-top-11/"><u>[New] In 2024, The Photographer's Companion to Master Color Correction (Top 11)</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-unlocking-windows-10-indispensable-hacks-and-fixes/"><u>[New] In 2024, Unlocking Windows 10  Indispensable Hacks & Fixes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-securing-your-playtime-with-diverse-gaming-screen-capture-software/"><u>[New] Securing Your Playtime with Diverse Gaming Screen Capture Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-best-ways-to-record-live-sports-streaming/"><u>[Updated] 2024 Approved  Best Ways to Record Live Sports Streaming</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-journey-through-high-dynamic-range-pc-viewing-and-creative-pursuits/"><u>[Updated] 2024 Approved  Journey Through High Dynamic Range  PC Viewing & Creative Pursuits</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-obscurity-to-star-in-3-simple-steps/"><u>[Updated] From Obscurity to Star in 3 Simple Steps</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-mastering-ps4-captures-with-obs-studio-your-complete-guide/"><u>[Updated] In 2024, Mastering PS4 Captures with OBS Studio - Your Complete Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-onestepcams-evaluation-are-we-overlooking-gems/"><u>2024 Approved  OneStepCams Evaluation  Are We Overlooking Gems?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-projecting-film-costs-for-your-music-video/"><u>2024 Approved  Projecting Film Costs for Your Music Video</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-real-time-vr-hardware-analysis/"><u>2024 Approved  Real-Time VR Hardware Analysis</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-top-10-android-mobas-essential-players-list/"><u>2024 Approved  Top 10 Android MOBAs  Essential Players' List</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-quest-for-collective-ownership-art-without-boundaries-for-2024/"><u>A Quest for Collective Ownership  Art Without Boundaries for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/anticipating-the-arrival-apple-watch-series-release-date-cutting-edge-specs-price-analysis-and-current-headlines/"><u>Anticipating the Arrival: Apple Watch Series Ⅷ Release Date, Cutting-Edge Specs, Price Analysis & Current Headlines</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/business-mastery-through-youtubes-top-ten-channels/"><u>Business Mastery Through YouTube's Top Ten Channels</u></a></li>
<li><a href="https://techtrends.techidaily.com/code-28-issues-on-your-pc-heres-how-to-fix-them/"><u>Code 28 Issues on Your PC? Here's How to Fix Them</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-to-top-22-graphic-design-suites-and-applications/"><u>Comprehensive Guide to Top 22 Graphic Design Suites and Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/connect-and-compete-a-step-by-step-guide-to-playing-games-on-ps5-with-others/"><u>Connect and Compete: A Step-by-Step Guide to Playing Games on PS5 With Others</u></a></li>
<li><a href="https://techtrends.techidaily.com/connect-and-enjoy-tiktoks-on-the-big-screen-a-comprehensive-how-to/"><u>Connect and Enjoy TikToks on the Big Screen: A Comprehensive How-To</u></a></li>
<li><a href="https://techtrends.techidaily.com/decoding-youtube-outages-reasons-and-remedies/"><u>Decoding YouTube Outages: Reasons and Remedies</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-restoring-mfplatdll-files-to-resolve-system-error-messages/"><u>Diagnosing & Restoring mfplat.dll Files to Resolve System Error Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/disabling-amber-alerts-the-ultimate-guide-for-android-users/"><u>Disabling AMBER Alerts: The Ultimate Guide for Android Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-6-amazing-free-substitutes-for-adobe-photoshop/"><u>Discover 6 Amazing Free Substitutes for Adobe Photoshop</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-whos-tuning-in-to-your-youtube-videos-and-why-they-watch/"><u>Discover Who's Tuning In to Your YouTube Videos and Why They Watch</u></a></li>
<li><a href="https://fox-helps.techidaily.com/envisioning-artistry-a-gopro-hero5-black-journey-to-excellence-for-2024/"><u>Envisioning Artistry  A GoPro Hero5 Black Journey to Excellence for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/find-new-connections-5-must-have-apps-for-building-relationships/"><u>Find New Connections: 5 Must-Have Apps for Building Relationships</u></a></li>
<li><a href="https://techtrends.techidaily.com/first-steps-in-home-acoustics-your-all-inclusive-guide-for-newbies/"><u>First Steps in Home Acoustics: Your All-Inclusive Guide for Newbies</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-silence-to-soundscapes-an-in-depth-beginners-handbook-on-home-audio-systems/"><u>From Silence to Soundscapes: An In-Depth Beginner's Handbook on Home Audio Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-to-accessing-netflix-through-your-gaming-console-nintendo-switch-included/"><u>Guide to Accessing Netflix Through Your Gaming Console, Nintendo Switch Included!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-tecno-spark-10-5g-frp-by-drfone-android/"><u>How Can We Bypass Tecno Spark 10 5G FRP?</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-block-unwanted-emergency-notifications-in-android-devices/"><u>How to Block Unwanted Emergency Notifications in Android Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-correctly-address-and-repair-ac1st16dll-is-absent-bugs/"><u>How to Correctly Address and Repair ac1st16.dll Is Absent Bugs</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-prevent-apple-music-from-auto-playing-next-tracks/"><u>How To Prevent Apple Music From Auto-Playing Next Tracks</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-screen-share-netflix/"><u>How to Screen Share Netflix</u></a></li>
<li><a href="https://techtrends.techidaily.com/hulus-errorrununk13-bug-easy-fixes-and-workarounds/"><u>Hulu's ERROR_RUNUNK13 Bug: Easy Fixes and Workarounds</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-the-apple-iphone-13-mini-icloud-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing the Apple iPhone 13 mini iCloud Lock</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-realme-v30t-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Realme V30T FRP Bypass With Best Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-how-to-do-a-poll-on-instagram-stories-a-complete-guide/"><u>In 2024, How to Do a Poll on Instagram Stories - a Complete Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-treacle-tracking-step-by-step-tutorial-on-summer-snack-monitoring/"><u>In 2024, Treacle Tracking  Step-by-Step Tutorial on Summer Snack Monitoring</u></a></li>
<li><a href="https://howto.techidaily.com/restore-missing-app-icon-on-samsung-galaxy-m14-4g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Samsung Galaxy M14 4G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/simple-steps-for-mirroring-android-content-on-your-fire-stick-device/"><u>Simple Steps for Mirroring Android Content on Your Fire Stick Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-correctly-address-the-problem-encountered-while-resetting-message-in-windows-11/"><u>Solved! How to Correctly Address the 'Problem Encountered While Resetting' Message in Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-adding-audio-tracks-to-your-instagram-videos/"><u>Step-by-Step Guide: Adding Audio Tracks to Your Instagram Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-correct-sequence-viewing-lord-of-the-rings-trilogy-step-by-step/"><u>The Correct Sequence: Viewing 'Lord of the Rings' Trilogy Step-by-Step</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-insiders-handbook-to-deciphering-snapchat-emojis/"><u>The Insider's Handbook to Deciphering Snapchat Emojis</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-lg-k51-smartphone-critique-impressive-aesthetics-overshadowed-by-lagging-cpu-speed/"><u>The LG K51 Smartphone Critique - Impressive Aesthetics Overshadowed by Lagging CPU Speed</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-gen-iphone-released-in-teasers-pricing-arrival-dates-and-speculations-on-its-advances/"><u>The Next-Gen iPhone Released in Teasers: Pricing, Arrival Dates and Speculations on Its Advances!</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-12-best-free-online-calling-apps-of-2024-you-should-try/"><u>Top 12 Best Free Online Calling Apps of 2024 You Should Try</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-infinix-note-30-vip-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Infinix Note 30 VIP Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-http-408-errors-a-comprehensive-guide-to-fixing-timeouts/"><u>Troubleshooting HTTP 408 Errors: A Comprehensive Guide to Fixing Timeouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-and-controlling-your-online-data-footprint/"><u>Understanding and Controlling Your Online Data Footprint</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-ray-tracing-technology-and-its-applications/"><u>Understanding Ray Tracing Technology and Its Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-expect-from-the-new-google-pixel-watch-leaked-specs-cost-forecasts-release-schedule/"><u>What to Expect From the New Google Pixel Watch: Leaked Specs, Cost Forecasts, Release Schedule</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/whats-not-advertised-ten-facts-about-instagram-reels-for-2024/"><u>What's Not Advertised  Ten Facts About Instagram Reels for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->