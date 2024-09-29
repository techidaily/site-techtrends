---
title: "Mac Users Rejoice: How to Reset Your DNS Records Effortlessly"
date: 2024-09-23T01:29:39.809Z
updated: 2024-09-29T03:32:37.506Z
categories:
  - BestProducts
description: "This Article Describes Mac Users Rejoice: How to Reset Your DNS Records Effortlessly"
excerpt: "This Article Describes Mac Users Rejoice: How to Reset Your DNS Records Effortlessly"
thumbnail: https://thmb.techidaily.com/8504b42a17782fb4587372cf2843bf5e6800b5714b57f9dcc9e3ed9d00739ee5.jpg
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

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-demystifying-complexities-a-guide-to-understanding-slug-lines/"><u>[New] 2024 Approved Demystifying Complexities A Guide to Understanding Slug Lines</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-navigating-vimeos-share-options/"><u>[New] In 2024, Navigating Vimeo's Share Options</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-navigating-vimeos-subscription-options-for-content-creators/"><u>[New] In 2024, Navigating Vimeo’s Subscription Options for Content Creators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-techniques-for-enhancing-film-scenes-with-focus/"><u>[New] Techniques for Enhancing Film Scenes with Focus</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-picks-for-personalizing-mbp-screens-with-skins-for-2024/"><u>[New] Top Picks for Personalizing MBP Screens with Skins for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-step-by-step-laptop-screenrecord-guide/"><u>[Updated] In 2024, Step-by-Step Laptop ScreenRecord Guide</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-the-fun-unlocking-gaming-experiences-right-on-your-youtube/"><u>Discover the Fun: Unlocking Gaming Experiences Right on Your YouTube!</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-step-by-step-tutorial-to-get-your-epson-et-4550-driver-running-on-a-pc-with-windows-os/"><u>Easy Step-by-Step Tutorial to Get Your Epson ET-4550 Driver Running on a PC with Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-to-establish-your-virtual-space-oculus-questquest-2-registration/"><u>Easy Steps to Establish Your Virtual Space: Oculus Quest/Quest 2 Registration</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x100-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Vivo X100 Phone without Any Data Loss</u></a></li>
<li><a href="https://techtrends.techidaily.com/ios-18-unveiled-launch-dates-zero-cost-new-capabilities-and-latest-updates/"><u>IOS 18 Unveiled: Launch Dates, Zero Cost, New Capabilities & Latest Updates</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-ai-from-home-expertly-curated-list-of-15-self-guided-cost-free-courses/"><u>Mastering AI From Home: Expertly Curated List of 15 Self-Guided, Cost-Free Courses</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-recovery-effective-strategies-to-correct-a-504-timeout-error/"><u>Mastering Recovery: Effective Strategies to Correct a 504 Timeout Error</u></a></li>
<li><a href="https://techtrends.techidaily.com/solution-strategies-for-eliminating-straight-line-distortions-on-desktop-displays/"><u>Solution Strategies for Eliminating Straight Line Distortions on Desktop Displays</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-uploading-multiple-photos-together-on-facebook/"><u>The Ultimate Guide to Uploading Multiple Photos Together on Facebook</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-the-secrets-to-reactivating-your-inactive-snapchat-id-a-comprehensive-walkthrough/"><u>Unlock the Secrets to Reactivating Your Inactive Snapchat ID – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://techtrends.techidaily.com/wwdc-2025-insights-apples-latest-innovations-revealed/"><u>WWDC 2025 Insights: Apple's Latest Innovations Revealed</u></a></li>
</ul></div>

