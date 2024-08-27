---
title: "Mastering the Solution to Windows 'Error 0X80070570': Step-by-Step Fixes"
date: 2024-08-26T07:40:28.404Z
updated: 2024-08-27T07:40:28.404Z
categories:
  - BestProducts
description: "This Article Describes Mastering the Solution to Windows 'Error 0X80070570': Step-by-Step Fixes"
excerpt: "This Article Describes Mastering the Solution to Windows 'Error 0X80070570': Step-by-Step Fixes"
thumbnail: https://thmb.techidaily.com/d529ee3f9777395e3e6b4e63c228e25fbb4330a46358a8f92c3ef7608136a4ab.jpg
---

## Error Code 0X80004005 Explained: Tips and Solutions to Fix It Now
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

## How to Fix Error Code 0x80004005

 Follow these steps in the order presented to troubleshoot error code 0x80004005:

1. [Run the Windows Update troubleshooter](https://support.microsoft.com/help/4027322/windows-update-troubleshooter) . The error can happen when an automatic Windows Update fails, or when files downloaded by Windows Update are corrupted. On Windows 7 or later, the easiest[way to fix problems with Windows updates](https://www.lifewire.com/how-to-fix-problems-caused-by-windows-updates-2625775) is to run the built-in automatic troubleshooter.
2. Delete everything in the Windows Update download folder. If the automatic troubleshooter does not fix the problem, open Windows[File Explorer](https://www.lifewire.com/what-is-a-file-manager-4589189) and navigate to**C:\\Windows\\SoftwareDistribution** , for Windows 11 or**C:\\Windows\\SoftwareDistribution\\Download** for earlier Windows versions, then delete everything inside the folder.
3. [Run Windows Update](https://www.lifewire.com/how-to-check-for-install-windows-updates-2624596) . If the problem is related to Windows Update, you may have to finish downloading and installing updates. After running the troubleshooter and manually deleting the files in the Windows Update folder, run Windows Update again.
4. [Delete temporary files](https://www.lifewire.com/how-to-delete-temporary-files-in-windows-2624709) . In some cases, a corrupt temporary file can cause error 0x80004005\. Use the Windows Disk Cleanup tool or type**%temp%** in the Windows search bar to find the**Temp** folder and delete everything inside it.
5. [Disable Outlook mail notifications](https://www.lifewire.com/configure-outlook-email-notifications-1173647) . The error code can occur when[Microsoft Outlook](https://www.lifewire.com/microsoft-outlook-4164620) attempts to notify you of new messages. If disabling this feature fixes the problem, then try[starting Outlook in Safe Mode](https://www.lifewire.com/outlook-safe-mode-4164302) . If that works, a simple re-install might fix your problem.
6. [Disable Windows Defender](https://www.lifewire.com/turn-off-windows-defender-4165378) . In some cases,[antivirus](https://www.lifewire.com/what-is-antivirus-software-152947) software can detect a false positive in connection with the Microsoft Outlook app. If you experience error code 0x80004005 when using Microsoft Outlook, and disabling notifications did not help, turning off antivirus software may fix the problem. Also,[disable Norton Antivirus](https://www.lifewire.com/disable-norton-antivirus-4589389) and other third-party antivirus programs you use.  
 Disabling antivirus software leaves the system vulnerable to malware. Try different[free antivirus programs](https://www.lifewire.com/best-free-antivirus-software-4151895) to find one that doesn't conflict with the applications you use.
7. [Use a different unzip program](https://www.lifewire.com/free-unzip-programs-1356643) . If you see the error code when extracting or opening compressed files (like[.zip](https://www.lifewire.com/zip-file-2622675) or[.rar](https://www.lifewire.com/rar-file-2622216) files), use a different extraction tool.
8. Re-register jdscript.dll and vbscript.dll. If you still see error 0x80004005 after trying to unzip files with other extraction tools, then re-registering these two[dynamic link libraries](https://www.lifewire.com/what-is-a-dll-file-2625852) (DLLs) may help.  
[Open the Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) as an administrator, type**regsvr32 jscript.dll** , then press the**Enter** key. Then, type**regsvr32 vbscript.dll** and press**Enter** .
9. [Add a key to the Windows Registry](https://www.lifewire.com/how-to-add-change-delete-registry-keys-values-2625145) . If you suspect error 0x80004005 in conjunction with copying or moving files,[open the Windows Registry Editor](https://www.lifewire.com/how-to-open-registry-editor-2625150) and go to **HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** .  
   * On a[32-bit](https://www.lifewire.com/32-bit-64-bit-2624554) system, create a new**DWORD** [registry value](https://www.lifewire.com/what-is-a-registry-value-2626042) called**LocalAccountTokenFilterPolicy** .  
   * On a 64-bit system, create a**QWORD** registry value called**LocalAccountTokenFilterPolicy** .  
 In both cases, set the value to**numeric 1** (on), then select**OK** . After that,[restart the Windows PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see if the problem is fixed.  
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.
10. Contact support. If none of these fixes work, or if you don't want to make changes to the Windows Registry, contact customer support for your Windows PC. The manufacturer may have potential solutions.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/best-desktop-pcs-4045927)

 FAQ

* How do I fix error code ws-37398-0?  
 Error code ws-37398-0 is a PS5 error code that occurs during PlayStation network server outages. Because the error stems from PlayStation, there's nothing you can do to fix it. You must wait until the network outage resolves.
* How do I fix error code 4b538e50 2k21?  
 This error occurs in the games_NBA 2K21_ and_NBA 2K22_ . It usually means your game files are outdated, and there's a pending file download or patch. To fix it, check to see if your computer or console still has game files to download, and wait for the downloading process to complete.
* How do I fix a code 10 error in Windows?  
 To[fix code 10 errors](https://www.lifewire.com/how-to-fix-code-10-errors-2623181) , which indicate that Device Manager can't start a hardware device, first try restarting your computer. If you recently installed a device, try uninstalling and reinstalling its drivers, or see if there are driver updates to install. You can also try installing the latest Windows update.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<li><a href="https://extra-tips.techidaily.com/new-capturing-online-clarity-a-zoomers-guide/"><u>[New] Capturing Online Clarity  A Zoomer's Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-igtv-title-and-description-revision/"><u>[New] Mastering IGTV Title & Description Revision</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-screensnap-2023-the-new-standard-in-recording/"><u>[New] ScreenSnap 2023 – The New Standard in Recording</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-breaking-the-monotony-innovative-yt-playlist-shuffling/"><u>[Updated] 2024 Approved  Breaking the Monotony  Innovative YT Playlist Shuffling</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-crafting-unique-ps3-gameplay-presentations-with-screen-recordings-for-2024/"><u>[Updated] Crafting Unique PS3 Gameplay Presentations with Screen Recordings for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-pretending-playfulness-making-mocks-and-laughs/"><u>[Updated] Pretending Playfulness  Making Mocks and Laughs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-undisclosed-aspects-what-you-dont-notice-as-a-story-viewer/"><u>[Updated] The Undisclosed Aspects  What You Don’t Notice as a Story Viewer</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-navigating-through-facebooks-recent-content-policy-shifts/"><u>2024 Approved  Navigating Through Facebook's Recent Content Policy Shifts</u></a></li>
<li><a href="https://techtrends.techidaily.com/avoid-buying-extra-tools-learn-to-open-your-iphones-sim-by-yourself/"><u>Avoid Buying Extra Tools - Learn to Open Your iPhone's SIM by Yourself</u></a></li>
<li><a href="https://techtrends.techidaily.com/cable-or-streaming-a-comprehensive-guide-comparing-both-options/"><u>Cable or Streaming? A Comprehensive Guide Comparing Both Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-most-captivating-lgbt-cinema-on-netflix-in-july-2024/"><u>Discover the Most Captivating LGBT Cinema on Netflix in July 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/do-you-really-need-a-third-party-app-to-remove-programs-exploring-the-alternatives/"><u>Do You Really Need a Third-Party App to Remove Programs: Exploring the Alternatives</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-file-transfer-sending-images-and-texts-from-print-device-to-desktop/"><u>Effortless File Transfer: Sending Images and Texts From Print Device to Desktop</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/effortless-fusion-of-youtube-videos-with-flv-format/"><u>Effortless Fusion of YouTube Videos with FlV Format</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721424159980-emoji-eradicated-tweets-linus-unravelled-trojan-truth-and-ais-main-mishaps-with-chatgpt/"><u>Emoji Eradicated Tweets, Linus Unravelled, Trojan Truth, and AI's Main Mishaps with ChatGPT.</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-insights-on-lg-channels-a-comprehensive-guide/"><u>Essential Insights on LG Channels: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/expert-guide-to-leveraging-obs-in-android/"><u>Expert Guide to Leveraging OBS in Android</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/expert-insights-on-saving-smartphone-moments-for-2024/"><u>Expert Insights on Saving Smartphone Moments for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-picks-the-ultimate-list-of-10-tools-for-finding-an-ideal-apartment/"><u>Expert Picks: The Ultimate List of 10 Tools for Finding an Ideal Apartment</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-world-easier-unlocking-google-maps-live-view-features-and-benefits/"><u>Exploring the World Easier: Unlocking Google Maps Live View Features and Benefits</u></a></li>
<li><a href="https://techtrends.techidaily.com/fixing-not-found-error-for-d3dx9dll-in-windows-systems/"><u>Fixing 'Not Found' Error for D3DX9.dll in Windows Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-the-flaky-wi-fi-flow/"><u>Fixing the Flaky Wi-Fi Flow</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-eliminate-linear-stripes-appearing-horizontally-across-your-desktop-display/"><u>How to Eliminate Linear Stripes Appearing Horizontally Across Your Desktop Display</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-kernel32dll-errors/"><u>How to Fix Kernel32.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-vmware-bsod-error-on-windows-11/"><u>How to Fix VMware BSOD Error on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-restore-ringtones-and-fix-muted-phone-issues-on-iphone/"><u>How to Restore Ringtones and Fix Muted Phone Issues on iPhone</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-retrieve-old-website-versions-using-the-internet-archives-wayback-machine/"><u>How to Retrieve Old Website Versions Using the Internet Archive's Wayback Machine</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-transfer-and-play-ps4-titles-on-a-new-ps5-system/"><u>How To Transfer and Play PS4 Titles On A New PS5 System?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-bargain-hunters-paradise-unveiling-top-10-shopping-spots-for-boxes/"><u>In 2024, Bargain Hunters' Paradise  Unveiling Top 10 Shopping Spots for Boxes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xr-with-a-mask-on-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XR with a Mask On | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-methods-to-transfer-from-apple-iphone-6-to-android-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Methods to Transfer from Apple iPhone 6 to Android | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-navigating-copyright-regulations-before-you-upload-on-tiktok/"><u>In 2024, Navigating Copyright Regulations Before You Upload on TikTok</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-the-basics-of-electronic-story-craftsmanship/"><u>In 2024, The Basics of Electronic Story Craftsmanship</u></a></li>
<li><a href="https://fox-access.techidaily.com/instantaneous-media-movement-android-to-iphone/"><u>Instantaneous Media Movement  Android to iPhone</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-the-latest-iphone-15-pro-max-built-to-survive-underwater-find-out-here/"><u>Is The Latest iPhone 15 Pro Max Built to Survive Underwater? Find Out Here!</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-your-dolby-atmos-experience-authentic/"><u>Is Your Dolby Atmos Experience Authentic?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-your-android-for-windows-11-webcam-functionality/"><u>Leveraging Your Android for Windows 11 Webcam Functionality</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-microsoft-teams-with-ai-the-ultimate-guide-to-leveraging-copilot/"><u>Mastering Microsoft Teams with AI: The Ultimate Guide to Leveraging Copilot</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/maximizing-money-smart-tactics-for-video-monetization-for-2024/"><u>Maximizing Money  Smart Tactics for Video Monetization for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-lenovo-thinkphone-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Lenovo ThinkPhone – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-problems-with-your-gmail-sync-process/"><u>Overcoming Problems With Your Gmail Sync Process</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-guide-to-free-hp-auditory-device-drivers-effortless-download/"><u>Quick Guide to Free HP Auditory Device Drivers - Effortless Download</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-honor-70-lite-5g-by-fonelab-android-recover-data/"><u>Recover lost data from Honor 70 Lite 5G</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/shutting-off-the-latest-iphones-tips-and-tricks-for-model-15-pro-pro-max-edition/"><u>Shutting Off the Latest iPhones - Tips and Tricks for Model 15 Pro, Pro Max Edition</u></a></li>
<li><a href="https://techtrends.techidaily.com/solve-wi-fi-problems-on-your-ipad-with-these-simple-fixes/"><u>Solve Wi-Fi Problems on Your iPad with These Simple Fixes</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-your-wi-fi-connection-issues-a-step-by-step-guide-for-vizio-tvs/"><u>Solving Your Wi-Fi Connection Issues: A Step-by-Step Guide for Vizio TVs</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-how-to-delete-programs-on-a-mac-computers/"><u>Step-by-Step Tutorial: How to Delete Programs on a Mac Computers</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-how-to-uninstall-samsung-smart-tv-applications/"><u>Step-by-Step Tutorial: How to Uninstall Samsung Smart TV Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-complete-walkthrough-for-implementing-reminders-on-slack-platform/"><u>The Complete Walkthrough for Implementing Reminders on Slack Platform</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-greatest-advancements-in-technology-after-1844-a-countdown-of-11/"><u>The Greatest Advancements in Technology After 1844: A Countdown of 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-legacy-of-10-ancient-human-communications/"><u>The Legacy of 10 Ancient Human Communications</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-resolving-missing-pdhdll-error-messages-in-windows/"><u>The Ultimate Guide to Resolving Missing Pdh.dll Error Messages in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-selecting-the-ideal-projector-what-matters-most/"><u>The Ultimate Guide to Selecting the Ideal Projector - What Matters Most?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-se-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-rated-gaming-systems-in-2/"><u>Top-Rated Gaming Systems in 2</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshoot-and-repair-mfplatdll-not-detected-issues-with-ease/"><u>Troubleshoot and Repair 'mfplat.dll' Not Detected Issues with Ease</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-guide-correcting-ftd2xxdll-not-detected-problems/"><u>Troubleshooting Guide: Correcting Ftd2xx.dll Not Detected Problems</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-missing-d3dx934dll-expert-advice-for-a-smooth-resolution/"><u>Troubleshooting Missing d3dx9_34.dll: Expert Advice for a Smooth Resolution</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-for-when-xlivedll-cant-be-located-on-your-pc/"><u>Troubleshooting Steps for When xlive.dll Can’t Be Located on Your PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-the-jvmdll-file-solutions-to-missing-and-not-found-error-messages/"><u>Troubleshooting the JVM.dll File: Solutions to 'Missing' And 'Not Found' Error Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-setting-up-your-own-wireless-movie-experience-in-the-dorm/"><u>Ultimate Guide: Setting Up Your Own Wireless Movie Experience in the Dorm</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/ultimate-list-must-follow-igtv-creators/"><u>Ultimate List  Must-Follow IGTV Creators</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Realme 11 Pro+? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->