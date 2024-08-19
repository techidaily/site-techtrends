---
title: Step-by-Step Strategies to Recover Deleted Numbers From Your Android Phonebook
date: 2024-08-18T22:39:46.669Z
updated: 2024-08-19T22:39:46.669Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Strategies to Recover Deleted Numbers From Your Android Phonebook
excerpt: This Article Describes Step-by-Step Strategies to Recover Deleted Numbers From Your Android Phonebook
thumbnail: https://www.lifewire.com/thmb/RdBqp1VTk4RYHgWZoDTdfij4BFI=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/android-app-icons-torsten-dettlaff-9b4e2ff50cc44e09aadacf3079b39376.jpg
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

## How to Fix Error Code 0x80004005

 Follow these steps in the order presented to troubleshoot error code 0x80004005:

1. [Run the Windows Update troubleshooter](https://support.microsoft.com/help/4027322/windows-update-troubleshooter) . The error can happen when an automatic Windows Update fails, or when files downloaded by Windows Update are corrupted. On Windows 7 or later, the easiest[way to fix problems with Windows updates](https://www.lifewire.com/how-to-fix-problems-caused-by-windows-updates-2625775) is to run the built-in automatic troubleshooter.
2. Delete everything in the Windows Update download folder. If the automatic troubleshooter does not fix the problem, open Windows[File Explorer](https://www.lifewire.com/what-is-a-file-manager-4589189) and navigate to**C:\\Windows\\SoftwareDistribution** , for Windows 11 or**C:\\Windows\\SoftwareDistribution\\Download** for earlier Windows versions, then delete everything inside the folder.
3. [Run Windows Update](https://www.lifewire.com/how-to-check-for-install-windows-updates-2624596) . If the problem is related to Windows Update, you may have to finish downloading and installing updates. After running the troubleshooter and manually deleting the files in the Windows Update folder, run Windows Update again.
4. [Delete temporary files](https://www.lifewire.com/how-to-delete-temporary-files-in-windows-2624709) . In some cases, a corrupt temporary file can cause error 0x80004005\. Use the Windows Disk Cleanup tool or type**%temp%** in the Windows search bar to find the**Temp** folder and delete everything inside it.
5. [Disable Outlook mail notifications](https://www.lifewire.com/configure-outlook-email-notifications-1173647) . The error code can occur when[Microsoft Outlook](https://www.lifewire.com/microsoft-outlook-4164620) attempts to notify you of new messages. If disabling this feature fixes the problem, then try[starting Outlook in Safe Mode](https://www.lifewire.com/outlook-safe-mode-4164302) . If that works, a simple re-install might fix your problem.
6. [Disable Windows Defender](https://www.lifewire.com/turn-off-windows-defender-4165378) . In some cases,[antivirus](https://www.lifewire.com/what-is-antivirus-software-152947) software can detect a false positive in connection with the Microsoft Outlook app. If you experience error code 0x80004005 when using Microsoft Outlook, and disabling notifications did not help, turning off antivirus software may fix the problem. Also,[disable Norton Antivirus](https://www.lifewire.com/disable-norton-antivirus-4589389) and other third-party antivirus programs you use.  
 Disabling antivirus software leaves the system vulnerable to malware. Try different[free antivirus programs](https://www.lifewire.com/best-free-antivirus-software-4151895) to find one that doesn't conflict with the applications you use.
7. [Use a different unzip program](https://www.lifewire.com/free-unzip-programs-1356643) . If you see the error code when extracting or opening compressed files (like[.zip](https://www.lifewire.com/zip-file-2622675) or[.rar](https://www.lifewire.com/rar-file-2622216) files), use a different extraction tool.
8. Re-register jdscript.dll and vbscript.dll. If you still see error 0x80004005 after trying to unzip files with other extraction tools, then re-registering these two[dynamic link libraries](https://www.lifewire.com/what-is-a-dll-file-2625852) (DLLs) may help.  
[Open the Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) as an administrator, type**regsvr32 jscript.dll** , then press the**Enter** key. Then, type**regsvr32 vbscript.dll** and press**Enter** .
9. [Add a key to the Windows Registry](https://www.lifewire.com/how-to-add-change-delete-registry-keys-values-2625145) . If you suspect error 0x80004005 in conjunction with copying or moving files,[open the Windows Registry Editor](https://www.lifewire.com/how-to-open-registry-editor-2625150) and go to **HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** .  
   * On a[32-bit](https://www.lifewire.com/32-bit-64-bit-2624554) system, create a new**DWORD** [registry value](https://www.lifewire.com/what-is-a-registry-value-2626042) called**LocalAccountTokenFilterPolicy** .  
   * On a 64-bit system, create a**QWORD** registry value called**LocalAccountTokenFilterPolicy** .  
 In both cases, set the value to**numeric 1** (on), then select**OK** . After that,[restart the Windows PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see if the problem is fixed.  
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.
10. Contact support. If none of these fixes work, or if you don't want to make changes to the Windows Registry, contact customer support for your Windows PC. The manufacturer may have potential solutions.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/best-desktop-pcs-4045927)

 FAQ

* How do I fix error code ws-37398-0?  
 Error code ws-37398-0 is a PS5 error code that occurs during PlayStation network server outages. Because the error stems from PlayStation, there's nothing you can do to fix it. You must wait until the network outage resolves.
* How do I fix error code 4b538e50 2k21?  
 This error occurs in the games_NBA 2K21_ and_NBA 2K22_ . It usually means your game files are outdated, and there's a pending file download or patch. To fix it, check to see if your computer or console still has game files to download, and wait for the downloading process to complete.
* How do I fix a code 10 error in Windows?  
 To[fix code 10 errors](https://www.lifewire.com/how-to-fix-code-10-errors-2623181) , which indicate that Device Manager can't start a hardware device, first try restarting your computer. If you recently installed a device, try uninstalling and reinstalling its drivers, or see if there are driver updates to install. You can also try installing the latest Windows update.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-rhythmripper-software-overview-and-testing/"><u>[New] 2024 Approved  RhythmRipper Software Overview & Testing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-best-no-cost-cross-platform-laptop-dvd-decoders/"><u>[New] Best No-Cost, Cross-Platform Laptop DVD Decoders</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-visual-virtuosity-unveiled-a-close-look-at-the-z32x-4k-monitor/"><u>[Updated] 2024 Approved  Visual Virtuosity Unveiled  A Close Look at the Z32X 4K Monitor</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-essential-list-of-macs-top-snipping-apps-for-2024/"><u>[Updated] The Essential List of Mac's Top Snipping Apps for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-hd-driver-problems-settled/"><u>[Win11] HD Driver Problems Settled</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-8-plus-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 8 Plus without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/affordable-tunes-for-students-the-ultimate-guide-on-how-to-score-a-spotify-discount-card/"><u>Affordable Tunes for Students: The Ultimate Guide on How to Score a Spotify Discount Card</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-gaming-sets-for-kids-navigating-through-console-options-and-extra-must-haves/"><u>Best Gaming Sets for Kids: Navigating Through Console Options & Extra Must-Haves</u></a></li>
<li><a href="https://techtrends.techidaily.com/can-electric-vehicles-handle-intense-heat-or-freezing-cold/"><u>Can Electric Vehicles Handle Intense Heat or Freezing Cold?</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-ev-ownership-perks-you-didnt-know-about-exclusive-parking-options-and-quick-travel-through-hov-lanes/"><u>Discover EV Ownership Perks You Didn't Know About: Exclusive Parking Options & Quick Travel Through HOV Lanes</u></a></li>
<li><a href="https://techtrends.techidaily.com/diy-mastery-crafting-the-perfect-projector-screen-for-movie-nights/"><u>DIY Mastery: Crafting the Perfect Projector Screen for Movie Nights</u></a></li>
<li><a href="https://techtrends.techidaily.com/get-your-hands-on-hot-tech-deals-this-years-amazon-prime-day-extravaganza/"><u>Get Your Hands on Hot Tech Deals – This Year's Amazon Prime Day Extravaganza</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-coredll-not-found-or-missing-errors/"><u>How to Fix Core.dll Not Found or Missing Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-recognize-and-deal-with-bogus-social-media-connections/"><u>How to Recognize and Deal with Bogus Social Media Connections</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-protecting-your-privacy-a-curated-list-of-cam-covers/"><u>In 2024, Protecting Your Privacy  A Curated List of Cam Covers</u></a></li>
<li><a href="https://techtrends.techidaily.com/independent-chatting-operating-messenger-outside-of-a-facebook-account-framework/"><u>Independent Chatting: Operating Messenger Outside of a Facebook Account Framework</u></a></li>
<li><a href="https://techtrends.techidaily.com/inserting-coding-snippets-directly-into-your-word-document-tips-and-tricks/"><u>Inserting Coding Snippets Directly Into Your Word Document - Tips & Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-connection-setting-up-pc-bluetooth-speaker-linkage-without-a-glitch/"><u>Master the Connection: Setting Up PC-Bluetooth Speaker Linkage Without a Glitch</u></a></li>
<li><a href="https://howto.techidaily.com/motorola-moto-g73-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Moto G73 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-the-internet-for-personal-phone-number-retrieval-tips-and-tricks/"><u>Navigating the Internet for Personal Phone Number Retrieval Tips and Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/ps4-controllers-unleashed-mastering-the-pair-up-process/"><u>PS4 Controllers Unleashed: Mastering the Pair-Up Process</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722887308611-reach-peak-performance-with-120-frames-per-second-on-your-ps5-console/"><u>Reach Peak Performance with 120 Frames Per Second on Your PS5 Console</u></a></li>
<li><a href="https://techtrends.techidaily.com/roku-tv-takedown-operating-without-the-remote/"><u>Roku TV Takedown: Operating without the Remote</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-oleaut32dll-file-not-found-a-step-by-step-guide/"><u>Solving oleAut32.dll File Not Found: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-the-mystery-strategies-for-correcting-propsysdll-file-absence-issues/"><u>Solving the Mystery: Strategies for Correcting PropSys.dll File Absence Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/sony-vr-headset-news-and-expected-price-release-date-specs-and-more-rumors/"><u>Sony VR Headset: News and Expected Price, Release Date, Specs; and More Rumors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/spark-paves-way-but-will-mavic-air-top-the-gaming-scene/"><u>Spark Paves Way, But Will Mavic Air Top the Gaming Scene?</u></a></li>
<li><a href="https://techtrends.techidaily.com/speed-vs-latency-unlocking-the-secrets-to-optimizing-memory-for-peak-pc-functionality/"><u>Speed vs Latency: Unlocking the Secrets to Optimizing Memory for Peak PC Functionality</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-fixes-for-when-zlibdll-is-nowhere-to-be-found/"><u>Step-by-Step Fixes for When 'Zlib.dll' Is Nowhere to Be Found</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-to-restart-malfunctioning-programs-on-your-mac/"><u>Step-by-Step Guide to Restart Malfunctioning Programs on Your Mac</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-activating-gmails-2fa-security-feature/"><u>Step-by-Step Guide: Activating Gmail's 2FA Security Feature</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-correcting-the-not-found-mfc42dll-error/"><u>Step-by-Step Guide: Correcting the 'Not Found' MFC42.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-windows-11s-observer-mode/"><u>Strategies for Stopping Windows 11'S Observer Mode</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-gen-m4-mac-mini-latest-insights-on-release-timeline-costs-and-technical-specifications/"><u>The Next-Gen M4 Mac Mini - Latest Insights on Release Timeline, Costs & Technical Specifications</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-premier-collection-of-samsung-smart-tv-applications-in-2e24/"><u>The Premier Collection of Samsung Smart TV Applications in 2E24</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-to-restore-your-iphones-ringtones/"><u>Troubleshooting Steps to Restore Your iPhone's Ringtones</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-why-arent-my-youtube-comments-appearing/"><u>Troubleshooting: Why Aren't My YouTube Comments Appearing?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->