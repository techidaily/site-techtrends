---
title: "Complete Guide: Steps to Remove Windows Restore Partition"
date: 2024-08-18T22:25:03.079Z
updated: 2024-08-19T22:25:03.079Z
categories:
  - BestProducts
description: "This Article Describes Complete Guide: Steps to Remove Windows Restore Partition"
excerpt: "This Article Describes Complete Guide: Steps to Remove Windows Restore Partition"
thumbnail: https://thmb.techidaily.com/a6f140ff4ddda64bd14cec3cab639274aa642e4bb60e8fa6d0c6031cee3c6ed0.jpg
---

## Complete Guide: Steps to Remove Windows Restore Partition

Close 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  What to Know

* In PowerShell or Command Prompt:**diskpart** \>**list disk** \>**select disk #** \>**list partition** \>**select partition #** \>**delete partition override** .
* To format partition: right-click**Start** \>**Disk Management** \> right-click**Unallocated** \>**New Simple Volume** \> follow wizard.

 This article explains how to delete a recovery partition in Windows 11, 10, 8, and 7\. It also explains how to format and expand a partition to use the unallocated space.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
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

 After you see a confirmation message, you can close the PowerShell/Command Prompt.

![partition override](https://www.lifewire.com/thmb/77odldkkcz9Dr2ifvItweMN-dSg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/009_delete-windows-recovery-partition-4128723-911baa68a0124e87b42297fc999ad2fa-b7cba53da27543f9a82eb6a6fd047464.jpg) 

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.
4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  
 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
3. Enter how much of the unallocated space you want to use, then select**Next** .  
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![drive size](https://www.lifewire.com/thmb/mXgg3V0zWVClHPqDGqa-nsiA1OA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/019_delete-windows-recovery-partition-4128723-68d4465915374357af41a11672bc0857-d19bbede5e6346e6a1f1240d4a738789.jpg)
4. Select**Finish** to terminate the wizard. The Windows partition will be resized to include the extra space.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-definitive-steps-to-record-your-favorite-hulu-episodes/"><u>[New] 2024 Approved  The Definitive Steps to Record Your Favorite Hulu Episodes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ideal-indoor-delights-mastering-mobile-lassitude-for-2024/"><u>[New] Ideal Indoor Delights  Mastering Mobile Lassitude for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-tiktoks-take-jujutsu-kaisen-challenges-and-laughs/"><u>[New] In 2024, TikTok's Take  Jujutsu Kaisen Challenges and Laughs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-harvest-happiness-best-agricultural-titles-to-play-with-friends/"><u>[Updated] 2024 Approved  Harvest Happiness  Best Agricultural Titles to Play With Friends</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-tips-for-ppt-video-production-for-2024/"><u>[Updated] Essential Tips for PPT Video Production for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mastering-real-time-photo-sharing-in-google-meet/"><u>[Updated] Mastering Real-Time Photo Sharing in Google Meet</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-immersive-odyssey-the-most-exciting-psvr-games-on-the-way/"><u>2024 Approved  Immersive Odyssey  The Most Exciting PSVR Games on the Way</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-apple-iphone-12-mini-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From Apple iPhone 12 mini</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722873937204-clear-focus-distracted-mind-learn-to-blur-your-backdrop-in-google-meet-today/"><u>Clear Focus, Distracted Mind? Learn to Blur Your Backdrop in Google Meet Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/comparing-neo-qled-and-oled-screens-which-offers-superior-picture-quality/"><u>Comparing Neo QLED and OLED Screens: Which Offers Superior Picture Quality?</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-7-apps-to-wake-up-to-our-expert-picks/"><u>Discover the Best 7 Apps to Wake Up To: Our Expert Picks!</u></a></li>
<li><a href="https://techtrends.techidaily.com/elite-selection-the-top-eight-best-games-to-play-on-your-smartphone/"><u>Elite Selection: The Top Eight Best Games to Play on Your Smartphone</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-top-5-tools-that-every-successful-twitch-broadcaster-must-utilize/"><u>Essential Top 5 Tools That Every Successful Twitch Broadcaster Must Utilize</u></a></li>
<li><a href="https://techtrends.techidaily.com/exclusive-leaks-on-the-newest-iphone-tech-and-pricing-strategies-s-model/"><u>Exclusive Leaks on the Newest iPhone Tech & Pricing Strategies 'S Model</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-dolby-atmos-sound-issues-resolving-unstarted-dolby-driver-on-windows-10/"><u>Fixing Dolby Atmos Sound Issues: Resolving Unstarted Dolby Driver on Windows 10</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-tecno-camon-30-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-installing-imessage-app-on-your-android-device/"><u>Guide: Installing iMessage App on Your Android Device</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hands-on-with-hp-envy-27-pushing-screen-tech-to-limits-for-2024/"><u>Hands-On with HP Envy 27  Pushing Screen Tech to Limits for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-enable-and-navigate-whatsapp-on-a-mac-device/"><u>How to Enable and Navigate WhatsApp on a Mac Device</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-samsung-galaxy-a54-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Samsung Galaxy A54 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-google-home-integration-with-your-desktop-computer/"><u>Mastering Google Home Integration with Your Desktop Computer</u></a></li>
<li><a href="https://techtrends.techidaily.com/ps5-controller-not-charging-heres-how-you-can-fix-it/"><u>PS5 Controller Not Charging? Here's How You Can Fix It!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-easy-startech-usb-visual-adapter-software-free-download/"><u>Quick and Easy: StarTech USB Visual Adapter Software Free Download</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-jvm-dll-file-not-detected-issues/"><u>Resolving JVM DLL File Not Detected Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-joining-an-itunes-shared-album-with-your-iphone/"><u>Step-by-Step Guide: Joining an iTunes Shared Album with Your iPhone</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-process-to-perform-a-full-reset-on-any-version-of-your-ipad-device/"><u>Step-by-Step Process to Perform a Full Reset on Any Version of Your iPad Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-best-literary-reader-programs-for-your-mobile-device-2024-edition/"><u>The Best Literary Reader Programs for Your Mobile Device - 2024 Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/the-seekers-blueprint-unlocking-shiny-chances-84/"><u>The Seeker’s Blueprint: Unlocking Shiny Chances (84)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-top-gains-on-social-media-secure-and-scalable-tactics/"><u>The Top Gains on Social Media - Secure & Scalable Tactics</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-vivo-y02t-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Vivo Y02T Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-free-messaging-applications-for-ios-devices/"><u>Top Free Messaging Applications for iOS Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-puzzle-adventure-apps-on-ios-exploring-titles-similar-to-the-room-and-myst/"><u>Top Puzzle Adventure Apps on iOS: Exploring Titles Similar to 'The Room' & 'Myst'</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-opengl32dll-mistakes-fixes-for-missingnotfound-issues/"><u>Troubleshooting OpenGL32.dll Mistakes - Fixes for Missing/NotFound Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-performing-a-complete-reboot-on-any-ipad-model/"><u>Ultimate Guide: Performing a Complete Reboot on Any iPad Model</u></a></li>
<li><a href="https://techtrends.techidaily.com/uninstalling-and-deactivating-the-facebook-app-on-android-easy-to-follow-steps/"><u>Uninstalling and Deactivating the Facebook App on Android: Easy-to-Follow Steps</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unlocking-value-the-samsung-galaxy-a71-5g-vs-top-flagship-competitors/"><u>Unlocking Value: The Samsung Galaxy A71 5G Vs. Top Flagship Competitors</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/us-vs-british-vocabulary-trails/"><u>US vs British Vocabulary Trails</u></a></li>
<li><a href="https://techtrends.techidaily.com/wired-free-entertainment-how-to-successfully-connect-a-fire-stick-with-your-phones-mobile-data/"><u>Wired-Free Entertainment: How to Successfully Connect a Fire Stick with Your Phone's Mobile Data</u></a></li>
<li><a href="https://techtrends.techidaily.com/wireless-printing-made-simple-setting-up-printer-sharing-on-all-connected-devices/"><u>Wireless Printing Made Simple: Setting up Printer Sharing on All Connected Devices</u></a></li>
</ul></div>
