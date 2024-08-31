---
title: "Protecting Your Photos on Linux Systems: A Step-by-Step Guide to Deleting Metadata with Exiftool"
date: 2024-08-30T15:07:25.259Z
updated: 2024-08-31T15:07:25.259Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/44b00e7ceffa68921ecf622a184f48a9d902f80a57b12969c744bb786188a75e.png
---

## Protecting Your Photos on Linux Systems: A Step-by-Step Guide to Deleting Metadata with Exiftool

### Key Takeaways

* Did you know smartphone pictures can contain sensitive data? Remove metadata to protect your privacy.
* EXIF tags store a lot of information about your photos, including device details and GPS coordinates.
* Use exiftool on Linux to easily strip all metadata from your images before sharing them online.

 Did you know that pictures you snap with your smartphone may include sensitive information? Posting them as-is on social media or elsewhere can be risky to your privacy unless you take steps to remove extra data from them. In this article you'll learn how to do just that on Linux with exiftool.

##  Why Should I Remove Metadata?

 Back in the days of analog cameras, the only "extra" information you needed to worry about being disclosed alongside them was what you physically wrote on the back of each photo. Fast-forward to modern times, and we've got the ability to capture moments instantly in digital form (and even keep thousands of them at a time on a single device). This shift made a lot of folks think about what could augment this new technology to make our lives even easier.

 In the mid-1990's, borrowing from the TIFF standard, research and standards bodies developed a way to embed extra information inside image files themselves. They called this new standard [Exchangable Image File Format (EXIF)](https://some-knowledge.techidaily.com/new-ignite-motivation-the-hottest-playlists-for-workouts/). Now you will see your picture libraries, for instance, using EXIF tags to help search, sort and categorize every image you take.

 The amount of data that gets stored in your images depends on manufacturer defaults, features enabled on your device and other factors. Along with basic information like the date/time taken and image resolution, just a small sample of other tags stored with your picture may include:

* The model name of the phone/camera used to take it
* Exposure time
* Whether the camera's flash was used or not
* A thumbnail, in binary format
* [GPS](https://win-forum.techidaily.com/how-to-access-and-understand-bios-on-windows-11-a-comprehensive-guide/) coordinates

 That last one is a particular privacy concern as it can be used to locate precisely where you or the subject of the picture were at the time the picture was taken.

 The other items are also interesting in that they can be used to enumerate, for example, exactly what type of device you used, right down to the model. This can, for instance, be used to plan a targeted [attack on your phone](https://desktop-recording.techidaily.com/1715859817771-updated-seeking-authentic-ps2-play-check-out-the-5-best-android-simulators/).

 If you take a look at [all the possible EXIF tags that could be embedded in your images](https://exiftool.org/TagNames/EXIF.html), you'll start to understand the importance of keeping some (most?) of them away from those who may want to use them for less-than-honest reaasons.

 So, with this knowledge, we'll move forward to protect ourselves with Linux and exiftool!

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
##  Installing Required Packages

 Exiftool is a platform-independent library and command line application, written in Perl, by Phil Harvey. It's available from [the official exiftool website](https://exiftool.org/), which also has a wealth of information, a FAQ and message forum for user questions.

 Exiftool is also available via your distribution's package repositories, which is how we'll install it in this tutorial.

 For Debian based distributions, install the libimage-exiftool-perl package using apt:

sudo apt install libimage-exiftool-perl

![Terminal window showing command to install exiftool on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-18.png) 

 For Redhat distros, use dnf to install the perl-Image-ExifTool package:

sudo dnf install perl-Image-ExifTool

![Terminal window showing command to install exiftool on Fedora](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-19.png) 

 For Arch distros like Manjaro, you'll install the perl-image-exiftool package with pacman:

sudo pacman -S perl-image-exiftool

![Terminal window showing command to install exiftool on Arch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Viewing Metadata on an Existing Image

![An old, red telephone booth](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/donor-1.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
Jordan Erickson / How-To Geek

 Here's a nice picture I took last year of a phone booth. Innocent enough, right? Well, now that we've got exiftool in our arsenal, let's take a look what metadata it's stowing:

exiftool donor.jpg

![Terminal window showing exiftool output with a donor image on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-all.png) 

 Compared to what could be recorded by other smartphones, this is pretty tame. You'll notice that I didn't have GPS enabled on my phone when snapping this photo since it was not recorded in the EXIF metadata. Even so, there's still other info I'd rather not share with just anyone. So let's just strip it _all_ from the image.

##  Stripping It All Out

 Removing all EXIF metadata is pretty simple:

exiftool -all= donor.jpg

![Terminal window showing command to remove EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-4-1.png) 

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The command above will create a backup of the original, appending "\_original" to the end of the filename. If you don't want this behavior, you can use:

exiftool -all= -overwrite_original donor.jpg

![Terminal window showing the command to remove all metadata and overwrite original file, not creating a backup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-5.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Verifying It's Removed Before Sharing

 Let's ensure we've gotten rid of everything before posting it online, shall we? We'll use the same command we used above to re-examine the file:

exiftool donor.jpg

![Terminal window showing command to view the nonexistent EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-6.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 Much better! There's not much here now, besides what's mandatory as per the EXIF spec.

 Posting pictures online has become ubiquitous. Of course, that doesn't mean you have to share more than you intended to. With exiftool in your arsenal, you can protect yourself and others a bit better. Additionally, along with the power of [scripting](https://common-error.techidaily.com/rebooting-woes-windows-10-troubleshooting/), you can do much more to manipulate the existing metadata in your image library than what's described in this tutorial.

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
<li><a href="https://extra-resources.techidaily.com/new-converting-srt-into-sub-quick-effective-ways/"><u>[New] Converting SRT Into SUB  Quick, Effective Ways</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ticklishtones-selecting-the-best-ringtones-for-smiles/"><u>[New] TicklishTones  Selecting the Best Ringtones for Smiles</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-avoiding-lost-sequences-with-obs-fixes/"><u>[Updated] 2024 Approved  Avoiding Lost Sequences with OBS Fixes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-guide-to-saving-games-on-windows-10-pro-for-2024/"><u>[Updated] Guide to Saving Games on Windows 10 Pro for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-transforming-flat-text-into-3d-masterpieces-photo-for-2024/"><u>[Updated] Transforming Flat Text Into 3D Masterpieces PHOTO for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-easy-steps-to-capture-iphone-screens-seamlessly/"><u>2024 Approved  Easy Steps to Capture iPhone Screens Seamlessly</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721105275449-bluetooth-troubles-solve-your-qualcomm-atheros-driver-problems-on-windows-10-today/"><u>Bluetooth Troubles? Solve Your Qualcomm Atheros Driver Problems on Windows 10 Today!</u></a></li>
<li><a href="https://techtrends.techidaily.com/comparing-ps5-console-models-the-differences-between-ps5-slim-and-standard-ps5/"><u>Comparing PS5 Console Models: The Differences Between PS5 Slim and Standard PS5</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-top-tier-streaming-options-dominating-2024s-entertainment-scene/"><u>Discover the Top-Tier Streaming Options Dominating 2024'S Entertainment Scene</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-the-ins-and-outs-of-apples-planned-home-robot-pricing-predictions-release-dates-and-technical-specifications/"><u>Discovering the Ins and Outs of Apple's Planned Home Robot: Pricing Predictions, Release Dates, and Technical Specifications</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-methods-for-deleting-programs-on-a-mac-computer/"><u>Easy Methods for Deleting Programs on a Mac Computer</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-solutions-when-your-windows-10-search-function-fails/"><u>Easy Solutions When Your Windows 10 Search Function Fails</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-screen-sharing-techniques-for-lg-branded-4k-televisions/"><u>Effortless Screen Sharing Techniques for LG Branded 4K Televisions</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-realtek-memory-card-reader-up-and-running-on-windows-11/"><u>Get Your Realtek Memory Card Reader Up & Running on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/how-to-join-google-meet-for-2024/"><u>How to Join Google Meet for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-use-chromecast-for-seamless-pc-screen-mirroring-on-your-home-television-setup/"><u>How to Use Chromecast for Seamless PC Screen Mirroring on Your Home Television Setup</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-master-level-techniques-for-attaching-srt-to-mp4-clips/"><u>In 2024, Master Level Techniques for Attaching SRT to MP4 Clips</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722892500504-inside-scoop-on-apples-futuristic-foldable-phone-anticipated-cost-scheduled-release-key-specs-and-exciting-rumors/"><u>Inside Scoop on Apple's Futuristic Foldable Phone - Anticipated Cost, Scheduled Release, Key Specs & Exciting Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/iphone-15-pro-max-vs-galaxy-s24-ultra-comparing-features-and-performance/"><u>IPhone 15 Pro Max Vs. Galaxy S24 Ultra: Comparing Features and Performance</u></a></li>
<li><a href="https://techtrends.techidaily.com/latest-comprehensive-guide-linksys-default-passwords-july-2024-update/"><u>Latest Comprehensive Guide: Linksys Default Passwords July 2024 Update</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-connection-a-comprehensive-walkthrough-for-linking-a-ps4-pad/"><u>Master the Connection: A Comprehensive Walkthrough for Linking a PS4 Pad</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-hurdles-a-comprehensive-guide-to-uploading-problems-on-instagram-stories/"><u>Overcoming Hurdles: A Comprehensive Guide to Uploading Problems on Instagram Stories</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-mapi32dll-file-not-found-step-by-step-guide/"><u>Resolving 'Mapi32.dll' File Not Found - Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/save-your-money-stream-more-tips-for-getting-netflix-without-the-price-tag/"><u>Save Your Money, Stream More: Tips for Getting Netflix Without the Price Tag</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-removing-your-likes-from-every-track-on-spotify/"><u>Step-by-Step Guide: Removing Your Likes From Every Track on Spotify</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-how-to-clean-up-your-friend-list-by-removing-multiples-on-snapchat/"><u>Step-by-Step Tutorial: How to Clean Up Your Friend List by Removing Multiples on Snapchat</u></a></li>
<li><a href="https://techtrends.techidaily.com/taylor-swift-cinematic-journey-how-to-binge-her-entire-movie-collection/"><u>Taylor Swift Cinematic Journey: How to Binge Her Entire Movie Collection</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-battle-of-viewing-choices-cable-television-vs-ott-streaming-explained/"><u>The Battle of Viewing Choices: Cable Television Vs. OTT Streaming Explained</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-epic-showdown-amds-epyc-processors-vs-nvidias-arm-powered-grace-who-wins-on-performance-double-the-speed-revealed/"><u>The Epic Showdown: AMD's EPYC Processors Vs. Nvidia's ARM-Powered Grace - Who Wins on Performance? Double the Speed Revealed!</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722871543949-ultimate-guide-resolving-the-notorious-blue-screen-of-death/"><u>Ultimate Guide: Resolving the Notorious 'Blue Screen of Death'</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-list-of-free-hdd-and-ssd-checkers-updates-for-july-202n4/"><u>Ultimate List of Free HDD & SSD Checkers: Updates for July 202N4</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-online-interactions-on-facebook-twitter-instagram-and-youtube/"><u>Understanding Online Interactions on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-7-secrets-to-improve-your-machines-speeding-capabilities/"><u>Unveiling 7 Secrets to Improve Your Machine's Speeding Capabilities</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-is-the-concept-of-wi-fi-calling-and-how-it-works/"><u>What Is the Concept of Wi-Fi Calling and How It Works?</u></a></li>
</ul></div>
