---
title: "Effortless Audio Sync: How to Link AirPods with a MacBook Air"
date: 2024-09-01T18:39:35.578Z
updated: 2024-09-02T18:39:35.578Z
categories:
  - BestProducts
description: "This Article Describes Effortless Audio Sync: How to Link AirPods with a MacBook Air"
excerpt: "This Article Describes Effortless Audio Sync: How to Link AirPods with a MacBook Air"
thumbnail: https://thmb.techidaily.com/c3cb24735a325c59b374deb74baa7c6af50100c3f603092c99cb6f1def444289.jpg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://extra-hints.techidaily.com/90s-chuckles-dissecting-the-vhs-of-the-goofies/"><u>'90S Chuckles  Dissecting the VHS of The Goofies</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-streaming-software-spectacle-choosing-between-virusmix-and-castpro/"><u>[New] 2024 Approved  Streaming Software Spectacle  Choosing Between VirusMix and CastPro</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-advanced-strategies-for-changing-user-numbers-in-tiktok/"><u>[New] Advanced Strategies for Changing User Numbers in TikTok</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-download-any-song-on-fb-for-free/"><u>[New] Download Any Song on FB for Free</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-vrecorder-basics-seamless-installation/"><u>[New] In 2024, VRecorder Basics  Seamless Installation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-instant-fb-video-to-high-quality-mp4/"><u>[New] Instant FB Video to High-Quality MP4</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-perfecting-pics-with-practicality-top-5-pc-snipping-tools/"><u>[New] Perfecting Pics with Practicality - Top 5 PC Snipping Tools</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-enhancing-on-screen-appeal-essential-tips-for-talking-head-shots/"><u>[Updated] Enhancing On-Screen Appeal  Essential Tips for Talking-Head Shots</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-leading-tech-for-remote-team-engagement-for-2024/"><u>[Updated] Leading Tech for Remote Team Engagement for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-linkedin-luminaries-chatting-with-snapchat/"><u>[Updated] LinkedIn Luminaries Chatting with Snapchat</u></a></li>
<li><a href="https://techtrends.techidaily.com/dvd-windows-11top10/"><u>「快適なDVDコピー: Windows 11で使える最新フリーソフトウェアTOP10」</u></a></li>
<li><a href="https://techtrends.techidaily.com/1-comprehensive-review-top-tier-dji-4k-footage-editing-software-options/"><u>1. Comprehensive Review: Top-Tier DJI 4K Footage Editing Software Options</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-mastering-the-price-of-youtube-marketing/"><u>2024 Approved  Mastering the Price of YouTube Marketing</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-honor-magic-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/1724765812017-dvd/"><u>日本語 DVDスリックダウンロード方法: セキュリティが低下するのを防ぐ</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nubia-red-magic-9-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://techtrends.techidaily.com/apple-updates-and-expert-advice-the-newest-trends-and-tech-insights/"><u>Apple Updates & Expert Advice: The Newest Trends and Tech Insights</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-ios-enhancement-rolled-out-by-macxdvd-for-latest-iphone-7-and-iphone-7-plus-devices/"><u>Comprehensive iOS Enhancement Rolled Out by MacXDVD for Latest iPhone 7 and iPhone 7 Plus Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/digiartymacx-dvd-ripper-pro/"><u>Digiarty在宅応援キャンペーン：MacX DVD Ripper Proと共に、アマゾンプライムで豪華な賞品を獲得する機会！</u></a></li>
<li><a href="https://techtrends.techidaily.com/dvd-movies-to-pc-conversion-made-easy-a-comprehensive-tutorial-on-using-vlc-with-screenshots-compatible-with-both-mac-and-windows-systems/"><u>DVD Movies to PC Conversion Made Easy: A Comprehensive Tutorial on Using VLC with Screenshots, Compatible With Both Mac and Windows Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-on-maintaining-excellent-quality-during-video-encoding-with-handbrake/"><u>Expert Tips on Maintaining Excellent Quality During Video Encoding with Handbrake</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-the-aukey-usb-30-hub-simple-design-with-advanced-features/"><u>Exploring the Aukey USB 3.0 Hub: Simple Design with Advanced Features</u></a></li>
<li><a href="https://techtrends.techidaily.com/free-movie-streaming-on-mac-using-popcorn-time-download-and-watch-without-glitches/"><u>Free Movie Streaming on Mac Using Popcorn Time - Download & Watch Without Glitches</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-iphone-6s-plus-by-drfone-ios/"><u>How to Bypass iCloud Lock on iPhone 6s Plus</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-eliminate-freezing-in-sifu-fps-on-pc-troubleshooting-steps/"><u>How to Eliminate Freezing in 'Sifu' FPS on PC - Troubleshooting Steps</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-restore-wi-fi-connectivity-in-your-iphone-following-the-ios-abstraction-understanding-and-resolving-common-problems/"><u>How to Restore Wi-Fi Connectivity in Your iPhone Following the iOS Abstraction - Understanding and Resolving Common Problems</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-successfully-set-up-facial-recognition-face-id-for-enhanced-security-on-iphone-x/"><u>How to Successfully Set Up Facial Recognition (Face ID) for Enhanced Security on iPhone X</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-ipad-hooray-access-exclusive-zero-cost-haunting-melodies-for-the-perfect-ghostly-ambiance/"><u>IPhone iPad Hooray! Access Exclusive, Zero-Cost Haunting Melodies for the Perfect Ghostly Ambiance</u></a></li>
<li><a href="https://techtrends.techidaily.com/mac-compatible-wmv-transcoder-effortless-conversion-of-wmv-files-into-high-quality-mp4-mkv-and-avi/"><u>Mac-Compatible WMV Transcoder: Effortless Conversion of WMV Files Into High-Quality MP4, MKV & AVI</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-game-on-10plus-trusted-websites-to-download-games-this-year/"><u>New 2024 Approved Game On! 10+ Trusted Websites to Download Games This Year</u></a></li>
<li><a href="https://techtrends.techidaily.com/optimize-your-library-with-vudus-dvd-to-digital-conversion-embrace-complete-viewing-flexibility/"><u>Optimize Your Library with Vudu's DVD-to-Digital Conversion – Embrace Complete Viewing Flexibility</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/preparing-for-peak-vr-performance-for-2024/"><u>Preparing For Peak VR Performance for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-15-plus-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 15 Plus Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/seamlessly-transfer-your-dvds-mac-to-android-conversion-guide/"><u>Seamlessly Transfer Your DVDs: Mac to Android Conversion Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/simple-guide-to-transforming-web-links-into-premium-quality-mp4-files-for-smooth-playback-on-ios-and-android-devices/"><u>Simple Guide to Transforming Web Links Into Premium-Quality MP4 Files for Smooth Playback on iOS & Android Devices</u></a></li>
<li><a href="https://win-blog.techidaily.com/starfield-errors-solved-how-to-ensure-smooth-gameplay-on-windows-and-mac/"><u>Starfield Errors Solved: How to Ensure Smooth Gameplay on Windows and Mac</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-moving-your-dvd-collection-to-a-streamlined-media-server/"><u>Step-by-Step Guide: Moving Your DVD Collection to a Streamlined Media Server</u></a></li>
<li><a href="https://techtrends.techidaily.com/strategie-per-duplicare-i-dvd-codificati-sulla-tua-macchina-apple/"><u>Strategie per Duplicare I DVD Codificati Sulla Tua Macchina Apple</u></a></li>
<li><a href="https://techtrends.techidaily.com/swiftly-transfer-your-ipad-data-to-mac-a-step-by-step-tutorial-under-17-seconds/"><u>Swiftly Transfer Your iPad Data to Mac: A Step-by-Step Tutorial (Under 17 Seconds)</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-must-watch-christmas-movies-on-dvd-purchase-or-rental-options/"><u>Top 10 Must-Watch Christmas Movies on DVD - Purchase or Rental Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-rated-youtube-music-extractor-apps-how-to-legally-save-tunes-from-youtube/"><u>Top Rated YouTube Music Extractor Apps: How to Legally Save Tunes From YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/transformateur-de-fichiers-mxf-pour-mac-convertissez-facilement-vers-mp4-mov-et-autres-formats/"><u>Transformateur De Fichiers MXF Pour Mac : Convertissez Facilement Vers MP4, MOV Et Autres Formats</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-a-nonfunctional-hyperx-cloud-stinger-mic-solutions-revealed/"><u>Troubleshooting a Nonfunctional HyperX Cloud Stinger Mic - Solutions Revealed</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-installing-freemake-video-converter-on-macos/"><u>Ultimate Guide: Installing Freemake Video Converter on macOS</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-the-legality-of-dvd-duplication-is-it-against-the-law/"><u>Understanding the Legality of DVD Duplication: Is It Against the Law?</u></a></li>
</ul></div>
