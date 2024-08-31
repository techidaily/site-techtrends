---
title: "Step-by-Step Tutorial: Contrasting File Systems in Windows 10 Vs. Windows 11"
date: 2024-08-30T15:08:11.129Z
updated: 2024-08-31T15:08:11.129Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/aa75ccceb27df582eb4900ae099d99b1731677ace1a8dcb38cd4f8698fb9bdda.jpg
---

## Step-by-Step Tutorial: Contrasting File Systems in Windows 10 Vs. Windows 11

### Quick Links

* [Compare Folders From Properties](https://tech-recovery.techidaily.com/the-ultimate-fix-for-when-youtube-comments-wont-load/)
* [Compare Folders Using Command Prompt](https://video-capture.techidaily.com/new-in-2024-exacting-speech-recognition-via-googles-precision-tools/)
* [Compare Folders With WinMerge](https://win-howtos.techidaily.com/how-to-repair-when-your-macs-trackpad-wont-respond/)

### Key Takeaways

* One way to compare folders is to right-click your folders one at a time and choose "Properties" for each. Then compare the Properties window of each folder.
* The robocopy command is a command-line tool that can be used to view the differences between folder.
* Use WinMerge to compare the contents and details of folders if you want a graphical tool.

 Do you want to compare the number of files or folders or simply visualize the difference between two folders? If so, you have two graphical and one command line method to do that. We’ll show you how to perform the folder comparison task on your Windows 11 or Windows 10 PC.

##  Compare Folders From Properties

 To compare the number of files, subfolders, the size, and the creation date of two folders, use the Properties option in Windows File Explorer. This lets you quickly glance at the main attributes of a folder.

 To start, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E. Find the first folder, right-click it, and select "Properties."

!['Properties' highlighted for a folder in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-folder-properties.jpg) 

 Keep the first folder’s "Properties" window open. Then, find the second folder, right-click it, and select "Properties."

 You now have the "Properties" window open for both your folders. Bring these windows side-by-side by [dragging them](https://extra-resources.techidaily.com/mastering-complex-video-effects-and-transitions-in-gopro-studio/), and you can see the differences in the contents of these folders. For example, you can see how many files both folders have, what size these folders are, and so on.

!['Properties' windows for two folders in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-compare-folder-properties.jpg) 

 That gives you a general overview of the differences between your folders.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
##  Compare Folders Using Command Prompt

 If you prefer command line methods over graphical ones, use the robocopy command in Command Prompt to see the differences between the two folders. This command is actually for [copying files from one folder to another](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/), but you can make it show the differences between two specified folders and not copy any files.

 To use robocopy, first open the Start Menu, search **Command Prompt**, and launch it.

![Command Prompt highlighted in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
 In Command Prompt, type the following command. Replace "Folder1" with the path to your first folder and "Folder2" with the path to your second folder. Ensure both folder paths are enclosed in double quotes.

 To copy a folder’s full path along with double quotes around the path, hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

robocopy "Folder1" "Folder2" /L /NJH /NJS /NP /NS

![The 'robocopy' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-compare-folders-command-prompt.jpg) 

 You’ll see the differences between your folders.

 If you’re curious as to what the robocopy command does, here’s an explanation of each flag we used with the command:

* **L**: This tells the command not to copy files but show the log of the files in the specified folder.
* **NJH**: This flag excludes junctions, hard links, and reparse points from consideration. This way, the command focuses on the regular files in the specified folders.
* **NJS**: This flag excludes symbolic links from the process.
* **NP**: This flag excludes folder timestamps.
* **NS**: This flag excludes file security information.

##  Compare Folders With WinMerge

 If you want more details about the differences in your folders, Windows doesn't have a built-in tool to help you with that. However, you can use a free third-party app called WinMerge to compare multiple folders.

 To use it, launch a web browser on your PC, head to the [WinMerge](https://winmerge.org/downloads/?lang=en) site, and download and install the app. Make sure to download the app’s executable and not the ZIP version.

 Open the WinMerge app, then select File > Open in the Menu Bar or press Ctrl+O.

![File > Open highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-folder-winmerge.jpg) 

 For the "1st File or Folder" field, select "Browse" and choose the first folder to compare.

!['Browse' highlighted for the '1st File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-add-first-folder-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 For the "2nd File or Folder" field, click the "Browse" button and choose the second folder to compare.

!['Browse' highlighted for the '2nd File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-add-second-folder-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In both fields, enable the "Read-Only" option. Click the "Folder: Filter" field and type **\*.\*** if it isn’t already there. This ensures the app compares all the files in both the specified folders. Then, at the bottom, click "Compare."

![Various comparison options highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-configure-comparison-options-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 On the following screen, you’ll see the comparison of the specified folders. You’ll see information like identical files in both folders, files missing from one folder, and so on.

![The comparison of two folders in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-folder-comparison-winmerge.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
 And that's how you know what one folder has that another doesn't. This can be really useful if you're trying to quickly compare different versions of the same folder, like you'd have when you[create a backup](https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-14-pro-max-if-youve-tried-everything-by-drfone-ios/).

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
<li><a href="https://techtrends.techidaily.com/the-future-of-mobile-tech-insights-into-foldable-iphones-price-specs-launch-date-and-latest-rumors/"><u>“The Future of Mobile Tech: Insights Into Foldable iPhones – Price, Specs, Launch Date & Latest Rumors</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-androids-prime-portable-gba-simulators-ranked-for-2024/"><u>[Updated] Android's Prime Portable GBA Simulators Ranked for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-interactive-presenters-synopsis-update-8/"><u>[Updated] In 2024, Interactive Presenter's Synopsis, Update 8</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-mastering-quick-retrieval-of-hidden-reddit-threads/"><u>[Updated] In 2024, Mastering Quick Retrieval of Hidden Reddit Threads</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-sorbet-surveillance-complete-guide-to-ice-cream-screen-capture/"><u>[Updated] Sorbet Surveillance  Complete Guide to Ice Cream Screen Capture</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-enhancing-revenue-the-15-premier-fb-insight-gadgets/"><u>2024 Approved  Enhancing Revenue  The 15 Premier FB Insight Gadgets</u></a></li>
<li><a href="https://techtrends.techidaily.com/2024s-top-rated-learning-platforms-a-comprehensive-review/"><u>2024’S Top-Rated Learning Platforms: A Comprehensive Review</u></a></li>
<li><a href="https://techtrends.techidaily.com/amd-radeon-graphics-driver-version-2410-download-and-installation-guide/"><u>AMD Radeon Graphics Driver Version 24.10: Download and Installation Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/anticipate-the-apple-watch-series-8-arrival-detailed-overview-on-specs-price-point-and-latest-updates/"><u>Anticipate the Apple Watch Series 8 Arrival: Detailed Overview on Specs, Price Point & Latest Updates</u></a></li>
<li><a href="https://techtrends.techidaily.com/audiences-unmasked-the-insiders-method-for-seeing-who-watches-your-youtube-content/"><u>Audiences Unmasked: The Insider’s Method for Seeing Who Watches Your YouTube Content</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-parental-monitoring-tools-our-recommendations/"><u>Best Parental Monitoring Tools : Our Recommendations</u></a></li>
<li><a href="https://techtrends.techidaily.com/bypassing-roku-remotes-innovative-ways-to-manipulate-your-television-settings/"><u>Bypassing Roku Remotes: Innovative Ways to Manipulate Your Television Settings</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-top-11-cinematic-gems-that-will-inspire-and-empower-you/"><u>Discover the Top 11 Cinematic Gems That Will Inspire and Empower You</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-to-correct-wininetdll-not-found-issues/"><u>Easy Steps to Correct 'wininet.dll Not Found' Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-solutions-to-address-ieframedll-issues-on-your-computer/"><u>Effective Solutions to Address ieframe.dll Issues on Your Computer</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-pick-an-optimal-mobile-case-that-suits-your-style-and-needs/"><u>How To Pick An Optimal Mobile Case That Suits Your Style and Needs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-motorola-moto-g13-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Motorola Moto G13 to Outlook | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oppo-a78-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Oppo A78? Look No Further | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-navigating-the-complexities-of-ps4-live-streaming-and-recording/"><u>In 2024, Navigating the Complexities of PS4 Live Streaming and Recording</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-revolutionized-action-recording-with-tomtoms-newest-bandit/"><u>In 2024, Revolutionized Action Recording with TomTom's Newest Bandit</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-motorola-edge-40-pro-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Motorola Edge 40 Pro Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/jumpstarting-a-dead-laptop-essential-troubleshooting-tips/"><u>Jumpstarting a Dead Laptop: Essential Troubleshooting Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-background-app-management-tips-to-keep-your-android-devices-efficient/"><u>Mastering Background App Management: Tips to Keep Your Android Devices Efficient</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/resolve-your-iphone-6s-keeps-asking-for-outlook-password-by-drfone-ios/"><u>Resolve Your iPhone 6s Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-d3dx924dll-error-a-comprehensive-guide/"><u>Resolving d3dx9_2‌​4.dll Error: A Comprehensive Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-directx-issues-in-battlefield-2042-a-step-by-step-guide/"><u>Solving DirectX Issues in Battlefield 2042: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-haldll-troubleshooting-in-windows-versions-a-step-by-step-guide/"><u>Solving Hal.dll Troubleshooting in Windows Versions: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-for-missing-or-unfound-wmvcoredll-files/"><u>The Ultimate Fix for Missing or Unfound Wmvcore.dll Files</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-for-the-zlibdll-error-missing-or-cannot-find-file-scenarios/"><u>The Ultimate Fix for the 'Zlib.dll' Error: Missing or Cannot Find File Scenarios</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-of-zero-cost-html-programs-for-windows-enthusiasts/"><u>The Ultimate List of Zero-Cost HTML Programs for Windows Enthusiasts</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-resolve-silent-anthem-gameplay-on-windows-10-systems/"><u>Troubleshooting Guide: Resolve Silent Anthem Gameplay on Windows 10 Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-for-missing-launchdll-files-in-windows/"><u>Troubleshooting Steps for Missing 'Launch.dll' Files in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-tips-overcoming-stop-error-0x00000078-phase0exception-quickly-and-easily/"><u>Troubleshooting Tips: Overcoming STOP Error 0X00000078 (PHASE0_EXCEPTION) Quickly and Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-solving-no-sound-on-iphone-restore-your-ringtones/"><u>Ultimate Guide: Solving No Sound on iPhone - Restore Your Ringtones</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-streaming-espn-on-demand-on-an-lg-smart-set-top-unit/"><u>Ultimate Guide: Streaming ESPN On Demand on an LG Smart Set-Top Unit</u></a></li>
<li><a href="https://techtrends.techidaily.com/unbeatable-tech-offers-amazon-prime-day-specials-you-cant-miss/"><u>Unbeatable Tech Offers: Amazon Prime Day Specials You Can't Miss</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleashing-funimate-joy-comprehensive-tutorials-for-2024/"><u>Unleashing Funimate Joy - Comprehensive Tutorials for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-teslas-robotic-future-breaking-stories-theoretical-costs-release-calendar-and-technical-specifications/"><u>Unveiling Tesla's Robotic Future: Breaking Stories, Theoretical Costs, Release Calendar, and Technical Specifications</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-apple-automobile-breaking-news-on-costs-specifications-and-projected-debut-date/"><u>Unveiling the Apple Automobile: Breaking News on Costs, Specifications & Projected Debut Date</u></a></li>
</ul></div>
