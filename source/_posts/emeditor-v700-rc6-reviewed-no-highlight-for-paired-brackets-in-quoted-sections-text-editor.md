---
title: "EmEditor v7.00 RC6 Reviewed: No Highlight for Paired Brackets in Quoted Sections (Text Editor)"
date: 2024-10-10T06:09:34.403Z
updated: 2024-10-14T11:55:00.008Z
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
<li><a href="https://article-posts.techidaily.com/2024-approved-diverse-forms-of-remote-controlled-flyers/"><u>2024 Approved Diverse Forms of Remote-Controlled Flyers</u></a></li>
<li><a href="https://win-tips.techidaily.com/advanced-document-management-through-native-templating-and-highlight-capabilities-explore-emeditor/"><u>Advanced Document Management Through Native Templating & Highlight Capabilities - Explore EmEditor</u></a></li>
<li><a href="https://solve-latest.techidaily.com/descubra-os-melhores-reprodutores-gratuitos-de-dvd-para-o-windows-11-com-a-ferramenta-de-download-winxdvd/"><u>Descubra Os Melhores Reprodutores Gratuitos De DVD Para O Windows 11 Com a Ferramenta De Download WinXDVD</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-text-editors-open-documents-addon-flaw-detected-bug-and-potential-impact/"><u>EmEditor Text Editor's Open Documents Addon Flaw: Detected Bug and Potential Impact</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-tutorial-simultaneously-editing-files-across-multiple-windows/"><u>EmEditor Tutorial: Simultaneously Editing Files Across Multiple Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-selection-of-incredibly-affordable-footage/"><u>Grand Selection of Incredibly Affordable Footage</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-and-easy-the-best-websites-for-jpg-to-gif-transformation/"><u>In 2024, Free & Easy The Best Websites for JPG to GIF Transformation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-redmi-13c-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi Redmi 13C Through Google Earth?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-oppo-find-n3-flip-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Oppo Find N3 Flip Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win-tips.techidaily.com/master-asp-file-editing-with-js-syntax-colorization-features-in-emeditor-text-editor/"><u>Master ASP File Editing with JS Syntax Colorization Features in EmEditor Text Editor</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/resolving-constant-crashes-fixing-persistent-freezing-issues-with-emeditor-v903-on-parallels/"><u>Resolving Constant Crashes: Fixing Persistent Freezing Issues with EmEditor v9.03 on Parallels</u></a></li>
<li><a href="https://fox-that.techidaily.com/understanding-the-causes-of-iphoneipad-overheating-solutions-and-prevention-tips/"><u>Understanding the Causes of iPhone/iPad Overheating: Solutions & Prevention Tips</u></a></li>
<li><a href="https://win-tips.techidaily.com/your-voice-matters-the-most-requested-additions-for-emeditors-latest-version/"><u>Your Voice Matters: The Most-Requested Additions for EmEditor's Latest Version</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

