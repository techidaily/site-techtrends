---
title: How To Effortlessly Transfer Your Digital Memories From Google to iCloud
date: 2024-09-22T00:26:15.653Z
updated: 2024-09-29T01:15:59.384Z
categories:
  - BestProducts
description: This Article Describes How To Effortlessly Transfer Your Digital Memories From Google to iCloud
excerpt: This Article Describes How To Effortlessly Transfer Your Digital Memories From Google to iCloud
thumbnail: https://www.lifewire.com/thmb/MouYC1WUMGTGZIOgQIjlDmG37sA=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/apple-icloud-photos-da26bb8f7f6c40ac9b4ec77af5a807d0.png
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

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
<li><a href="https://some-guidance.techidaily.com/updated-mosaicmaker-elite-designing-with-digital-threads/"><u>[Updated] MosaicMaker Elite Designing with Digital Threads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-tecno-spark-go-2024-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Tecno Spark Go (2024) Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/amp-up-your-ig-videos-crafting-winning-marketing-tactics/"><u>Amp Up Your IG Videos Crafting Winning Marketing Tactics</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-list-of-10-premium-free-email-accounts/"><u>Discover the Ultimate List of 10 Premium Free Email Accounts</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-masterful-zoom-techniques-simple-iphone-solutions/"><u>In 2024, Masterful Zoom Techniques Simple iPhone Solutions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-saving-gameplay-moments-for-the-web/"><u>In 2024, Saving Gameplay Moments for the Web</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on Apple iPhone 15 Pro</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/indispensable-twitch-streaming-solutions-the-ultimate-top-5-picks-for-content-creators/"><u>Indispensable Twitch Streaming Solutions: The Ultimate Top 5 Picks for Content Creators</u></a></li>
<li><a href="https://techtrends.techidaily.com/method-for-integrating-bots-with-your-discord-server-configuration/"><u>Method for Integrating Bots with Your Discord Server Configuration</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-the-5-most-popular-iphone-navigation-apps/"><u>The Ultimate Guide to the 5 Most Popular iPhone Navigation Apps</u></a></li>
<li><a href="https://techtrends.techidaily.com/time-update-tutorial-setting-correct-hours-and-date-on-amazon-kindle-paperwhite/"><u>Time Update Tutorial: Setting Correct Hours & Date on Amazon Kindle Paperwhite</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-universal-convenience-expert-tips-on-creating-customizable-remote-control-software/"><u>Unlocking Universal Convenience: Expert Tips on Creating Customizable Remote Control Software</u></a></li>
<li><a href="https://techtrends.techidaily.com/upcoming-samsung-event-in-202date-range-insights-forecasts-and-exciting-developments-awaiting-reveal/"><u>Upcoming Samsung Event in 202([Date Range]): Insights, Forecasts & Exciting Developments Awaiting Reveal</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-s-top-rated-free-flv-video-editing-tools/"><u>Updated S Top-Rated Free FLV Video Editing Tools</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-do-if-microsoft-outlooks-spelling-correction-wont-work/"><u>What to Do If Microsoft Outlook's Spelling Correction Won't Work</u></a></li>
</ul></div>

