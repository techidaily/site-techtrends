---
title: "[SOLVED] Windows 10 Installation Has Failed"
date: 2024-08-18T21:09:37.129Z
updated: 2024-08-19T21:09:37.129Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes [SOLVED] Windows 10 Installation Has Failed
excerpt: This Article Describes [SOLVED] Windows 10 Installation Has Failed
thumbnail: https://thmb.techidaily.com/5d2a2664a22a9ce0adee406a11257a41dccd9059883156b786595c2defcdb7b3.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-streamline-your-playtime-with-nvidia/"><u>[New] 2024 Approved  Streamline Your Playtime with NVIDIA</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-bridging-the-media-gap-coordinating-vids-on-twitter-and-tumblr-for-2024/"><u>[New] Bridging the Media Gap  Coordinating Vids on Twitter & Tumblr for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-how-to-edit-youtube-videos-in-finalcut-pro/"><u>[New] In 2024, How to Edit YouTube Videos in Finalcut Pro</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-pick-your-favorite-top-ios-apps-for-facebook-video-loading/"><u>[New] In 2024, Pick Your Favorite  Top iOS Apps for Facebook Video Loading</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-zoom-into-your-workspace-learn-screen-casting-via-ezvide/"><u>[New] Zoom Into Your Workspace  Learn Screen Casting via EZvide</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-video-avi-into-graphic-image-gif-filmoras-complete-guide/"><u>2024 Approved  Mastering Video (AVI) Into Graphic Image (GIF)  Filmora's Complete Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-comprehensive-tutorial-on-setting-up-two-factor-authentication-in-gmail/"><u>A Comprehensive Tutorial on Setting Up Two-Factor Authentication in Gmail</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-guide-to-discovering-virtual-augmentations/"><u>A Guide to Discovering Virtual Augmentations</u></a></li>
<li><a href="https://techtrends.techidaily.com/access-free-literature-the-ultimate-list-of-17-book-download-sites/"><u>Access Free Literature: The Ultimate List of 17 Book Download Sites</u></a></li>
<li><a href="https://techtrends.techidaily.com/alexa-versus-google-assistant-which-one-reigns-supreme/"><u>Alexa Versus Google Assistant - Which One Reigns Supreme?</u></a></li>
<li><a href="https://techtrends.techidaily.com/apple-watch-cell-data-woes-discover-how-to-restore-and-improve-mobile-connectivity-on-your-wrist-device/"><u>Apple Watch Cell Data Woes? Discover How to Restore and Improve Mobile Connectivity on Your Wrist Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/cross-platform-enjoyment-how-to-stream-your-favorite-videos-from-pc-or-mac-to-apple-tv-with-vlc/"><u>Cross-Platform Enjoyment: How to Stream Your Favorite Videos From PC or Mac to Apple TV with VLC</u></a></li>
<li><a href="https://techtrends.techidaily.com/decoding-the-solution-to-lameencdll-errors-within-your-audacity-lame-mp3-projects/"><u>Decoding the Solution to lame_enc.dll Errors Within Your Audacity LAME MP3 Projects</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-the-most-popular-cam-recorder-software-top-18/"><u>Discover the Most Popular Cam Recorder Software (Top 18)</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-these-10-popular-alternatives-to-netflix-at-no-charge/"><u>Discover These 10 Popular Alternatives to Netflix at No Charge</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-text-messaging-automation-techniques-for-ios-smartphone-enthusiasts/"><u>Effective Text Messaging Automation Techniques for iOS Smartphone Enthusiasts</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-instructions-for-transmitting-oral-notes-with-iphones-built-in-tools-and-apps/"><u>Effortless Instructions for Transmitting Oral Notes with iPhone's Built-In Tools and Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tricks-to-conquer-the-royal-match-challenge/"><u>Essential Tricks to Conquer the Royal Match Challenge</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/explore-and-exploit-mondly-to-perfection/"><u>Explore and Exploit Mondly to Perfection</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-gaming-to-memories-easy-steps-for-recording-ps4-games-live/"><u>From Gaming to Memories: Easy Steps for Recording PS4 Games Live</u></a></li>
<li><a href="https://techtrends.techidaily.com/has-the-papacy-embraced-digital-communication-with-emails-under-pope-francis/"><u>Has the Papacy Embraced Digital Communication with Emails Under Pope Francis?</u></a></li>
<li><a href="https://techtrends.techidaily.com/impact-of-ram-speed-and-access-times-on-computer-performance/"><u>Impact of RAM Speed & Access Times on Computer Performance</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-mr-beasts-monetary-milestones/"><u>In 2024, Mr. Beast’s Monetary Milestones</u></a></li>
<li><a href="https://techtrends.techidaily.com/key-fact-3-relative-abundance-the-height-or-area-of-each-peak-represents-the-relative-amount-of-ions-at-that-specific-mz-ratio-compared-to-the-total-ion-cou83/"><u>Key Fact #3: Relative Abundance - The Height or Area of Each Peak Represents the Relative Amount of Ions at that Specific M/Z Ratio Compared to the Total Ion Count, Expressed as a Percentage.</u></a></li>
<li><a href="https://techtrends.techidaily.com/masterclass-choosing-a-phone-case-that-protects-and-stands-out/"><u>Masterclass: Choosing a Phone Case that Protects & Stands Out</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-art-of-gesture-tracking-for-2024/"><u>Mastering the Art of Gesture Tracking for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-rated-video-creation-tools-for-windows-10/"><u>New Top-Rated Video Creation Tools for Windows 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/reviving-the-brightness-of-your-androids-screen-how-to-fix-dark-screens/"><u>Reviving the Brightness of Your Android's Screen – How-To Fix Dark Screens</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-tracking-and-analyzing-your-internet-consumption/"><u>Step-by-Step Guide: Tracking and Analyzing Your Internet Consumption</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-beginners-pathway-to-installing-and-running-windows-10-on-a-fresh-hard-drive/"><u>The Beginner's Pathway to Installing and Running Windows 10 on a Fresh Hard Drive</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-complete-guide-to-securing-your-twitch-account-with-2fa-setup-and-use-instructions/"><u>The Complete Guide to Securing Your Twitch Account with 2FA Setup & Use Instructions</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-future-of-googles-smartphone-lineup-insights-into-google-pixel-nines-arrival-estimated-price-points-and-hardware-specs/"><u>The Future of Google's Smartphone Lineup: Insights Into Google Pixel Nine's Arrival, Estimated Price Points & Hardware Specs</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-walkthrough-for-powering-down-iphone-models-15-propro-max/"><u>The Ultimate Walkthrough for Powering Down iPhone Models 15 Pro/Pro Max</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-tv-series-airing-currently-on-max-network/"><u>Top TV Series Airing Currently on MAX Network</u></a></li>
<li><a href="https://techtrends.techidaily.com/turning-network-discovery-on-and-off-the-ultimate-tutorial-for-windows-11-users/"><u>Turning Network Discovery ON and OFF: The Ultimate Tutorial for Windows 11 Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/unified-audio-powerhouse-tips-for-linking-up-your-bluetooth-speakers-easily/"><u>Unified Audio Powerhouse: Tips for Linking Up Your Bluetooth Speakers Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-your-pcs-potential-how-to-enjoy-mobile-gaming-and-apps-with-windows-1-setup-for-android-in-windows-10/"><u>Unlock Your PC's Potential: How to Enjoy Mobile Gaming and Apps with Windows 1# Setup for Android in Windows 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/unraveling-the-details-of-roaming-charges-with-atandt-wireless-services/"><u>Unraveling the Details of Roaming Charges with AT&T Wireless Services</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->