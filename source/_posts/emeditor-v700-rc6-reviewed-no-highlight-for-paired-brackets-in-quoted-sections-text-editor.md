---
title: "EmEditor v7.00 RC6 Reviewed: No Highlight for Paired Brackets in Quoted Sections (Text Editor)"
date: 2024-10-01T17:13:42.067Z
updated: 2024-10-08T16:15:15.245Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/b53e4c331196053afd389dad87c586f0b9c8a334fc4c9d3f146c8a4bb6f2e065.jpg
---

## EmEditor v7.00 RC6 Reviewed: No Highlight for Paired Brackets in Quoted Sections (Text Editor)

Viewing 9 posts - 1 through 9 (of 9 total)

* Author  
Posts
* December 14, 2007 at 3:58 am [#5160](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/8b0cab4b6072a9b0664f8d97be026201?s=80&d=identicon&r=g)chjfth](https://www.emeditor.com/forums/users/chjfth/ "View chjfth's profile")  
Member  
When I upgrade EmEditor from 6.00.4 to 7.00.RC6, I found matching brackets in single or double brackets “() {}” can not be highlighted any more. I check that “Highlight Matching Parentheses/Brackets” has been checked, and the highlight color has been configured(actually the same as they are in EmEditor v6).  
 I want the highlight back please.  
December 14, 2007 at 4:42 am [#5161](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> chjfth wrote:  
> When I upgrade EmEditor from 6.00.4 to 7.00.RC6, I found matching brackets in single or double brackets “() {}” can not be highlighted any more. I check that “Highlight Matching Parentheses/Brackets” has been checked, and the highlight color has been configured(actually the same as they are in EmEditor v6).  
>  
> I want the highlight back please.  
 Are you working on a huge file? Please create a small sample file to reproduce the issue. If you believe this was a bug, please send me the sample file after zipped and write detailed procedure how to reproduce the issue. My email is [tech@emurasoft.com](https://tools.techidaily.com/emeditor/products/)  
December 15, 2007 at 4:25 pm [#5166](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/8b0cab4b6072a9b0664f8d97be026201?s=80&d=identicon&r=g)chjfth](https://www.emeditor.com/forums/users/chjfth/ "View chjfth's profile")  
Member  
I can’t believe you said that. I’ve tried it on at least three Windows machines(WinXP SP2 & Win2000 SP4 both involved), and they all exhibit what I’ve said. Just create an empty file, press F11 and select “C++”, then key in () “()”, — quotes should be keyed in. You see yourself whether the round brackets in the quotes are highlighted. In case yourself are cofused by what you will be seeing, please install EmEditor v6 and compare to it.  
 If you demand a real Windows environment, please download this VMware virtual machine(brand new Win2000 Simplified Chinese version) and install EmEditor v7 RC6 in it and see. <http://down.nlscan.com/Misc/Internet-Keep-Ref/%5Fvmware-5-Win2kchs-nsExec-bug.7z>  
December 15, 2007 at 5:18 pm [#5167](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I use Virtual PC 2007 for Windows 2000 environment. I press F11 and select “C++”, and then type “()”. Now “()” are highlighted. It seems all right to me. Do I need to type something else after “()”? If you installed any plug-ins, can you try uninstalling or disabling all extra plug-ins?  
December 16, 2007 at 12:52 am [#5168](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/8b0cab4b6072a9b0664f8d97be026201?s=80&d=identicon&r=g)chjfth](https://www.emeditor.com/forums/users/chjfth/ "View chjfth's profile")  
Member  
For EmEditor v7 RC6, whether something is typed after “()”, the brackets never highlight up to now.  
 I install EmEditor v7 RC6 on a machine(that vmware machine I posted above) that EmEditor has never been installed and only install the default plugins bundled.  
 See the screen shot please:  
 Brackets highlighted:  
 Brackets NOT highlighted in quotes:  
December 16, 2007 at 1:31 am [#5170](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I am sorry for misunderstanding. You should have first showed me your screenshots. () inside single or double quotes do not work any more. This is the specification of the new version. Most people want to jump to matching bracket (in programs), and want to ignore those inside single or double quotes.  
December 16, 2007 at 2:48 am [#5172](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/8b0cab4b6072a9b0664f8d97be026201?s=80&d=identicon&r=g)chjfth](https://www.emeditor.com/forums/users/chjfth/ "View chjfth's profile")  
Member  
Yup! That’s a useful feature anyway, can you tell me what the keyboard shortcut is for “jump to matching bracket”.  
 However, I use EmEditor as my favorite editor for writing makefiles, and there are lots and lots of cases where brackets are inside double quotes. So, please give user a choice instead of dropping the old good feature. EmEditor has done a great job of providing options to various user preferences, so why not adhere to that good tradition.  
 See my complex makefile here: <http://gnumakeuniproc.svn.sourceforge.net/viewvc/gnumakeuniproc/GMU-main/trunk/GnumakeUniproc/GnumakeUniproc.mki?revision=413&view=markup>  
December 16, 2007 at 4:52 am [#5173](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> chjfth wrote:  
> Yup! That’s a useful feature anyway, can you tell me what the keyboard shortcut is for “jump to matching bracket”.  
>  
> However, I use EmEditor as my favorite editor for writing makefiles, and there are lots and lots of cases where brackets are inside double quotes. So, please give user a choice instead of dropping the old good feature. EmEditor has done a great job of providing options to various user preferences, so why not adhere to that good tradition.  
>  
> See my complex makefile here: <http://gnumakeuniproc.svn.sourceforge.net/viewvc/gnumakeuniproc/GMU-main/trunk/GnumakeUniproc/GnumakeUniproc.mki?revision=413&view=markup>  
 CTRL + \] to jump to the matching bracket.  
 If you can disable single/double quotation marks in the Highlight (2) tab of Properties, and then all matching brackets will be highlighted.  
December 16, 2007 at 5:37 am [#5174](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/8b0cab4b6072a9b0664f8d97be026201?s=80&d=identicon&r=g)chjfth](https://www.emeditor.com/forums/users/chjfth/ "View chjfth's profile")  
Member  
Well, I know what you mean. But that’s not a decent solution. Looking forward to your fix on this issue. Thank you in advance.
* Author  
Posts

Viewing 9 posts - 1 through 9 (of 9 total)

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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-best-video-enhancement-apps-for-tiktok-mastery-on-w-indospc/"><u>[Updated] 2024 Approved Best Video Enhancement Apps for TikTok Mastery on W Indos/PC</u></a></li>
<li><a href="https://win-tips.techidaily.com/1-quick-and-easy-methods-for-converting-cda-audio-files-into-mp3-format/"><u>1. Quick & Easy Methods for Converting CDA Audio Files Into MP3 Format</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bereik-ongeklokt-830000-stock-videos-ideale-bron-voor-uw-marketing-creatie/"><u>Bereik Ongeklokt 830.000 Stock-Videos: Ideale Bron Voor Uw Marketing Creatie</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725286299984-dvd/"><u>DVDコピー不可能容量超え問題 - ストレージオーバーの落ち着かせ方</u></a></li>
<li><a href="https://win-tips.techidaily.com/effortless-mp4-slicing-guide-avoiding-re-encoding-for-pristine-results/"><u>Effortless MP4 Slicing Guide - Avoiding Re-Encoding for Pristine Results</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/from-chatgpt-to-claude-understanding-the-leadership-in-4-aspects/"><u>From ChatGPT to Claude: Understanding The Leadership in 4 Aspects</u></a></li>
<li><a href="https://win-tips.techidaily.com/guide-capturing-your-zoom-sessions-with-ease-pc-and-mobile-device-tutorial/"><u>Guide: Capturing Your Zoom Sessions with Ease - PC & Mobile Device Tutorial</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/jpegs-to-pdf-conversion-an-in-depth-tutorial-for-consolidating-images/"><u>JPEGs to PDF Conversion - An In-Depth Tutorial for Consolidating Images</u></a></li>
<li><a href="https://win-tips.techidaily.com/leading-ai-singularizer-for-optimal-sound-engineering-boost-your-mixes-with-ease/"><u>Leading AI Singularizer for Optimal Sound Engineering: Boost Your Mixes with Ease</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mastering-smart-bills-with-ai-your-step-by-step-strategy-for-implementing-intelligent-e-invoicing-systems/"><u>Mastering Smart Bills with AI: Your Step-by-Step Strategy for Implementing Intelligent E-Invoicing Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-whatsapps-voice-exchange/"><u>Navigating WhatsApp's Voice Exchange</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015696857-no-audio-in-your-g435-headset-heres-what-you-can-do/"><u>No Audio in Your G435 Headset? Here's What You Can Do!</u></a></li>
<li><a href="https://win-tips.techidaily.com/professional-pdf-esignature-maker-generate-secure-digital-signatures-easily/"><u>Professional PDF eSignature Maker - Generate Secure Digital Signatures Easily</u></a></li>
<li><a href="https://win-tips.techidaily.com/simple-techniques-for-combining-different-sound-tracks-together/"><u>Simple Techniques for Combining Different Sound Tracks Together</u></a></li>
<li><a href="https://win-tips.techidaily.com/simple-tricks-how-to-change-your-youtube-videos-into-3gp-format-with-ease/"><u>Simple Tricks: How to Change Your YouTube Videos Into 3GP Format with Ease</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-tecno-phantom-v-flip-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Tecno Phantom V Flip Location | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

