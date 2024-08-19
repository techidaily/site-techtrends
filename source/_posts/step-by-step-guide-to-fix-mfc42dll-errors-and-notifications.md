---
title: Step-by-Step Guide to Fix 'mfc42.dll' Errors and Notifications
date: 2024-08-18T22:27:18.308Z
updated: 2024-08-19T22:27:18.308Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Guide to Fix 'mfc42.dll' Errors and Notifications
excerpt: This Article Describes Step-by-Step Guide to Fix 'mfc42.dll' Errors and Notifications
thumbnail: https://www.lifewire.com/thmb/EtiFx7U6WzUo3LZ6JesX-4bzJ6I=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/mfc42-dll-error-message-5af065a01f4e130037445df2.PNG
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
<li><a href="https://youtube-videos.techidaily.com/new-a-step-by-step-guide-to-your-profit-share-in-youtube-shorts/"><u>[New] A Step-by-Step Guide to Your Profit Share in YouTube Shorts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-expedite-vimeo-video-playback/"><u>[Updated] In 2024, Expedite Vimeo Video Playback</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1716069006162-updated-in-2024-top-sandbox-adventures-not-to-skip/"><u>[Updated] In 2024, Top Sandbox Adventures Not To Skip!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagrams-secret-weapon-tailoring-photos-to-standout-highlights/"><u>[Updated] Instagram's Secret Weapon  Tailoring Photos to Standout Highlights</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-prime-fb-video-snatcher-and-upgrades-for-firefox-for-2024/"><u>[Updated] Prime FB Video Snatcher & Upgrades for FireFox for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-flip-side-to-visual-storytelling-how-to-rotate-your-images-on-instagram-for-2024/"><u>[Updated] The Flip-Side to Visual Storytelling  How to Rotate Your Images on Instagram for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-complete-walkthrough-on-shutting-down-your-iphone-15-series-device/"><u>A Complete Walkthrough on Shutting Down Your iPhone 15 Series Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/analyzing-the-resilience-and-functionality-of-evs-in-harsh-thermal-environments/"><u>Analyzing the Resilience and Functionality of EVs in Harsh Thermal Environments</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capturing-audio-masterpieces-using-audacity/"><u>Capturing Audio Masterpieces Using Audacity</u></a></li>
<li><a href="https://techtrends.techidaily.com/change-text-in-instagram-posts-easily-editing-essentials/"><u>Change Text in Instagram Posts Easily - Editing Essentials</u></a></li>
<li><a href="https://win-able.techidaily.com/collaborative-endeavors-reach-new-heights-with-the-official-release-of-it-takes-two/"><u>Collaborative Endeavors Reach New Heights with the Official Release of 'It Takes Two'</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-kensun-portable-air-compressor-evaluation-durability-and-convenience-on-the-go/"><u>Comprehensive Kensun Portable Air Compressor Evaluation: Durability and Convenience on the Go</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-strategy-on-flagging-all-email-threads-simultaneously-in-gmail/"><u>Comprehensive Strategy on Flagging All Email Threads Simultaneously in Gmail</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-tips-on-dealing-with-msvcr7-groovy-errors-in-windows/"><u>Comprehensive Tips on Dealing with Msvcr7 Groovy Errors in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-chatgpt-an-introduction-to-advanced-ai-communication-tools/"><u>Demystifying ChatGPT: An Introduction to Advanced AI Communication Tools</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-all-the-exciting-ps-vr-2-launching-games-unveiled-to-date/"><u>Discover All the Exciting PS VR 2 Launching Games Unveiled to Date</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-how-to-locate-a-person-using-their-iphone/"><u>Discover How to Locate a Person Using Their iPhone</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-to-troubleshoot-unverified-developer-issues-on-your-mac/"><u>Easy Steps to Troubleshoot Unverified Developer Issues on Your Mac</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-tutorial-for-building-an-oculus-quest-and-quest-2-username-and-password/"><u>Easy Tutorial for Building an Oculus Quest & Quest 2 Username and Password</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-coordination-discover-the-7-ultimate-calendar-apps-to-sync-busy-family-routines/"><u>Effortless Coordination: Discover the 7 Ultimate Calendar Apps to Sync Busy Family Routines</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tless-entertainment-looping-youtube-videos-for-tv-viewers/"><u>Effortless Entertainment  Looping YouTube Videos for TV Viewers</u></a></li>
<li><a href="https://techtrends.techidaily.com/enabling-iphone-text-messages-imessage-on-android-phones/"><u>Enabling iPhone Text Messages (iMessage) on Android Phones</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-history-of-aol-instant-messenger-what-is-aim/"><u>Exploring the History of AOL Instant Messenger – What Is AIM?</u></a></li>
<li><a href="https://techtrends.techidaily.com/fixing-missing-binkw32dll-effective-strategies-and-tips/"><u>Fixing 'Missing binkw32.dll': Effective Strategies and Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-overcome-user-permissions-in-windows-navigating-through-trustedinstaller/"><u>How to Overcome User Permissions in Windows Navigating Through TrustedInstaller</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-resolve-the-msodll-file-cannot-be-found-issue/"><u>How to Resolve the 'Mso.Dll File Cannot Be Found' Issue</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-s23-ultra-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy S23 Ultra Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y02t-bootloader-easily-by-drfone-android/"><u>How to Unlock Vivo Y02T Bootloader Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/identifying-supporters-a-guide-to-monitoring-saves-on-instagram/"><u>Identifying Supporters: A Guide to Monitoring Saves on Instagram</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-latest-trend-get-8plus-free-tools-for-cutting-and-sharing-video-content/"><u>Instagram's Latest Trend  Get 8+ Free Tools for Cutting & Sharing Video Content</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-15-restart-methods-a-detailed-instructional-guide/"><u>IPhone 15 Restart Methods: A Detailed Instructional Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-it-time-to-switch-to-an-rtx-gpu-for-your-pc/"><u>Is It Time to Switch to an RTX GPU for Your PC?</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-audio-editing-eliminating-lameencdll-errors-for-flawless-mp3-output-with-audacity/"><u>Mastering Audio Editing: Eliminating lame_enc.dll Errors for Flawless MP3 Output with Audacity</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-14-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from 14.</u></a></li>
<li><a href="https://techtrends.techidaily.com/quick-fixes-for-jvmdll-error-when-its-missing-or-unavailable/"><u>Quick Fixes for JVM.dll Error: When It's Missing or Unavailable</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-msodll-file-not-found-issues-on-your-pc/"><u>Resolving 'Mso.DLL File Not Found' Issues on Your PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-ietfame-dll-issues-step-by-step-solutions/"><u>Resolving Ietfame DLL Issues: Step-by-Step Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/revealing-the-curious-eyes-methods-for-finding-out-your-google-docs-readers/"><u>Revealing the Curious Eyes: Methods for Finding Out Your Google Docs Readers</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-capturing-images-of-your-ps4-gameplay/"><u>Step-by-Step Guide: Capturing Images of Your PS4 Gameplay</u></a></li>
<li><a href="https://techtrends.techidaily.com/streamlining-your-studies-with-these-9-essential-technology-items/"><u>Streamlining Your Studies with These 9 Essential Technology Items</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-top-free-film-selections-to-watch-this-july-2024-on-youtube/"><u>The Ultimate List: Top Free Film Selections to Watch This July 2024 on YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-affordable-home-theater-setup-essentials/"><u>Top Affordable Home Theater Setup Essentials</u></a></li>
<li><a href="https://techtrends.techidaily.com/transition-from-gmail-with-ease-find-your-perfect-match-among-these-8-services/"><u>Transition From Gmail with Ease: Find Your Perfect Match Among These 8 Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-miracast-connectivity-problems-tips-to-fix-device-support-issues/"><u>Troubleshoot Miracast Connectivity Problems: Tips to Fix Device Support Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-stop-code-0x0000001d-expert-solutions/"><u>Troubleshooting Stop Code 0X0000001D: Expert Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/twitch-security-essentials-the-ultimate-guide-to-setting-up-and-utilizing-2fa/"><u>Twitch Security Essentials: The Ultimate Guide to Setting Up and Utilizing 2FA</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722881682881-uncover-the-most-effective-skype-substitutes-free-options/"><u>Uncover the Most Effective Skype Substitutes - Free Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/unhindered-mobile-access-with-metro-by-t-mobile-comprehensive-roaming-coverage-explained/"><u>Unhindered Mobile Access with Metro by T-Mobile – Comprehensive Roaming Coverage Explained</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-the-secrets-how-to-get-back-deleted-texts-on-all-kind-of-phones/"><u>Unlock the Secrets: How To Get Back Deleted Texts on All Kind of Phones</u></a></li>
<li><a href="https://techtrends.techidaily.com/why-are-we-shifting-towards-electric-automobiles-an-in-depth-guide/"><u>Why Are We Shifting Towards Electric Automobiles? An In-Depth Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/windows-woes-be-gone-a-users-manual-for-restoring-winhttpdll-files/"><u>Windows Woes Be Gone: A User’s Manual for Restoring Winhttp.dll Files</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->