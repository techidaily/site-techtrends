---
title: How To Turn Off the 'For You Page' Suggestions on Instagram Easily
date: 2024-08-18T21:25:57.051Z
updated: 2024-08-19T21:25:57.051Z
categories:
  - BestProducts
description: This Article Describes How To Turn Off the 'For You Page' Suggestions on Instagram Easily
excerpt: This Article Describes How To Turn Off the 'For You Page' Suggestions on Instagram Easily
thumbnail: https://www.lifewire.com/thmb/WrBuxX4mP0MaLiNpfnsihklt_ls=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-932007804-c6377c1eabd346b28f376de9bbf2e441.jpg
---

## Effortless Typography Tweaks in Windows 11 – Learn How to Change Fonts Easily
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### What to Know

* Go to**Settings** \>**Personalization** \>**Fonts** to find the name of the font you want to use throughout Windows 11.
* Then, create a REG file using that name to replace the current system font. Open the REG file to change the font.
* Not all Windows fonts will change, but some do. It's easy to restore the default font if you change your mind.

 This article teaches you how to change the Windows 11 system font so that various areas of the OS will use the font type you prefer. It also covers how to undo these steps to restore the default font.

## How to Change the System Font in Windows 11

 The quickest way to change the Windows 11 font is through a Windows Registry edit, which we'll do by creating a[REG file](https://www.lifewire.com/how-to-create-edit-and-use-reg-files-2622817) .

1. Open Settings, then select**Personalization** on the left, followed by**Fonts** on the right. Another way to get there is through the Run command:**ms-settings:fonts** .  
![The Personalization settings in Windows 11](https://www.lifewire.com/thmb/SJdYi81a1Rm29jJ6p7V24JP49ss=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/personalization-settings-windows-11-83afd8d0867d4d39a1b87dff59dd8fae.png)
2. Scroll down to**Available fonts** , and find and select the font you're interested in using.  
 If you don't see the font you want, you can take this time to download it. Lots of websites have free fonts, but you can also[buy fonts online](https://www.lifewire.com/buy-fonts-for-desktop-publishing-1077714) . Then, return to this area of Settings to see it. Our[How to Install Fonts in Windows 11](https://www.lifewire.com/install-fonts-in-windows-11-5192443) guide can help if you need it.
3. Locate the**Full name** line in the**Metadata** section, and write it down exactly as it's written. In our example, we recorded**Franklin Gothic Medium** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Full Name and Franklin Gothic Medium highlighted in Windows 11 font settings](https://www.lifewire.com/thmb/TLWCZLK0sdGg9XBIj1y4Ma1EuAA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_how-to-change-the-font-in-windows-11-6827640-97099a55349a45e392459345af24caf1.jpg)
4. Open Notepad, or a[different text editor](https://www.lifewire.com/best-free-text-editors-4155819) if you prefer, and paste the following:  
 `Windows Registry Editor Version 5.00`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"=""`  
`"Segoe UI Bold (TrueType)"=""`  
`"Segoe UI Bold Italic (TrueType)"=""`  
`"Segoe UI Italic (TrueType)"=""`  
`"Segoe UI Light (TrueType)"=""`  
`"Segoe UI Semibold (TrueType)"=""`  
`"Segoe UI Symbol (TrueType)"=""`  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"="Franklin Gothic Medium"`
5. In the last line of the document, replace**Franklin Gothic Medium** with the name of the font you recorded in Step 3 (keep the quotes around the name).  
![Franklin Gothic Medium highlighted in Windows Notepad with REG file contents](https://www.lifewire.com/thmb/5UM6sKcUZ5_xlc9vkHeFpUtlwpk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-change-the-font-in-windows-11-6827640-babf346069c14d8caa00e4c43d7992b6.jpg)
6. If you're using Notepad, go to**File** \>**Save as** , and type a name in the**File name** box.
7. Choose**All files** from the**Save as type** menu.
8. Type**.reg** at the end of the file name. Our example reads**Franklin Gothic.reg** , but yours can be called whatever you want; just make sure it ends with that file extension.
9. Choose a folder on your computer to save the file (the Desktop folder works), and then select**Save** .  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![FranklinGothic.reg and Save highlighted in a Notepad document with REG file extension](https://www.lifewire.com/thmb/4p0dmSoOCDSVSqxK6o9QnPtNX1U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-change-the-font-in-windows-11-6827640-9563197f19ae4d848482def07b741adc.jpg)
10. Close the text editor, and then double-click or double-tap the REG file from the folder you just saved it to.
11. Press**Yes** on the User Account Control window, then**Yes** again on the Registry Editor prompt (pictured below), and finally**OK** on the success message.  
![Yes highlighted in the Registry Editor prompt in Windows 11](https://www.lifewire.com/thmb/tViUCj2SD1eHRKNxSY2gP3-IusQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-change-the-font-in-windows-11-6827640-acbf618a85854ff58bb4ca6f3a0d7384.jpg)
12. [Reboot your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see the font changes. The quickest method is to right-click the Start button and go to**Shut down or sign out** \>**Restart** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does Changing the System Font Do?

 Changing the computer font in Windows 11 will switch up the way text looks throughout the operating system. Desktop icon text and the links in Control Panel are a couple of examples, but it's most obvious in other areas, such as the Run dialog box.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Windows 11 font type change in Run and Control Panel](https://www.lifewire.com/thmb/eN6m7hD9Mgh_sWhJB-Jl9QOeR2c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-11-changed-font-type-control-panel-run-desktop-365bc4a2e315498f96aa4115713f7d59.png)

 However, not every part of Windows will change to the new font. All the text within Settings, Start menu, Clock, Quick Settings, and numerous other areas aren't affected.

[Troubleshooting Installed Fonts That Won't Work](https://www.lifewire.com/cant-use-installed-fonts-1074154)

## How to Restore the Default Font in Windows 11

 The best way to get the original Windows 11 font back is to reverse the registry tweak that changed it in the first place. To do that, repeat the steps from above, but replace the Notepad text with different code.

 You can do this one of two ways. This first method is easiest only if you still have the original REG file:

1. Right-click the REG file from wherever you saved it during Step 9, and select**Edit in Notepad** .
2. Highlight all the text that's in there, and replace it with this:  
 `Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"="segoeui.ttf"`  
`"Segoe UI Black (TrueType)"="seguibl.ttf"`  
`"Segoe UI Black Italic (TrueType)"="seguibli.ttf"`  
`"Segoe UI Bold (TrueType)"="segoeuib.ttf"`  
`"Segoe UI Bold Italic (TrueType)"="segoeuiz.ttf"`  
`"Segoe UI Emoji (TrueType)"="seguiemj.ttf"`  
`"Segoe UI Historic (TrueType)"="seguihis.ttf"`  
`"Segoe UI Italic (TrueType)"="segoeuii.ttf"`  
`"Segoe UI Light (TrueType)"="segoeuil.ttf"`  
`"Segoe UI Light Italic (TrueType)"="seguili.ttf"`  
`"Segoe UI Semibold (TrueType)"="seguisb.ttf"`  
`"Segoe UI Semibold Italic (TrueType)"="seguisbi.ttf"`  
`"Segoe UI Semilight (TrueType)"="segoeuisl.ttf"`  
`"Segoe UI Semilight Italic (TrueType)"="seguisli.ttf"`  
`"Segoe UI Symbol (TrueType)"="seguisym.ttf"`  
`"Segoe MDL2 Assets (TrueType)"="segmdl2.ttf"`  
`"Segoe Print (TrueType)"="segoepr.ttf"`  
`"Segoe Print Bold (TrueType)"="segoeprb.ttf"`  
`"Segoe Script (TrueType)"="segoesc.ttf"`  
`"Segoe Script Bold (TrueType)"="segoescb.ttf"`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"=-`
3. Save the file.
4. Exit Notepad, and then open the REG file. Accept all the prompts to edit the registry.
5. If the changes don't take effect immediately (they did for us), reboot your computer.

 If you don't have the original REG file readily available to edit, just repeat the steps at the top of this page. When you get to the part about pasting the code into Notepad, use the modified code from Step 2 above, and don't make any changes to it.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing Other Fonts in Windows 11

 The method outlined in this article isn't how it typically works when you want to use a new font in Windows. The directions explained above are unique for two reasons: Windows doesn't have a built-in way to change the system font, and you're changing the_system_ font, not just the font type for a single app.

 Most programs have their own font settings so you can make changes that apply to just that one program. And doing it is extremely easy because Windows 11_does_ provide a way to easily install a font that can be used by any of your software.

 For example, if you've downloaded a font you'd like to use in Microsoft Word,[install the font to your computer](https://www.lifewire.com/install-fonts-in-windows-11-5192443) , and it'll be available the next time you open Word. That's usually how it works: install the fonts to your computer to give all your programs access to them.

 You can, for instance, change the default font and size in Outlook by choosing an installed font. The same applies when you[pick a new default font for Thunderbird emails](https://www.lifewire.com/change-default-font-thunderbird-1173143) . Online apps need separate instructions since they don't typically access local fonts:[here's how to edit Gmail's default font options](https://www.lifewire.com/change-the-default-compose-font-face-and-color-in-gmail-1171898) in your browser.

 With some programs, there's a special folder in the app's installation directory that's used to load fonts for that one piece of software. This is how you[install fonts just for Photoshop](https://www.lifewire.com/installing-fonts-for-photoshop-only-1702271) .

[How to Manage Your Fonts in Windows](https://www.lifewire.com/too-many-windows-fonts-1077817)

 FAQ

* How do I change the font size on my Windows desktop icons?  
 To change the default text size in Windows 11, go to**Start** \>**Settings** \>**Accessibility** \>**Text size** . Use the slider to adjust the preview text size and select**Apply** .
* What font is used in Windows?  
 The default system font for Windows 11 is called Segoe UI. Pronounced “see-go,” this is the standard font for all Microsoft products.
* How do I change the default font in Microsoft Office?  
 You can[change the default font in Microsoft Office](https://www.lifewire.com/change-default-font-in-microsoft-office-2511891) apps by creating a template. For example, in Microsoft Word, create a new template and go to the**Home** tab, then right-click any style. Select**Modify** , then choose a font under**Formatting** . Make sure**New documents based on this template** is selected, then select**OK** .

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
<li><a href="https://techtrends.techidaily.com/subway-surfers-cheatsheet-advanced-play-methods-from-gaming-pros/"><u>'Subway Surfers' Cheatsheet: Advanced Play Methods From Gaming Pros</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-boost-your-like-ratio-tips-for-squaring-up-videos-for-2024/"><u>[New] Boost Your Like Ratio  Tips for Squaring Up Videos for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-parts-to-proficiency-assembling-a-powerhouse-4k-video-editor-pc/"><u>[Updated] From Parts to Proficiency  Assembling a Powerhouse 4K Video Editor PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-privacy-pioneers-explore-instagram-stories-secretly/"><u>[Updated] In 2024, Privacy Pioneers  Explore Instagram Stories Secretly</u></a></li>
<li><a href="https://techtrends.techidaily.com/boosting-your-twitter-following-proven-strategies-and-tips/"><u>Boosting Your Twitter Following: Proven Strategies and Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/customizing-your-pc-tips-for-altering-the-color-of-the-taskbar-in-windows-11/"><u>Customizing Your PC: Tips for Altering the Color of the Taskbar in Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/definitive-steps-to-permanent-deletion-of-your-account-on-yahoo-mail-services/"><u>Definitive Steps to Permanent Deletion of Your Account on Yahoo Mail Services</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-repairing-a-frozen-apple-watch-face-screen/"><u>Diagnosing and Repairing a Frozen Apple Watch Face Screen</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-online-speed-on-your-mac-by-resetting-dns-settings/"><u>Enhance Online Speed on Your Mac by Resetting DNS Settings</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tips-to-address-helperdll-cant-be-found-mistake/"><u>Essential Tips to Address Helper.dll Can't Be Found Mistake</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-advice-restoring-lost-keys-on-your-computers-keyboard/"><u>Expert Advice: Restoring Lost Keys on Your Computer's Keyboard</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-strategies-for-effective-gopro-time-lapse-footage/"><u>Expert Strategies for Effective GoPro Time-Lapse Footage</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-concept-of-output-impedance-what-you-need-to-know/"><u>Exploring the Concept of Output Impedance: What You Need to Know</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-great-divide-comparing-chatgpt-and-bing-ai-in-10-key-ways/"><u>Exploring The Great Divide: Comparing ChatGPT and Bing AI in 10 Key Ways</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-infinix-zero-30-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Infinix Zero 30 5G FRP Locks</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-clear-cache-and-cookies-in-every-major-browser/"><u>How to Clear Cache and Cookies in Every Major Browser</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-setup-hdmi-connection-between-laptop-and-tv-a-comprehensive-walkthrough/"><u>How To Setup HDMI Connection Between Laptop & TV – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-15-plus-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 15 Plus with 3 Methods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-techniques-to-enhance-your-slow-motion-photos-for-instagram-audiences/"><u>In 2024, Techniques to Enhance Your Slow Motion Photos for Instagram Audiences</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unique-soundscapes-for-your-one-person-show/"><u>In 2024, Unique Soundscapes for Your One-Person Show</u></a></li>
<li><a href="https://techtrends.techidaily.com/infusing-accessibility-how-to-enable-transcript-features-for-ig-stories/"><u>Infusing Accessibility: How to Enable Transcript Features for IG Stories</u></a></li>
<li><a href="https://techtrends.techidaily.com/legal-ways-to-discover-someones-mobile-number-online/"><u>Legal Ways to Discover Someone’s Mobile Number Online</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-capturing-images-of-your-desktop-screen/"><u>Step-by-Step Guide: Capturing Images of Your Desktop Screen</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-definitive-techniques-to-keep-your-mechanical-keyboard-spotless/"><u>The Definitive Techniques to Keep Your Mechanical Keyboard Spotless</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-six-most-effective-money-saving-website-sources-for-deals-and-coupon-savings/"><u>The Six Most Effective Money-Saving Website Sources for Deals and Coupon Savings</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-fixes-for-missing-or-unavailable-d3d9dll-on-your-pc/"><u>The Ultimate Fixes for Missing or Unavailable d3d9.dll on Your PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-features-to-evaluate-before-purchasing-your-next-projector/"><u>Top Features to Evaluate Before Purchasing Your Next Projector</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-restoring-deleted-messages-on-gmail/"><u>Ultimate Guide: Restoring Deleted Messages on Gmail</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-time-lapse-magic-the-best-apps-for-capturing-stunning-videos-on-iphone-and-android/"><u>Updated Time-Lapse Magic The Best Apps for Capturing Stunning Videos on iPhone and Android</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722851932959-vizio-televisions-and-wi-fi-woes-heres-how-you-can-fix-it/"><u>Vizio Televisions and Wi-Fi Woes? Here's How You Can Fix It!</u></a></li>
</ul></div>
