---
title: "Resolving Constant Crashes: Fixing Persistent Freezing Issues with EmEditor v9.03 on Parallels"
date: 2024-10-12T18:23:20.275Z
updated: 2024-10-14T03:51:56.996Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/4526e24333ba977c51600360964ccfdbc4ba0f9b4255ce54480ebe44b63f8c8e.jpg
---

## Resolving Constant Crashes: Fixing Persistent Freezing Issues with EmEditor v9.03 on Parallels

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* November 10, 2009 at 2:35 pm [#7812](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ddbe0e18d95107c0ac040f07643edc0c?s=80&d=identicon&r=g)TimGreen](https://www.emeditor.com/forums/users/TimGreen/ "View TimGreen's profile")  
Member  
I do a lot of work with a Windows XP virtual machine in Parallels Desktop on an Intel Mac. Up to version 8 I’ve used EmEditor for almost all my editing needs in this environment and it has always been absolutely stable and reliable. I just bought the update to version 9 and updated to 9.03 and now EmEditor is freezing constantly when I use it in the XP VM in Parallels. I then have to force EmEditor to terminate with Task Manager and restart XP, because the whole system becomes unstable. This is the only program this happens with.  
 As far as I can see this has something to do with the way EmEd 9 is using the Windows clipboard, which is linked to the Mac OS X clipboard in Parallels so that you can copy and paste between the two systems. The first sign of an impending freeze is usually that the shared clipboard becomes corrupted and then stops working, then EmEd freezes completely and needs to be killed to exit. I’m also using 9.03 on my Windows 7/64 development machine on hardware and there it works fine.  
 I know that this is a bit of an unusual scenario but I’ve really come to depend on EmEditor and I’d like to go on using the new version if possible. Is it possible that any fix for this might become available? I’d be happy to do any testing necessary with a debug coded version if you like… :-)  
November 10, 2009 at 5:19 pm [#7814](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> TimGreen wrote:  
> I do a lot of work with a Windows XP virtual machine in Parallels Desktop on an Intel Mac. Up to version 8 I’ve used EmEditor for almost all my editing needs in this environment and it has always been absolutely stable and reliable. I just bought the update to version 9 and updated to 9.03 and now EmEditor is freezing constantly when I use it in the XP VM in Parallels. I then have to force EmEditor to terminate with Task Manager and restart XP, because the whole system becomes unstable. This is the only program this happens with.  
>  
> As far as I can see this has something to do with the way EmEd 9 is using the Windows clipboard, which is linked to the Mac OS X clipboard in Parallels so that you can copy and paste between the two systems. The first sign of an impending freeze is usually that the shared clipboard becomes corrupted and then stops working, then EmEd freezes completely and needs to be killed to exit. I’m also using 9.03 on my Windows 7/64 development machine on hardware and there it works fine.  
>  
> I know that this is a bit of an unusual scenario but I’ve really come to depend on EmEditor and I’d like to go on using the new version if possible. Is it possible that any fix for this might become available? I’d be happy to do any testing necessary with a debug coded version if you like… :-)  
 If the Clipboard history is the issue, please open regedit.exe, and set MaxClipboardHistory (REG\_DWORD) as 0 in HKEY\_CURRENT\_USERSoftwareemsoftEmEditor v3Common. This will effectively disable the Clipboard history. Thank you for using EmEditor!  
November 11, 2009 at 8:17 am [#7816](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ddbe0e18d95107c0ac040f07643edc0c?s=80&d=identicon&r=g)TimGreen](https://www.emeditor.com/forums/users/TimGreen/ "View TimGreen's profile")  
Member  
Hi Yutaka,  
 Thanks for your answer: I tried setting that registry value but it doesn’t seem to work, in fact it seems to make it a little worse. After a lot of testing it seems that the problem is the tray utility. If I exit the tray utility and run EmEd without it everything seems to work.  
 Have there been any significant changes in the way the tray utility works in version 9?  
November 11, 2009 at 7:01 pm [#7817](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> TimGreen wrote:  
> Hi Yutaka,  
>  
> Thanks for your answer: I tried setting that registry value but it doesn’t seem to work, in fact it seems to make it a little worse. After a lot of testing it seems that the problem is the tray utility. If I exit the tray utility and run EmEd without it everything seems to work.  
>  
> Have there been any significant changes in the way the tray utility works in version 9?  
 There is no significant change in emedtray.exe (Tray Icon).
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-essential-listings-for-easy-access-to-youtube-intro-files-for-2024/"><u>[New] Essential Listings for Easy Access to YouTube Intro Files for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-mastering-cross-platform-media-engines-a-buyers-guide/"><u>[New] Mastering Cross-Platform Media Engines A Buyer's Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-next-gen-key-smartwatch-opens-your-mac/"><u>[Updated] Next-Gen Key Smartwatch Opens Your Mac</u></a></li>
<li><a href="https://win-tips.techidaily.com/advanced-document-management-through-native-templating-and-highlight-capabilities-explore-emeditor/"><u>Advanced Document Management Through Native Templating & Highlight Capabilities - Explore EmEditor</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-text-editors-open-documents-addon-flaw-detected-bug-and-potential-impact/"><u>EmEditor Text Editor's Open Documents Addon Flaw: Detected Bug and Potential Impact</u></a></li>
<li><a href="https://blog-min.techidaily.com/guia-pratico-criando-sua-obra-prima-em-video-caseira-com-excelencia-dicas-e-truques/"><u>Guia Prático: Criando Sua Obra-Prima Em Vídeo Caseira Com Excelência - Dicas E Truques</u></a></li>
<li><a href="https://win-tips.techidaily.com/how-to-enable-line-commenting-feature-within-emeditor-text-editor/"><u>How to Enable Line Commenting Feature Within EmEditor Text Editor</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/master-asp-file-editing-with-js-syntax-colorization-features-in-emeditor-text-editor/"><u>Master ASP File Editing with JS Syntax Colorization Features in EmEditor Text Editor</u></a></li>
<li><a href="https://change-location.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/resolve-emeditor-errors-during-text-wrapping-feature-use-for-smooth-editing-experience/"><u>Resolve EmEditor Errors During Text Wrapping Feature Use for Smooth Editing Experience</u></a></li>
<li><a href="https://article-files.techidaily.com/streamlined-video-conferencing-utilizing-the-power-of-zoom-in-win10/"><u>Streamlined Video Conferencing Utilizing the Power of Zoom in Win10</u></a></li>
<li><a href="https://win-tips.techidaily.com/test-your-browsers-with-emeditor-a-comprehensive-text-editor-for-macros/"><u>Test Your Browsers with EmEditor: A Comprehensive Text Editor for Macros</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-best-cheap-action-cameras-to-purchase-for-under-100/"><u>The Best Cheap Action Cameras to Purchase for Under $100</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722897213254-understanding-error-code-0x80070570-and-easy-troubleshooting-steps/"><u>Understanding Error Code 0X80070570 & Easy Troubleshooting Steps</u></a></li>
<li><a href="https://win-tips.techidaily.com/why-choose-emeditor-unveiling-the-shift-from-traditional-editors-to-enhanced-security-measures/"><u>Why Choose EmEditor? Unveiling the Shift From Traditional Editors to Enhanced Security Measures</u></a></li>
<li><a href="https://win-tips.techidaily.com/your-voice-matters-the-most-requested-additions-for-emeditors-latest-version/"><u>Your Voice Matters: The Most-Requested Additions for EmEditor's Latest Version</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

