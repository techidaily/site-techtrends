---
title: "DirectX 12 Installation on Windows 11: A Step-by-Step Tutorial"
date: 2024-08-18T21:08:31.252Z
updated: 2024-08-19T21:08:31.252Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes DirectX 12 Installation on Windows 11: A Step-by-Step Tutorial"
excerpt: "This Article Describes DirectX 12 Installation on Windows 11: A Step-by-Step Tutorial"
thumbnail: https://thmb.techidaily.com/e0dd15b42e7cb5414bdb7af5c281fcfdfef62e342cd4798dfe7202dea8939dfe.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-chronicles-of-triumph-ranking-the-ultimate-game-odysseys/"><u>[New] 2024 Approved  Chronicles of Triumph  Ranking the Ultimate Game Odysseys</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-conquer-video-production-obs-studio-and-android/"><u>[New] 2024 Approved  Conquer Video Production  OBS Studio and Android</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-paying-creator-status-on-youtube/"><u>[New] 2024 Approved  High-Paying Creator Status on YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-cutting-edge-strategies-to-minimize-vids-for-instagram-on-macos-for-2024/"><u>[New] Cutting-Edge Strategies to Minimize Vids for Instagram on macOS for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-your-channel-with-these-top-11-budget-friendly-tools/"><u>[New] Elevate Your Channel with These Top 11 Budget-Friendly Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-downloadable-instagram-footage-tech-tips-for-computers-and-macs/"><u>[New] In 2024, Downloadable Instagram Footage  Tech Tips for Computers & Macs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-essential-tips-building-an-instagram-money-machine/"><u>[New] In 2024, Essential Tips  Building an Instagram Money Machine</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-8-windows-podcast-solutions/"><u>[New] Optimal 8-Windows Podcast Solutions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-team-videography-methods-for-channel-expansion/"><u>[New] Team Videography Methods for Channel Expansion</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-expertly-selected-best-9-video-conference-apps-for-cross-platform-use/"><u>[Updated] 2024 Approved  Expertly Selected Best 9 Video Conference Apps for Cross-Platform Use</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-chorus-and-content-music-magic-on-social-media-stories/"><u>[Updated] Chorus & Content  Music Magic on Social Media Stories</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-step-by-step-end-screen-customization-guide-for-vimeo/"><u>[Updated] In 2024, Step-by-Step End Screen Customization Guide for Vimeo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-ultimate-guide-to-instagram-influence-5-strategies-with-examples/"><u>[Updated] The Ultimate Guide to Instagram Influence  5 Strategies with Examples</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-inside-the-innovative-world-of-kinemaster-your-android-game-companion/"><u>2024 Approved  Inside the Innovative World of KineMaster - Your Android Game Companion</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-luminous-filmmaking-transform-your-videos-with-pro-tips/"><u>2024 Approved  Luminous Filmmaking  Transform Your Videos with Pro Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/beat-the-missing-rockalldlldll-file-proven-strategies-and-solutions/"><u>Beat the 'Missing rockalldll.dll File': Proven Strategies and Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/breaking-down-cellular-networks-what-exactly-is-a-phone-carrier/"><u>Breaking Down Cellular Networks: What Exactly Is a Phone Carrier?</u></a></li>
<li><a href="https://techtrends.techidaily.com/buying-guide-how-to-find-the-best-television-model-for-optimal-viewing-comfort-at-home/"><u>Buying Guide: How to Find the Best Television Model for Optimal Viewing Comfort at Home</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-linksys-default-passwords-update-july-2024-edition/"><u>Comprehensive Guide: Linksys Default Passwords Update - July 2024 Edition</u></a></li>
<li><a href="https://techtrends.techidaily.com/connect-and-create-friendships-easily-using-these-5-revolutionary-apps/"><u>Connect and Create Friendships Easily Using These 5 Revolutionary Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722848191270-conquering-remote-recruitment-a-comprehensive-list-of-the-9-most-effective-skype-interview-techniques/"><u>Conquering Remote Recruitment: A Comprehensive List of the 9 Most Effective Skype Interview Techniques</u></a></li>
<li><a href="https://media-tips.techidaily.com/convert-mp4-videos-into-editable-gifs-top-free-online-tools/"><u>Convert MP4 Videos Into Editable GIFs: Top Free Online Tools</u></a></li>
<li><a href="https://techtrends.techidaily.com/creating-professional-looking-text-with-line-formatting-in-microsoft-word/"><u>Creating Professional-Looking Text with Line Formatting in Microsoft Word</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-correcting-horizontal-streaks-in-monitor-images/"><u>Diagnosing and Correcting Horizontal Streaks in Monitor Images</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-selection-of-free-hdd-testers-as-of-july-2024/"><u>Discover the Ultimate Selection of Free HDD Testers as of July 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-guide-restoring-audio-in-non-responsive-stereo-receivers/"><u>Easy Guide: Restoring Audio in Non-Responsive Stereo Receivers</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-viewing-experience-with-the-ideal-image-settings-on-samsung-4k-models/"><u>Enhance Viewing Experience with the Ideal Image Settings on Samsung 4K Models</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-factors-in-picking-the-right-phone-guard-expert-advice/"><u>Essential Factors in Picking the Right Phone Guard: Expert Advice</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-freebies-the-ultimate-list-of-11-software-updater-programs-for-everyone/"><u>Essential Freebies: The Ultimate List of 11 Software Updater Programs for Everyone</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-for-restoring-windows-10-search-capability-get-started-now/"><u>Expert Tips for Restoring Windows 10 Search Capability – Get Started Now</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-on-how-to-restore-your-lenovo-computer-to-its-original-settings/"><u>Expert Tips on How to Restore Your Lenovo Computer to Its Original Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-versatile-applications-top-10-ways-to-use-powertoys/"><u>Explore Versatile Applications: Top 10 Ways to Use PowerToys</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-vivo-g2-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Vivo G2 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-restore-functionality-to-dvd-blu-ray-and-cd-drives-that-wont-open/"><u>How To Restore Functionality to DVD, Blu-Ray & CD Drives That Won't Open</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-honor-magic-5-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-wirelessly-connect-and-use-your-ps4s-control-gadget/"><u>How to Wirelessly Connect and Use Your PS4's Control Gadget</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-xiaomi-14-ultra-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Xiaomi 14 Ultra</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-apple-iphone-8-plus-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 8 Plus Without Passcode Easily</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/in-depth-review-fugetek-ft-568-exceptional-quality-for-a-superior-selfie-experience/"><u>In-Depth Review: Fugetek FT-568 - Exceptional Quality for a Superior Selfie Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/introducing-apples-newest-macbook-a-look-at-the-latest-upgrade/"><u>Introducing Apple's Newest MacBook: A Look at the Latest Upgrade</u></a></li>
<li><a href="https://techtrends.techidaily.com/ipad-bargains-and-discounts-find-the-perfect-offer-today/"><u>IPad Bargains & Discounts - Find the Perfect Offer Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-macbook-heat-top-tips-for-monitoring-your-laptops-temperature/"><u>Mastering MacBook Heat: Top Tips for Monitoring Your Laptop's Temperature</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-the-command-prompt-inside-windows-explorer-a-tutorial/"><u>Navigating the Command Prompt Inside Windows Explorer – A Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/persistent-file-placement-on-windows-10-understanding-how-your-files-stay-put-between-boots/"><u>Persistent File Placement on Windows 10: Understanding How Your Files Stay Put Between Boots</u></a></li>
<li><a href="https://extra-resources.techidaily.com/sky-cameras-rivalry-dji-m310-vs-gopro-hero5-session/"><u>Sky Cameras Rivalry  DJI M310 VS GoPro HERO5 Session</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-adjusting-your-kindle-paperwhites-display-time/"><u>Step-by-Step Guide: Adjusting Your Kindle Paperwhite's Display Time</u></a></li>
<li><a href="https://techtrends.techidaily.com/syncing-success-easily-navigate-icloud-photos-on-apple-windows-and-android/"><u>Syncing Success: Easily Navigate iCloud Photos on Apple, Windows & Android</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-complete-fix-for-when-you-cant-locate-d3dx933dll-on-windows-pcs/"><u>The Complete Fix for When You Can't Locate d3dx9_33.dll on Windows PCs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-evolution-of-ai-assessment-beyond-turing-here-are-5-innovations/"><u>The Evolution of AI Assessment: Beyond Turing, Here Are 5 Innovations</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-premier-selection-of-cable-modemrouter-hybrids-in-2e24/"><u>The Premier Selection of Cable-Modem/Router Hybrids in 2E24</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-for-when-wmvcoredll-is-not-found-or-missing/"><u>The Ultimate Fix for When Wmvcore.dll Is Not Found or Missing</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-selection-7-excellent-alarm-apps-you-should-try/"><u>The Ultimate Selection: 7 Excellent Alarm Apps You Should Try</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-oneplus-nord-ce-3-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your OnePlus Nord CE 3 5G Phone</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-titles-only-available-on-playstation-5-your-complete-guide/"><u>Top Titles Only Available on PlayStation 5: Your Complete Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/toshiba-bluetooth-drivers-free-download-for-seamless-connectivity/"><u>Toshiba Bluetooth Drivers - Free Download for Seamless Connectivity</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshoot-and-enhance-your-windows-eb-experience-get-the-latest-usb-c-driver-downloads-here/"><u>Troubleshoot & Enhance Your Windows Eb Experience – Get the Latest USB-C Driver Downloads Here</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-bass-quakes-how-to-stop-subwoofer-rumbling-noises-completely/"><u>Troubleshooting Bass Quakes: How to Stop Subwoofer Rumbling Noises Completely</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-whea-unrecoverable-mistakes-in-your-system/"><u>Troubleshooting WHEA Unrecoverable Mistakes in Your System</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-your-ps5-dualsense-steps-to-resolve-charging-issues/"><u>Troubleshooting Your PS5 DualSense: Steps To Resolve Charging Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-how-to-resolve-the-mapp32dll-not-found-issue/"><u>Troubleshooting: How to Resolve the 'mapp32.dll Not Found' Issue</u></a></li>
<li><a href="https://techtrends.techidaily.com/turning-off-voice-assistant-feature-in-your-samsung-television-setup/"><u>Turning Off Voice Assistant Feature in Your Samsung Television Setup</u></a></li>
<li><a href="https://techtrends.techidaily.com/tutorial-streaming-online-content-on-your-smart-tv-setup/"><u>Tutorial: Streaming Online Content on Your Smart TV Setup</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-steps-to-successfully-update-and-install-the-latest-ios-version/"><u>Ultimate Guide: Steps to Successfully Update & Install the Latest iOS Version</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/universal-unlock-pattern-for-motorola-g24-power-by-drfone-android/"><u>Universal Unlock Pattern for Motorola G24 Power</u></a></li>
<li><a href="https://techtrends.techidaily.com/unreposting-correcting-auto-repost-mistakes-on-tiktok-made-simple/"><u>Unreposting: Correcting Auto-Repost Mistakes on TikTok Made Simple</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-titans-of-the-digital-realm-top-10-sites-dominating-todays-web-scene/"><u>Unveiling the Titans of the Digital Realm: Top 10 Sites Dominating Today's Web Scene</u></a></li>
<li><a href="https://techtrends.techidaily.com/upgrading-inbox-notifications-crafting-your-own-ringtone-preferences-on-googles-gmail-platform/"><u>Upgrading Inbox Notifications: Crafting Your Own Ringtone Preferences on Google's Gmail Platform</u></a></li>
<li><a href="https://some-guidance.techidaily.com/what-are-the-best-sites-to-download-text-effects-in-2024/"><u>What Are The Best Sites To Download Text Effects, In 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/wireless-connection-pairing-your-airpods-with-a-windows-based-hp-notebook/"><u>Wireless Connection: Pairing Your AirPods with a Windows-Based HP Notebook</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->