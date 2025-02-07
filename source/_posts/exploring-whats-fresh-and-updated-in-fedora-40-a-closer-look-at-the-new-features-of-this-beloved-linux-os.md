---
title: Exploring What's Fresh and Updated in Fedora 40 - A Closer Look at the New Features of This Beloved Linux OS
date: 2025-02-06T16:10:08.569Z
updated: 2025-02-07T16:08:29.442Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/default-fedora-40-background-with-fedora-40-word-and-logo.jpg
---

## Exploring What's Fresh and Updated in Fedora 40 - A Closer Look at the New Features of This Beloved Linux OS

### Quick Links

* [Fedora at 40](https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-infinix-note-30-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Fedora's Atomic Desktops](https://article-helps.techidaily.com/new-grow-picture-dimensions-maintain-fidelity/)
* [Linux Kernel 6.8](https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-motorola-moto-e13-to-pc-drfone-by-drfone-android/)
* [The GNOME 46 Desktop](https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-xiaomi-13t-pro-frp-bypass-by-drfone-android/)
* [Application Versions](https://extra-skills.techidaily.com/2024-approved-speedy-streams-start-here-snapchat-for-starters/)
* [The Roaring Forties](https://audio-shaping.techidaily.com/updated-melody-eraser-pro-craft-personalized-instrumental-compositions/)

### Key Takeaways

* Fedora 40 boasts speed gains and GNOME 46, providing a blazing user experience.
* Fedora 40 offers Atomic Desktops that use immutable spins with rpm-ostree for specific use cases.
* Kernel 6.8 introduces improved security, operational benefits, and impressive hardware compatibility.

 Fedora Linux has hit the big four-oh! With Fedora 40 released, and the first patches available, it’s time to fire up this popular distribution and take it for a test run.

##  Fedora at 40

 They say life begins at 40\. Whether that’s true or not, Fedora Linux certainly seems to have found renewed vigor with this milestone release. Fedora was always a fast distribution, and this time round it’s even more noticeable.

 Coupled with the speed gains in the new GNOME 46 desktop, you get a blazing user experience. I don’t recall using a Linux desktop as fast as this. But as we’ll see, there’s more to Fedora 40 than speed gains and GNOME 46.

 Fedora’s official desktop is GNOME, and that’s the version we checked out. There are 10 other variants, or “spins” of Fedora 40 available, each with a different desktop environment, so you’ve got plenty of choice.

![The Fedora 40 default GNOME desktop with a wallpaper showing a blurred forest scene](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/1-9.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 Thankfully, you get a selection of bundled desktop wallpapers to choose from because the default one is too muted and drab for my liking. But don’t let that set the tone. Fedora 40 is [anything but boring](https://facebook-video-footage.techidaily.com/updated-smooth-transition-of-short-videos-to-youtube-device-guide/).

##  Fedora's Atomic Desktops

 Fedora 40 has [all the usual spins available](https://fedoraproject.org/spins/), with some additional organizational changes to immutable spins.

 The immutable spins are now called Atomic Desktops. The four Atomic Desktops are Silverblue, which uses GNOME as its desktop environment manager, Kinoite, which uses KDE Plasma, Budgie, which uses its own Budgie desktop environment, and Sway, which uses the Sway tiling manager.

 These all use [rpm-ostree](https://coreos.github.io/rpm-ostree/), which describes itself as a hybrid image and package manager system. Operating system vendors can release images that are downloaded and installed, and then modified by a collection of RPM packages on the local computer.

 Images are created, tested, and updated as required, off-line, by the vendor. Once they’re ready, they can be downloaded to the target computers, IoT devices, virtual servers, and so forth. Additional local modifications are achieved by adding applications from RPMs, in a process called _layering_.

 This gives a very granular means of rolling back from upgrades without affecting user data. These are spins intended for specific use cases, usually where the scale of installations and updates is a factor. In most cases, you’ll be better served with a regular Fedora spin.

 But, if you were wondering where the immutable spins have gone, they’re still here, but with a name change.

##  Linux Kernel 6.8

 We used a post-release version of Fedora, patched up to date. This gave us kernel version 6.8.7\. New kernels bring two categories of benefits. One is bug fixes and security patches, which are vital in helping protect your computer. The other benefits are operational improvements or new features. Kernel 6.8 delivers in both camps.

 Security is bolstered with extended support for Secure Boot and disk encryption, and the ability to “stack” Linux security modules so that you can layer your protection. Intel Shadow Stack is now supported.

 Running processes can verify their return addresses, which is the location in memory that code execution should return to when the current process has concluded. Processes can compare the value retrieved from the stack with the value retrieved from the Shadow Stack. Differences between the two values might indicate suspicious or malicious activity.

 Operational benefits include replacing the Completely Fair Scheduler (CFS) with a new Earliest Eligible Virtual Deadline First (EEVDF) CPU scheduler. The new scheduler is said to reduce latency in certain scenarios.

![The output from neofetch in a terminal on a Fedora 40 Linux computer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/12-2.png) 

Dave McKay/How-To Geek

 There’s improved hardware compatibility, laptops benefit from optimized power management, and KVM virtualization now supports up to a staggering 4096 virtual CPUs. Users of the IBM POWER processor ppc64el can nest virtual machines.

 Support for the intel\_idle CPU Idle Time Management Driver (part of the CPU idle time management subsystem) has been rolled out to the Grand Ridge and Sierra Forest processors. There’s also support for the Intel Meteor Lake graphics.

 AMD CPUs aren’t ignored, they receive a collection of performance enhancements.

 Still on the topic of security, although not specifically kernel related, many of the systemd services have security settings enabled by default to better protect them and isolate them from other processes. This means if they are compromised, the threat is more effectively contained.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The GNOME 46 Desktop

 We’ve got a detailed roundup of the new [GNOME 46 desktop environment](https://vimeo-videos.techidaily.com/new-the-ultimate-video-editing-experience-for-vimeo-enthusiasts-for-2024/), but it’s worth pointing out a few of the notable items.

 The Files file browser now searches globally by default. To search in the local directory and subdirectories only, click the new directory/magnifying glass icon beside the search field.

![Fedora 40 Files browser with the local search icon highlighted](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/2-7.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 There’s a new search facility in Preferences, making it easier to find the option you want to change.

![The Fedora 40 Files browser showing the search function in Preferences](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/3-6.png) 

Dave McKay/How-To Geek

 The copying and moving progress indicator has been relocated to the lower-left corner of the Files window. Clicking it shows further details.

![The file copying indicator in Fedora 40's Files file Browser](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/4-4.png) 

Dave McKay/How-To Geek

 The Settings application gains a System menu option, grouping together related items like Region & Language and Date & Time.

![The System option and screen in the Settings application](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/5-6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 You’ll also find a new feature under System > Remote Desktop > Remote Login. With desktop sharing enabled, this option allows you to remotely connect to your computer from an RDP client on another computer.

![The Remote Login screen in the Settings application](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/6-3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 On/Off Shapes is a new feature under Accessibility > Seeing that lets you enable or disable on/off indicators in slider controls.

![The On/Off Symbols option in the Settings application](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/7-4.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 One of the best new additions is the ability to connect to Microsoft OneDrive personal storage, and access your remote files and directories from right inside the Files browser.

 This option requires GNOME 4.6.1, so make sure you’re patched up to date.

 You’ll find the option under Online Accounts > Microsoft 365.

![The Online Accounts screen in the Preferences application with the Microsft 365 option highlighted](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/8-4.png) 

Dave McKay/How-To Geek

 Completely ignore the first dialog that pops up, just click the blue "Sign In" button.

![The Microsoft 365 Account dialog. Ignore all fields, and click the blue Sign In button](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/9-4.png) 

Dave McKay/How-To Geek

 Click the blue "Sign In" button on the next dialog that appears.

![The second Microsft 365 Account dialog. Click the blue Sign In button](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/10-3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Dave McKay/How-To Geek

 Your web browser opens, prompting you to enter your Microsoft 365 credentials. Once you’re logged in, your OneDrive will appear in the Files browser.

![The Fedora 40 Files borwser with a mounted connection to a OneDrive account](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/11-2.png) 

Dave McKay/How-To Geek

##  Application Versions

 Here are the software versions of some of the major bundled packages, and a few we installed to see what versions we received from the repositories.

* **Kernel**: 6.8.7-300.fc40.x86\_64
* **Binutils**: 2.41-34.fc40
* **GNOME**: 46.1
* **LibreOffice**: 24.2.2.1
* **Python**: 3.12.1
* **RPM**: 4.19.1.1
* **Perl**: 5.38.2
* **Boxes**: 46.0-stable
* **GCC**: 14.0.1
* **glibc**: 2.39

##  The Roaring Forties

 Fedora continues to improve, release after release, and despite hitting 40, it shows no signs of slowing down. In fact, with the speed increases in this release, you could say it has accelerated.

 With its security enhancements, remote login, and access to OneDrive storage, an upgrade to Fedora 40 is a no-brainer.

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
<li><a href="https://driver-error.techidaily.com/solved-cant-open-acpi-atk0100-kernel-mode-driver/"><u>[Solved] Can’t Open ACPI ATK0100 Kernel Mode Driver</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-from-stills-to-motion-creating-engaging-timelapse-videos-on-ipad/"><u>[Updated] From Stills to Motion Creating Engaging Timelapse Videos on iPad</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-essential-steps-to-compress-youtube-video-spaces/"><u>2024 Approved The Essential Steps to Compress YouTube Video Spaces</u></a></li>
<li><a href="https://techtrends.techidaily.com/android-users-handbook-for-making-the-most-out-of-the-measuring-tool-app/"><u>Android Users' Handbook for Making the Most Out of The Measuring Tool App</u></a></li>
<li><a href="https://techtrends.techidaily.com/finding-missed-notifications-tips-for-iphone-users/"><u>Finding Missed Notifications: Tips for iPhone Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/fix-rpcrt4dll-not-detected-problems-efficiently-and-quickly/"><u>Fix Rpcrt4.dll Not Detected Problems Efficiently and Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-unsupported-platform-detected-error-while-installing-your-intel-serial-io-driver/"><u>Fixing the 'Unsupported Platform Detected' Error While Installing Your Intel Serial IO Driver</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-turn-off-amber-alerts-on-android/"><u>How to Turn Off AMBER Alerts on Android</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-apple-iphone-15-plus-look-no-further-drfone-by-drfone-virtual-ios/"><u>Looking For A Location Changer On Apple iPhone 15 Plus? Look No Further | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/screen-partnership-contracts-downloadable-for-2024/"><u>Screen Partnership Contracts, Downloadable for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-on-how-to-disable-cortanas-copilot-feature-in-windows-11/"><u>Step-by-Step Instructions on How to Disable Cortana's Copilot Feature in Windows 11</u></a></li>
</ul></div>

