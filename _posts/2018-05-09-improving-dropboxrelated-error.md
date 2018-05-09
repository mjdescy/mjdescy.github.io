---
layout: post
title: "Improving Dropbox-related error messages in SwiftoDo"
microblog: false
audio: 
date: 2018-05-09 00:02:45 -0400
guid: http://mjdescy.micro.blog/2018/05/09/improving-dropboxrelated-error.html
---
I've done a lot of work rewriting the Dropbox code in [SwiftoDo](https://swiftodoapp.com). At this point, any error messages it generates are a now a little less well written—they are more generic—but they will appear more quickly, with greater consistency, and will reappear (as you would expect) each time Dropbox is accessed until the problem is fixed. Plus, the new error messages will provide a _little_ more information about what went wrong than they did before. I hope it's the right tradeoff.
