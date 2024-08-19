---
title: Steps To Combat Heavy Memory Usage on Windows 10 [Resolved]
date: 2024-08-18T21:07:38.783Z
updated: 2024-08-19T21:07:38.783Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Steps To Combat Heavy Memory Usage on Windows 10 [Resolved]
excerpt: This Article Describes Steps To Combat Heavy Memory Usage on Windows 10 [Resolved]
thumbnail: https://thmb.techidaily.com/15c27a9dd37e7d971ec6b1dda7daf6d5203783d6fa46bb3c8b563de8f86481fa.jpg
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-initiating-into-the-world-of-facebook-video-content-creation/"><u>[New] 2024 Approved  Initiating Into the World of Facebook Video Content Creation</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-streaming-obs-content-to-instagram/"><u>[New] 2024 Approved  Streaming OBS Content to Instagram</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-small-scale-startups-guide-to-trustworthy-video-tools-for-2024/"><u>[New] Small-Scale Startups' Guide to Trustworthy Video Tools for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-craft-viral-stories-on-fb-with-pro-tips/"><u>[Updated] Craft Viral Stories on FB with Pro Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-how-to-flawlessly-post-srt-files-in-multiple-social-environments/"><u>[Updated] How to Flawlessly Post SRT Files in Multiple Social Environments</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unveiling-the-blueprint-best-practices-for-social-media-video-publishing/"><u>[Updated] In 2024, Unveiling the Blueprint  Best Practices for Social Media Video Publishing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-video-twisting-techniques-boost-your-instagram-media-presentation/"><u>[Updated] In 2024, Video Twisting Techniques  Boost Your Instagram Media Presentation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-mac-capture-techniques-overview-char-limit-156-for-2024/"><u>[Updated] Top Mac Capture Techniques Overview (Char Limit  156) for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-add-fade-inout-premiere-pro/"><u>2024 Approved  How to Add Fade In/Out Premiere Pro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-luts-for-enhanced-photoshop-images/"><u>2024 Approved  Mastering LUTs for Enhanced Photoshop Images</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-future-of-laptops-with-apples-m1-max-attachments/"><u>2024 Approved  The Future of Laptops with Apple’s M1 Max Attachments</u></a></li>
<li><a href="https://techtrends.techidaily.com/academic-achievement-with-technology-uncovering-the-9-must-have-devices-and-gadgets-for-modern-education/"><u>Academic Achievement with Technology: Uncovering The 9 Must-Have Devices and Gadgets for Modern Education</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>Can I use iTools gpx file to catch the rare Pokemon On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-free-cad-tools-of-2023-our-picks/"><u>Discover the Best Free CAD Tools of 2023 – Our Picks!</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-connections-a-guide-to-effortlessly-search-people-on-facebook/"><u>Discovering Connections: A Guide to Effortlessly Search People on Facebook</u></a></li>
<li><a href="https://techtrends.techidaily.com/educational-concessions-on-the-microsoft-store-tips-for-enrollment/"><u>Educational Concessions on the Microsoft Store: Tips for Enrollment</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/effortless-animated-addition-how-to-send-and-share-gifs-on-snapchat/"><u>Effortless Animated Addition  How to Send and Share GIFs on Snapchat</u></a></li>
<li><a href="https://techtrends.techidaily.com/exclusive-selection-the-leading-docu-series-on-max-this-july-2024/"><u>Exclusive Selection: The Leading Docu-Series on Max This July 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722873186445-get-a-headstart-on-the-next-wave-comprehensive-guide-to-the-rumored-samsung-galaxy-s25-its-price-arrival-and-technical-innovations/"><u>Get a Headstart on the Next Wave: Comprehensive Guide to the Rumored Samsung Galaxy S25 - Its Price, Arrival & Technical Innovations!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/google-pixel-fold-music-recovery-recover-deleted-music-from-google-pixel-fold-by-fonelab-android-recover-music/"><u>Google Pixel Fold Music Recovery - Recover Deleted Music from Google Pixel Fold</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-overcome-netflix-streaming-problems-on-lg-tv-screens-with-19-techniques/"><u>How to Overcome Netflix Streaming Problems on LG TV Screens with 19 Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-youtube-manages-content-post-upload-for-2024/"><u>How YouTube Manages Content Post-Upload for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-lava-blaze-2-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Lava Blaze 2 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-samsung-galaxy-s23-fe-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Samsung Galaxy S23 FE Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-zte-axon-40-lite-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on ZTE Axon 40 Lite with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/inside-look-at-the-upcoming-google-pixel-tablet-official-launch-dates-and-comprehensive-specs-reviewed/"><u>Inside Look at the Upcoming Google Pixel Tablet: Official Launch Dates & Comprehensive Specs Reviewed</u></a></li>
<li><a href="https://techtrends.techidaily.com/inside-tips-on-making-a-reservation-at-the-genius-bar-in-any-apple-store/"><u>Inside Tips on Making a Reservation at the Genius Bar in Any Apple Store</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-gaming-powerhouse-showdown-discover-the-ideal-device-for-gamers/"><u>IPhone Gaming Powerhouse Showdown: Discover the Ideal Device for Gamers</u></a></li>
<li><a href="https://techtrends.techidaily.com/james-bond-cinematic-journey-a-comprehensive-guide-from-casino-royale-to-no-time-to-die/"><u>James Bond Cinematic Journey: A Comprehensive Guide From Casino Royale to No Time To Die</u></a></li>
<li><a href="https://techtrends.techidaily.com/join-samsung-unpacked-webcast-top-strategies-and-links/"><u>Join Samsung Unpacked Webcast: Top Strategies and Links</u></a></li>
<li><a href="https://techtrends.techidaily.com/new-to-twitch-clear-up-these-5-misconceptions-about-live-chatting/"><u>New to Twitch? Clear Up These 5 Misconceptions About Live Chatting</u></a></li>
<li><a href="https://techtrends.techidaily.com/revamp-windows-11-speed-diagnose-and-solve-common-causes-of-system-latency/"><u>Revamp Windows 11 Speed: Diagnose and Solve Common Causes of System Latency</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-removing-image-retention-from-your-monitor-or-tv/"><u>Step-by-Step Solutions: Removing Image Retention From Your Monitor or TV</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-future-on-wheels-teslas-autonomous-taxi-its-prospective-pricing-launch-details-uncovered/"><u>The Future on Wheels: Tesla's Autonomous Taxi, Its Prospective Pricing, Launch Details Uncovered</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-for-when-you-cant-locate-mingwm10dll-on-windows/"><u>The Ultimate Fix for When You Can't Locate Mingwm10.dll on Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-solution-for-coredll-disappeared-messages/"><u>The Ultimate Solution for 'Core.dll' Disappeared Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-when-your-iphone-doesnt-ring-easy-fixes-inside/"><u>Troubleshooting When Your iPhone Doesn't Ring – Easy Fixes Inside</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-integrating-high-speed-internet-into-your-home-cinema-experience/"><u>Ultimate Guide: Integrating High-Speed Internet Into Your Home Cinema Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-resolving-shell32dll-missing-and-not-detected-issues-on-your-computer/"><u>Ultimate Guide: Resolving 'Shell32.dll Missing' And 'Not Detected' Issues on Your Computer</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unpacking-the-features-of-jacos-smartpro-digital-tire-inflator-compact-high-power-tool-overview/"><u>Unpacking the Features of Jaco's SmartPro Digital Tire Inflator: Compact, High-Power Tool Overview</u></a></li>
<li><a href="https://techtrends.techidaily.com/virtual-attendees-blueprint-how-to-join-and-watch-samsungs-tech-reveals-online/"><u>Virtual Attendee's Blueprint: How to Join and Watch Samsung's Tech Reveals Online</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->