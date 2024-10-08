---
title: Master ASP File Editing with JS Syntax Colorization Features in EmEditor Text Editor
date: 2024-10-06T16:50:02.549Z
updated: 2024-10-08T16:40:38.822Z
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-craft-your-own-style-the-art-of-bordered-instagram-photos/"><u>[New] In 2024, Craft Your Own Style The Art of Bordered Instagram Photos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-mastery-over-buffering-in-vimeo-streams-revised-tips/"><u>[Updated] 2024 Approved Mastery Over Buffering in Vimeo Streams (Revised Tips)</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-best-practices-in-upgrading-to-a-high-end-4k-camera-lens/"><u>[Updated] In 2024, Best Practices in Upgrading to a High-End 4K Camera Lens</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-4k-lg-display-assessment-the-ultimate-31mu97-b/"><u>2024 Approved 4K LG Display Assessment The Ultimate 31MU97-B</u></a></li>
<li><a href="https://win-tips.techidaily.com/advantages-of-switching-from-windows-home-to-pro-comprehensive-tutorial-on-easy-transition-and-feature-boosts-techexpertguide/"><u>Advantages of Switching From Windows Home to Pro – Comprehensive Tutorial on Easy Transition and Feature Boosts | TechExpertGuide</u></a></li>
<li><a href="https://win-tips.techidaily.com/azure-unveils-radius-revolutionizing-open-source-tools-for-hybrid-cloud-environments-technews/"><u>Azure Unveils Radius - Revolutionizing Open Source Tools for Hybrid Cloud Environments | TechNews</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/best-video-trimming-tools-discover-the-premier-online-clippers-to-optimize-your-content-creation/"><u>Best Video Trimming Tools : Discover the Premier Online Clippers to Optimize Your Content Creation</u></a></li>
<li><a href="https://win-tips.techidaily.com/critical-countdown-for-microsoft-addressing-significant-issues-plaguing-windows-11-before-deadline-approaches-says-zdnet/"><u>Critical Countdown for Microsoft: Addressing Significant Issues Plaguing Windows 11 Before Deadline Approaches, Says ZDNet</u></a></li>
<li><a href="https://win-tips.techidaily.com/elevate-your-experience-benefits-and-steps-for-upgrading-windows-10-home-to-pro-edition/"><u>Elevate Your Experience: Benefits and Steps for Upgrading Windows 10 Home to Pro Edition</u></a></li>
<li><a href="https://win-tips.techidaily.com/how-to-download-microsoft-office-at-no-cost-expert-tips-from-zdnet/"><u>How to Download Microsoft Office at No Cost: Expert Tips From ZDNet</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-motorola-g54-5g-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Motorola G54 5G</u></a></li>
<li><a href="https://win-tips.techidaily.com/how-to-resolve-windows-pc-issues-caused-by-microsoft-july-security-update-and-prevent-bitlocker-recovery-mode-expert-fixes-on-zdnet/"><u>How to Resolve Windows PC Issues Caused by Microsoft July Security Update and Prevent BitLocker Recovery Mode - Expert Fixes on ZDNet</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-fundamental-tips-for-broadcasting-fan-favorite-sports/"><u>In 2024, Fundamental Tips for Broadcasting Fan-Favorite Sports</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-how-to-start-a-facebook-giveaway-post/"><u>In 2024, How to Start a Facebook Giveaway Post</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-vivo-y77t-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Vivo Y77t to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/is-bing-stepping-back-from-its-battle-against-google-insights-revealed-technews/"><u>Is Bing Stepping Back From Its Battle Against Google? Insights Revealed | TechNews</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

