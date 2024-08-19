---
title: "Troubleshooting Windows 11 Install Failures: Expert Tips and Tricks"
date: 2024-08-18T21:08:18.310Z
updated: 2024-08-19T21:08:18.310Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Windows 11 Install Failures: Expert Tips and Tricks"
excerpt: "This Article Describes Troubleshooting Windows 11 Install Failures: Expert Tips and Tricks"
thumbnail: https://thmb.techidaily.com/3a3db1628b8f2814d2040ecfe00634d164ea4b5f3058a85b825026993cb96502.jpg
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
<li><a href="https://fox-hovers.techidaily.com/new-baffled-by-blank-screens-on-a6400/"><u>[New] Baffled by Blank Screens on A6400</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/he-new-earnings-threshold-youtubes-500-rule/"><u>[New] The New Earnings Threshold  YouTube's $500 Rule</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-best-quick-fixes-top-5-no-download-online-gif-to-video-convertors/"><u>[Updated] 2024 Approved  Best Quick Fixes  Top 5 No-Download, Online GIF to Video Convertors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-5-gaming-earbuds-for-video-creators/"><u>[Updated] 2024 Approved  Essential 5 Gaming Earbuds for Video Creators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-enjoy-games-not-glitches-use-nvidia-for-2024/"><u>[Updated] Enjoy Games, Not Glitches - Use NVIDIA for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-advanced-techniques-for-live-action-sims-playback/"><u>[Updated] In 2024, Advanced Techniques for Live-Action Sims Playback</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-video-traffic-triumph-key-youtube-seo-tools/"><u>[Updated] In 2024, Video Traffic Triumph - Key YouTube SEO Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leading-open-source-20-best-pubg-images/"><u>[Updated] Leading Open Source  20 Best PUBG Images</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-master-tips-securing-audio-for-unboxing-vids/"><u>[Updated] Master Tips  Securing Audio for Unboxing Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-the-world-of-iphone-hdr-a-beginners-guide/"><u>[Updated] Navigating the World of iPhone HDR  A Beginner's Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-disconnect-on-snapchat-are-they-blocked-in-2024/"><u>[Updated] The Disconnect on Snapchat  Are They Blocked, In 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unlock-xps-movie-magic-software-essentials/"><u>[Updated] Unlock XP's Movie Magic Software Essentials</u></a></li>
<li><a href="https://facebook.techidaily.com/2022s-worst-of-the-tech-world-exposed/"><u>2022'S Worst of the Tech World Exposed</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-close-up-views-on-web-conferencing/"><u>2024 Approved  Mastering Close-Up Views on Web Conferencing</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-infinix-note-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-itel-a70-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Itel A70 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-beginners-guide-to-mastering-photo-cutout-in-apples-latest-ios-update-tips-and-tricks/"><u>A Beginner's Guide to Mastering Photo Cutout in Apple's Latest iOS Update: Tips and Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-comprehensive-checklist-for-purchasing-a-tech-device-for-education-needs/"><u>A Comprehensive Checklist for Purchasing a Tech Device for Education Needs</u></a></li>
<li><a href="https://techtrends.techidaily.com/affordable-music-streaming-on-a-budget-securing-spotifys-educational-offer/"><u>Affordable Music Streaming on a Budget: Securing Spotify's Educational Offer</u></a></li>
<li><a href="https://techtrends.techidaily.com/audio-evolution-contrasting-home-theater-receivers-with-traditional-stereo-units/"><u>Audio Evolution: Contrasting Home Theater Receivers with Traditional Stereo Units</u></a></li>
<li><a href="https://techtrends.techidaily.com/beginners-handbook-to-registering-a-meta-oculus-quest-or-quest-2-id/"><u>Beginner's Handbook to Registering a Meta (Oculus) Quest or Quest 2 ID</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-engagement-a-comprehensive-guide-to-embedding-annotations-on-ig-stories/"><u>Boost Engagement: A Comprehensive Guide to Embedding Annotations on IG Stories</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-infinix-hot-40i-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Infinix Hot 40i</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-repairing-jvmdll-is-missing-or-corrupt-issues/"><u>Comprehensive Guide: Repairing 'JVM.DLL Is Missing or Corrupt' Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-uninstalling-pre-installed-windows-backup-zone/"><u>Comprehensive Guide: Uninstalling Pre-Installed Windows Backup Zone</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-insights-into-the-world-of-netflix-digital-streaming/"><u>Comprehensive Insights Into the World of Netflix Digital Streaming</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-5-apple-watch-apps-to-optimize-your-nightly-zzzs/"><u>Discover the Ultimate 5 Apple Watch Apps to Optimize Your Nightly Zzz's</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-list-where-to-watch-films-without-payment/"><u>Discover the Ultimate List: Where to Watch Films Without Payment</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails/"><u>Elevate Your Digital Footprint  Crafting Compelling Shorts Thumbnails</u></a></li>
<li><a href="https://techtrends.techidaily.com/elevate-your-inbox-the-top-8-non-gmail-email-providers/"><u>Elevate Your Inbox: The Top 8 Non-Gmail Email Providers</u></a></li>
<li><a href="https://techtrends.techidaily.com/eliminate-ai-assistance-uninstalling-copilot-from-windows-11-easily/"><u>Eliminate AI Assistance: Uninstalling Copilot From Windows 11 Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-features-and-history-of-google-hangouts/"><u>Exploring the Features and History of Google Hangouts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/filmora-guide-efficiently-convert-avi-files-to-gifs-on-both-operating-systems/"><u>Filmora Guide  Efficiently Convert AVI Files to GIFs on Both Operating Systems</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-asus-rog-phone-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/going-digital-in-the-theatre-of-your-household-a-guide-on-internet-integration-and-usage/"><u>Going Digital in the Theatre of Your Household: A Guide on Internet Integration and Usage</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-sharing-your-gaming-adventures-with-friends-on-the-ps5/"><u>Guide: Sharing Your Gaming Adventures with Friends on the PS5</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-do-i-replace-a-broken-or-missing-key-on-my-laptops-keyboard/"><u>How Do I Replace a Broken or Missing Key on My Laptop's Keyboard?</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-activate-siris-read-aloud-capability-for-ios-and-macos-systems/"><u>How To Activate Siri's Read Aloud Capability for iOS and macOS Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-power-down-the-latest-ios-devices-iphone-1eby-and-pro-max-tips/"><u>How to Power Down the Latest iOS Devices: IPhone 1Eby and Pro Max Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-rectify-missing-d3d941dll-error-messages-on-your-pc/"><u>How to Rectify Missing D3d9_41.dll Error Messages on Your PC?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-12-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock iPhone 12 Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-vivo-y36-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-vivo-s18-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Vivo S18 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-everything-from-apple-iphone-6-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Everything from Apple iPhone 6 to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-security-hacked-how-to-get-into-your-locked-device-without-a-pin/"><u>IPhone Security Hacked: How to Get Into Your Locked Device Without a PIN</u></a></li>
<li><a href="https://techtrends.techidaily.com/mac-users-rejoice-mastering-whatsapp-communication-in-macos-environment/"><u>Mac Users Rejoice! Mastering WhatsApp Communication in macOS Environment</u></a></li>
<li><a href="https://techtrends.techidaily.com/macos-terminal-tricks-for-accessing-concealed-files-easily/"><u>MacOS Terminal Tricks for Accessing Concealed Files Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-casting-technology-connect-your-device-to-an-lg-smart-tv/"><u>Mastering Casting Technology: Connect Your Device to an LG Smart TV</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-citations-how-to-credit-chatgpt-in-academic-writing/"><u>Mastering Citations: How to Credit ChatGPT in Academic Writing</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/mastering-visual-storytelling-captioning-for-tiktok-videos/"><u>Mastering Visual Storytelling  Captioning for TikTok Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-the-differences-of-secure-messaging-apps-signal-vs-whatsapp-breakdown/"><u>Navigating the Differences of Secure Messaging Apps: Signal Vs. WhatsApp Breakdown</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-your-mobile-journey-is-an-iphone-or-android-device-right-for-you/"><u>Navigating Your Mobile Journey: Is An iPhone Or Android Device Right For You?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/practical-tips-for-console-game-recordings/"><u>Practical Tips for Console Game Recordings</u></a></li>
<li><a href="https://data-wizards.techidaily.com/seamless-social-experience-across-facebook-linkedin-and-youtube/"><u>Seamless Social Experience Across Facebook, LinkedIn and YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/secure-your-email-with-ease-activating-gmail-2fa/"><u>Secure Your Email with Ease: Activating Gmail 2FA</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-to-fixing-the-broken-voice-chat-on-valorant/"><u>Step-by-Step Guide to Fixing the Broken Voice Chat on Valorant</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-hardware-new-drivers-aoc-e1659fwu/"><u>Streamline Hardware: New Drivers - AOC E1659FWU</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-insiders-scoop-on-how-telegram-has-revolutionized-digital-communication/"><u>The Insider's Scoop on How Telegram Has Revolutionized Digital Communication</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-5-best-no-cost-global-voice-communication-platforms/"><u>Top 5 Best No-Cost Global Voice Communication Platforms</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-resolving-ietfmuidll-mistakes-effectively/"><u>Ultimate Guide: Resolving ietfmui.dll Mistakes Effectively</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-step-by-step-instructions-for-deleting-your-tiktok-profile/"><u>Ultimate Guide: Step-by-Step Instructions for Deleting Your TikTok Profile</u></a></li>
<li><a href="https://techtrends.techidaily.com/uncover-the-reason-behind-your-iphone-not-producing-sound-and-fix-it-now/"><u>Uncover the Reason Behind Your iPhone Not Producing Sound & Fix It Now</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->