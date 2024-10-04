---
title: How To Effortlessly Transfer Your Digital Memories From Google to iCloud
date: 2024-09-29T16:55:28.111Z
updated: 2024-10-04T16:19:48.591Z
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
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-discovering-the-quintessential-25-influence-kings-and-queens/"><u>[New] 2024 Approved Discovering The Quintessential 25 Influence Kings and Queens</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-steps-for-effective-ipad-screen-casts/"><u>[Updated] In 2024, Steps for Effective iPad Screen Casts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-capturing-perfection-the-top-review-of-screensnapper-2023/"><u>2024 Approved Capturing Perfection The Top Review of 'ScreenSnapper' 2023</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streaming-high-quality-vr-videos-made-easy-for-ios-users/"><u>2024 Approved Streaming High-Quality VR Videos Made Easy for IOS Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-comprehensive-guide-to-aols-famous-im-service-unveiling-the-secrets-of-aim/"><u>A Comprehensive Guide to AOL's Famous IM Service: Unveiling the Secrets of AIM</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/a-comprehensive-tutorial-on-completely-formatting-an-iphone-via-pc-or-mac/"><u>A Comprehensive Tutorial on Completely Formatting an iPhone via PC or Mac</u></a></li>
<li><a href="https://techtrends.techidaily.com/cleaning-the-insertion-site-with-soap-and-water-is-done-to-prevent-infection-but-its-not-specific-for-catheter-irrigation/"><u>Cleaning the Insertion Site with Soap and Water Is Done to Prevent Infection, but It's Not Specific for Catheter Irrigation</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-your-instagram-interactions-commenting-with-eye-catching-gifs/"><u>Enhance Your Instagram Interactions: Commenting With Eye-Catching GIFs</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-get-a-dell-student-discount/"><u>How to Get a Dell Student Discount</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-unlock-the-power-of-dvd-creation-a-beginners-guide-to-movie-making-software/"><u>New 2024 Approved Unlock the Power of DVD Creation A Beginners Guide to Movie Making Software</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-opengl32dll-missing-error-on-your-computer-a-step-by-step-guide/"><u>Resolving OpenGL32.dll Missing Error on Your Computer: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-detecting-phony-social-network-outreaches/"><u>The Ultimate Guide: Detecting Phony Social Network Outreaches</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-5-remedies-to-resolve-your-ipads-onoff-malfunction-issues/"><u>Top 5 Remedies to Resolve Your iPad’s On/Off Malfunction Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unleash-your-twitter-potential-premium-video-upload-tools/"><u>Unleash Your Twitter Potential Premium Video Upload Tools</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-make-it-a-valentines-day-to-remember-diy-video-ideas-for-your-loved-one/"><u>Updated 2024 Approved Make It a Valentines Day to Remember DIY Video Ideas for Your Loved One</u></a></li>
</ul></div>

