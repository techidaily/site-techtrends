---
title: "Resolving the Error: How to Fix 'The Application Failed to Launch - Error Code 0xC0000142'"
date: 2024-08-18T21:09:29.833Z
updated: 2024-08-19T21:09:29.833Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Resolving the Error: How to Fix 'The Application Failed to Launch - Error Code 0xC0000142'"
excerpt: "This Article Describes Resolving the Error: How to Fix 'The Application Failed to Launch - Error Code 0xC0000142'"
thumbnail: https://thmb.techidaily.com/919428e7eabfca4b711aa4a4cd51f4e93cb7908e27ba9c3d55f238a99b357fbb.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-advanced-techniques-for-screen-recorders-in-video-games/"><u>[New] Advanced Techniques for Screen Recorders in Video Games</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-leveraging-instagram-stories-with-ease-and-flair/"><u>[Updated] 2024 Approved  Leveraging Instagram Stories with Ease and Flair</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-seamless-downloads-at-hand-the-best-5-chrome-extensions-for-fb-videos/"><u>[Updated] 2024 Approved  Seamless Downloads at Hand  The Best 5 Chrome Extensions for FB Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-unlocking-potential-expert-insights-into-hashtag-usage-on-facebook/"><u>[Updated] 2024 Approved  Unlocking Potential  Expert Insights Into Hashtag Usage on Facebook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevate-your-social-media-presence-with-personalized-instagram-icons-for-2024/"><u>[Updated] Elevate Your Social Media Presence with Personalized Instagram Icons for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-heartwarming-hits-this-seasons-ultimate-family-movies/"><u>[Updated] Heartwarming Hits  This Season's Ultimate Family Movies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-sharpen-your-videoleap-videos-from-afar/"><u>[Updated] In 2024, Sharpen Your Videoleap Videos From Afar</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-strategies-to-have-your-video-embrace-by-vimeo-experts/"><u>[Updated] Strategies to Have Your Video Embrace by Vimeo Experts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-complete-guide-mastering-final-cut-pro/"><u>2024 Approved  Complete Guide  Mastering Final Cut Pro</u></a></li>
<li><a href="https://techtrends.techidaily.com/android-meets-windows-11-a-guide-to-emulating-mobile-apps-on-desktop/"><u>Android Meets Windows 11: A Guide to Emulating Mobile Apps on Desktop</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-online-houses-purchasing-unique-tailored-boxed-gifts-for-2024/"><u>Best Online Houses  Purchasing Unique, Tailored Boxed Gifts for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/cross-compatibility-solutions-a-step-by-step-tutorial-for-running-android-games-and-apps-on-windows-11/"><u>Cross-Compatibility Solutions: A Step-by-Step Tutorial for Running Android Games and Apps on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-document-viewer-unveiling-the-secrets-of-google-docs-tracking/"><u>Discovering Document Viewer: Unveiling the Secrets of Google Docs Tracking</u></a></li>
<li><a href="https://techtrends.techidaily.com/dive-into-digital-reading-with-the-perfect-laptop-or-smartphone/"><u>Dive Into Digital Reading with the Perfect Laptop or Smartphone</u></a></li>
<li><a href="https://techtrends.techidaily.com/diy-guide-removing-line-defects-from-your-television-display/"><u>DIY Guide: Removing Line Defects From Your Television Display</u></a></li>
<li><a href="https://techtrends.techidaily.com/duet-videos-unveiled-a-beginners-path-to-engaging-with-songs-on-tiktok/"><u>Duet Videos Unveiled: A Beginner's Path to Engaging with Songs on TikTok</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortlessly-conceal-your-surroundings-a-guide-to-blurring-backgrounds-on-google-meet/"><u>Effortlessly Conceal Your Surroundings: A Guide to Blurring Backgrounds on Google Meet</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722856478933-enhancing-security-with-twitchs-dual-authentication-setup-and-usage-guide/"><u>Enhancing Security with Twitch's Dual Authentication: Setup and Usage Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-educational-technology-the-9-key-electronics-for-academic-success/"><u>Essential Educational Technology: The 9 Key Electronics for Academic Success</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-discs-to-streaming-understanding-netflixs-transition-from-dvd-rentals/"><u>From Discs to Streaming: Understanding Netflix's Transition From DVD Rentals</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-system-upgraded-with-free-qualcomm-atheros-ar938x-drivers-today/"><u>Get Your System Upgraded with Free Qualcomm Atheros AR938X Drivers Today</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-find-lost-iphone-7-plus-backup-files-on-windows-pc-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to find lost iPhone 7 Plus Backup files on Windows PC? | Stellar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-12-pro-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme 12 Pro 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-realme-11-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Realme 11 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-the-past-accelerated-access-to-archived-content/"><u>In 2024, Navigating the Past  Accelerated Access to Archived Content</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-lava-blaze-curve-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Lava Blaze Curve 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://extra-support.techidaily.com/instant-image-clarity-picart-background-cleansing-hacks-for-2024/"><u>Instant Image Clarity  PicArt Background Cleansing Hacks for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/logitech-webcam-mic-not-working-heres-how-to-restore-audio-functionality-successfully/"><u>Logitech Webcam Mic Not Working? Here's How to Restore Audio Functionality Successfully</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-conversations-a-guide-to-chatting-efficiently-with-mozilla-thunderbird/"><u>Mastering Conversations: A Guide to Chatting Efficiently with Mozilla Thunderbird</u></a></li>
<li><a href="https://techtrends.techidaily.com/quick-fixes-to-improve-low-volume-on-your-iphone-phone-calls/"><u>Quick Fixes to Improve Low Volume on Your iPhone Phone Calls</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-d3dx934dll-file-missing-a-step-by-step-guide/"><u>Resolving 'D3dx9_34.dll' File Missing: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/sonys-2024-unveilings-exclusive-updates-and-latest-gadgetry-insights/"><u>Sony's 2024 Unveilings: Exclusive Updates & Latest Gadgetry Insights</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-on-creating-captioned-videos-for-insta-stories/"><u>Step-by-Step Tutorial on Creating Captioned Videos for Insta Stories</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-on-creating-homemade-projector-screens/"><u>Step-by-Step Tutorial on Creating Homemade Projector Screens</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-maxs-hit-tv-programmes-our-picks-for-now/"><u>The Ultimate Guide to Max's Hit TV Programmes - Our Picks for Now</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-best-mobile-apps-tailored-for-high-school-students/"><u>The Ultimate List: Best Mobile Apps Tailored for High School Students</u></a></li>
<li><a href="https://extra-tips.techidaily.com/transform-your-imagination-into-reality-with-top-animation-software/"><u>Transform Your Imagination Into Reality with Top Animation Software</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-a-locked-or-deactivated-instagram-effective-solutions/"><u>Troubleshooting a Locked or Deactivated Instagram: Effective Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-noisy-hardware-steps-to-repair-an-overbearing-computer-fan/"><u>Troubleshooting Noisy Hardware: Steps to Repair an Overbearing Computer Fan</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722871238067-understanding-and-utilizing-the-windows-11-battery-analysis-tool-for-optimal-performance/"><u>Understanding and Utilizing the Windows 11 Battery Analysis Tool for Optimal Performance</u></a></li>
<li><a href="https://techtrends.techidaily.com/unpacking-the-new-features-at-apples-worldwide-developer-conference-2nd25/"><u>Unpacking the New Features at Apple's Worldwide Developer Conference 2nD25</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-essentials-of-microsofts-regular-software-updates-known-as-patch-tuesday/"><u>Unveiling The Essentials Of Microsoft's Regular Software Updates – Known As Patch Tuesday</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-most-recent-ipad-release-and-features/"><u>Unveiling the Most Recent iPad Release and Features</u></a></li>
<li><a href="https://techtrends.techidaily.com/usb-20-demystified-an-in-depth-look-at-transfer-rates-cord-types-and-plug-ins/"><u>USB 2.0 Demystified: An In-Depth Look at Transfer Rates, Cord Types & Plug-Ins</u></a></li>
<li><a href="https://techtrends.techidaily.com/whatsapp-vs-signal-comparing-messaging-app-features-and-privacy/"><u>WhatsApp vs Signal: Comparing Messaging App Features and Privacy</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->