---
title: Effortless Mac Multi-Monitor Configuration Techniques
date: 2024-08-30T15:22:03.083Z
updated: 2024-08-31T15:22:03.083Z
categories:
  - BestProducts
description: This Article Describes Effortless Mac Multi-Monitor Configuration Techniques
excerpt: This Article Describes Effortless Mac Multi-Monitor Configuration Techniques
thumbnail: https://www.lifewire.com/thmb/SFDykkrgMWww5ACWNZgMftXl0WE=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/hero-44ba4dd7731143f4b7ba6398ab667dcb.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-expedient-techniques-to-spot-and-expel-deceptive-insta-connections/"><u>[New] Expedient Techniques to Spot and Expel Deceptive Insta Connections</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-transform-gameplay-into-a-masterpiece-using-fbx/"><u>[New] In 2024, Transform Gameplay Into a Masterpiece Using FBX</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-disconnect-on-snapchat-are-they-blocked/"><u>[New] The Disconnect on Snapchat  Are They Blocked?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-the-clear-choice-between-projectors-and-televisions-for-4k-quality/"><u>[Updated] 2024 Approved  The Clear Choice Between Projectors and Televisions for 4K Quality</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-complete-overview-of-full-scene-in-ppro/"><u>2024 Approved  Complete Overview of Full Scene in PPro</u></a></li>
<li><a href="https://techtrends.techidaily.com/8-ways-to-fix-the-parse-error-on-android/"><u>8 Ways to Fix the Parse Error on Android</u></a></li>
<li><a href="https://techtrends.techidaily.com/all-you-need-to-know-about-the-new-samsung-z-fold-4-availability-price-range-and-specs-revealed/"><u>All You Need to Know About the New Samsung Z Fold 4 - Availability, Price Range, and Specs Revealed</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/college-life-made-easier-with-youtube-premium-tips-for-students-seeking-a-discounted-subscription/"><u>College Life Made Easier with YouTube Premium: Tips for Students Seeking a Discounted Subscription</u></a></li>
<li><a href="https://techtrends.techidaily.com/complete-tutorial-on-how-to-take-off-and-switch-phone-screen-guard/"><u>Complete Tutorial on How to Take Off and Switch Phone Screen Guard</u></a></li>
<li><a href="https://techtrends.techidaily.com/deciphering-the-clues-of-opened-messages-a-comprehensive-tutorial-for-gmail-users/"><u>Deciphering the Clues of Opened Messages - A Comprehensive Tutorial for Gmail Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-techniques-for-leveraging-the-measure-app-on-your-android-device/"><u>Effective Techniques for Leveraging the Measure App on Your Android Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-tips-for-adding-captions-and-text-in-microsoft-photos-app/"><u>Essential Tips for Adding Captions & Text in Microsoft Photos App</u></a></li>
<li><a href="https://techtrends.techidaily.com/experiencing-issues-with-nintendo-switch-online-service-outage-or-connection-problem/"><u>Experiencing Issues with Nintendo Switch Online - Service Outage or Connection Problem?</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-for-handling-errors-what-to-do-when-you-cant-find-d3dx924dll/"><u>Expert Tips for Handling Errors: What To Do When You Can't Find d3dx9_24.dll</u></a></li>
<li><a href="https://techtrends.techidaily.com/fix-askew-screen-issues-a-step-by-step-approach-for-clear-computer-monitors/"><u>Fix Askew Screen Issues: A Step-by-Step Approach for Clear Computer Monitors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-it-common-issues-and-fixes-for-non-working-arrow-key-functionality/"><u>Fixed It! Common Issues and Fixes for Non-Working Arrow Key Functionality</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-infinix-hot-40i-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Infinix Hot 40i Pattern Lock Screen</u></a></li>
<li><a href="https://techtrends.techidaily.com/global-audience-picks-top-10-most-visited-sites-online/"><u>Global Audience Picks: Top 10 Most Visited Sites Online</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-activating-your-new-echo-dot-by-placing-it-into-pairing-mode/"><u>Guide: Activating Your New Echo Dot by Placing It Into Pairing Mode</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-mirror-your-windows-pc-display-to-a-tv-using-chromecast-technology/"><u>How to Mirror Your Windows PC Display to a TV Using Chromecast Technology</u></a></li>
<li><a href="https://techtrends.techidaily.com/illuminate-the-darkness-restoring-visibility-in-windows-11-system-issues/"><u>Illuminate the Darkness: Restoring Visibility in Windows 11 System Issues</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-building-a-strong-online-presence-with-attractive-video-thumbnails/"><u>In 2024, Building a Strong Online Presence with Attractive Video Thumbnails</u></a></li>
<li><a href="https://techtrends.techidaily.com/join-forces-in-melody-the-ultimate-way-to-share-your-favorite-songs-on-spotify-with-friends/"><u>Join Forces in Melody: The Ultimate Way to Share Your Favorite Songs on Spotify With Friends</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/merry-media-archive-inspector/"><u>Merry Media Archive Inspector</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-through-the-history-of-ipados-updates-and-features/"><u>Navigating Through the History of iPadOS Updates and Features</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-effortless-video-editing-how-to-add-effects-in-fcp-x-in-3-steps-for-2024/"><u>New Effortless Video Editing How to Add Effects in FCP X in 3 Steps for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-issues-with-non-responsive-mozilla-thunderbird-application/"><u>Resolving Issues with Non-Responsive Mozilla Thunderbird Application</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-the-issue-a-step-by-step-guide-to-solving-error-code-0x80004005/"><u>Resolving the Issue: A Step-by-Step Guide to Solving Error Code 0X80004005</u></a></li>
<li><a href="https://techtrends.techidaily.com/secure-your-network-the-official-july-2024-list-of-linksys-default-passwords-exposed/"><u>Secure Your Network: The Official July 2024 List of Linksys Default Passwords Exposed</u></a></li>
<li><a href="https://techtrends.techidaily.com/smart-shopping-navigating-through-the-latest-tech-trends-for-students-laptops/"><u>Smart Shopping: Navigating Through the Latest Tech Trends for Students' Laptops</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-to-fix-mfc42dll-errors-and-notifications/"><u>Step-by-Step Guide to Fix 'mfc42.dll' Errors and Notifications</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-updating-your-ch3-ch340g-serial-converters-drivers-on-microsofts-modern-operating-system/"><u>Step-by-Step Guide: Updating Your CH3지터글 (CH340G) Serial Converter's Drivers on Microsoft's Modern Operating System</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-for-the-zlibdll-not-detected-problem/"><u>Step-by-Step Solutions for the 'zlib.dll Not Detected' Problem</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tips-on-viewing-spider-man-no-way-home-through-streaming-services/"><u>Step-by-Step Tips on Viewing 'Spider Man: No Way Home' Through Streaming Services</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-for-enabling-second-screen-display-on-lg-television-models/"><u>Step-by-Step Tutorial for Enabling Second Screen Display on LG Television Models</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-on-securing-and-implementing-new-ios-enhancements/"><u>Step-by-Step Tutorial on Securing & Implementing New iOS Enhancements</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/successfully-overcoming-device-driver-hurdles-on-windows-7-8-and-tenth-with-startech/"><u>Successfully Overcoming Device Driver Hurdles on Windows 7, 8 & Tenth with StarTech</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-future-of-smartphones-inside-scoop-on-teslas-anticipated-release-cost-estimates-and-tech-specs-rumors/"><u>The Future of Smartphones: Inside Scoop on Tesla's Anticipated Release, Cost Estimates, and Tech Specs Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-picks-enjoy-family-friendly-films-on-disneyplus-this-july/"><u>Top Picks: Enjoy Family-Friendly Films on Disney+ This July</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-to-repair-non-ejecting-cd-dvd-and-blu-ray-drives/"><u>Troubleshooting Steps to Repair Non-Ejecting CD, DVD & Blu-Ray Drives</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-achieving-instagram-verification-status/"><u>Ultimate Guide: Achieving Instagram Verification Status</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-steps-to-securely-update-your-fb-password/"><u>Ultimate Guide: Steps to Securely Update Your FB Password</u></a></li>
<li><a href="https://techtrends.techidaily.com/unleashing-ais-potency-pioneering-profound-global-change/"><u>Unleashing AI’s Potency: Pioneering Profound Global Change</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-the-power-of-emojis-on-your-iphone-tips-and-tricks/"><u>Unlocking the Power of Emojis on Your iPhone - Tips & Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-apples-macos-timeline-a-full-breakdown/"><u>Unveiling Apple's macOS Timeline: A Full Breakdown</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-distinctions-mac-vs-pc-a-comprehensive-guide/"><u>Unveiling the Distinctions: Mac Vs. PC – A Comprehensive Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/watching-netflix-content-a-complete-guide-for-nintendo-switch-users/"><u>Watching Netflix Content – A Complete Guide for Nintendo Switch Users</u></a></li>
</ul></div>
