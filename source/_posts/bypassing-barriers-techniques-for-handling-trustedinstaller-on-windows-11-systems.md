---
title: "Bypassing Barriers: Techniques for Handling TrustedInstaller on Windows 11 Systems"
date: 2024-08-18T21:39:09.305Z
updated: 2024-08-19T21:39:09.305Z
categories:
  - BestProducts
description: "This Article Describes Bypassing Barriers: Techniques for Handling TrustedInstaller on Windows 11 Systems"
excerpt: "This Article Describes Bypassing Barriers: Techniques for Handling TrustedInstaller on Windows 11 Systems"
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Bypassing Barriers: Techniques for Handling TrustedInstaller on Windows 11 Systems
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

## Why Do I Need Permission From TrustedInstaller?

 Provided you're the primary user of your home computer, you might be surprised to find out you need anyone’s permission to deal with files on your own PC.

 All Windows 10 PCs have an in-built Microsoft account known as the TrustedInstaller. This account exists to prevent accidental damage to important system files, so it's given ownership over many important operating system files. For you to be able to take control of these files, you need to make yourself the owner as described above.  

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-from-silent-videos-to-engaging-content-swiftly-add-captions-on-fb/"><u>[New] 2024 Approved  From Silent Videos to Engaging Content  Swiftly Add Captions on FB</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-comparing-sharex-with-industry-leaders/"><u>[New] Comparing ShareX with Industry Leaders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-explaining-instagrams-inverted-video-effect/"><u>[New] Explaining Instagram’s Inverted Video Effect</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-revolutionize-your-photos-with-these-best-grid-makers-for-ig/"><u>[New] In 2024, Revolutionize Your Photos with These Best Grid Makers for IG</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-mastering-digital-vaults-best-cloud-platforms-for-future-success/"><u>[New] Mastering Digital Vaults  Best Cloud Platforms for Future Success</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-navigating-video-uploads-on-social-platforms-for-2024/"><u>[New] Navigating Video Uploads on Social Platforms for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-boosting-your-instagram-aesthetics-implementing-borders-on-photos/"><u>[Updated] Boosting Your Instagram Aesthetics  Implementing Borders on Photos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-an-all-inclusive-guide-to-initiate-multiplatform-communication-via-skype-groups/"><u>[Updated] In 2024, An All-Inclusive Guide to Initiate Multiplatform Communication via Skype Groups</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-cubic-cottages-for-newcomers-to-mc-world/"><u>[Updated] In 2024, Cubic Cottages for Newcomers to MC World</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-cease-playback-failures-fix-facebook-videos/"><u>2024 Approved  Cease Playback Failures - Fix Facebook Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-constructing-unique-instagram-post-images/"><u>2024 Approved  Constructing Unique Instagram Post Images</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-niche-networking-on-youtube-from-phone-small-scale-approach/"><u>2024 Approved  Niche Networking on Youtube From Phone, Small-Scale Approach</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-proven-ways-to-unlock-tecno-spark-20-proplus-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Tecno Spark 20 Pro+ Phone When You Forget the Password</u></a></li>
<li><a href="https://techtrends.techidaily.com/avoiding-spam-how-to-set-up-a-domain-safelist-for-your-email-on-mac-os-x/"><u>Avoiding Spam: How to Set Up a Domain Safelist for Your Email on Mac OS X</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-transferring-documents-from-your-printer-to-pc/"><u>Easy Steps: Transferring Documents From Your Printer to PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-troubleshooting-for-linking-your-computer-with-a-logitech-mouse/"><u>Easy Troubleshooting for Linking Your Computer with a Logitech Mouse</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-a-breath-of-fresh-air-in-your-pc-the-alluring-floral-note-of-new-thermal-gel/"><u>Experience a Breath of Fresh Air in Your PC: The Alluring Floral Note of New Thermal Gel</u></a></li>
<li><a href="https://techtrends.techidaily.com/explore-these-8-fantastic-no-cost-html-editors-available-for-windows/"><u>Explore These 8 Fantastic No-Cost HTML Editors Available for Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/from-zero-to-hero-how-to-successfully-boot-windows-11-on-a-newly-installed-drive/"><u>From Zero to Hero: How to Successfully Boot Windows 11 on a Newly Installed Drive</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722892057082-guide-unlocking-windows-pin-protection-in-windows-10/"><u>Guide: Unlocking Windows ‛Pin Protection' In Windows 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-code-39-errors-in-windows/"><u>How to Fix Code 39 Errors in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-repair-vcompdll-cannot-be-found-errors-comprehensive-fixes-for-windows-users/"><u>How to Repair 'vcomp.dll Cannot Be Found' Errors: Comprehensive Fixes for Windows Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-send-and-receive-faxes-for-free-with-these-services/"><u>How to Send & Receive Faxes for Free with These Services</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-turn-network-sharing-onoff-in-windows-10-your-ultimate-guide/"><u>How to Turn Network Sharing On/Off in Windows 10 - Your Ultimate Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-14-effective-methods-zero-budget-webinar-recording-tips/"><u>In 2024, 14 Effective Methods  Zero Budget Webinar Recording Tips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-future-of-storage-cutting-edge-cost-effective-solutions/"><u>In 2024, Future of Storage  Cutting-Edge, Cost-Effective Solutions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-make-content-stand-out-the-ultimate-guide-to-youtube-responses/"><u>In 2024, Make Content Stand Out  The Ultimate Guide to YouTube Responses</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-art-of-perfect-selfies-a-guide-to-using-selfie-lights-effectively/"><u>Mastering the Art of Perfect Selfies: A Guide to Using Selfie Lights Effectively</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-how-to-add-and-modify-audio-keyframes-in-final-cut-pro-x-for-2024/"><u>New How to Add and Modify Audio Keyframes in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/order-of-adventure-arranging-the-how-to-train-your-dragon-films-correctly/"><u>Order of Adventure: Arranging the How to Train Your Dragon Films Correctly</u></a></li>
<li><a href="https://techtrends.techidaily.com/protecting-your-tech-investment-how-waterproof-is-the-iphone-15-pro-max-really/"><u>Protecting Your Tech Investment: How Waterproof Is the iPhone 15 Pro Max Really?</u></a></li>
<li><a href="https://techtrends.techidaily.com/spotlight-on-sonys-afela-decoding-expected-price-points-release-dates-and-rumored-vehicle-capabilities/"><u>Spotlight on Sony's AFELA: Decoding Expected Price Points, Release Dates & Rumored Vehicle Capabilities</u></a></li>
<li><a href="https://techtrends.techidaily.com/star-wars-movie-marathon-order-a-step-by-step-guide-for-disney-plus-subscribers/"><u>Star Wars Movie Marathon Order: A Step-by-Step Guide for Disney Plus Subscribers</u></a></li>
<li><a href="https://facebook.techidaily.com/steer-clear-of-others-in-fb-on-this-day-feature/"><u>Steer Clear of Others in FB On This Day Feature</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-capturing-your-screen-on-windowsmac/"><u>Step-by-Step Guide: Capturing Your Screen on Windows/Mac</u></a></li>
<li><a href="https://buynow-info.techidaily.com/step-by-step-guide-saving-images-from-your-microsoft-word-presentations/"><u>Step-by-Step Guide: Saving Images From Your Microsoft Word Presentations</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-solutions-for-iphone-screen-sharing-glitches/"><u>Step-by-Step Solutions for iPhone Screen Sharing Glitches</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-strategies-for-choosing-all-correspondence-on-googles-mail-service/"><u>Step-by-Step Strategies for Choosing All Correspondence on Google's Mail Service</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tips-for-reconnecting-your-ipad-to-wi-fi-networks/"><u>Step-by-Step Tips for Reconnecting Your iPad to Wi-Fi Networks</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-lowdown-on-the-latest-leaks-for-oculus-quest-3-lite-specs-pricing-and-release-schedule-uncovered/"><u>The Lowdown on the Latest Leaks for Oculus Quest 3 Lite – Specs, Pricing, and Release Schedule Uncovered!</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-picking-your-ideal-motherboard-7-key-points/"><u>The Ultimate Guide to Picking Your Ideal Motherboard - 7 Key Points</u></a></li>
<li><a href="https://techtrends.techidaily.com/uncover-hidden-history-retrieving-erased-phone-numbers-from-android-phones/"><u>Uncover Hidden History: Retrieving Erased Phone Numbers From Android Phones</u></a></li>
<li><a href="https://techtrends.techidaily.com/understanding-memes-an-introductory-guide/"><u>Understanding Memes: An Introductory Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/windows-11-users-manual-how-to-hide-or-remove-the-news-and-interests-panel/"><u>Windows 11 User's Manual: How to Hide or Remove the News and Interests Panel</u></a></li>
</ul></div>
