---
title: Master ASP File Editing with JS Syntax Colorization Features in EmEditor Text Editor
date: 2024-10-11T07:02:07.549Z
updated: 2024-10-14T11:18:55.246Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/96b0dc304ed2f0b22e595834a3c54ad25662873342662329d5363509351a52f0.jpg
---

## Master ASP File Editing with JS Syntax Colorization Features in EmEditor Text Editor

January 29, 2008 at 3:20 pm [#5390](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/3597879799f03e6f1ad5d2ca5a32d334?s=80&d=identicon&r=g)Passiday](https://www.emeditor.com/forums/users/Passiday/ "View Passiday's profile")

Participant

Ok, I have learned how to do the trick.

 It seems like the editor keeps the last assumed scripting language in memory, and rewriting the declaration, and even reopening the file does not help to redraw the colors.

 However, if I copy the code, paste it in new document, and save it as ASP file, the editor changes it’s present assumed scripting language.

 Here are the steps for repeating the bug:

 1\. Start new document (A), write the following code:

 <\\%  
 ‘AAAA’  
 \\%>  
 2\. Start another new document (B)  
 3\. Copy the code from document A to document B.  
 4\. Save the document B as “test.asp”  
 At this point you should see the ‘AAAA’ in green.  
 5\. Change the scripting language in declaration to JScript in document B. The syntax coloring does not change.  
 6\. Save the document B. The syntax coloring does not change.  
 7\. Close the document B, reopen it from “recently viewed files” list. The syntax coloring does not change.  
 8\. Create new document C, copy the code from document B to document C (it’s not with JScript declaration). Save the document C. The syntax coloring is now updated.

 Whenever the editor has assumed the language, if I then open an ASP file, it is displayed with this assumed language coloring, not the one that could be detectable from the file declaration.

 Besides that, there are many files that are used as includes in the main file, and those do not have “@” declaration. There should be at least hacky way (ie, keyword in comments) to tell the editor what is the scripting language. Or, the default language could be set up in options somewhere, or the language could be detected with more advanced algorythm.

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
<li><a href="https://remote-screen-capture.techidaily.com/updated-advanced-users-techniques-for-effective-macscreencasting/"><u>[Updated] Advanced Users Techniques for Effective MacScreencasting</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-why-are-my-instagram-photos-flipped-seeking-answers/"><u>[Updated] Why Are My Instagram Photos Flipped? Seeking Answers</u></a></li>
<li><a href="https://win-tips.techidaily.com/advanced-document-management-through-native-templating-and-highlight-capabilities-explore-emeditor/"><u>Advanced Document Management Through Native Templating & Highlight Capabilities - Explore EmEditor</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-text-editors-open-documents-addon-flaw-detected-bug-and-potential-impact/"><u>EmEditor Text Editor's Open Documents Addon Flaw: Detected Bug and Potential Impact</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-tutorial-simultaneously-editing-files-across-multiple-windows/"><u>EmEditor Tutorial: Simultaneously Editing Files Across Multiple Windows</u></a></li>
<li><a href="https://win-tips.techidaily.com/emeditor-v700-rc6-reviewed-no-highlight-for-paired-brackets-in-quoted-sections-text-editor/"><u>EmEditor v7.00 RC6 Reviewed: No Highlight for Paired Brackets in Quoted Sections (Text Editor)</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/handbrake-unterstutzung-fur-av1-codec-and-umwandlung-von-av1-dateien/"><u>HandBrake Unterstützung Für AV1 Codec & Umwandlung Von AV1 Dateien</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-tecno-pova-5mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Tecno Pova 5Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/how-to-enable-line-commenting-feature-within-emeditor-text-editor/"><u>How to Enable Line Commenting Feature Within EmEditor Text Editor</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-infinix-zero-5g-2023-turbomirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Infinix Zero 5G 2023 TurboMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-compressor-for-fcpx-best-practices-for-exporting-and-delivering-videos/"><u>New 2024 Approved Compressor for FCPX Best Practices for Exporting and Delivering Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/perfect-every-frame-windows-11-and-storyremix-combo-guide-to-video-editing/"><u>Perfect Every Frame Windows 11 & StoryRemix Combo Guide to Video Editing</u></a></li>
<li><a href="https://win-tips.techidaily.com/resolving-constant-crashes-fixing-persistent-freezing-issues-with-emeditor-v903-on-parallels/"><u>Resolving Constant Crashes: Fixing Persistent Freezing Issues with EmEditor v9.03 on Parallels</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-10-heartening-films-for-optimism-and-power/"><u>Top 10 Heartening Films for Optimism & Power</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/transform-personal-experiences-through-direct-webcam-capture-using-vlc/"><u>Transform Personal Experiences Through Direct Webcam Capture Using VLC</u></a></li>
<li><a href="https://win-tips.techidaily.com/why-choose-emeditor-unveiling-the-shift-from-traditional-editors-to-enhanced-security-measures/"><u>Why Choose EmEditor? Unveiling the Shift From Traditional Editors to Enhanced Security Measures</u></a></li>
<li><a href="https://win-tips.techidaily.com/your-voice-matters-the-most-requested-additions-for-emeditors-latest-version/"><u>Your Voice Matters: The Most-Requested Additions for EmEditor's Latest Version</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

