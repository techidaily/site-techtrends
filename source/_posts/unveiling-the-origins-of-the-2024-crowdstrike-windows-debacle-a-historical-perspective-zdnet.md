---
title: Unveiling the Origins of the 2024 CrowdStrike Windows Debacle – A Historical Perspective | ZDNet
date: 2024-10-02T16:33:36.931Z
updated: 2024-10-04T16:09:41.729Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/d23b1bfe46d7327ba14e76a44acc0f6ab574b958/2024/07/22/8a1c7b1d-5462-44b0-ad87-f790f10be8d9/gettyimages-2162005028.jpg?width=170&height=96&fit=crop&auto=webp
---

## Unveiling the Truth: How CrowdStrike and Windows Experienced a Major Meltdown – A Historical Perspective | Tech Insights

![blue screens of death](https://www.zdnet.com/a/img/resize/eac9d76c42c0a34ae6e396e98f44792477293162/2024/07/22/8a1c7b1d-5462-44b0-ad87-f790f10be8d9/gettyimages-2162005028.jpg?auto=webp&width=1280)

Harun Ozalp/Anadolu via Getty Images

_\[Updated 24-July with details from CrowdStrike's preliminary post-incident review\]_

Microsoft Windows powers more than a billion PCs and millions of servers worldwide, many of them playing key roles in facilities that serve customers directly. So, what happens when a trusted software provider delivers an update that causes those PCs to immediately stop working?

As of July 19, 2024, we know the answer to that question: Chaos ensues.

**Also: [7 password rules to live by in 2024, according to security experts](https://www.zdnet.com/article/7-password-rules-to-live-by-in-2024-according-to-security-experts/)**

In this case, the trusted software developer is a firm called CrowdStrike Holdings, whose previous claim to fame was being the security firm that analyzed the 2016 hack of servers owned by the Democratic National Committee. That's just a quaint memory now, as the firm will forever be known as The Company That Caused [The Largest IT Outage In History](https://www.zdnet.com/article/crowdstrike-causes-windows-outage-chaos-for-airports-banks-and-more-heres-what-happened/). It grounded airplanes, cut off access to some banking systems, disrupted major healthcare networks, and threw at least one news network off the air.

[Microsoft estimates](https://blogs.microsoft.com/blog/2024/07/20/helping-our-customers-through-the-crowdstrike-outage/) that the CrowdStrike update affected 8.5 million Windows devices. That's a tiny percentage of the worldwide installed base, but as David Weston, Microsoft's Vice President for Enterprise and OS Security, notes, "the broad economic and societal impacts reflect the use of CrowdStrike by enterprises that run many critical services." According to [a Reuters report](https://www.reuters.com/technology/cybersecurity/crowdstrike-update-that-caused-global-outage-likely-skipped-checks-experts-say-2024-07-20/), "Over half of Fortune 500 companies and many government bodies such as the top US cybersecurity agency itself, the Cybersecurity and Infrastructure Security Agency, use the company's software."

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What happened?

CrowdStrike, which sells security software designed to keep systems safe from external attacks, pushed a faulty ["sensor configuration update"](https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/) to the millions of PCs worldwide running its Falcon Sensor software. That update was, according to CrowdStrike, a "Channel File" whose function was to identify newly observed, malicious activity by cyberattackers.

Although the update file had a .sys extension, it was not itself a kernel driver. It communicates with other components in the Falcon sensor that run in the same space as the Windows kernel, the most privileged level on a Windows PC, where they interact directly with memory and hardware. CrowdStrike says a "logic error" in that code caused Windows PCs and servers to crash within seconds after they booted up, displaying a STOP error, more colloquially known as the Blue Screen of Death (BSOD).

**Also: [Microsoft is changing how it delivers Windows updates: 4 things you need to know](https://www.zdnet.com/article/microsoft-is-changing-how-it-delivers-windows-updates-4-things-you-need-to-know/)**

In a [Preliminary Post Incident Review](https://www.crowdstrike.com/falcon-content-update-remediation-and-guidance-hub/) posted on its website July 24, CrowdStrike confirmed some details about the incident that had previously been reported and added a few more. The code that failed was part of the Falcon sensor, which runs in the Windows kernel space. Version 7.11 of the sensor was released on February 28, 2024\. According to CrowdStrike, this release introduced "a new \[InterProcess Communication (IPC)\] Template Type to detect novel attack techniques that abuse Named Pipes. This release followed all Sensor Content testing procedures..."

Three additional instances of the IPC Template Type were deployed between April 8 and April 24, without incident. On July 19, the company says, "two additional IPC Template Instances were deployed. Due to a bug in the Content Validator, one of the two Template Instances passed validation despite containing problematic content data." Those instances were deployed into production. "When received by the sensor and loaded into the Content Interpreter," the report continues, "problematic content in Channel File 291 resulted in an out-of-bounds memory read triggering an exception. This unexpected exception could not be gracefully handled, resulting in a Windows operating system crash (BSOD)."

**Also: [Who needs ransomware when a faulty software update can shut down critical infrastructure?](https://www.zdnet.com/article/who-needs-ransomware-when-a-faulty-software-update-can-shut-down-critical-infrastructure/)**

Repairing the damage from a flaw like this is a painfully tedious process that requires manually rebooting every affected PC into the Windows Recovery Environment and then deleting the defective file from the PC using the old-school command line interface. If the PC in question has its system drive protected by Microsoft's BitLocker encryption software, as virtually all business PCs do, the fix requires one extra step: entering a unique 48-character BitLocker recovery key to gain access to the drive and allow the removal of the faulty CrowdStrike driver.

If you know anyone whose job involves administering Windows PCs in a corporate network that uses the CrowdStrike code, you can be confident they are very busy right now, and will be for days to come.

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## We've seen this movie before

When I first heard about this catastrophe (and I am not misusing that word, I assure you), I thought it sounded familiar. On Reddit's Sysadmin Subreddit, user u/externedguy [reminded me why](https://www.reddit.com/r/sysadmin/comments/1e7488p/turns%5Fout%5Fceo%5Fof%5Fcrowdstrike%5Fis%5Fformer%5Fcto%5Fof/). Maybe you remember this story from 14 years ago:

> **["Defective McAfee update causes worldwide meltdown of XP PCs."](https://www.zdnet.com/article/defective-mcafee-update-causes-worldwide-meltdown-of-xp-pcs/)**
> 
> Oops, they did it again.
> 
> At 6AM today, McAfee released an update to its antivirus definitions for corporate customers that had a slight problem. And by "slight problem," I mean the kind that renders a PC useless until tech support shows up to repair the damage manually. As I commented on Twitter earlier today, I'm not sure any virus writer has ever developed a piece of malware that shut down as many machines as quickly as McAfee did today.

In that case, McAfee had delivered a faulty virus definition (DAT) file to PCs running Windows XP. That file falsely detected a crucial Windows system file, Svchost.exe, as a virus and deleted it. The result, according to [a contemporary report](https://isc.sans.edu/diary/McAfee+DAT+5958+Update+Issues/8656), is that "affected systems will enter a reboot loop and \[lose\] all network access."

**Also: [The best VPN services: Expert tested and reviewed](https://www.zdnet.com/article/best-vpn/)**

The parallels between that 2010 incident and this year's CrowdStrike outage are uncanny. At its core was a defective update, pushed to millions of PCs running a powerful software agent, causing the affected devices to stop working. Recovery required manual intervention on every single device. Plus, the flawed code was pushed out by a public security company desperately trying to grow in a brutally competitive marketplace.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

The timing was particularly unfortunate for McAfee. Intel had [announced its intention to acquire McAfee for $7.68 billion](https://www.intc.com/news-events/press-releases/detail/733/intel-to-acquire-mcafee) on April 19, 2010\. The defective DAT file was released two days later, on April 21.

That 2010 McAfee screw-up was a big deal, kneecapping Fortune 500 companies (including Intel!) as well as universities and government/military deployments worldwide. It knocked 10% of the cash registers at Australia's largest grocery chain offline, forcing the closure of 14 to 18 stores.

**Also: [5 ways to save your Windows 10 PC in 2025 - and most are free](https://www.zdnet.com/article/5-ways-to-save-your-windows-10-pc-in-2025-and-most-are-free/)**

In the You Can't Make This Up Department… CrowdStrike's founder and CEO, George Kurtz, was McAfee's Chief Technology Officer during that 2010 incident.

What makes the 2024 sequel so much worse is that it also affected Windows-based servers running in the cloud, on Microsoft Azure and on AWS. Just as with the many laptops and desktop PCs that were bricked by this faulty update, the cloud-based servers require time-consuming manual interventions to recover.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CrowdStrike's QA failed

Surprisingly, this isn't CrowdStrike's first faulty Falcon sensor update this year.

Less than a month earlier, [according to a report from The Stack](https://www.thestack.technology/crowdstrike-bug-maxes-out-100-of-cpu-requires-windows-reboots/), CrowdStrike released a detection logic update for the Falcon sensor that exposed a bug in the sensor's Memory Scanning feature. "The result of the bug," CrowdStrike wrote in a customer advisory, "is a logic error in the CsFalconService that can cause the Falcon sensor for Windows to consume 100% of a single CPU core." The company rolled back the update, and customers were able to resume normal operations by rebooting.

**Also: [When Windows 10 support runs out, you have 5 options but only 2 are worth considering](https://www.zdnet.com/article/when-windows-10-support-ends-you-have-5-options-but-only-2-are-worth-considering/)**

At the time, computer security expert Will Thomas [noted on X/Twitter](https://x.com/BushidoToken/status/1806630671051378868), "\[T\]his just goes to show how important it is to download new updates to one machine to test it first before rolling out to the whole fleet!" 

In that 2010 incident, the root cause turned out to be [a complete breakdown of the QA process](https://www.zdnet.com/article/mcafee-admits-inadequate-quality-control-caused-pc-meltdown/). It seems self-evident that a similar failure in QA is at work here. Were these two CrowdStrike updates not tested before they were pushed out to millions of devices?

Part of the problem might be a company culture that's long on tough talk. In the most recent CrowdStrike earnings call, CEO George Kurtz boasted about the company's ability to "ship game-changing products at a rapid pace," taking special aim at Microsoft:

> And more recently, following yet another major Microsoft breach in CIS' Cyber Safety Review Board's findings, we received an outpouring of requests from the market for help. We decided enough is enough, there's a widespread crisis of confidence among security and IT teams within the Microsoft security customer base.
> 
> \[…\]
> 
> Feedback has been overwhelmingly positive. CISAs now have the ability to reduce monoculture risk from only using Microsoft products and cloud services. Our innovation continues at breakneck pace multiplying the reasons for the market to consolidate on Falcon. Thousands of organizations are consolidating on the Falcon platform.

Given recent events, some of those customers might be wondering whether that "breakneck pace" is part of the problem.

As part of its initial response, CrowdStrike says it plans to take additional measures to improve "software resiliency and testing." More importantly, it plans to implement a "staggered deployment strategy ... in which updates are gradually deployed to larger portions of the sensor base, starting with a canary deployment." The company also committed to provide customers with "greater control over the delivery of Rapid Response Content updates by allowing granular selection of when and where these updates are deployed."

Meanwhile, the United States House of Representatives Homeland Security Committee plans to call CrowdStrike's CEO up for hearings on what went wrong, and CrowdStrike's Chief Security Officer, Shawn Henry, [posted an apology on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7220983915421806592/), admitting "On Friday, we failed you. ... The confidence we built in drips over the years was lost in buckets within hours, and it was a gut punch."

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How much fault should Microsoft shoulder?

It's impossible to let Microsoft completely off the hook. After all, the Falcon sensor problems were unique to Windows PCs, as admins of Linux and Mac-focused shops were quick to remind us.

Partly, that's an architectural issue. Developers of system-level apps for Windows, including security software, historically implement their features using kernel extensions and drivers. As this example illustrates, faulty code running in the kernel space can cause unrecoverable crashes, whereas code running in user space can't.

**Also: [7 ways to make Windows 11 less annoying](https://www.zdnet.com/article/seven-ways-to-make-windows-11-less-annoying/)**

That used to be the case with MacOS as well, but in 2020, with MacOS 11, Apple changed the architecture of its flagship OS to [strongly discourage the use of kernel extensions](https://support.apple.com/guide/security/securely-extending-the-kernel-sec8e454101b/web). Instead, developers are urged to write system extensions that run in user space rather than at the kernel level. On MacOS, CrowdStrike [uses Apple's Endpoint Security Framework](https://ir.crowdstrike.com/news-releases/news-release-details/crowdstrike-bolsters-endpoint-protection-platform-new) and says using that design, "Falcon achieves the same levels of visibility, detection, and protection exclusively via a user space sensor."

Could Microsoft make the same sort of change for Windows? Perhaps, but doing so would certainly bring down the wrath of antitrust regulators, especially in Europe. The problem is especially acute because Microsoft has a lucrative enterprise security business, and any architectural change that makes life more difficult for competitors like CrowdStrike would be rightly seen as anticompetitive.

Indeed, a Microsoft spokesperson told the Wall Street Journal that it can't follow Apple's lead because of antitrust concerns. [According to the WSJ report](https://www.wsj.com/tech/cybersecurity/microsoft-tech-outage-role-crowdstrike-50917b90?st=n4q3srxshb10vz3&reflink=desktopwebshare%5Fpermalink), "In 2009, Microsoft agreed it would give makers of security software the same level of access to Windows that Microsoft gets." That concern might be open for debate, but given Microsoft's history with EU regulators, it's understandable why the company hasn't wanted to get tangled up in that argument. 

Microsoft currently [offers APIs for Microsoft Defender for Endpoint](https://learn.microsoft.com/en-us/defender-endpoint/api/apis-intro), but competitors aren't likely to use them. They'd much rather argue that their software is superior, and using the "inferior" offering from Microsoft would be hard to explain to customers.

Nonetheless, this incident, which caused many billions of dollars' worth of damage, should be a wake-up call for the entire IT community. At a minimum, CrowdStrike needs to step up its testing game, and customers need to be more cautious about allowing this sort of code to deploy on their networks without testing it themselves.

#### Featured

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[20 years later, real-time Linux makes it to the kernel - really](https://www.zdnet.com/article/20-years-later-real-time-linux-makes-it-to-the-kernel-really/ "20 years later, real-time Linux makes it to the kernel - really")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[Want a programming job? Learn these three languages](https://www.zdnet.com/article/want-a-programming-job-learn-these-three-languages/ "Want a programming job? Learn these three languages")

* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [20 years later, real-time Linux makes it to the kernel - really](https://www.zdnet.com/article/20-years-later-real-time-linux-makes-it-to-the-kernel-really/ "20 years later, real-time Linux makes it to the kernel - really")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [Want a programming job? Learn these three languages](https://www.zdnet.com/article/want-a-programming-job-learn-these-three-languages/ "Want a programming job? Learn these three languages")

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
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-financial-gains-the-youtube-money-flow-from-1m-views/"><u>[Updated] 2024 Approved Financial Gains The Youtube Money Flow From 1M Views</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-google-pixel-7a-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Google Pixel 7a PC | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/find-and-update-your-toshiba-laptops-drivers-on-microsoft-windows-today/"><u>Find and Update Your Toshiba Laptop's Drivers on Microsoft Windows - Today</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-honor-90-lite-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Honor 90 Lite to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-decoding-the-secrets-behind-iconic-mukbang-videos/"><u>In 2024, Decoding the Secrets Behind Iconic Mukbang Videos</u></a></li>
<li><a href="https://win-amazing.techidaily.com/logitech-driver-download-for-windows-quickly-and-easily/"><u>Logitech Driver Download for Windows. Quickly & Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-your-livestreams-advanced-features-of-manycam-and-online-webcams/"><u>Master Your Livestreams: Advanced Features of ManyCam and Online Webcams</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-manycam-a-step-by-step-guide-to-crafting-custom-video-filters/"><u>Mastering ManyCam: A Step-by-Step Guide to Crafting Custom Video Filters</u></a></li>
<li><a href="https://extra-information.techidaily.com/motorcycles-viewfinder-gems-top-5-helmets-with-hats-for-the-modern-rider/"><u>Motorcycle's Viewfinder Gems – Top 5 Helmets with Hats for the Modern Rider</u></a></li>
<li><a href="https://techtrends.techidaily.com/multiplecam-ultimate-live-streaming-app-and-fake-camera-solution/"><u>MultipleCam: Ultimate Live Streaming App and Fake Camera Solution</u></a></li>
<li><a href="https://techtrends.techidaily.com/real-time-broadcasting-made-easy-with-manycam-the-ultimate-live-streaming-and-fake-webcam-solution/"><u>Real-Time Broadcasting Made Easy with ManyCam: The Ultimate Live Streaming & Fake Webcam Solution</u></a></li>
<li><a href="https://techtrends.techidaily.com/real-time-streaming-discover-the-versatility-of-manycam-your-ultimate-webcam-and-vr-solution/"><u>Real-Time Streaming: Discover the Versatility of ManyCam - Your Ultimate Webcam and VR Solution</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-live-streaming-tools-discover-the-power-of-manycams-virtual-webcams-and-hd-video-recording/"><u>Top Live Streaming Tools: Discover the Power of ManyCam's Virtual Webcams and HD Video Recording</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-webcam-tools-and-extensions-boost-your-doctors-visits-on-doxyme-using-manycam-features/"><u>Top Webcam Tools & Extensions: Boost Your Doctor's Visits on Doxy.me Using ManyCam Features</u></a></li>
</ul></div>

