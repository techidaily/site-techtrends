---
title: "Protecting Your Photos on Linux Systems: A Step-by-Step Guide to Deleting Metadata with Exiftool"
date: 2025-02-02T16:05:48.524Z
updated: 2025-02-07T16:04:48.830Z
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

##  Installing Required Packages

 Exiftool is a platform-independent library and command line application, written in Perl, by Phil Harvey. It's available from [the official exiftool website](https://exiftool.org/), which also has a wealth of information, a FAQ and message forum for user questions.

 Exiftool is also available via your distribution's package repositories, which is how we'll install it in this tutorial.

 For Debian based distributions, install the libimage-exiftool-perl package using apt:

sudo apt install libimage-exiftool-perl

![Terminal window showing command to install exiftool on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-18.png) 

 For Redhat distros, use dnf to install the perl-Image-ExifTool package:

sudo dnf install perl-Image-ExifTool

![Terminal window showing command to install exiftool on Fedora](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-19.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For Arch distros like Manjaro, you'll install the perl-image-exiftool package with pacman:

sudo pacman -S perl-image-exiftool

![Terminal window showing command to install exiftool on Arch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1.png) 

##  Viewing Metadata on an Existing Image

![An old, red telephone booth](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/donor-1.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Jordan Erickson / How-To Geek

 Here's a nice picture I took last year of a phone booth. Innocent enough, right? Well, now that we've got exiftool in our arsenal, let's take a look what metadata it's stowing:

exiftool donor.jpg

![Terminal window showing exiftool output with a donor image on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-all.png) 

 Compared to what could be recorded by other smartphones, this is pretty tame. You'll notice that I didn't have GPS enabled on my phone when snapping this photo since it was not recorded in the EXIF metadata. Even so, there's still other info I'd rather not share with just anyone. So let's just strip it _all_ from the image.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Stripping It All Out

 Removing all EXIF metadata is pretty simple:

exiftool -all= donor.jpg

![Terminal window showing command to remove EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-4-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The command above will create a backup of the original, appending "\_original" to the end of the filename. If you don't want this behavior, you can use:

exiftool -all= -overwrite_original donor.jpg

![Terminal window showing the command to remove all metadata and overwrite original file, not creating a backup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-5.png) 

##  Verifying It's Removed Before Sharing

 Let's ensure we've gotten rid of everything before posting it online, shall we? We'll use the same command we used above to re-examine the file:

exiftool donor.jpg

![Terminal window showing command to view the nonexistent EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/new-smooth-transition-synchronizing-your-iphones-albums-with-icloud-backup-for-2024/"><u>[New] Smooth Transition Synchronizing Your iPhone's Albums with iCloud Backup for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-how-to-upload-without-rt-video-tweets/"><u>[Updated] 2024 Approved How to Upload Without RT Video Tweets</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-pixelpilot-photovideo-slide-show-for-macos/"><u>[Updated] PixelPilot Photovideo Slide Show for macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-easily-hosting-a-zoom-conference/"><u>2024 Approved Easily Hosting a Zoom Conference</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/annual-compilation-of-premium-free-lut-choices-for-2024/"><u>Annual Compilation of Premium Free LUT Choices for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-how-to-access-and-view-the-samsung-unpacked-presentation/"><u>Guide: How to Access and View the Samsung Unpacked Presentation</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-stream-your-laptop-display-on-tv-through-hdmi-connection/"><u>How to Stream Your Laptop Display on TV Through HDMI Connection?</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-microsoft-edge-exe-crashes-a-comprehensive-guide/"><u>Resolving Microsoft Edge Exe Crashes: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-fixes-for-tiktok-hiccups-getting-back-in-sync-with-the-app/"><u>The Ultimate Fixes for TikTok Hiccups: Getting Back in Sync with the App</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-steps-for-your-surface-pros-wi-fi-connection-issues/"><u>Troubleshooting Steps for Your Surface Pro's Wi-Fi Connection Issues</u></a></li>
<li><a href="https://techtrends.techidaily.com/using-household-items-a-guide-to-opening-your-iphone-sim-tray-without-a-tool/"><u>Using Household Items: A Guide to Opening Your iPhone SIM Tray without a Tool</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-tecno-pova-5-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Tecno Pova 5 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-know-about-the-upcoming-apple-watch-ultra-projections-on-price-release-schedule-specs-and-insider-rumors/"><u>What to Know About the Upcoming Apple Watch Ultra: Projections on Price, Release Schedule, Specs and Insider Rumors</u></a></li>
</ul></div>

