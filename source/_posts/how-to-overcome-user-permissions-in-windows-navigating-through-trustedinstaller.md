---
title: How to Overcome User Permissions in Windows Navigating Through TrustedInstaller
date: 2024-08-18T22:20:53.077Z
updated: 2024-08-19T22:20:53.077Z
categories:
  - BestProducts
description: This Article Describes How to Overcome User Permissions in Windows Navigating Through TrustedInstaller
excerpt: This Article Describes How to Overcome User Permissions in Windows Navigating Through TrustedInstaller
thumbnail: https://www.lifewire.com/thmb/bN_F8h8TKTX1N0seGbQ341fq0Y0=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-179036384-b081a08d421b4b6da954cac5b8461946.jpg
---

## How to Overcome User Permissions in Windows Navigating Through TrustedInstaller
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-easily-erase-identity-blurring-techniques-in-videos/"><u>[New] 2024 Approved  Easily Erase Identity  Blurring Techniques in Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-boosting-your-contents-impact-on-instagram-for-2024/"><u>[New] Boosting Your Content's Impact on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-essential-android-ad-blocking-the-top-7-app-list-for-2024/"><u>[New] Essential Android Ad Blocking  The Top 7 App List for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-step-up-your-film-game-on-instagram-with-border-tips/"><u>[New] In 2024, Step up Your Film Game on Instagram with Border Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-art-of-screenshots-vertical-video-editing-in-fcpx-for-2024/"><u>[New] The Art of Screenshots  Vertical Video Editing in FCPX for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-adding-depth-with-3d-text-in-photoshop-workflows/"><u>[Updated] Adding Depth with 3D Text in Photoshop Workflows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-explore-the-ultimate-list-of-comedy-tears-on-instagram/"><u>[Updated] Explore the Ultimate List of Comedy-Tears On Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harness-the-power-of-iphones-shutter-speed-for-motion-blurs/"><u>[Updated] Harness the Power of iPhone’s Shutter Speed for Motion Blurs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-boosting-social-reach-share-tiktoks-with-a-twist-of-twitter/"><u>[Updated] In 2024, Boosting Social Reach  Share TikToks with a Twist of Twitter</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-simplified-steps-for-crafting-professional-srt-files/"><u>[Updated] Simplified Steps for Crafting Professional SRT Files</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-the-comprehensive-guide-to-top-8-collaborative-video-collage-tools-android-for-2024/"><u>[Updated] The Comprehensive Guide to Top 8 Collaborative Video Collage Tools (Android) for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-top-10-tools-to-perfect-your-igtv-edits-for-2024/"><u>[Updated] Top 10 Tools to Perfect Your IGTV Edits for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/10-free-netflix-alternatives-to-try/"><u>10 Free Netflix Alternatives to Try</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-silent-insights-into-improving-visual-elements/"><u>2024 Approved  Silent Insights Into Improving Visual Elements</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essentials-comprehensive-editing-tutorial/"><u>2024 Approved  The Essentials  Comprehensive Editing Tutorial</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722876016475-aol-mail-issues-determining-whether-its-a-downtime-scenario-or-personal-connectivity-problem/"><u>AOL Mail Issues: Determining Whether It's a Downtime Scenario or Personal Connectivity Problem</u></a></li>
<li><a href="https://techtrends.techidaily.com/are-others-facing-nintendo-switch-online-disruption-too-or-is-it-an-individual-glitch/"><u>Are Others Facing Nintendo Switch Online Disruption Too, or Is It an Individual Glitch?</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-free-entertainment-platforms-similar-to-netflix-top-10-picks/"><u>Best Free Entertainment Platforms Similar to Netflix (Top 10 Picks)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-samsung-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Samsung .</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-maisto-rock-crawler-rc-car-evaluation-ideal-choice-for-the-whole-family/"><u>Comprehensive Maisto Rock Crawler RC Car Evaluation - Ideal Choice for the Whole Family</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-4-free-web-based-calendar-tools-available-today/"><u>Discover the Best 4 Free Web-Based Calendar Tools Available Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-sites-to-view-free-music-videos-on-your-computer-or-phone/"><u>Discover the Best Sites to View Free Music Videos on Your Computer or Phone</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-techniques-for-inserting-text-based-programming-into-microsoft-word/"><u>Effortless Techniques for Inserting Text-Based Programming Into Microsoft Word</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-advice-resolving-launchdll-cannot-be-found-problems-quickly-and-effectively/"><u>Expert Advice: Resolving 'Launch.dll Cannot Be Found' Problems Quickly and Effectively</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Poco C55 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-atandt-apple-iphone-15-plus-with-3-methods-by-drfone-ios/"><u>How to Unlock AT&T Apple iPhone 15 Plus with 3 Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-oppo-reno-11f-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Oppo Reno 11F 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-itel-p55t-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Itel P55T Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/learn-how-to-mirror-your-smartphone-or-tablet-onto-an-lg-tv-easily/"><u>Learn How to Mirror Your Smartphone or Tablet Onto an LG TV Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/maximizing-smartphone-snaps-guide-for-ios-devices/"><u>Maximizing Smartphone Snaps: Guide for iOS Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/pros-and-cons-making-the-right-choice-on-blu-ray-players/"><u>Pros and Cons: Making the Right Choice on Blu-Ray Players</u></a></li>
<li><a href="https://techtrends.techidaily.com/quick-fixes-to-correct-microsoft-visual-cplusplus-redistributable-missing-errors/"><u>Quick Fixes to Correct Microsoft Visual C++ Redistributable Missing Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/recovering-your-deactivated-instagram-presence-effective-strategies-and-solutions/"><u>Recovering Your Deactivated Instagram Presence: Effective Strategies and Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolve-shaky-and-fluttering-screens-on-surface-pro-expert-tips/"><u>Resolve Shaky and Fluttering Screens on Surface Pro - Expert Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/simplify-your-routine-explore-these-top-7-alarm-clock-app-recommendations/"><u>Simplify Your Routine: Explore These Top 7 Alarm Clock App Recommendations</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-javascript-file-jsksriptdll-absence-issues/"><u>Solving JavaScript File 'jsksript.dll' Absence Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-indicating-emails-have-been-read-in-googles-mail-service/"><u>Step-by-Step: Indicating Emails Have Been Read in Google's Mail Service</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ise-guide-to-transform-youtube-clips-into-animated-gifs/"><u>Stepwise Guide to Transform Youtube Clips Into Animated GIFs</u></a></li>
<li><a href="https://techtrends.techidaily.com/streamline-your-chaotic-life-with-these-7-essential-shared-calendar-solutions-for-families/"><u>Streamline Your Chaotic Life with These 7 Essential Shared Calendar Solutions for Families</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fix-getting-your-surface-pro-reconnected-to-wi-fi/"><u>The Ultimate Fix: Getting Your Surface Pro Reconnected to Wi-Fi</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-review-for-mohu-blade-tv-antenna-outstanding-aesthetics-and-robust-indoor-coverage/"><u>The Ultimate Review for Mohu Blade TV Antenna: Outstanding Aesthetics and Robust Indoor Coverage</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-to-buying-durable-and-watertight-phone-covers/"><u>Ultimate Guide to Buying Durable and Watertight Phone Covers</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-unleashing-power-saving-hacks-on-apples-shortcuts-app-top-18/"><u>Ultimate Guide: Unleashing Power-Saving Hacks on Apple's Shortcuts App (Top 18)</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-roku-express-and-stick-key-contrasts-explored/"><u>Unveiling Roku Express and Stick: Key Contrasts Explored</u></a></li>
<li><a href="https://techtrends.techidaily.com/wireless-entertainment-setting-up-amazon-firestick-with-a-home-theater-projector/"><u>Wireless Entertainment: Setting up Amazon Firestick with a Home Theater Projector</u></a></li>
</ul></div>
