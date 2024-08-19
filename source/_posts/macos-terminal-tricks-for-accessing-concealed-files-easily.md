---
title: MacOS Terminal Tricks for Accessing Concealed Files Easily
date: 2024-08-18T22:23:48.593Z
updated: 2024-08-19T22:23:48.593Z
categories:
  - BestProducts
description: This Article Describes MacOS Terminal Tricks for Accessing Concealed Files Easily
excerpt: This Article Describes MacOS Terminal Tricks for Accessing Concealed Files Easily
thumbnail: https://www.lifewire.com/thmb/klGzkHFGCUaqiWyKpafLJvoSONc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508.jpg
---

## MacOS Terminal Tricks for Accessing Concealed Files Easily
 Your Mac has a few secrets, hidden folders, and files that are invisible to you. You may not even realize how much hidden data there is on your Mac, from basic things, such as preference files for user data and apps, to core system data that your Mac needs to run correctly. Apple hides these files and folders to prevent you from accidentally changing or deleting important data that your Mac needs.

 Apple's reasoning is good, but there are times when you may need to view these out-of-the-way corners of your Mac's file system. You'll find that accessing these hidden corners of your Mac is one of the steps in many Mac troubleshooting guides, as well as guides for backing up important data, such as[mail messages](https://www.lifewire.com/transfer-apple-mail-to-new-mac-2260915) or[Safari bookmarks](https://www.lifewire.com/back-up-or-move-safari-bookmarks-to-new-mac-2260891) . Fortunately, Apple includes ways to access these hidden goodies in[OS X](https://www.lifewire.com/install-mac-os-on-pc-5075590) and the more recent[macOS](https://www.lifewire.com/what-is-macos-4691239) . This guide concentrate on using the Terminal app, which provides a command line-like interface to many of the Mac's core functions.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![macOS Terminal with hidden files in a Finder window superimposed](https://www.lifewire.com/thmb/0GxCNfM-Nwq84X9L67jj4gSEqP4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508-fb8027cc5efa44e2a3c858234aac1ae3.jpg)

 With Terminal, a simple command is all it takes to get your Mac to spill its secrets.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## More About Terminal

 If the power of the Terminal app intrigues you, you can find out more about what secrets Terminal can uncover in this guide:[Use the Terminal Application to Access Hidden Features](https://www.lifewire.com/mac-terminal-commands-4774997) .

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
<li><a href="https://extra-skills.techidaily.com/new-snapchat-tricks-unleashing-yourself-with-a-cartoon-lens/"><u>[New] Snapchat Tricks  Unleashing Yourself with a Cartoon Lens</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamlining-windows-photos-with-customized-audio-and-visual-settings/"><u>[New] Streamlining Windows Photos with Customized Audio & Visual Settings</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-complete-evaluation-hero4-black-interface/"><u>[Updated] Complete Evaluation  Hero4 Black Interface</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-enrich-your-videos-expert-recommended-players-guide/"><u>2024 Approved  Enrich Your Videos  Expert-Recommended Players' Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974735927-accelerate-gaming-with-an-updated-intel-graphics-3000-driver-on-w10-platform/"><u>Accelerate Gaming with an Updated Intel Graphics 3000 Driver on W10 Platform.</u></a></li>
<li><a href="https://techtrends.techidaily.com/amd-boosts-instinct-mi1000-revenue-forecast-targeting-4-billion-vs-nvidias-staggering-40b-estimate/"><u>AMD Boosts Instinct MI1000 Revenue Forecast: Targeting $4 Billion Vs. Nvidia's Staggering $40B Estimate</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-your-gaming-experience-tips-for-reaching-120fps-on-playstation-5/"><u>Boost Your Gaming Experience: Tips for Reaching 120Fps on PlayStation 5</u></a></li>
<li><a href="https://network-issues.techidaily.com/breaking-barrier-amd-succeeds-in-loading-driver-on-win10/"><u>Breaking Barrier: AMD Succeeds in Loading Driver on Win10</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-fixes-for-advapi32dll-not-detected-or-lost-mistakes/"><u>Comprehensive Fixes for Advapi32.dll Not Detected or Lost Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-11s-rounded-edges/"><u>Eliminate Windows 11'S Rounded Edges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tips-for-multi-tasking-with-split-view-on-macbook-air/"><u>Essential Tips for Multi-Tasking with Split View on MacBook Air</u></a></li>
<li><a href="https://techtrends.techidaily.com/exclusive-amazon-prime-day-offers-on-latest-gadgets-and-electronics/"><u>Exclusive Amazon Prime Day Offers on Latest Gadgets & Electronics</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-strategies-to-address-and-repair-code-28-malfunctions-in-windows/"><u>Expert Strategies to Address and Repair Code 28 Malfunctions in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-compatible-intel-usb-30-driver-pack-for-windows-10-systems/"><u>Free Download: Compatible Intel USB 3.0 Driver Pack for Windows 10 Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-for-taming-your-systems-roaring-fan-an-easy-fix/"><u>Guide for Taming Your System's Roaring Fan – An Easy Fix</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-did-the-early-days-shape-up-the-story-behind-netflixs-dvd-subscription-model/"><u>How Did the Early Days Shape Up? The Story Behind Netflix’s DVD Subscription Model</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-save-and-watch-netflix-movies-offline-on-your-laptop/"><u>How to Save and Watch Netflix Movies Offline on Your Laptop</u></a></li>
<li><a href="https://techtrends.techidaily.com/identifying-ipads-equipped-with-internal-navigation-systems/"><u>Identifying iPads Equipped with Internal Navigation Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/imaginary-giggles-generate-with-kapwings-maker/"><u>Imaginary Giggles  Generate with Kapwing's Maker</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-infinix-smart-8-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Infinix Smart 8 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-from-your-apple-iphone-13-pro-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock from your Apple iPhone 13 Pro and iPad?</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-users-manual-how-to-mute-emergency-and-amber-messages/"><u>IPhone Users' Manual: How to Mute Emergency and AMBER Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/locate-missing-inbox-items-expert-advice-on-recovering-deleted-emails-in-googles-messaging-service/"><u>Locate Missing Inbox Items: Expert Advice on Recovering Deleted Emails in Google's Messaging Service</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-art-of-timed-message-dispatch-on-apples-mobile-os/"><u>Mastering the Art of Timed Message Dispatch on Apple's Mobile OS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-new-milestone-achieved-filmora-x-expands-to-arm-platform/"><u>New 2024 Approved New Milestone Achieved Filmora X Expands to ARM Platform</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-yuva-3-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Yuva 3</u></a></li>
<li><a href="https://techtrends.techidaily.com/resetting-your-lenovo-notebook-a-step-by-step-tutorial-for-fresh-startup/"><u>Resetting Your Lenovo Notebook: A Step-by-Step Tutorial for Fresh Startup</u></a></li>
<li><a href="https://techtrends.techidaily.com/samsung-tv-trick-easily-downloading-and-setting-up-a-different-web-browser/"><u>Samsung TV Trick: Easily Downloading and Setting Up a Different Web Browser</u></a></li>
<li><a href="https://techtrends.techidaily.com/separating-fact-from-fiction-is-your-connection-to-nintendo-switch-online-compromised-or-just-server-issues/"><u>Separating Fact From Fiction: Is Your Connection to Nintendo Switch Online Compromised or Just Server Issues?</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-for-completely-refreshing-any-ipad-model-through-a-hard-reset/"><u>Step-by-Step Instructions for Completely Refreshing Any iPad Model Through a Hard Reset</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-art-of-attraction-steering-your-instagram-creativity-towards-sponsorship-success-for-2024/"><u>The Art of Attraction  Steering Your Instagram Creativity Towards Sponsorship Success for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-breakdown-of-streaming-systems-and-their-functions-in-todays-tech-scene/"><u>The Ultimate Breakdown of Streaming Systems and Their Functions in Today's Tech Scene</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-crafting-awkward-potions-with-maximum-benefits-in-minecraft/"><u>The Ultimate Guide to Crafting Awkward Potions with Maximum Benefits in Minecraft</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-5-must-try-automated-pinning-apps-for-boosting-your-pinterest-game/"><u>Top 5 Must-Try Automated Pinning Apps for Boosting Your Pinterest Game</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-the-variations-between-cat5-and-cat6-network-cabling/"><u>Understanding the Variations Between Cat5 & Cat6 Network Cabling</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-future-insider-info-on-apples-upcoming-ring-with-rumored-cost-and-details/"><u>Unveiling the Future: Insider Info on Apple's Upcoming Ring with Rumored Cost & Details</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-power-of-recuva-elite-analysis-on-superior-data-rescue-applications/"><u>Unveiling the Power of Recuva: Elite Analysis on Superior Data Rescue Applications</u></a></li>
<li><a href="https://program-issues.techidaily.com/zombie-army-4-on-pc-how-to-solve-unexpected-shutdown-problems/"><u>Zombie Army 4 on PC - How to Solve Unexpected Shutdown Problems</u></a></li>
</ul></div>
