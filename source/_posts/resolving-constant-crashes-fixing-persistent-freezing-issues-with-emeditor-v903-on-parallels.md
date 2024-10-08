---
title: "Resolving Constant Crashes: Fixing Persistent Freezing Issues with EmEditor v9.03 on Parallels"
date: 2024-10-07T16:06:47.385Z
updated: 2024-10-08T16:55:32.244Z
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-the-ultimate-tiktok-video-locker-free-and-clear/"><u>[New] 2024 Approved The Ultimate TikTok Video Locker - FREE & Clear</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-broadcast-battle-obs-against-wirecast/"><u>[Updated] In 2024, Broadcast Battle OBS Against Wirecast</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-cinematic-chronicles-in-depth-video-tech-reviews/"><u>[Updated] In 2024, Cinematic Chronicles In-Depth Video Tech Reviews</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-scripting-summative-stories/"><u>[Updated] In 2024, Scripting Summative Stories</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-prime-unlimited-space-service-catalogue-for-2024/"><u>[Updated] Prime Unlimited Space Service Catalogue for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unleashing-creativity-in-micro-videography-and-photography-for-2024/"><u>[Updated] Unleashing Creativity in Micro Videography and Photography for 2024</u></a></li>
<li><a href="https://win-tips.techidaily.com/aprende-a-aprovechar-la-tecnologia-de-camaras-virtuais-obs-en-el-2024-guia-detallada/"><u>Aprende a Aprovechar La Tecnología De Camaras Virtuais OBS en El 2024 - Guia Detallada</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/banishing-static-like-motion-in-aerial-videos/"><u>Banishing Static-Like Motion in Aerial Videos</u></a></li>
<li><a href="https://win-tips.techidaily.com/conversione-gratuita-online-da-m4a-a-avi-con-movavi/"><u>Conversione Gratuita Online: Da M4A a AVI Con Movavi</u></a></li>
<li><a href="https://win-tips.techidaily.com/descubra-como-transformar-fotos-raw-en-formatos-jpg-facilmente/"><u>Descubra Como Transformar Fotos RAW en Formatos JPG Fácilmente</u></a></li>
<li><a href="https://win-tips.techidaily.com/free-web-based-mov-to-mp4-converter-easy-mov-file-transformation-with-moveave-video-software/"><u>Free Web-Based MOV to MP4 Converter - Easy MOV File Transformation with Moveave Video Software</u></a></li>
<li><a href="https://win-tips.techidaily.com/gratuit-gebaseerd-swf-toevoegen-naar-mp3-professionele-lijst-van-bewerken-movavi/"><u>Gratuit Gebaseerd SWF-Toevoegen Naar MP3: Professionele Lijst Van Bewerken - Movavi</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-composing-cinematic-cues-trailer-soundscapes-guide/"><u>In 2024, Composing Cinematic Cues Trailer Soundscapes Guide</u></a></li>
<li><a href="https://win-tips.techidaily.com/movavi-converter-review-aiff-vs-wav-an-in-depth-guide-to-selecting-the-best-audio-format/"><u>Movavi Converter Review: AIFF vs WAV - An In-Depth Guide to Selecting the Best Audio Format</u></a></li>
<li><a href="https://win-tips.techidaily.com/online-tiff-jpeg/"><u>Online 무료 제공: 오픈 소스의 Tiff 이미지를 Jpeg으로 구독하는 방법</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/precision-planning-of-collaborative-slack-plus-filmora-meetings-for-2024/"><u>Precision Planning of Collaborative Slack + Filmora Meetings for 2024</u></a></li>
<li><a href="https://win-tips.techidaily.com/transformar-imagenes-de-rw2-a-jpg-sin-coste-adicional-con-la-herramienta-online-de-muoviavi/"><u>Transformar Imágenes De RW2 a JPG Sin Coste Adicional Con La Herramienta Online De MuoviAVI</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538">
  <img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

