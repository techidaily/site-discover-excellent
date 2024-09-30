---
title: "How to Bypass Windows Defender Restriction From Group Policy: A Step-by-Step Guide"
date: 2024-09-24T10:52:04.449Z
updated: 2024-09-30T04:22:27.958Z
tags:
  - product
  - antivirus
  - utilities
categories:
  - malwarefox
thumbnail: https://thmb.techidaily.com/33139754522d3393b0a998cc016bffa1b55254150a3f5abcd672e5d0c2f8e9f3.jpg
---

## How to Bypass Windows Defender Restriction From Group Policy: A Step-by-Step Guide

With the growing cyber threats, a good security solution is the need of the hour. Windows users have the luxury of a robust security program, **Windows Defender**, which is now known as **Microsoft Defender**. It comes in-built into the latest Windows 10 devices. 

![TotalAv Logo](https://www.malwarefox.com/wp-content/uploads/2024/02/totalav-svg.webp "totalav-svg")

**Stay malware-free with reliable antivirus**

Don't compromise your Data and Privacy. TotalAV is a top-notch antivirus program that handles various viruses, trojans, and other malware that may target your devices. It will safeguard your devices and enhance your system performance.

**4.9**/5

⭐ **Editor's Choice**

✔️ Excellent Malware Detection  
✔️ Multiple set of Features  
✔️ 30 Day Money-Back

[](https://tools.techidaily.com/malwarefox/products/) Get TotalAV > 

Taking lessons from the backlashes it receives after its initial release, Microsoft made some necessary security changes. Today, Microsoft Defender is one of the [top antivirus solutions](https://tools.techidaily.com/malwarefox/products/) in the cybersecurity field and used by millions of users.

However, this extensive security program can malfunction and stop working because of a few errors caused intentionally to stop it; one of those errors is “**Windows Defender blocked by Group Policy**.” 

In this guide, we would list out the possible fixes for this error.

[Is Windows Defender Enough?](https://tools.techidaily.com/malwarefox/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why “Windows Defender blocked by Group Policy” Error Occurs?

There could be a number of reasons for this error to happen. Here are the most common ones.

* Another [third-party antivirus](https://tools.techidaily.com/malwarefox/products/) or antimalware is clashing with the Windows Defender program.
* Cybercriminals might have used infiltrate Group Policy using [malware](https://tools.techidaily.com/malwarefox/products/) to disable the security of the Windows system.
* Some unauthorized changes in the Group Policies can also lead to the error. The changes can be made by mistake or intentionally too.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to fix “Windows Defender is Turned off by Group Policy”?

### **Using Group Policy Editor**

**_Note_**_: The Group Policy Editor is not available on the Windows 10 Home version_

1. Search for the **Group Policy Editor** in the windows search bar and launch it.![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. In the editor, navigate to: **Computer Configuration** \-> **Administrative Templates** \-> **Windows Components** \-> **Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Locate “**Turn off Microsoft Defender Antivirus**” and double click on it to open it.![Turn Off Microsoft Defender Antivirus](https://www.malwarefox.com/wp-content/uploads/2020/10/Turn-Off-Microsoft-Defender-Antivirus.png)
4. In order to enable the Microsoft Defender, click on the **Disabled** bullet.![Enable-MS-Defender](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-Defender.png)
5. Click **Apply** and **OK** to finish the configuration.
6. Restart the system to enable the settings.

---

### **Using Registry Editor**

1. Search for “**Registry Editor**” in the windows search box and launch it.![launch registry editor](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-registry-editor.png)
2. Navigate to or copy & paste this path to reach the Windows Defender folder: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender**
3. Right-click on the **DisableRealTimeMonitoring** key and Delete it.![Delete DisableRealtimeMonitoring key](https://www.malwarefox.com/wp-content/uploads/2020/10/Delete-DisableRealtimeMonitoring-key.png)
4. Exit from the Registry Editor and reboot your system to apply the changes.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

---

### **Using the PowerShell Command**

1. Search for the **Windows Powershell** in the Windows search box and select **Run as Administrator.**![PowerShell Run as Admin](https://www.malwarefox.com/wp-content/uploads/2020/10/PowerShell-Run-as-Admin.jpg)
2. Type or copy & paste this command and hit the enter key: **_Set-MpPreference -DisableRealtimeMonitoring 0_**![Enable MS defender with Powershell](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-defender-with-Powershell.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### **Using Windows Settings**

1. Right-click on the windows start icon and choose Settings from the list.![Settings](https://www.malwarefox.com/wp-content/uploads/2020/10/Settings.png)
2. Select **Update & Security** settings.![Update and Security](https://www.malwarefox.com/wp-content/uploads/2020/10/Update-and-Security.png)
3. From the left-pane choose **Windows Security**![launch windows security](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-windows-security.png)
4. Next, click on **Virus & threat protection**.![Choose virus & threat protection](https://www.malwarefox.com/wp-content/uploads/2020/10/Choose-virus-threat-protection.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Navigate to Virus & threat protection settings and click on **Manage settings**.![manage V&T settings](https://www.malwarefox.com/wp-content/uploads/2020/10/manage-VT-settings.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Toggle the switch to turn on the Microsoft Defender **real-time protection**.![turn On the Real Time protection](https://www.malwarefox.com/wp-content/uploads/2020/10/turn-On-the-RT-protection.png)

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### **Disable the Third-Party Security App**

The “Windows Defender blocked by Group Policy” error can also be caused if any third-party application has conflicts with the Defender. So, if you really require Windows Defender to run, try disabling the third-party antimalware or antivirus application and then launch the Defender app.

[How to Choose Best Antivirus for Windows 10](https://tools.techidaily.com/malwarefox/products/)

---

## Final Words

These are the top working solutions to fix the Windows Defender blocked by Group Policy error. If you apply the steps correctly, you would be able to run the Defender application eventually. However, if the problem persists even after trying the above methods, you can get the robust security solutions like **[Malwarefox](https://tools.techidaily.com/malwarefox/products/)**, that can provide better protection than the Microsoft Defender.

**Why my Windows Defender is turned off?** 

Windows Defender on your system can be turned off because of the various reasons like any third-party security app is conflicting with it, or a malware attack has infiltrated and modified the settings to disable it.

**Where is Windows Defender in group policy?** 

To edit the Windows Defender settings in the group policy editor, you can follow this path: **Local Computer Policy > Administrative Templates > Windows Components > Windows Defender Antivirus.** In the latest Windows version, the name of the Windows Defender is changed to **Microsoft Defender.** On those systems, the path to be followed is: **Local Computer Policy > Administrative Templates > Windows Components > Microsoft Defender Antivirus**.

### Leave a Comment [Cancel reply](https://tools.techidaily.com/malwarefox/products/)

Comment

Name Email 

Save my name, email, and website in this browser for the next time I comment.

Δ

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
<li><a href="https://some-techniques.techidaily.com/new-humorous-hits-lifetime-access-to-memes/"><u>[New] Humorous Hits Lifetime Access to Memes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-amuse-others-via-adobe-meme-making/"><u>[Updated] Amuse Others via Adobe Meme-Making</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-hitpaw-screen-recorder-review-and-alternative-for-2024/"><u>[Updated] HitPaw Screen Recorder Review and Alternative for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-cost-free-multi-os-video-player-releases/"><u>10 Cost-Free, Multi-OS Video Player Releases</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/create-a-zip-file-easily-for-windows-7-and-windows-10/"><u>Create a ZIP File Easily for Windows 7 & Windows 10</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722857320118-critical-points-you-need-to-assess-for-a-smart-dash-cam-buy/"><u>Critical Points You Need to Assess for a Smart Dash Cam Buy</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-find-my-friends-work-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/easy-methods-for-downloading-and-transforming-yoga-journal-footage-to-various-video-codecs-such-as-mp4-avi-mov-etc/"><u>Easy Methods for Downloading & Transforming Yoga Journal Footage to Various Video Codecs Such as MP4, AVI, MOV Etc.</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/effortless-audio-file-conversion-transform-caf-to-wav-mp3-m4a-aiff-aac-with-the-universal-audio-format-converter/"><u>Effortless Audio File Conversion: Transform CAF to WAV, MP3, M4A, AIFF, AAC with the Universal Audio Format Converter</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/free-converter-tool-transform-youtube-videos-into-swf-format-seamlessly/"><u>Free Converter Tool: Transform YouTube Videos Into SWF Format Seamlessly</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/free-tunein-music-converter-save-your-favorite-songs-as-mp3wav-files/"><u>Free TuneIn Music Converter: Save Your Favorite Songs as MP3/WAV Files</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/guide-converting-and-saving-mark-mansons-speaker-series-in-multiple-formats-mp4-mp3-avi/"><u>Guide: Converting and Saving Mark Manson's Speaker Series in Multiple Formats (MP4, MP3, AVI)</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/guide-how-can-i-save-datacamp-tutorial-videos-for-offline-learning/"><u>Guide: How Can I Save DataCamp Tutorial Videos for Offline Learning?</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/how-to-convert-videos-from-chomikuj-to-common-formats-like-mp4-mov-and-avi-with-ease/"><u>How to Convert Videos From Chomikuj to Common Formats Like MP4, MOV & AVI with Ease</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/how-to-save-your-favorite-films-as-mp4-mov-or-avi-files-directly-from-movie-box-the-ultimate-downloading-tutorial/"><u>How To Save Your Favorite Films As MP4, MOV or AVI Files Directly From Movie Box: The Ultimate Downloading Tutorial</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-file-document-with-digital-signature-software-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a .pdf file document with digital signature software</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Oppo Reno 11 Pro 5G? | Dr.fone</u></a></li>
</ul></div>

