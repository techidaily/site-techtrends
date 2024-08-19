---
title: Easy Steps to Completely Delete Programs From Windows 10
date: 2024-08-18T21:06:36.624Z
updated: 2024-08-19T21:06:36.624Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Easy Steps to Completely Delete Programs From Windows 10
excerpt: This Article Describes Easy Steps to Completely Delete Programs From Windows 10
thumbnail: https://thmb.techidaily.com/4d8389239c924325f747de29a6fa5fd56f085170de1cb456669c5929df51dc2a.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-is-it-possible-to-watch-fb-videos-on-tv/"><u>[New] 2024 Approved  Is It Possible to Watch FB Videos on TV ?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-streamline-your-media-experience-windows-films-to-vimeo/"><u>[New] 2024 Approved  Streamline Your Media Experience  Windows Films to Vimeo</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-influencing-now-top-10-hashtags-for-your-next-post-for-2024/"><u>[New] Influencing Now  Top 10 Hashtags for Your Next Post for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-ultimate-list-of-viral-stock-images-and-stories/"><u>2024 Approved  The Ultimate List of Viral Stock Images & Stories</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/2024-approved-wealthy-web-showrunners/"><u>2024 Approved  Wealthy Web Showrunners</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-samsung-galaxy-f34-5g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Samsung Galaxy F34 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://techtrends.techidaily.com/all-you-need-to-know-about-the-next-big-apple-unveiling-time-table-and-buzzing-rumors/"><u>All You Need to Know About the Next Big Apple Unveiling: Time Table & Buzzing Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/anticipating-the-arrival-apple-watch-series-release-date-cutting-edge-specs-price-analysis-and-current-headlines/"><u>Anticipating the Arrival: Apple Watch Series Ⅷ Release Date, Cutting-Edge Specs, Price Analysis & Current Headlines</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/blue-screen-of-death-kernel-data-inpage-error-solved/"><u>Blue Screen of Death: Kernel Data Inpage Error Solved</u></a></li>
<li><a href="https://techtrends.techidaily.com/code-28-issues-on-your-pc-heres-how-to-fix-them/"><u>Code 28 Issues on Your PC? Here's How to Fix Them</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-to-top-22-graphic-design-suites-and-applications/"><u>Comprehensive Guide to Top 22 Graphic Design Suites and Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/connect-and-enjoy-tiktoks-on-the-big-screen-a-comprehensive-how-to/"><u>Connect and Enjoy TikToks on the Big Screen: A Comprehensive How-To</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-stunning-animations-with-these-7-best-drawing-software-for-2024/"><u>Create Stunning Animations with These 7 Best Drawing Software for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/decoding-youtube-outages-reasons-and-remedies/"><u>Decoding YouTube Outages: Reasons and Remedies</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-restoring-mfplatdll-files-to-resolve-system-error-messages/"><u>Diagnosing & Restoring mfplat.dll Files to Resolve System Error Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/disabling-amber-alerts-the-ultimate-guide-for-android-users/"><u>Disabling AMBER Alerts: The Ultimate Guide for Android Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-6-amazing-free-substitutes-for-adobe-photoshop/"><u>Discover 6 Amazing Free Substitutes for Adobe Photoshop</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-8-reading-apps-of-2024-we-love/"><u>Discover the Ultimate 8 Reading Apps of 2024 We Love!</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-whos-tuning-in-to-your-youtube-videos-and-why-they-watch/"><u>Discover Who's Tuning In to Your YouTube Videos and Why They Watch</u></a></li>
<li><a href="https://techtrends.techidaily.com/find-new-connections-5-must-have-apps-for-building-relationships/"><u>Find New Connections: 5 Must-Have Apps for Building Relationships</u></a></li>
<li><a href="https://techtrends.techidaily.com/first-steps-in-home-acoustics-your-all-inclusive-guide-for-newbies/"><u>First Steps in Home Acoustics: Your All-Inclusive Guide for Newbies</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-silence-to-soundscapes-an-in-depth-beginners-handbook-on-home-audio-systems/"><u>From Silence to Soundscapes: An In-Depth Beginner's Handbook on Home Audio Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-to-accessing-netflix-through-your-gaming-console-nintendo-switch-included/"><u>Guide to Accessing Netflix Through Your Gaming Console, Nintendo Switch Included!</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-block-unwanted-emergency-notifications-in-android-devices/"><u>How to Block Unwanted Emergency Notifications in Android Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-correctly-address-and-repair-ac1st16dll-is-absent-bugs/"><u>How to Correctly Address and Repair ac1st16.dll Is Absent Bugs</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-prevent-apple-music-from-auto-playing-next-tracks/"><u>How To Prevent Apple Music From Auto-Playing Next Tracks</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-screen-share-netflix/"><u>How to Screen Share Netflix</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-itel-a05s-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Itel A05s Location by Number | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/hulus-errorrununk13-bug-easy-fixes-and-workarounds/"><u>Hulu's ERROR_RUNUNK13 Bug: Easy Fixes and Workarounds</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-6s-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 6s Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-approaches-for-combining-chatgpt-with-your-google-drive-files/"><u>Innovative Approaches for Combining ChatGPT with Your Google Drive Files</u></a></li>
<li><a href="https://techtrends.techidaily.com/inside-scoop-google-tv-streaming-stick-launch-date-pricing-strategies-and-featured-performance-insights/"><u>Inside Scoop: Google TV Streaming Stick Launch Date, Pricing Strategies, and Featured Performance Insights</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-redmi-12-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Redmi 12 5GFRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-hyper-v-for-efficient-linux-vm-creation-in-windows/"><u>Leveraging Hyper-V for Efficient Linux VM Creation in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/mobile-mirroring-watch-anywhere-with-your-android-and-firestick-combo/"><u>Mobile Mirroring: Watch Anywhere with Your Android and Firestick Combo</u></a></li>
<li><a href="https://techtrends.techidaily.com/simple-steps-for-mirroring-android-content-on-your-fire-stick-device/"><u>Simple Steps for Mirroring Android Content on Your Fire Stick Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-adding-audio-tracks-to-your-instagram-videos/"><u>Step-by-Step Guide: Adding Audio Tracks to Your Instagram Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-correct-sequence-viewing-lord-of-the-rings-trilogy-step-by-step/"><u>The Correct Sequence: Viewing 'Lord of the Rings' Trilogy Step-by-Step</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-insiders-handbook-to-deciphering-snapchat-emojis/"><u>The Insider's Handbook to Deciphering Snapchat Emojis</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-gen-iphone-released-in-teasers-pricing-arrival-dates-and-speculations-on-its-advances/"><u>The Next-Gen iPhone Released in Teasers: Pricing, Arrival Dates and Speculations on Its Advances!</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-leading-websites-a-comprehensive-ranking-of-global-internet-giants/"><u>Top 10 Leading Websites: A Comprehensive Ranking of Global Internet Giants</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-12-best-free-online-calling-apps-of-2024-you-should-try/"><u>Top 12 Best Free Online Calling Apps of 2024 You Should Try</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-http-408-errors-a-comprehensive-guide-to-fixing-timeouts/"><u>Troubleshooting HTTP 408 Errors: A Comprehensive Guide to Fixing Timeouts</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-and-controlling-your-online-data-footprint/"><u>Understanding and Controlling Your Online Data Footprint</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-ray-tracing-technology-and-its-applications/"><u>Understanding Ray Tracing Technology and Its Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-expect-from-the-new-google-pixel-watch-leaked-specs-cost-forecasts-release-schedule/"><u>What to Expect From the New Google Pixel Watch: Leaked Specs, Cost Forecasts, Release Schedule</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->