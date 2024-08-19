---
title: "Troubleshooting Windows 10: Fix the Uninstallable Error Code#80240020"
date: 2024-08-18T21:08:17.385Z
updated: 2024-08-19T21:08:17.385Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Windows 10: Fix the Uninstallable Error Code#80240020"
excerpt: "This Article Describes Troubleshooting Windows 10: Fix the Uninstallable Error Code#80240020"
thumbnail: https://thmb.techidaily.com/e4680a85088d1a2f44c589b1c74f41a831760d9eaf6ae422f8b959a2a9262d12.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-10-must-try-microphones-for-exceptional-asmr-sounds/"><u>[New] 2024 Approved  10 Must-Try Microphones for Exceptional ASMR Sounds</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-ensemble-dynamics-crafting-collaborative-content-for-musicians/"><u>[New] 2024 Approved  Ensemble Dynamics  Crafting Collaborative Content for Musicians</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-secret-story-spotters-top-5-app-recommendations/"><u>[New] 2024 Approved  Secret Story Spotters  Top 5 App Recommendations</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photographic-power-up-grid-software-of-the-decade/"><u>[New] Photographic Power-Up  Grid Software of the Decade</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-expressive-sketches-for-fortnite-icons/"><u>[Updated] 2024 Approved  Expressive Sketches for Fortnite Icons</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-art-of-creating-spherical-shots-with-fisheye-lenses/"><u>[Updated] 2024 Approved  The Art of Creating Spherical Shots with Fisheye Lenses</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-tips-to-counteract-obs-fullscreen-woes-for-2024/"><u>[Updated] Tips to Counteract OBS Fullscreen Woes for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-ways-to-watch-facebook-live-on-tv/"><u>[Updated] Ways To Watch Facebook Live On TV</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-on-apple-iphone-7-plus-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock On Apple iPhone 7 Plus? How to Fix it?</u></a></li>
<li><a href="https://techtrends.techidaily.com/battlenet-outage-or-local-network-error-identifying-common-issues-with-blizzard-services/"><u>Battle.net Outage or Local Network Error? Identifying Common Issues with Blizzard Services.</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-of-the-best-12-must-try-free-internet-phone-call-apps/"><u>Best of the Best: 12 Must-Try Free Internet Phone Call Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/celebrate-diversity-best-lgbt-movies-to-watch-on-netflix-in-jul-24/"><u>Celebrate Diversity: Best LGBT Movies to Watch on Netflix in Jul '24</u></a></li>
<li><a href="https://techtrends.techidaily.com/crafting-memorable-evenings-with-a-personalized-in-house-karaoke-event/"><u>Crafting Memorable Evenings with a Personalized In-House Karaoke Event</u></a></li>
<li><a href="https://techtrends.techidaily.com/fixing-not-found-issues-with-launchdll-for-windows-users/"><u>Fixing 'Not Found' Issues with Launch.dll for Windows Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-prepare-your-tv-and-audio-systems-for-an-unforgettable-super-bowl-experience-at-home/"><u>How to Prepare Your TV and Audio Systems for an Unforgettable Super Bowl Experience at Home</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-x-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone X Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-8-plus-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone 8 Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-synergistic-campaigns-brands-and-youtube-hand-in-hand/"><u>In 2024, Synergistic Campaigns  Brands & YouTube Hand in Hand</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-mac-a-comprehensive-guide-to-using-whatsapp/"><u>Mastering Mac: A Comprehensive Guide to Using WhatsApp</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigate-with-power-using-command-prompt-inside-file-explorer-sections/"><u>Navigate with Power: Using Command Prompt Inside File Explorer Sections</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-security-warnings-in-browsers-fixing-the-connection-is-not-secure-dilemma/"><u>Overcoming Security Warnings in Browsers - Fixing the ‘Connection Is Not Secure’ Dilemma</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-issues-with-your-wii-console-difficulties-in-reading-game-cds/"><u>Resolving Issues with Your Wii Console: Difficulties in Reading Game CDs</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-htc-u23-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from HTC U23</u></a></li>
<li><a href="https://techtrends.techidaily.com/sneak-peek-of-the-samsung-galaxy-z-fold-7-prospective-price-tag-release-date-and-specs-revealed-by-rumors/"><u>Sneak Peek of the Samsung Galaxy Z Fold 7: Prospective Price Tag, Release Date & Specs Revealed by Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-to-fix-libcurldll-errors-in-windows/"><u>Step-by-Step Guide to Fix libcurl.dll Errors in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-for-removing-your-shared-posts-on-tiktok-easily/"><u>Step-by-Step Instructions for Removing Your Shared Posts on TikTok Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-for-viewing-espn-plus-on-lg-smart-tvs/"><u>Step-by-Step Instructions for Viewing ESPN Plus on LG Smart TVs</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-for-overcoming-stop-0x0000007b-critical-process-died-bsod-glitches/"><u>Step-by-Step Solutions for Overcoming STOP 0X0000007B Critical Process Died BSOD Glitches</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/techniques-to-achieve-crystal-clear-youtube-soundtracks/"><u>Techniques to Achieve Crystal-Clear YouTube Soundtracks</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-insiders-secret-effortless-fire-stick-remote-pairing-techniques-unveiled/"><u>The Insider's Secret: Effortless Fire Stick Remote Pairing Techniques Unveiled</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-blank-screens-solutions-for-computers-that-boot-without-display/"><u>Troubleshooting Blank Screens: Solutions for Computers that Boot Without Display</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-iphones-a-comprehensive-walkthrough-for-using-recovery-mode/"><u>Troubleshooting iPhones: A Comprehensive Walkthrough for Using Recovery Mode</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/troubleshooting-quieted-facebook-streams-for-2024/"><u>Troubleshooting Quieted Facebook Streams for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-when-your-macos-app-wont-launch/"><u>Troubleshooting Steps When Your macOS App Won't Launch</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unclogging-saturation-issue-gpt-in-windows/"><u>Unclogging Saturation Issue: GPT in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-and-fixing-the-problem-when-yahoo-mail-doesnt-receive-messages/"><u>Understanding & Fixing the Problem When Yahoo Mail Doesn't Receive Messages</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-avi-video-editing-made-easy-top-trimming-tools-for-every-platform/"><u>Updated AVI Video Editing Made Easy Top Trimming Tools for Every Platform</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->