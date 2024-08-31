---
title: "MacOS Users' Manual: How to Access Contents of RAR Files Easily"
date: 2024-08-30T15:10:38.535Z
updated: 2024-08-31T15:10:38.535Z
categories:
  - BestProducts
description: "This Article Describes MacOS Users' Manual: How to Access Contents of RAR Files Easily"
excerpt: "This Article Describes MacOS Users' Manual: How to Access Contents of RAR Files Easily"
thumbnail: https://thmb.techidaily.com/bbd20210fc5074f713b02b244d2b1993bd6b418eec110dce123959527009d1b5.png
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
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
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
<li><a href="https://youtube-sure.techidaily.com/mmediate-youtube-audience-insights-for-2024/"><u>[New] Immediate YouTube Audience Insights for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-proven-strategies-for-device-screening-for-2024/"><u>[New] Proven Strategies for Device Screening for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-redefine-video-communication-with-your-webcam/"><u>[Updated] In 2024, Redefine Video Communication with Your Webcam</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-reviving-rarities-your-guide-to-scanning-and-storing-age-old-photos/"><u>[Updated] In 2024, Reviving Rarities  Your Guide to Scanning and Storing Age-Old Photos</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-secrets-low-light-iphone-photography/"><u>[Updated] Unveiling Secrets  Low Light iPhone Photography</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-adopt-the-best-practices-of-live-streaming-with-google-meet-youtube/"><u>2024 Approved  Adopt the Best Practices of Live Streaming with Google Meet Youtube</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-directors-cut-assessment-video-editor-review/"><u>2024 Approved  Director's Cut Assessment – Video Editor Review</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-leading-5-digital-videography-devices/"><u>2024 Approved  Leading 5 Digital Videography Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/analyzing-ffmpegs-compatibility-with-original-soundscape-for-2024/"><u>Analyzing FFmpeg's Compatibility with Original Soundscape for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/code-39-mistakes-in-windows-explained-and-fixed-easily/"><u>Code 39 Mistakes in Windows Explained and Fixed Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/computer-boots-but-stays-dark-a-step-by-step-guide-to-fix-a-blank-monitor-issue/"><u>Computer Boots but Stays Dark: A Step-by-Step Guide to Fix a Blank Monitor Issue</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722899111866-connecting-apple-homepod-to-your-tv-a-comprehensive-tutorial/"><u>Connecting Apple HomePod to Your TV: A Comprehensive Tutorial</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-dacs-determining-if-a-digital-to-analog-converter-is-right-for-you/"><u>Demystifying DACs: Determining if a Digital-to-Analog Converter Is Right for You</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-strategies-to-address-and-mend-missing-dynamic-link-library-problems/"><u>Effective Strategies to Address and Mend Missing Dynamic Link Library Problems</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-text-chatting-with-these-tricks-for-your-ipad-user-interface/"><u>Effortless Text Chatting with These Tricks for Your iPad User Interface</u></a></li>
<li><a href="https://techtrends.techidaily.com/find-my-missing-email-address-with-these-easy-tips/"><u>Find My Missing Email Address with These Easy Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-novice-to-pro-advanced-tips-for-efficiently-snapping-photos-on-your-computer/"><u>From Novice to Pro: Advanced Tips for Efficiently Snapping Photos on Your Computer</u></a></li>
<li><a href="https://techtrends.techidaily.com/galaxy-unleashed-2023-probing-the-price-tag-and-launch-date-of-the-anticipated-samsung-galaxy-s25/"><u>Galaxy Unleashed 2023: Probing the Price Tag & Launch Date of the Anticipated Samsung Galaxy S25</u></a></li>
<li><a href="https://techtrends.techidaily.com/homegrown-hits-how-to-successfully-plan-and-throw-an-unforgettable-karaoke-evening-in/"><u>Homegrown Hits! How To Successfully Plan and Throw an Unforgettable Karaoke Evening In</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-safeguard-your-files-discover-the-five-best-ways-to-back-up-and-protect-your-data/"><u>How to Safeguard Your Files: Discover the Five Best Ways to Back Up and Protect Your Data</u></a></li>
<li><a href="https://techtrends.techidaily.com/instagram-tips-how-to-disable-suggested-user-profiles-and-posts/"><u>Instagram Tips: How to Disable Suggested User Profiles and Posts</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-art-of-ps4-gameplay-capture-a-beginners-guide/"><u>Master the Art of PS4 Gameplay Capture - A Beginner's Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-appointment-setup-with-apples-in-store-experts/"><u>Mastering Appointment Setup with Apple's In-Store Experts</u></a></li>
<li><a href="https://techtrends.techidaily.com/maximizing-savings-navigating-the-path-to-a-reduced-youtube-premium-plan-as-a-learner/"><u>Maximizing Savings: Navigating the Path to a Reduced YouTube Premium Plan as a Learner</u></a></li>
<li><a href="https://techtrends.techidaily.com/microsoft-disruptions-highlight-critical-risks-in-government-use-of-major-technology-providers/"><u>Microsoft Disruptions Highlight Critical Risks in Government Use of Major Technology Providers</u></a></li>
<li><a href="https://techtrends.techidaily.com/protect-your-system-with-these-15-free-pre-installed-antivirus-apps/"><u>Protect Your System with These 15 Free, Pre-Installed Antivirus Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-how-to-troubleshoot-and-correct-windows-code-28-errors/"><u>Step-by-Step Guide: How to Troubleshoot and Correct Windows Code 28 Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-for-microsoft-outlook-spelling-errors/"><u>Step-by-Step Solutions for Microsoft Outlook Spelling Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-gen-marvel-probing-into-the-price-availability-and-specs-of-the-samsung-galaxy-z-fold-7-through-current-industry-rumors/"><u>The Next-Gen Marvel: Probing Into the Price, Availability & Specs of the Samsung Galaxy Z Fold 7 Through Current Industry Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-how-to-guide-for-app-management-on-a-samsung-tv/"><u>The Ultimate How-To Guide for App Management on a Samsung TV</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-list-of-12-fantastic-free-keyboard-proficiency-lessons-for-people-of-all-ages/"><u>Ultimate List of 12 Fantastic FREE Keyboard Proficiency Lessons for People of All Ages</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-tutorial-linking-disneyplus-streams-effortlessly-to-your-chromecast-device/"><u>Ultimate Tutorial: Linking Disney+ Streams Effortlessly to Your Chromecast Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/watch-movies-on-the-go-find-your-match-with-our-list-of-12-free-streamers/"><u>Watch Movies on the Go: Find Your Match with Our List of 12 Free Streamers</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-expect-from-the-newly-announced-google-pixel-fold-2-price-release-dates-specifications-and-insider-gossip/"><u>What to Expect From the Newly Announced Google Pixel Fold 2: Price, Release Dates, Specifications & Insider Gossip</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-upgrade-for-thinkpad-install-new-drivers/"><u>Windows Upgrade for Thinkpad: Install New Drivers</u></a></li>
<li><a href="https://techtrends.techidaily.com/your-comprehensive-roadmap-to-finding-and-buying-a-home-entertainment-system/"><u>Your Comprehensive Roadmap to Finding and Buying a Home Entertainment System</u></a></li>
</ul></div>
