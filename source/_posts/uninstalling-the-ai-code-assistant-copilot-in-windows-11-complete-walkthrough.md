---
title: "Uninstalling the AI Code Assistant: Copilot in Windows 11 - Complete Walkthrough"
date: 2024-08-04 14:19:45
updated: 2024-08-06 12:27:20
categories:
  - BestProducts
description: "This Article Describes Uninstalling the AI Code Assistant: Copilot in Windows 11 - Complete Walkthrough"
excerpt: "This Article Describes Uninstalling the AI Code Assistant: Copilot in Windows 11 - Complete Walkthrough"
thumbnail: https://thmb.techidaily.com/7d6e2b9a5733a0050649c4f29381b12d84c8d65f1f8c8318505f7587599ebd84.jpg
---

## Uninstalling the AI Code Assistant: Copilot in Windows 11 - Complete Walkthrough

Close 

###  What to Know

* Open**Taskbar settings** \>**Personalization** \>**Taskbar** \> turn off the toggle switch for**Copilot in Windows** .
* In Windows 11 Home, use the Registry Editor to create a new key for Copilot.
* In Windows 11 Professional, use the Group Policy Editor to turn off Copilot.

 This guide will show you how to hide the Copilot button from the desktop and also disable the Copilot button more permanently.

##  How to Hide the Copilot Button in Windows 11 

 To hide Microsoft Copilot, use a toggle switch in your taskbar personalization settings. The fastest way to access these settings is directly from the taskbar.

1. Click an empty spot on the taskbar.  
![The Taskbar in Windows 11](https://www.lifewire.com/thmb/_tH0bsxuGgz9q4beZ3mFtwVUqoU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Windows-11-Taskbar-02634e2dbe144cedb9e516a8ec711b6d.jpg)
2. Select**Taskbar settings** from the menu.  
![The "Taskbar settings" option in Windows 11](https://www.lifewire.com/thmb/tnvgh8gkmiFdn7rT3V4k6qx0ppE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Taskbar-Settings-118f0d752c214b99a546c09aab6bdf8e.jpg)
3. Turn off the toggle switch for**Copilot in Windows** under Taskbar items.  
![Toggle switch for Copilot button in Windows 11 Settings](https://www.lifewire.com/thmb/WNlpYBDm-XOI4m0YHVGJHhjghfg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Copilot-Toggle-Windows11-d13cc8492f734d69a6fac15fd7f21da4.jpg)

##  How to Remove the Copilot Button From Settings 

 You can access the same toggle switch from the Settings screen:

1. Select**Start** \>**Settings** from the menu. Alternatively, press the**Windows** +**I** keys on your keyboard.
2. Select**Personalization** on the left, and then scroll down and open**Taskbar** . Here, you can control which buttons appear on the taskbar.  
![The Personalization menu in Windows 11 settings with the Taskbar section highlighted](https://www.lifewire.com/thmb/7u28qGRikZkwh0wgjYf2Jx735cM=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Personalization-and-Taskbar-582cfbcc54aa472c80e38830186b450b.jpg)
3. Turn off the toggle switch next to**Copilot in Windows** .  
![Toggle switch for Copilot button in Windows 11 Settings](https://www.lifewire.com/thmb/WNlpYBDm-XOI4m0YHVGJHhjghfg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Copilot-Toggle-Windows11-d13cc8492f734d69a6fac15fd7f21da4.jpg)
4. Return to the desktop. You should no longer see the Copilot button on your taskbar.

 This only hides the button; you can still open Copilot in a separate desktop sidebar by pressing the**Windows** +**C** shortcut key.

##  Can You Disable Microsoft Copilot in Windows? 

 Since Copilot is integrated into Windows 11, you can't uninstall it like a typical app. However, Windows 11 users on the Professional, Education, or Enterprise editions can use the Group Policy Editor to disable it more permanently. Users on Windows 11 Home will need to fall back on a Registry tweak.

 Once you apply these methods, Copilot won't reappear when you use the keyboard shortcut. Don't worry; these methods are reversible, allowing you to easily restore Copilot if you want to benefit from generative AI on Windows later.

##  How to Disable Copilot in Windows 11 Home 

 Touching the registry is always risky for those who are not knowledgeable about it. Always create a backup of your registry and a restore point as failsafes if things go wrong. Then, follow the steps to disable Microsoft Copilot with the Registry Editor.

1. Open**Start** and type "**registry** " in the search box to find the Registry Editor.
2. Scroll down the tree view on the left to the following registry entry:**HKEY\_CURRENT\_USER\\Software\\Policies\\Microsoft\\Windows**  
![Windows Registry Editor with a path highlighted](https://www.lifewire.com/thmb/ue6l7XRFw54ugwAe-yzVVm8eTgU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Windows-Registry-path-f80296aef19f4b25922e954df779b8b8.jpg)
3. Right-click**Windows** , and then select**New** \>**Key** . Label the key as**WindowsCopilot** .  
![A screen from Windows Registry Editor with the Windows, New, and Key options highlighted](https://www.lifewire.com/thmb/mPeluMQC4p3ypnPWtf2d7aHfVcE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Windows-new-key-8ff0b3a8661b4417bc40582a822cc6bd.jpg)
4. Right-click the new**WindowsCopilot** key, and then select**New** \>**DWORD (32-bit) Value** . Name the DWORD**TurnOffWindowsCopilot** .
5. Double-click the**TurnOffWindowsCopilot** option and type**1** in the Value Data text field. The Base should be the default "Hexadecimal". Press OK.  
![The "Edit DWORD Value" window in Windows 11 Registry Editor with the Value date field highlighted](https://www.lifewire.com/thmb/8bVuuVjsqst_Mnb_e6gqpEeKCvw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Windows-Registry-e93dfaf6db3b408cbf20f168ec4383b5.jpg)
6. Restart your PC for the changes to take effect. The Copilot toggle switch will also disappear from Settings.

##  How to Disable Copilot With Group Policy in Windows 11 

 The Group Policy Editor is an administrative tool available in higher editions of Windows. Users and admins use it to manage policies within a system-wide networked environment, and they can also access the Copilot setting.

1. Open**Start** , type "**Group Policy Editor** " in the search field, and then press Enter.
2. In the Group Policy Editor window, navigate to the following path:  
**User Configuration** \>**Administrative Templates** \>**Windows Components** \>**Windows Copilot**
3. In the right pane, right-click**Turn off Windows Copilot** and select**Edit** .
4. The**Turn off Windows Copilot** dialog box will appear with several options. Choose**Enabled** to disable the Copilot button in Windows.  
![The "Enabled" button in Registry Editor](https://www.lifewire.com/thmb/5vxf02IvhldoaIQyAPi_qeRKuIg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Enabled-Button-1a91efeff29c4f61bd89a3448e76036b.jpg)
5. Click**Apply** and**OK** . Restart your PC for the changes to take effect.  
![The OK and Apply buttons in Windows 11 Registry Editor](https://www.lifewire.com/thmb/j6w6opO-Wy8ppmX8hUZyqxVmg0Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/OK-Apply-1a8a274b3e734bd896faa25ad67e28b9.jpg)
6. To undo these changes, select the**Disabled** radio button and restart your PC again.

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
