---
title: Detailed Instructions for Disabling the Windows Restore Feature
date: 2024-11-24T16:44:33.586Z
updated: 2024-11-28T17:39:38.412Z
categories:
  - BestProducts
description: This Article Describes Detailed Instructions for Disabling the Windows Restore Feature
excerpt: This Article Describes Detailed Instructions for Disabling the Windows Restore Feature
thumbnail: https://www.lifewire.com/thmb/ALlLdPlK0nhyrSKTrZhz_J3x2vc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/hard-drive-56a2cb273df78cf7727a0201.jpg
---

## Detailed Instructions for Disabling the Windows Restore Feature

Close 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  What to Know

* In PowerShell or Command Prompt:**diskpart** \>**list disk** \>**select disk #** \>**list partition** \>**select partition #** \>**delete partition override** .
* To format partition: right-click**Start** \>**Disk Management** \> right-click**Unallocated** \>**New Simple Volume** \> follow wizard.

 This article explains how to delete a recovery partition in Windows 11, 10, 8, and 7\. It also explains how to format and expand a partition to use the unallocated space.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you see a confirmation message, you can close the PowerShell/Command Prompt.

![partition override](https://www.lifewire.com/thmb/77odldkkcz9Dr2ifvItweMN-dSg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/009_delete-windows-recovery-partition-4128723-911baa68a0124e87b42297fc999ad2fa-b7cba53da27543f9a82eb6a6fd047464.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  
 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
3. Enter how much of the unallocated space you want to use, then select**Next** .  
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
<li><a href="https://article-knowledge.techidaily.com/new-photography-perks-fast-and-fun-edits-using-windows-paint-app/"><u>[New] Photography Perks Fast & Fun Edits Using Windows Paint App</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/tep-by-step-throwing-epic-intros-with-imovie/"><u>[New] Step-by-Step Throwing Epic Intros with iMovie</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-7-exceptional-drone-gimbals-unveiled/"><u>[Updated] 7 Exceptional Drone Gimbals Unveiled</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-simple-guide-to-effective-and-smooth-iphone-screen-recordings/"><u>[Updated] In 2024, Simple Guide to Effective & Smooth Iphone Screen Recordings</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-fundamentals-of-captivating-video-scripts/"><u>[Updated] The Fundamentals of Captivating Video Scripts</u></a></li>
<li><a href="https://techtrends.techidaily.com/abbyy-announces-global-growth-initiative-through-structural-reorganization-press-release/"><u>ABBYY Announces Global Growth Initiative Through Structural Reorganization - Press Release</u></a></li>
<li><a href="https://techtrends.techidaily.com/abbyy-erleichtert-automatisierte-kreditorenbuchhaltung-mit-nahtloser-sap-integration-und-mobilen-funktionen/"><u>ABBYY Erleichtert Automatisierte Kreditorenbuchhaltung Mit Nahtloser SAP-Integration Und Mobilen Funktionen.</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-find-x6-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo Find X6 Pro</u></a></li>
<li><a href="https://techtrends.techidaily.com/aiabbyyneoml/"><u>AIソリュティアル開発に必要な機械学習ライブラリ：ABBYYオープンソースとNeoML</u></a></li>
<li><a href="https://techtrends.techidaily.com/ameliorez-le-traitement-des-factures-pour-votre-grande-association-de-logement-avec-le-partenariat-abbyy-lautomatisation-facile-et-efficace/"><u>Améliorez Le Traitement Des Factures Pour Votre Grande Association De Logement Avec Le Partenariat ABBYY : L'automatisation Facile Et Efficace</u></a></li>
<li><a href="https://techtrends.techidaily.com/avancez-en-comptabilite-amelioration-ocr-via-abbyya-document-intelligence-strategies-efficaces/"><u>Avancez en Comptabilité: Amélioration OCR via Abbyya Document Intelligence - Stratégies Efficaces</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-your-website-traffic-with-automated-personalization-powered-by-crawlerbot-technology/"><u>Boost Your Website Traffic with Automated Personalization: Powered by CrawlerBot Technology</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-your-websites-engagement-using-advanced-cookiebot-tracking-technology/"><u>Boost Your Website's Engagement Using Advanced Cookiebot Tracking Technology</u></a></li>
<li><a href="https://techtrends.techidaily.com/boosting-sap-automation-through-integrated-content-insights-by-leveraging-abbyy-technology/"><u>Boosting SAP Automation Through Integrated Content Insights by Leveraging ABBYY Technology.</u></a></li>
<li><a href="https://techtrends.techidaily.com/boosting-site-interactions-with-cookiebot-technology-integration/"><u>Boosting Site Interactions with Cookiebot Technology Integration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-machines-pass-the-turing-test-exploring-possibilities-and-challenges/"><u>Can Machines Pass the Turing Test? Exploring Possibilities and Challenges</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-samsung-galaxy-f34-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Samsung Galaxy F34 5G? Try These Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-honor-x50iplus-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Honor X50i+ to iPod | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-6-websites-to-buy-your-next-television-set/"><u>Top 6 Websites to Buy Your Next Television Set</u></a></li>
</ul></div>

