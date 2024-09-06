---
title: Detailed Instructions for Disabling the Windows Restore Feature
date: 2024-09-05T11:41:09.761Z
updated: 2024-09-06T11:41:09.761Z
categories:
  - BestProducts
description: This Article Describes Detailed Instructions for Disabling the Windows Restore Feature
excerpt: This Article Describes Detailed Instructions for Disabling the Windows Restore Feature
thumbnail: https://www.lifewire.com/thmb/ALlLdPlK0nhyrSKTrZhz_J3x2vc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/hard-drive-56a2cb273df78cf7727a0201.jpg
---

## Detailed Instructions for Disabling the Windows Restore Feature

Close 

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  What to Know

* In PowerShell or Command Prompt:**diskpart** \>**list disk** \>**select disk #** \>**list partition** \>**select partition #** \>**delete partition override** .
* To format partition: right-click**Start** \>**Disk Management** \> right-click**Unallocated** \>**New Simple Volume** \> follow wizard.

 This article explains how to delete a recovery partition in Windows 11, 10, 8, and 7\. It also explains how to format and expand a partition to use the unallocated space.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete a Recovery Partition in Windows 

 Because recovery partitions are protected, the steps for removing them differ from deleting a normal partition.

 When you[ create a recovery partition for Windows](https://www.lifewire.com/create-recovery-drive-all-versions-windows-2200650) , it's best to store it on an[ external drive](https://www.lifewire.com/what-is-an-external-drive-2625867) in case something happens to your computer. After saving it somewhere else, you can delete the recovery partition from your PC to free up space.

1. Right-click the Start menu and select**Terminal (Admin)** Windows 11,**Windows PowerShell (Admin)** , or**Command Prompt (Admin)** .  
 If you're using Windows 7 or earlier, you'll have to[ open Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) another way, like through the Start menu or Run dialog box.
2. Type**diskpart** and press**Enter** , then type**list disk** and press**Enter** .
3. A list of disks displays. Type   **select disk _#_**  (where _#_ is the number of the disk with the recovery partition) and press **Enter** .  
 If you're unsure which one it's on, find out by opening the[ Disk Management tool](https://www.lifewire.com/disk-management-2625863) .  
![Select Disk](https://www.lifewire.com/thmb/1Mt2ZXpoT3G6vxjBufv-L3Ax_IM=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/005_delete-windows-recovery-partition-4128723-39d975e00e4342e4ab2690b442c55cc3-5a89be105dd942a0b63ac8b7daf23288.jpg)
4. Type **list partition**  and press **Enter** . A list of partitions displays. Type **select partition #**  (where _#_ is the number of the recovery partition) and press **Enter** .  
![select partition](https://www.lifewire.com/thmb/EWAsDd1kl5UkUHvxcACEQzBdvyw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/007_delete-windows-recovery-partition-4128723-fcdf0b8b44b84e00b08b0da8a89f5052-5befaed89aef4289bc842118b9c4dbfd.jpg)
5. Type **delete partition override** and press**Enter** .
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you see a confirmation message, you can close the PowerShell/Command Prompt.

![partition override](https://www.lifewire.com/thmb/77odldkkcz9Dr2ifvItweMN-dSg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/009_delete-windows-recovery-partition-4128723-911baa68a0124e87b42297fc999ad2fa-b7cba53da27543f9a82eb6a6fd047464.jpg) 

## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  
<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
3. Enter how much of the unallocated space you want to use, then select**Next** .  
![drive size](https://www.lifewire.com/thmb/mXgg3V0zWVClHPqDGqa-nsiA1OA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/019_delete-windows-recovery-partition-4128723-68d4465915374357af41a11672bc0857-d19bbede5e6346e6a1f1240d4a738789.jpg)
4. Select**Finish** to terminate the wizard. The Windows partition will be resized to include the extra space.
<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 FAQ

* Is it safe to delete a recovery partition in Windows?  
 Yes. Removing a recovery partition will not affect the Windows operating system.
* How do I restore a deleted Windows recovery partition?  
 To restore deleted recovery partitions,[ rebuild the Windows Boot Configuration Drive](https://www.lifewire.com/how-to-rebuild-the-bcd-in-windows-2624508) , use a third-party tool, or reinstall Windows.
* How do I factory reset Windows without a recovery partition?  
 Use[ Reset This PC](https://www.lifewire.com/reset-this-pc-complete-walkthrough-2624538) to restore your Windows PC to factory settings. In Windows 8, use Refresh Your PC to back up your files first.
* How do I create a recovery drive in Windows?  
 In Windows 11 or 10, search for**Create a recovery drive** and check the box beside**Back up system files to the recovery drive** . Next, connect a USB drive, then select**Next** . You can also[ create a recovery drive in Windows 8](https://www.lifewire.com/how-to-create-a-windows-recovery-drive-2625164) .

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

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
<li><a href="https://video-screen-grab.techidaily.com/new-handsonguide-to-yourwebcamrecord/"><u>[New] HandsOnGuide to YourWebcamRecord</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-streamlined-recording-the-very-best-fullscreen-software/"><u>[New] In 2024, Streamlined Recording  The Very Best Fullscreen Software</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-accessing-global-events-facebook-live-on-roku-devices/"><u>[Updated] 2024 Approved  Accessing Global Events  Facebook Live on Roku Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-ultimate-guide-to-cost-free-online-collaboration-tools/"><u>[Updated] The Ultimate Guide to Cost-Free Online Collaboration Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-accelerated-mp4-conversion-for-fb-media/"><u>2024 Approved  Accelerated MP4 Conversion for FB Media</u></a></li>
<li><a href="https://fox-info.techidaily.com/comparative-study-of-toolwizs-photography-tools-for-2024/"><u>Comparative Study of Toolwiz's Photography Tools for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-tutorial-on-how-to-obtain-and-set-up-the-most-recent-ios-update/"><u>Comprehensive Tutorial on How to Obtain and Set Up the Most Recent iOS Update</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-tutorial-running-chkdsk-for-error-free-drives-in-windows/"><u>Comprehensive Tutorial: Running ChkDsk for Error-Free Drives in Windows</u></a></li>
<li><a href="https://ai-topics.techidaily.com/demystifying-ai-game-generators/"><u>Demystifying AI Game Generators</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-oled-the-mechanics-of-organic-light-emitting-diodes-explained/"><u>Demystifying OLED: The Mechanics of Organic Light Emitting Diodes Explained</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-repairing-missing-vcompdll-files-comprehensive-fixes/"><u>Diagnosing and Repairing Missing vcomp.dll Files | Comprehensive Fixes</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-ai-chatbot-options-beyond-chatgpt/"><u>Discover the Best AI Chatbot Options Beyond ChatGPT</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ultimate-list-of-free-online-calling-applications-for-202/"><u>Discover the Ultimate List of Free Online Calling Applications for 202지</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/discovering-each-korean-day-your-quick-reference/"><u>Discovering Each Korean Day: Your Quick Reference</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-steps-to-properly-maintain-your-lcd-television/"><u>Essential Steps to Properly Maintain Your LCD Television</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tips-on-selecting-an-ideal-surge-protector-for-electronic-devices/"><u>Essential Tips on Selecting an Ideal Surge Protector for Electronic Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-to-restore-incoming-call-functionality-on-your-samsung-galaxy-watch/"><u>Expert Tips to Restore Incoming Call Functionality on Your Samsung Galaxy Watch</u></a></li>
<li><a href="https://win-dash.techidaily.com/explore-the-enhanced-features-of-the-newly-released-sticky-notes-application-for-windows-11/"><u>Explore the Enhanced Features of the Newly Released Sticky Notes Application for Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-hevc-files-on-motorola-razr-40-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Failed to play HEVC files on Motorola Razr 40</u></a></li>
<li><a href="https://techtrends.techidaily.com/finding-email-information-best-practices-and-tips/"><u>Finding Email Information - Best Practices and Tips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/fixing-ralink-rt3290-drivers-troubleshooting-on-windows-10-8-and-7/"><u>Fixing Ralink RT3290 Drivers: Troubleshooting on Windows 10, 8 & 7</u></a></li>
<li><a href="https://techtrends.techidaily.com/get-ahead-with-verizons-latest-smartphone-trade-in-deals/"><u>Get Ahead with Verizon's Latest Smartphone Trade-In Deals</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-choose-your-ideal-phone-case/"><u>How to Choose Your Ideal Phone Case</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-erase-photos-off-of-your-facebook-account-safely-and-quickly/"><u>How to Erase Photos Off of Your Facebook Account Safely and Quickly</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/orating-cold-season-selecting-warm-video-themes-for-2024/"><u>Invigorating Cold Season  Selecting Warm Video Themes for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-twitter-effective-strategies-to-boost-your-follower-count/"><u>Mastering Twitter: Effective Strategies to Boost Your Follower Count</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-common-hurdles-effortless-fixes-for-your-netflix-app-on-lg-screens/"><u>Overcoming Common Hurdles: Effortless Fixes for Your Netflix App on LG Screens</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/prime-choices-cheap-pc-capture-software-listed/"><u>Prime Choices  Cheap PC Capture Software Listed</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-the-no-signal-problem-a-step-by-step-guide-for-your-xbox-one/"><u>Solving the 'No Signal' Problem: A Step-by-Step Guide for Your Xbox One</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-complete-tutorial-on-converting-your-spotify-lists-to-readable-text-files/"><u>The Complete Tutorial on Converting Your Spotify Lists to Readable Text Files</u></a></li>
<li><a href="https://article-tips.techidaily.com/the-ultimate-guide-to-zooming-your-tiktok-videos-for-2024/"><u>The Ultimate Guide to Zooming Your TikTok Videos for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-infinix-note-30-vip-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Infinix Note 30 VIP for Parents | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-picks-must-watch-lgbtqplus-series-on-netflix-in-july-2024/"><u>Top Picks: Must-Watch LGBTQ+ Series on Netflix in July 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722842968224-top-rated-ipad-offers-just-in-time-grab-yours-today/"><u>Top-Rated iPad Offers Just in Time: Grab Yours Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-disappearing-dark-mode-on-facebook-expert-tips-and-tricks/"><u>Troubleshooting Disappearing Dark Mode on Facebook: Expert Tips and Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-tips-for-when-your-ipad-cant-find-a-wi-fi-signal/"><u>Troubleshooting Tips for When Your iPad Can’t Find a Wi-Fi Signal</u></a></li>
<li><a href="https://techtrends.techidaily.com/turn-off-rapid-point-and-click-features-a-guide-for-mac-users/"><u>Turn Off Rapid Point-and-Click Features: A Guide for Mac Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/unconventional-methods-to-remove-your-iphones-sim-a-step-by-step-guide/"><u>Unconventional Methods to Remove Your iPhone’s SIM: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-our-picked-selection-of-top-free-virtual-calendars/"><u>Unveiling Our Picked Selection of Top Free Virtual Calendars</u></a></li>
<li><a href="https://techtrends.techidaily.com/usb-30-and-nvme-empowering-your-xbox-one-game-library-through-external-hard-drives/"><u>USB 3.0 and NVMe: Empowering Your Xbox One Game Library Through External Hard Drives</u></a></li>
</ul></div>
