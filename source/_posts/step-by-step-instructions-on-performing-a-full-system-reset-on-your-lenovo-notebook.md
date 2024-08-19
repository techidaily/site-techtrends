---
title: Step-by-Step Instructions on Performing a Full System Reset on Your Lenovo Notebook
date: 2024-08-18T22:14:55.404Z
updated: 2024-08-19T22:14:55.404Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Instructions on Performing a Full System Reset on Your Lenovo Notebook
excerpt: This Article Describes Step-by-Step Instructions on Performing a Full System Reset on Your Lenovo Notebook
thumbnail: https://www.lifewire.com/thmb/Fq16m0NQY-_nhfott8MIvMaFiI8=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/christian-salas-DjGRskJdBws-unsplash-972e0e380ece40ceb4fdfdedb3fbc7e2.jpg
---

## The Critical Point at \(S=-1\) Could Be Asymptotically Stable or Unstable Depending on Further Details About the System Dynamics Not Provided Here
 The error will always appear on a STOP message, more commonly called a[Blue Screen of Death (BSOD)](https://www.lifewire.com/blue-screen-of-death-bsod-2625816) .  

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix STOP 0x0000007B Errors

 Some of these steps may require you to[access Windows via Safe Mode](https://www.lifewire.com/how-do-i-start-windows-in-safe-mode-2624480) . Just skip those steps if that's not possible.

1. [Restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) if you haven't already done so. The STOP 0x0000007B blue screen error might be a fluke.  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Restart Windows 10 PC](https://www.lifewire.com/thmb/6CTZiV6xDkGZI7BTsLaucfk5k0g=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/restartWindows10-7722f41a53714d9ba98b4d59e1614b6c.jpg)
2. Did you just install or make a change to a hard drive controller? If so, there's a good chance that the change you made caused the STOP 0x0000007B error. Undo the change and test for the 0x7B blue screen error.  
 Depending on what changes you made, some solutions might include:  
   * Removing or reconfiguring the newly installed hard drive controller  
   * [Starting up with Last Known Good Configuration](https://www.lifewire.com/how-to-start-windows-7-using-last-known-good-configuration-2626308) to undo related[registry](https://www.lifewire.com/windows-registry-2625992) and driver changes  
   * [Using System Restore](https://www.lifewire.com/how-to-use-system-restore-in-windows-2626131) to undo recent changes  
   * [Rolling back the hard drive controller device driver](https://www.lifewire.com/how-to-roll-back-a-driver-in-windows-2619217) to the version prior to your driver update
3. [Verify that the SCSI chain is correctly terminated](https://web.archive.org/web/20181208051243/http://www.pcguide.com/ref/hdd/if/scsi/cablesTermination-c.html) , assuming you're using[SCSI](https://www.lifewire.com/small-computer-system-interface-scsi-2626002) hard drives in your computer. Incorrect SCSI termination has been known to cause STOP 0x0000007B errors.  
 Most home computers don't utilize SCSI hard drives but instead[PATA](https://www.lifewire.com/parallel-ata-pata-2625957) or[SATA](https://www.lifewire.com/serial-ata-sata-2626009) .
4. Verify that the hard drive is properly installed. An improperly installed hard drive could cause this error and other issues.
5. [Verify that the hard drive is configured properly in BIOS](https://web.archive.org/web/20181212064707/http://www.pcguide.com/ref/hdd/bios/biosSettings-c.html) . The STOP 0x0000007B error could occur if the hard drive settings in[BIOS](https://www.lifewire.com/bios-basic-input-output-system-2625820) are incorrect.
6. [Scan your computer for viruses](https://www.lifewire.com/properly-scan-your-computer-for-viruses-and-other-malware-2624526) . Certain malware that infects the[master boot record](https://www.lifewire.com/what-is-a-master-boot-record-mbr-2625936) (MBR) or[boot sector](https://www.lifewire.com/what-is-a-boot-sector-2625815) can cause STOP 0x0000007B errors.  
 Make sure your virus scanning software is updated and configured to scan the MBR and boot sector. See our[Best Free Antivirus Software](https://www.lifewire.com/best-free-antivirus-software-4151895) list if you don't already have one.
7. [Update the drivers for your hard drive controller](https://www.lifewire.com/how-to-update-drivers-in-windows-2619214) . If the drivers to your hard drive controller are outdated, incorrect, or corrupted, the STOP 0x0000007B error will likely occur.  
 If the error occurs during the Windows setup process and you suspect that the reason is driver related, be sure to install the latest hard drive controller driver from the manufacturer for use during the installation of the[operating system](https://www.lifewire.com/operating-systems-2625912) .  
 This is a likely solution if the second[hexadecimal number](https://www.lifewire.com/what-is-hexadecimal-2625897) _after_ the STOP code is 0xC0000034.
8. Change the SATA mode in BIOS to[IDE](https://www.lifewire.com/what-is-an-ide-cable-2625908) mode. Disabling some of the advanced features of SATA drives in BIOS could stop the STOP 0x0000007B error from showing up, especially if you're seeing it in Windows XP or during a Windows XP installation.  
 Depending on your BIOS make and version, SATA mode may be referred to as_AHCI mode_ and IDE mode may be referred to as either_Legacy_ ,_ATA_ , or_Compatibility Mode_ .  
 While not a common solution, you might also want to try the reverse: see if IDE mode is selected in BIOS and if so, change it to AHCI, especially if you see the STOP 0x0000007B error in Windows 10, 8, 7, or Vista.  
 If you see this STOP error_after making the BIOS change_ on a Windows 7 or Vista computer, you might need to enable the AHCI disk driver. See [Microsoft's instructions](https://support.microsoft.com/en-us/help/922976/error-message-occurs-after-you-change-the-sata-mode-of-the-boot-drive) on making that change in Windows Registry.
9. [Run chkdsk on your hard drive](https://www.lifewire.com/chkdsk-command-2625838) . If the boot volume is corrupted, the chkdsk command might repair the corruption.  
 You'll likely have to run chkdsk from the[Recovery Console](https://www.lifewire.com/recovery-console-2625991) .  
 This will likely be the solution if the second hexadecimal number_after_ the STOP code is 0xC0000032.
10. [Perform an extensive test of your hard drive](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) . If your hard drive has a physical problem, one very likely situation is the STOP 0x0000007B error you're seeing.  
[Replace the hard drive](https://www.lifewire.com/how-to-replace-a-hard-drive-2626200) if the diagnostics you complete suggest that there is a hardware problem with the drive.
11. [Run the fixmbr command](https://www.lifewire.com/fixmbr-command-2625887) to create a new master boot record. A corrupted master boot record might be causing your STOP 0x0000007B error.  
 This will likely be the solution if the second hexadecimal number_after_ the STOP code is 0xC000000E.
12. [Clear the CMOS](https://www.lifewire.com/how-to-clear-cmos-2624545) . Sometimes the STOP 0x0000007B error is caused by a BIOS memory issue. Clearing the CMOS could solve that problem.
13. [Update your BIOS](https://www.lifewire.com/how-to-update-bios-4783238) . In some situations, an outdated BIOS could cause this error due to incompatibilities with a hard drive controller.
14. Update the hard drive controller's[firmware](https://www.lifewire.com/what-is-firmware-2625881) if possible. Just as with the BIOS in the previous step, an incompatibility could be causing the 0x7B error and a firmware update from the manufacturer may correct the problem.
15. [Repair your Windows installation](https://www.lifewire.com/how-do-i-automatically-repair-windows-problems-2624907) . If you've just replaced the[motherboard](https://www.lifewire.com/motherboards-system-boards-and-mainboards-2618154) in a computer without reinstalling Windows then this will likely fix your problem.  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![Repair Windows screen](https://www.lifewire.com/thmb/F11Jk0jxq6MD66N_WFyvaIvuTag=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/repairwindows-5ddd983ddbee4fa5ab34fe8d57eb61ec.jpg)  
 Sometimes a Windows repair will not fix a STOP 0x0000007B error. In those cases, a[clean installation of Windows](https://www.lifewire.com/how-to-clean-install-windows-2624904) should do the trick.  
 If you haven't just replaced your motherboard, a Windows reinstall probably_will not_ fix your STOP 0x7B issue.
16. [Perform basic STOP error troubleshooting](https://www.lifewire.com/how-to-fix-a-blue-screen-of-death-2624518) . If none of the specific steps above help fix the STOP 0x0000007B error you're seeing, take a look at this general STOP error troubleshooting guide. Since most STOP errors are similarly caused, some of the suggestions might help.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Need More Help?

 If you're not interested in fixing this problem yourself, see[How Do I Get My Computer Fixed?](https://www.lifewire.com/how-do-i-get-my-computer-fixed-2625167) for a full list of your support options, plus help with everything along the way like figuring out repair costs, getting your files off, choosing a repair service, and a whole lot more.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Causes of the STOP 0x0000007B Errors

 One of the errors below, or a combination of both errors, might display on the STOP message:

 STOP: 0x0000007BINACCESSIBLE\_BOOT\_DEVICE  

 The STOP 0x0000007B error may also be abbreviated as STOP 0x7B, but the full[STOP code](https://www.lifewire.com/what-is-a-stop-code-2625685) will always be what's displayed on the blue screen STOP message.

 If Windows is able to start after the STOP 0x7B error, you might be prompted with a_Windows has recovered from an unexpected shutdown_ message that shows:

 Problem Event Name: BlueScreenBCCode: 7b  

 STOP 0x0000007B errors are caused by[device driver](https://www.lifewire.com/what-is-a-device-driver-2625796) issues (especially those related to[hard drive](https://www.lifewire.com/what-is-a-hard-disk-drive-2618152) and other storage controllers), viruses, data corruption, and sometimes even[hardware](https://www.lifewire.com/computer-hardware-2625895) failures.

 Any of Microsoft's Windows NT based operating systems could experience this error. This includes[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) ,[Windows XP](https://www.lifewire.com/windows-xp-2626354) , Windows 2000, and Windows NT.

 If STOP 0x0000007B isn't the exact STOP code you're seeing or INACCESSIBLE\_BOOT\_DEVICE isn't the exact message, check our[Complete List of STOP Error Codes](https://www.lifewire.com/blue-screen-error-codes-4065576) and reference the troubleshooting information for the STOP message that you are seeing.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-direct-pathway-iphone-media-to-pc-transfer/"><u>[New] 2024 Approved  Direct Pathway  IPhone Media to PC Transfer</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-the-art-of-saving-just-a-bit-from-youtube-videos/"><u>[New] 2024 Approved  The Art of Saving Just a Bit From YouTube Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-crafting-the-perfect-minecraft-archive-6-key-strategies/"><u>[Updated] Crafting the Perfect Minecraft Archive  6 Key Strategies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transform-your-viewers-experience-with-top-mac-streamers/"><u>[Updated] Transform Your Viewers' Experience with Top Mac Streamers</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-what-is-mixed-reality/"><u>[Updated] What Is Mixed Reality?</u></a></li>
<li><a href="https://techtrends.techidaily.com/ace-your-searches-essential-tips-and-techniques-for-google-gemini-usage/"><u>Ace Your Searches: Essential Tips and Techniques for Google Gemini Usage</u></a></li>
<li><a href="https://techtrends.techidaily.com/adapting-ios-messaging-with-these-tips-for-android-enthusiasts/"><u>Adapting iOS Messaging with These Tips for Android Enthusiasts</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-7-plusipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on Apple iPhone 7 Plus/iPad/iPod</u></a></li>
<li><a href="https://techtrends.techidaily.com/car-audio-woes-understanding-the-causes-of-non-working-speakers/"><u>Car Audio Woes: Understanding the Causes of Non-Working Speakers</u></a></li>
<li><a href="https://techtrends.techidaily.com/complete-guide-restoring-functionality-of-water-damaged-iphonesipods/"><u>Complete Guide: Restoring Functionality of Water-Damaged iPhones/iPods</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oneplus-11r-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For OnePlus 11R</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-bass-management-a-comprehensive-explanation-of-its-role-and-functionality/"><u>Demystifying Bass Management: A Comprehensive Explanation of Its Role & Functionality</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-messaging-techniques-within-the-mozilla-thunderbird-application/"><u>Effective Messaging Techniques Within the Mozilla Thunderbird Application</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722886365938-enhancing-user-experience-modify-your-windows-10-taskbar-appearance-with-colored-themes/"><u>Enhancing User Experience: Modify Your Windows 10 Taskbar Appearance with Colored Themes</u></a></li>
<li><a href="https://techtrends.techidaily.com/experience-nintendos-magic-discovering-the-top-6-super-mario-adventures-on-your-pc/"><u>Experience Nintendo's Magic: Discovering the Top 6 Super Mario Adventures on Your PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/experience-the-blend-of-classic-and-cutting-edge-with-the-amd-zen-3-upgraded-ayaneo-am01-mini-pc/"><u>Experience the Blend of Classic and Cutting-Edge with the AMD Zen 3 Upgraded Ayaneo AM01 Mini PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-connecting-with-snapchats-help-desk/"><u>Guide: Connecting with Snapchat's Help Desk</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-securely-pin-your-chat-threads-in-instagram-a-comprehensive-guide/"><u>How to Securely Pin Your Chat Threads in Instagram: A Comprehensive Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722890149483-hulu-viewing-tips-for-lg-smart-tv-users-get-started-today/"><u>Hulu Viewing Tips for LG Smart TV Users - Get Started Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/icloud-freeing-up-space-deleting-images-without-losing-your-iphone-copies/"><u>ICloud Freeing Up Space - Deleting Images without Losing Your iPhone Copies</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-getting-started-with-periscope-is-it-free-sign-up-process/"><u>In 2024, Getting Started with Periscope  Is It Free? Sign-Up Process</u></a></li>
<li><a href="https://extra-information.techidaily.com/learn-the-best-monitors-for-xbox-series-x-here-for-2024/"><u>Learn The Best Monitors for Xbox Series X Here for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-data-integration-the-ultimate-technique-for-combining-dual-excel-columns/"><u>Mastering Data Integration: The Ultimate Technique for Combining Dual Excel Columns</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-art-of-correcting-dysfunctional-amazon-prime-video-subtitles/"><u>Mastering the Art of Correcting Dysfunctional Amazon Prime Video Subtitles</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-setup-how-to-integrate-devices-with-bose-soundlink-technology/"><u>Mastering the Setup: How To Integrate Devices with Bose Soundlink Technology</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-dash-cameras-a-guide-to-making-an-informed-decision-with-these-9-insights/"><u>Navigating Dash Cameras: A Guide to Making an Informed Decision with These 9 Insights</u></a></li>
<li><a href="https://techtrends.techidaily.com/neo-qled-versus-oled-technology-unveiling-their-contrasts/"><u>Neo QLED Versus OLED Technology - Unveiling Their Contrasts</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-avi-file-joiner-top-10-free-and-easy-to-use-software-options/"><u>New 2024 Approved AVI File Joiner Top 10 Free and Easy-to-Use Software Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/optimized-home-networking-solutions-top-modem-and-router-combos-of-the-year/"><u>Optimized Home Networking Solutions: Top Modem and Router Combos of the Year</u></a></li>
<li><a href="https://techtrends.techidaily.com/reviving-your-deactivated-snapchat-a-step-by-step-guide/"><u>Reviving Your Deactivated Snapchat: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/star-trek-series-marathon-watching-from-the-original-through-to-beyond/"><u>Star Trek Series Marathon: Watching From The Original Through to Beyond</u></a></li>
<li><a href="https://techtrends.techidaily.com/steps-to-recover-a-disabled-or-deactivated-instagram-profile-a-comprehensive-guide/"><u>Steps to Recover a Disabled or Deactivated Instagram Profile: A Comprehensive Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/stream-your-computers-desktop-onto-any-screen-with-easy-chromecast-integration/"><u>Stream Your Computer's Desktop Onto Any Screen with Easy Chromecast Integration</u></a></li>
<li><a href="https://techtrends.techidaily.com/take-control-of-your-apple-music-settings-to-stop-autoplay-functionality/"><u>Take Control of Your Apple Music Settings to Stop Autoplay Functionality</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-insiders-tactic-revealing-the-list-of-people-who-saved-your-post/"><u>The Insider's Tactic: Revealing the List of People Who Saved Your Post</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-of-must-have-classroom-technology-essentials-for-pupils/"><u>The Ultimate List of Must-Have Classroom Technology Essentials for Pupils</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-and-fixing-a-loud-computer-fan-easy-diy-solutions/"><u>Troubleshooting and Fixing a Loud Computer Fan - Easy DIY Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-iphone-audio-issues-enhance-call-sound-quality-easily/"><u>Troubleshooting iPhone Audio Issues - Enhance Call Sound Quality Easily!</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-restart-options-for-macbook-pro-users/"><u>Troubleshooting: Restart Options for MacBook Pro Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722854357401-tutorial-adjusting-languages-and-regions-on-ios-devices/"><u>Tutorial: Adjusting Languages and Regions on iOS Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-how-to-sync-with-your-bose-soundlink-wirelessly/"><u>Ultimate Guide: How to Sync with Your Bose SoundLink Wirelessly</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722873941003-unbeatable-apple-watch-offers-dont-miss-out-on-savings/"><u>Unbeatable Apple Watch Offers - Don't Miss Out on Savings</u></a></li>
<li><a href="https://fox-direct.techidaily.com/unlocking-secrets-of-strong-openings-podcasters-guidebook/"><u>Unlocking Secrets of Strong Openings  Podcaster's Guidebook</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-the-secrets-of-searching-for-ev-chargers-with-google-maps-tips/"><u>Unlocking the Secrets of Searching for EV Chargers with Google Maps Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/windows-11-users-manual-removing-the-news-update-widget/"><u>Windows 11 User's Manual: Removing the News Update Widget</u></a></li>
</ul></div>
