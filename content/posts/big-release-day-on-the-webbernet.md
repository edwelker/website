---
title: 'Big release day on the webbernet'
date: '2008-03-05T23:06:37-05:00'
status: publish
permalink: /2008/03/05/big-release-day-on-the-webbernet
author: Eddie
excerpt: ''
type: post
id: 77
category:
    - firefox
    - ie
    - ie8
    - javascript
    - microformats
    - microsoft
    - standards
    - web
tag:
    - acid2
    - beta
    - contacts
    - css
    - 'fire eagle'
    - 'geo tagging'
    - gmail
    - google
    - html
    - openAIM
    - 'operator plugin'
    - release
    - software
    - whitepapers
    - 'wia aria'
    - yahoo
post_format: []
---
So I guess it’s simply the time of year. Many big releases today... software, APIs, and more!

First, the biggest. [IE8 has been released](http://www.microsoft.com/windows/products/winfamily/ie/ie8/readiness/default.htm "Microsoft releases Internet Explorer 8 Beta") in initial beta. The release was also included a general overview of IE8’s new features and fixes. It’s actually quite a lot of information to absorb all at once. I’ve skimmed a number of [the IE8 whitepapers](http://code.msdn.microsoft.com/ie8whitepapers "Whitepapers for Microsoft Internet Explorer 8"), and feel the biggest changes are W3C’s [WIA-ARIA](http://www.w3.org/TR/wai-aria/ "Web Accessibility Initiative-Accessible Rich Internet Applications") support, [Acid2](http:// "Acid 2") compliance, the [javascript selectors api](http://go.microsoft.com/fwlink?LinkID=110273 "selectors api"), and their assertion of achieving [CSS 2.1 compliance](http://code.msdn.microsoft.com/Project/Download/FileDownload.aspx?ProjectName=ie8whitepapers&DownloadId=1025 "css 2.1 compliance"). Of course, the devil is in the details, and there is no company for which that statement is more true. They have a lot of work ahead, and we know they talk a good game. The big upside, however, is that they are actually talking about it. Out in the open. Big step, and I applaud them for that.

The other biggest buzz of the day was from Yahoo, in announcing the [beta of their Fire Eagle service](http://fireeagle.yahoo.net/ "Yahoo Fire Eagle Website"), an API for broadcasting your physical location to the web. I wouldn’t call it earth-shattering, but I think that there’s a good chance a number of cool things are built with it. [Watch the video of it’s introduction](http://developer.yahoo.net/blogs/theater/archives/2008/03/fire_eagle_launches.html "Yahoo's Fire Eagle API introduced"), and then [take a look here](http://blog.programmableweb.com/2008/03/05/yahoo-launches-fire-eagle/ "Yahoo Fire Eagle Quick Overview") to quickly get an idea of the details. It would appear from the details that it was written in a highly usable way.

Of more direct importance to me, [Google has announced their Contacts API](http://googledataapis.blogspot.com/2008/03/3-2-1-contact-api-has-landed.html "Google introduces Contacts API for accessing Gmail contacts securely"). I despise when sites ask me to enter my username/password for *other sites*. The most offensive request is for Gmail. I don’t have any interesting emails, let me tell you... but I certainly don’t want to let others read them. The Contacts API is a safe way for distribution and use of your Gmail contacts, without threatening the security of your Gmail account or your other Google-stored information. With this, I should be able to sync my Gmail contacts with my desktop mail contacts. I’m very happy about that.

Heading up the long-since-overdue category, [AOL has announced they’ve opened their Instant Messenger Protocol, OpenAIM](http://dev.aol.com/aim "AOL opens Instant Messenger Protocol, OpenAIM"). **Finally**. I remember ages ago when... well, it’s all in the past now. That’s one big wall that has been broken down between protocols, and hopefully Yahoo and Microsoft will fall in line. It will be great if other apps can finally use the features that have been limited to the AIM client for all this time. I use [Adium](http://www.adiumx.com/ "Adium; A Mac Instant Messenging Client") and [Pidgin](http://www.pidgin.im/ "Pidgin; Open Source Messenging Client") most of the time (Adium, I believe uses Pidgin’s core), and look forward to seeing what they do with the new open protocol. (On a personal note, hopefully this doesn’t spell any negative news for my friends who work on AIM.)

And to round things off, here’s two smaller releases today (one based on IE8’s Activities):

- The [Firefox Operator plugin](https://addons.mozilla.org/en-US/firefox/addon/4106 "Operator Plugin for Mozilla Firefox") (for [Microformats](http://www.microformats.org "Microformats website")) has already [given a go at implementing Activities](http://www.kaply.com/weblog/2008/03/05/microsoft-activities-for-firefox/ "Operator Plugin initial release implementing Activities"), which were announced at today’s IE8 overview.
- [The New York Times has contributed a perl module to CPAN](http://open.blogs.nytimes.com/2008/03/05/the-new-york-times-perl-profiler/ "New York Times contributes profiling perl module to CPAN"). Looks like a useful profiling tool, especially since it profiles line-by-line.