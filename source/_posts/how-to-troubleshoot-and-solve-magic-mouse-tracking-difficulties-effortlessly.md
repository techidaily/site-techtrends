---
title: How to Troubleshoot and Solve Magic Mouse Tracking Difficulties Effortlessly
date: 2024-08-18T21:41:54.031Z
updated: 2024-08-19T21:41:54.031Z
categories:
  - BestProducts
description: This Article Describes How to Troubleshoot and Solve Magic Mouse Tracking Difficulties Effortlessly
excerpt: This Article Describes How to Troubleshoot and Solve Magic Mouse Tracking Difficulties Effortlessly
thumbnail: https://www.lifewire.com/thmb/c_hz5OlxkH7ZRUIDzcWIIkqWves=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/MagicMouse2-144-56a5d5543df78cf7728a106b.jpg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-10-free-recorder-apps-for-slack-meetings-and-video-conferencing/"><u>[New] In 2024, 10 FREE Recorder Apps for Slack Meetings & Video Conferencing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-compelling-youtube-profile-definitions/"><u>[Updated] 2024 Approved  Crafting Compelling YouTube Profile Definitions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-effortlessly-schedule-meetings-with-zoom-through-email-for-2024/"><u>[Updated] Effortlessly Schedule Meetings with Zoom Through Email for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/accidentally-repotted-learn-to-remove-a-repot-in-tiktok-without-stress/"><u>Accidentally Repotted? Learn to Remove a Repot in TikTok Without Stress</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-samsung-galaxy-a14-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Samsung Galaxy A14 5G is off? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-vision-unveiled-8-revolutionary-applications-for-professionals-and-enthusiasts-alike/"><u>ChatGPT Vision Unveiled: 8 Revolutionary Applications for Professionals and Enthusiasts Alike</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/comparing-leading-free-and-paid-zoom-transcription-systems-for-2024/"><u>Comparing Leading Free & Paid Zoom Transcription Systems for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabled-iphone-15-how-to-unlock-a-disabled-iphone-15-by-drfone-ios/"><u>Disabled iPhone 15 How to Unlock a Disabled iPhone 15?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/engaging-video-summaries-for-books/"><u>Engaging Video Summaries for Books</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-viewing-experience-with-the-ideal-image-settings-on-samsung-4k-models/"><u>Enhance Viewing Experience with the Ideal Image Settings on Samsung 4K Models</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-novice-to-master-the-definitive-guide-to-playing-pokemon-go/"><u>From Novice to Master: The Definitive Guide to Playing Pokémon GO</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-get-your-stubborn-airpods-back-on-track-resetting-made-easy/"><u>How To Get Your Stubborn AirPods Back On Track – Resetting Made Easy</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-quickly-address-not-found-or-missing-d3dx933dll-errors/"><u>How To Quickly Address 'Not Found' Or 'Missing' d3dx9_33.dll Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-restore-functionality-to-dvd-blu-ray-and-cd-drives-that-wont-open/"><u>How To Restore Functionality to DVD, Blu-Ray & CD Drives That Won't Open</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-successfully-fix-and-reset-an-unresponsive-samsung-soundbar/"><u>How to Successfully Fix and Reset an Unresponsive Samsung Soundbar</u></a></li>
<li><a href="https://techtrends.techidaily.com/identifying-ipads-equipped-with-onboard-navigation-systems/"><u>Identifying iPads Equipped with Onboard Navigation Systems</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ultimate-guide-to-free-pptp-vpn-for-beginners-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Free PPTP VPN For Beginners On Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/in-depth-review-fugetek-ft-568-exceptional-quality-for-a-superior-selfie-experience/"><u>In-Depth Review: Fugetek FT-568 - Exceptional Quality for a Superior Selfie Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-art-of-custom-display-settings-in-apples-finder-full-guide-to-managing-folders-and-subfolders/"><u>Mastering the Art of Custom Display Settings in Apple's Finder - Full Guide to Managing Folders & Subfolders</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-fix-how-to-resolve-ac1st16dll-missing-file-problems/"><u>Step-by-Step Fix: How to Resolve 'Ac1st16.dll' Missing File Problems</u></a></li>
<li><a href="https://techtrends.techidaily.com/syncing-success-easily-navigate-icloud-photos-on-apple-windows-and-android/"><u>Syncing Success: Easily Navigate iCloud Photos on Apple, Windows & Android</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-premier-selection-of-cable-modemrouter-hybrids-in-2e24/"><u>The Premier Selection of Cable-Modem/Router Hybrids in 2E24</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-for-when-wmvcoredll-is-not-found-or-missing/"><u>The Ultimate Fix for When Wmvcore.dll Is Not Found or Missing</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-selection-7-excellent-alarm-apps-you-should-try/"><u>The Ultimate Selection: 7 Excellent Alarm Apps You Should Try</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-walkthrough-for-watching-fandango-on-your-apple-tv-at-home/"><u>The Ultimate Walkthrough for Watching Fandango on Your Apple TV at Home</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-titles-only-available-on-playstation-5-your-complete-guide/"><u>Top Titles Only Available on PlayStation 5: Your Complete Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-your-ps5-dualsense-steps-to-resolve-charging-issues/"><u>Troubleshooting Your PS5 DualSense: Steps To Resolve Charging Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-how-to-resolve-the-mapp32dll-not-found-issue/"><u>Troubleshooting: How to Resolve the 'mapp32.dll Not Found' Issue</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-gif-repository-capturing-the-essence-in-frames/"><u>Twitter Gif Repository  Capturing the Essence in Frames</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-top-five-gratis-cybersecurity-tools-to-tackle-malware/"><u>Unveiling the Top Five Gratis Cybersecurity Tools to Tackle Malware</u></a></li>
</ul></div>
