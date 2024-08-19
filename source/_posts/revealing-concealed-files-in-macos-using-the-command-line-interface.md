---
title: Revealing Concealed Files in macOS Using the Command Line Interface
date: 2024-08-18T21:26:51.097Z
updated: 2024-08-19T21:26:51.097Z
categories:
  - BestProducts
description: This Article Describes Revealing Concealed Files in macOS Using the Command Line Interface
excerpt: This Article Describes Revealing Concealed Files in macOS Using the Command Line Interface
thumbnail: https://www.lifewire.com/thmb/klGzkHFGCUaqiWyKpafLJvoSONc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508.jpg
---

## Revealing Concealed Files in macOS Using the Command Line Interface
 Your Mac has a few secrets, hidden folders, and files that are invisible to you. You may not even realize how much hidden data there is on your Mac, from basic things, such as preference files for user data and apps, to core system data that your Mac needs to run correctly. Apple hides these files and folders to prevent you from accidentally changing or deleting important data that your Mac needs.

 Apple's reasoning is good, but there are times when you may need to view these out-of-the-way corners of your Mac's file system. You'll find that accessing these hidden corners of your Mac is one of the steps in many Mac troubleshooting guides, as well as guides for backing up important data, such as[mail messages](https://www.lifewire.com/transfer-apple-mail-to-new-mac-2260915) or[Safari bookmarks](https://www.lifewire.com/back-up-or-move-safari-bookmarks-to-new-mac-2260891) . Fortunately, Apple includes ways to access these hidden goodies in[OS X](https://www.lifewire.com/install-mac-os-on-pc-5075590) and the more recent[macOS](https://www.lifewire.com/what-is-macos-4691239) . This guide concentrate on using the Terminal app, which provides a command line-like interface to many of the Mac's core functions.

![macOS Terminal with hidden files in a Finder window superimposed](https://www.lifewire.com/thmb/0GxCNfM-Nwq84X9L67jj4gSEqP4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508-fb8027cc5efa44e2a3c858234aac1ae3.jpg)

 With Terminal, a simple command is all it takes to get your Mac to spill its secrets.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-capture-twitter-gifs-on-your-computer-quickly-for-2024/"><u>[New] Capture Twitter Gifs on Your Computer Quickly for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-metaversal-motivation-a-curated-list-of-inspiring-quotes/"><u>[New] Metaversal Motivation  A Curated List of Inspiring Quotes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-rhythmic-rarities-assembling-the-best-dj-video-samples-for-2024/"><u>[Updated] Rhythmic Rarities  Assembling the Best DJ Video Samples for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/10-best-webcams-you-should-know-for-2024/"><u>10 Best Webcams You Should Know for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-in-depth-giroptic-complete-immersion/"><u>2024 Approved  In-Depth Giroptic Complete Immersion</u></a></li>
<li><a href="https://techtrends.techidaily.com/anticipating-the-arrival-of-oneplus-10-a-closer-look-at-estimated-price-launch-date-and-speculative-features/"><u>Anticipating the Arrival of OnePlus 10 – A Closer Look at Estimated Price, Launch Date, and Speculative Features</u></a></li>
<li><a href="https://facebook.techidaily.com/audio-free-video-free-ig-live-experience/"><u>Audio-Free, Video-Free IG Live Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-fixes-for-linear-display-anomalies-on-personal-computers/"><u>Comprehensive Fixes for Linear Display Anomalies on Personal Computers</u></a></li>
<li><a href="https://techtrends.techidaily.com/decoding-chatgpthem-who-is-steering-this-ai-revolution/"><u>Decoding ChatGPT'hem: Who Is Steering This AI Revolution?</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-the-silent-phone-effective-remedies-to-restore-your-iphones-ringtones/"><u>Diagnosing the 'Silent Phone': Effective Remedies to Restore Your iPhone's Ringtones</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-all-there-is-to-know-about-netflix-the-premier-leader-in-online-streaming-services/"><u>Discover All There Is To Know About Netflix – The Premier Leader in Online Streaming Services</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-integration-of-fubotv-onto-your-amazon-firestick-device/"><u>Easy Integration of FuboTV Onto Your Amazon Firestick Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-on-integrating-various-fortnite-accounts-efficiently/"><u>Expert Tips on Integrating Various Fortnite Accounts Efficiently</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-the-oneplus-nord-n10-5g-an-unmissable-player-in-the-market/"><u>Exploring the OnePlus Nord N10 5G - An Unmissable Player in the Market</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-how-to-remove-subtitles-from-amazon-prime-video-watches/"><u>Guide: How to Remove Subtitles From Amazon Prime Video Watches</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-charge-your-phone-without-a-charger/"><u>How to Charge Your Phone Without a Charger</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-correctly-address-the-d3dx925dll-file-not-found-problem/"><u>How to Correctly Address the 'd3dx9_25.dll' File Not Found Problem</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-link-your-disneyplus-subscription-with-chromecast-for-an-enhanced-viewing-experience/"><u>How to Link Your Disney+ Subscription With Chromecast for an Enhanced Viewing Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-deactivate-microsofts-virtual-assistant-copilot-on-windows-11-computers/"><u>How To: Deactivate Microsoft's Virtual Assistant, Copilot, on Windows 11 Computers</u></a></li>
<li><a href="https://techtrends.techidaily.com/leading-self-driving-car-makers-the-ultimate-list/"><u>Leading Self-Driving Car Makers : The Ultimate List</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-methods-to-correct-your-401-access-denied-issue/"><u>Mastering Methods to Correct Your 401 Access Denied Issue</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-art-of-multiplayer-experiences-on-sonys-latest-console/"><u>Mastering the Art of Multiplayer Experiences on Sony's Latest Console</u></a></li>
<li><a href="https://techtrends.techidaily.com/method-resetting-and-changing-passwords-for-other-users-in-windows-environment/"><u>Method: Resetting and Changing Passwords for Other Users in Windows Environment</u></a></li>
<li><a href="https://techtrends.techidaily.com/microsoft-downtime-exposes-the-need-for-government-policies-against-overdependence-on-large-scale-tech-entities/"><u>Microsoft Downtime Exposes the Need for Government Policies Against Overdependence on Large-Scale Tech Entities</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-your-digital-scrapbook-finding-stored-reels-on-instagram-with-simple-steps/"><u>Navigating Your Digital Scrapbook: Finding Stored Reels on Instagram with Simple Steps</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-microsoft-edge-hurdles-a-comprehensive-repair-manual/"><u>Overcoming Microsoft Edge Hurdles: A Comprehensive Repair Manual</u></a></li>
<li><a href="https://techtrends.techidaily.com/parental-control-setup-limiting-access-to-online-videos-on-ipads/"><u>Parental Control Setup: Limiting Access to Online Videos on iPads</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premier-vr-manipulators-to-try-now-for-2024/"><u>Premier VR Manipulators to Try Now for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/siri-text-reading-guide-accessibility-features-on-ios-and-mac-devices/"><u>Siri Text Reading Guide: Accessibility Features on iOS and Mac Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-for-adding-emojis-to-communications-on-your-iphone-device/"><u>Step-by-Step Instructions for Adding Emojis to Communications on Your iPhone Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-essential-gadgets-and-accessories-for-summer-days-out/"><u>The Ultimate Guide: Essential Gadgets and Accessories for Summer Days Out</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-12-complimentary-keyboard-skills-courses-ideal-for-learners-at-any-age/"><u>Top 12 Complimentary Keyboard Skills Courses: Ideal for Learners at Any Age</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-missing-mfc42dll-errors-in-windows-systems/"><u>Troubleshooting Missing mfc42.dll Errors in Windows Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-erasing-personal-data-with-a-factory-restore-on-lenovo-systems/"><u>Ultimate Guide: Erasing Personal Data with a Factory Restore on Lenovo Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722902649952-unlock-the-potential-of-your-windows-11-by-running-android-apps-with-these-simple-steps/"><u>Unlock the Potential of Your Windows 11 by Running Android Apps with These Simple Steps!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-perfection-real-user-appreciation/"><u>Video Perfection - Real User Appreciation</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722887307809-watching-fubotv-heres-how-you-can-stream-it-using-fire-stick-easily/"><u>Watching FuboTV? Here's How You Can Stream It Using Fire Stick Easily!</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-do-when-you-cant-get-new-emails-in-your-yahoo-account/"><u>What to Do When You Can't Get New Emails in Your Yahoo Account</u></a></li>
<li><a href="https://techtrends.techidaily.com/yahoo-messenger-explained-its-history-and-reason-behind-the-closure/"><u>Yahoo! Messenger Explained: Its History and Reason Behind the Closure</u></a></li>
</ul></div>
