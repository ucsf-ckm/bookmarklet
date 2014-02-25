---
layout: default
title: Reload via EZproxy
---
# EZproxy Bookmarklet for iOS
*Mobile browsers require several steps to install a bookmarklet, but if you set it up, the mobile version is easy to use. *

## Part One: Setup
1. On iPad, go to **Settings** and tap **Safari**
2. Set **Show Favorites Bar** > ON
3. iPhone has no favorites bar, so skip and go to Part Two

*You can control what appears in your iPad Favorites Bar by opening Safari and tapping the bookmarks icon. Then tap Edit.*

## Part Two: Creating the Bookmark
1. Open **Safari** browser and view this page (the one you're reading now)
2. Tap on the **share icon** ![share icon](img/share-icon.png) found at top or bottom of your screen
3. Tap **Bookmark** ![bookmark icon](img/bookmark-icon-box.png) found at top or bottom of your screen to save this page
4. Ensure that it will be saving to **Locations** > **Favorites** and then tap **Done**

## Part Three: Editing the Bookmarklet
Select and copy the bookmarklet code. If needed, adjust the selection, to include all before tapping **Copy**
<textarea readonly="readonly">javascript:void((function(){location.href='https://ucsf.idm.oclc.org/login?qurl='+encodeURIComponent(location.href);})());</textarea>
2. Next, tap the **bookmarks icon** ![bookmark no text](img/bookmark-icon.png) found at top or bottom of your screen and be sure you're viewing **Favorites**
3. Tap **Edit**
4. Select the bookmark saved in Part Two, called **Reload via EZproxy**
5. Tap the **address/URL field** and clear it by tapping the **x**
6. Tap on the word **Address**, and tap **Paste** to add the javascript code
7. Tap **Done** twice: once in the keyboard and once at lower corner of the Favorites box

## Using the Bookmarklet
1. NOTE: Safari on iPad now has a visible **Favorites Bar** below the URL/Address line with **Reload via EZproxy** bookmarklet. No bar on iPhone, but tap **Bookmarks icon** to find the saved bookmarklet)
2. If you've clicked to view an article, and you are not granted full access, tap the bookmarklet. You will be prompted to log in with your MyAccess credentials.
3. Once authenticated as UCSF, you should get the full text.
4. NOTE: Bookmarklet is only needed if you go *directly* to a journal website rather than through the UCSF Library website links.

## Problems?
-	The Library does not subscribe. Check [holdings.](http://ucsf.worldcat.org/m/)
-	The Library needs to adjust our EZproxy configuration. [Report](http://m.ucsf.edu/#/library/help) the problem.
-	Your MyAccess login is invalid. [Verify](https://myaccess.ucsf.edu/) your account.
-	Need help with EZproxy? Contact [Library Support.](http://m.ucsf.edu/#/library/help)
