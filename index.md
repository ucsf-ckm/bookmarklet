---
layout: default
title: Reload via EZproxy
---
 [![UCSF Library](img/ucsf_header_basic.png)](http://www.library.ucsf.edu/)

# EZproxy Bookmarklet for iOS
*Mobile browsers require several taps and some copy-paste to install a bookmarklet, but if you take a few minutes to set it up, the mobile version is easy to use. *

## Part One: Setup
1. On iPad, go to **Settings** and tap **Safari**
2. Set **Show Favorites Bar** > ON
3. iPhone has no favorites bar, so skip and go to Part Two

*You can control what appears in your iPad Favorites Bar by opening Safari and tapping the bookmarks icon (open book) in the upper right. Then tap Edit.*

## Part Two: Creating the Bookmark
1. Open **Safari** browser and view this page (the one you're reading now)
2. Tap on the **share icon** ![share icon](img/share-icon.png)
3. Tap **Bookmark** to save this page ![bookmark icon](img/bookmark-icon-box.png)
4. Ensure that it will be saving to **Locations** > **Favorites** and then tap **Done**

## Part Three: Editing the Bookmarklet
1. Select and copy the bookmarklet code at bottom of this page
2. Tap the **bookmarks icon** ![bookmark no text](img/bookmark-icon.png) and be sure you're viewing **Favorites**
3. Tap **Edit**
4. Select the bookmark saved in Part Two, called **Reload via EZproxy**
5. Tap the **address/URL field** and clear it by tapping the **x**
6. Tap on the word **Address**, and tap **Paste** to add the javascript code
7. Tap **Done** twice: once in the keyboard and once at lower corner of the Favorites box

## Using the Bookmarklet
1. Open Safari: on iPad you now have a visible **Favorites Bar** below the URL/Address line with **Reload via EZproxy** bookmarklet. On iPhone there is no bar, but tap **Bookmarks icon** to view)
2. NOTE: Bookmarklet is only needed if you go *directly* to a journal website rather than through the UCSF Library website.
3. If you've clicked to view a full article and you are not granted access, tap the bookmarklet. You will be prompted to log in with your MyAccess credentials.
4. Once authenticated as UCSF, you should get the full text.

## Bookmarklet Code
Tap and hold to select. If needed, adjust the selection, to include all before tapping **Copy**

<input readonly="readonly" class="form-control" value="javascript:void((function(){location.href='https://ucsf.idm.oclc.org/login?qurl='+encodeURIComponent(location.href);})());"></input>

## Problems?
-	The Library does not subscribe. Check [holdings.](http://ucsf.worldcat.org/m/)
-	The Library needs to adjust our EZproxy configuration. [Report](http://m.ucsf.edu/#/library/help) the problem.
-	Your MyAccess login is invalid. [Verify](https://myaccess.ucsf.edu/) your account.
-	Need help with EZproxy? Contact [Library Support.](http://m.ucsf.edu/#/library/help)