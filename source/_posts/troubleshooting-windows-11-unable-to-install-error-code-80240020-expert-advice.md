---
title: Troubleshooting Windows 11 Unable to Install Error (Code 80240020) – Expert Advice
date: 2024-08-18T21:05:44.197Z
updated: 2024-08-19T21:05:44.198Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Troubleshooting Windows 11 Unable to Install Error (Code 80240020) – Expert Advice
excerpt: This Article Describes Troubleshooting Windows 11 Unable to Install Error (Code 80240020) – Expert Advice
thumbnail: https://thmb.techidaily.com/ed631fce79a85bf0cd5e756384d355b32be9ff521aba55cfa7af4917eeac790c.jpg
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hourly-high-stakes-views-yts-1-to-10-rankings/"><u>[New] 2024 Approved  Hourly High-Stakes Views  YT's #1 to #10 Rankings</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-perfecting-sound-capture-reviewed-mac-compatible-recorders/"><u>[New] 2024 Approved  Perfecting Sound Capture  Reviewed Mac-Compatible Recorders</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-tech-insightfulness-a-global-experts-assessment/"><u>[New] 2024 Approved  Tech Insightfulness  A Global Experts' Assessment</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-borrow-without-cost-images-from-leading-youtubers-archives-for-2024/"><u>[New] Borrow Without Cost Images From Leading YouTubers' Archives for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-freeweb-cams-features-uncovered-in-detail-for-2024/"><u>[New] FreeWeb Cam's Features Uncovered in Detail for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-rapid-recovery-of-elusive-memories/"><u>[Updated] In 2024, Rapid Recovery of Elusive Memories</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unlocking-user-preferences-with-instagrams-real-time-feedback-for-2024/"><u>[Updated] Unlocking User Preferences with Instagram's Real-Time Feedback for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigate-with-precision-the-complete-guide-to-idevice-podcast-downloads/"><u>2024 Approved  Navigate with Precision  The Complete Guide to iDevice Podcast Downloads</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-full-scope-on-netflix-your-go-to-source-for-understanding-the-modern-tv-service/"><u>A Full Scope on Netflix - Your Go-To Source for Understanding the Modern TV Service</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-guide-to-choosing-an-ipad-with-native-global-positioning-service/"><u>A Guide to Choosing an iPad with Native Global Positioning Service</u></a></li>
<li><a href="https://techtrends.techidaily.com/all-about-meta-quest-3-upcoming-features-cost-breakdown-and-release-timeline/"><u>All About Meta Quest 3: Upcoming Features, Cost Breakdown & Release Timeline</u></a></li>
<li><a href="https://extra-hints.techidaily.com/camera-shake-in-photographyvideo-what-you-need-to-know/"><u>Camera Shake In Photography/Video | What You Need to Know</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/cinematic-converter-turn-humble-footage-into-breathtaking-films/"><u>Cinematic Converter Turn Humble Footage Into Breathtaking Films</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-solutions-to-resolve-directxdirectinputdll-problems-on-windows-pcs/"><u>Comprehensive Solutions to Resolve directx.directinput.dll Problems on Windows PCs</u></a></li>
<li><a href="https://article-tips.techidaily.com/conquering-peaks-and-valleys-comparing-the-mightiest-gopros-b-and-sessions-for-2024/"><u>Conquering Peaks and Valleys  Comparing the Mightiest GoPros, B & Sessions for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-tags-a-complete-explanation-on-how-and-why-we-label-thingspeople/"><u>Demystifying Tags – A Complete Explanation on How and Why We Label Things/People</u></a></li>
<li><a href="https://techtrends.techidaily.com/diy-tech-support-overcoming-the-frequent-hurdles-with-your-tv/"><u>DIY Tech Support: Overcoming the Frequent Hurdles with Your TV</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-solutions-for-when-you-cant-locate-opengl32dll-file/"><u>Effective Solutions for When You Can't Locate OpenGL32.dll File</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-your-productivity-on-facebook-with-these-5-simple-strategies/"><u>Enhance Your Productivity on Facebook with These 5 Simple Strategies</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-no-cost-drives-test-suites-expert-picks-for-q3-2024/"><u>Essential No-Cost Drives Test Suites: Expert Picks for Q3 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-top-10-alternatives-to-chatgpt-that-will-amaze-you/"><u>Exploring the Top 10 Alternatives to ChatGPT That Will Amaze You</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-problems-with-non-responsive-amd-radeon-software-application/"><u>Fixing Problems with Non-Responsive AMD Radeon Software Application</u></a></li>
<li><a href="https://techtrends.techidaily.com/freshly-updated-d-link-default-passwords-for-enhanced-security-july-2024/"><u>Freshly Updated D-Link Default Passwords for Enhanced Security (July 2024)</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-to-turning-off-wireless-emergency-alerts-wea-for-amber-on-andriod-phones/"><u>Guide to Turning Off Wireless Emergency Alerts (WEA) for AMBER on Andriod Phones</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-nokia-c22-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Nokia C22 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-comment-with-gifs-on-instagram/"><u>How to Comment With GIFs on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-get-started-with-fandango-on-amazons-firestick-a-comprehensive-tutorial/"><u>How to Get Started with Fandango on Amazon's Firestick: A Comprehensive Tutorial</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-implement-2fa-two-factor-authentication-in-google-mail-for-robust-protection/"><u>How to Implement 2FA (Two-Factor Authentication) in Google Mail for Robust Protection</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-xiaomi-redmi-note-12-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Xiaomi Redmi Note 12 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-xiaomi-13t-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Xiaomi 13T phone? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-x50iplus-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor X50i+ to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XS, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-ultimate-guide-to-music-copyright-etiquette-on-ig/"><u>In 2024, The Ultimate Guide to Music Copyright Etiquette on IG</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-apple-iphone-8-plus-without-passcode-easily-drfone-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 8 Plus Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/incorporating-pinterest-into-facebook-enhance-visual-appeal-and-traffic/"><u>Incorporating Pinterest Into Facebook: Enhance Visual Appeal and Traffic</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-art-of-dealing-with-pc-rebooting-problems-effective-strategies/"><u>Master the Art of Dealing with PC Rebooting Problems: Effective Strategies</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-nintendos-game-boy-advance-classics-on-your-idevice/"><u>Mastering Nintendo's Game Boy Advance Classics on Your iDevice</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-twitter-chats-successfully-with-these-4-key-tools-to-track-hashtags/"><u>Navigating Twitter Chats Successfully with These 4 Key Tools to Track Hashtags</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-most-chromebook-owners-will-find-themselves-wondering-which-online-video-editor-is-the-best-one-lets-have-a-look-at-some-of-the-best-online-video-editor/"><u>New Most Chromebook Owners Will Find Themselves Wondering, Which Online Video Editor Is the Best One. Lets Have a Look at some of the Best Online Video Editors that Will Help You Create Visually Engaging</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-pcs-blue-screen-of-death-effective-repair-strategies-revealed/"><u>Overcoming PC's Blue Screen of Death: Effective Repair Strategies Revealed</u></a></li>
<li><a href="https://techtrends.techidaily.com/quick-fixes-and-tips-to-overcome-the-notorious-netflix-error-1-19-nw/"><u>Quick Fixes and Tips to Overcome the Notorious Netflix Error 1-19 (NW)</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-the-missing-libxml2dll-file-a-comprehensive-guide/"><u>Resolving the Missing libxml2.dll File: A Comprehensive Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/should-you-buy-into-minecraft-realms-an-seo-insight-into-its-true-worth/"><u>Should You Buy Into Minecraft Realms? An SEO Insight Into Its True Worth</u></a></li>
<li><a href="https://techtrends.techidaily.com/sonys-roadmap-to-innovation-key-releases-news-highlights-and-expert-analysis/"><u>Sony's Roadmap to Innovation – Key Releases, News Highlights, and Expert Analysis</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-capturing-your-playstation-4-gaming-sessions/"><u>Step-by-Step Guide: Capturing Your PlayStation 4 Gaming Sessions</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-mastering-the-setup-of-your-smart-device-with-any-universal-remote/"><u>Step-by-Step Guide: Mastering the Setup of Your Smart Device with Any Universal Remote</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-resolving-shelldll-missing-files-issues-effectively/"><u>Step-by-Step Guide: Resolving Shell.DLL Missing Files Issues Effectively</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-restoring-wi-fi-access-for-surface-booktablet-users/"><u>Step-by-Step Guide: Restoring Wi-Fi Access for Surface Book/Tablet Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-starting-your-macbook-pro-from-scratch/"><u>Step-by-Step Guide: Starting Your MacBook Pro From Scratch</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-for-fixing-problems-with-uploading-instagram-stories/"><u>Step-by-Step Solutions for Fixing Problems with Uploading Instagram Stories</u></a></li>
<li><a href="https://some-skills.techidaily.com/swift-upload-of-sizeable-videos-from-iphone-to-mac-desktop-for-2024/"><u>Swift Upload of Sizeable Videos From iPhone to Mac Desktop for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-level-of-gaming-sony-vr-headset-info-release-date-speculations-cost-predictions-technical-breakdown-and-hidden-rumors/"><u>The Next Level of Gaming: Sony VR Headset Info- Release Date Speculations, Cost Predictions, Technical Breakdown & Hidden Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-how-to-configuring-your-universal-remote-with-simple-steps/"><u>The Ultimate How-To: Configuring Your Universal Remote with Simple Steps</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-of-5-social-networking-apps-to-enhance-your-friends-collection/"><u>The Ultimate List of 5 Social Networking Apps to Enhance Your Friends Collection</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-selection-smart-glasses/"><u>The Ultimate Selection: Smart Glasses</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-funny-apple-device-prank-ideas-for-your-buddies/"><u>Top 10 Funny Apple Device Prank Ideas for Your Buddies</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-15-free-window-11-theme-packs-download-options/"><u>Top 15 FREE Window 11 Theme Packs: Download Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-techniques-to-resolve-frequent-televison-issues-effectively/"><u>Top Techniques to Resolve Frequent Televison Issues Effectively</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-tips-for-leveraging-copilot-within-your-microsoft-teams-experience/"><u>Ultimate Tips for Leveraging Copilot Within Your Microsoft Teams Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-and-fixing-xlive-dll-file-not-found-issues-easily/"><u>Understanding and Fixing XLive DLL File Not Found Issues Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-the-difference-do-tweets-get-shared-as-retweets-or-re-tweets/"><u>Understanding the Difference: Do Tweets Get Shared as 'Retweets' Or 'Re-Tweets'?</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Vivo X Flip | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->