---
title: How to Fix STOP 0X0000007B BSOD Errors
date: 2024-11-06T03:39:52.825Z
updated: 2024-11-07T18:45:54.877Z
categories:
  - BestProducts
description: This Article Describes How to Fix STOP 0X0000007B BSOD Errors
excerpt: This Article Describes How to Fix STOP 0X0000007B BSOD Errors
thumbnail: https://www.lifewire.com/thmb/isn0ko2HLlTK7WUnMbUXQcunVqg=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/blue-screen-of-death-bsod-windows-56a6faab3df78cf772913ee6.png
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-insights-into-instagram-video-constraint/"><u>[Updated] In 2024, Insights Into Instagram Video Constraint</u></a></li>
<li><a href="https://solve-popular.techidaily.com/1-iphone-update-stuck-solve-insufficient-storage-error-on-your-device/"><u>1. IPhone Update Stuck? Solve Insufficient Storage Error on Your Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/macx-video-converter-pro/"><u>公式 MacX Video Converter Pro 使用方法解説：新たなバージョンで利用可能なライセンスコード登録ガイド</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-in-action-chatgpts-transformative-use-cases/"><u>AI in Action: ChatGPT's Transformative Use Cases</u></a></li>
<li><a href="https://techtrends.techidaily.com/beyond-traditional-cooking-embrace-ai-with-chatgpt-as-your-culinary-expert/"><u>Beyond Traditional Cooking: Embrace AI with ChatGPT as Your Culinary Expert</u></a></li>
<li><a href="https://win-rankings.techidaily.com/como-crear-una-copia-exacta-del-sistema-en-windows-nuevo-11-para-ambos-tipos-de-arquitectura-binaria/"><u>Cómo Crear Una Copia Exacta Del Sistema en Windows Nuevo 11 Para Ambos Tipos De Arquitectura Binaria</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhanced-video-experience-how-firefox-126-leverages-nvidias-rtx-technology-on-youtube/"><u>Enhanced Video Experience: How Firefox 126 Leverages NVIDIA's RTX Technology on YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhancing-creative-workflow-with-microsoft-copilots-new-video-generation-features/"><u>Enhancing Creative Workflow with Microsoft Copilot's New Video Generation Features</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-4-revolutionary-electric-vehicle-innovations-set-to-transform-transportation/"><u>Exploring 4 Revolutionary Electric Vehicle Innovations Set to Transform Transportation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1725286458952-exploring-standard-dvd-resolution-is-it-sd-480p-hd-720p-or-uhd-108/"><u>Exploring Standard DVD Resolution - Is It SD (480P), HD (720P), or UHD (108 )?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-pro-max-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 Pro Max to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/introducing-amds-pro-8000-series-advanced-npu-capabilities-in-high-performance-desktops/"><u>Introducing AMD's Pro 8000 Series: Advanced NPU Capabilities in High-Performance Desktops</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-a-meta-quest-based-virtual-reality-device-awaiting-its-debut-as-a-rival-to-steam-deck/"><u>Is a Meta Quest-Based Virtual Reality Device Awaiting Its Debut as a Rival to Steam Deck?</u></a></li>
<li><a href="https://techtrends.techidaily.com/macx-downloader-protect-and-save-videosmusic-from-youtube-on-windows-and-mac-platforms/"><u>MacX Downloader: Protect & Save Videos/Music From YouTube on Windows & Mac Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-repair-damaged-pdf-v11-files-by-stellar-guide/"><u>Quickly Repair Damaged PDF v1.1 Files</u></a></li>
<li><a href="https://techtrends.techidaily.com/stream-movies-anywhere-download-the-movie-box-app-for-mac-iphone-and-ipad/"><u>Stream Movies Anywhere: Download The Movie Box App for Mac, iPhone & iPad</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-why-isnt-my-print-screen-working-solutions-for-windows-1110/"><u>Troubleshooting: Why Isn't My Print Screen Working? Solutions for Windows 11/10</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unlock-new-perspectives-budget-4k-action-with-akaso-ek7000/"><u>Unlock New Perspectives - Budget 4K Action with AKASO EK7000</u></a></li>
</ul></div>

