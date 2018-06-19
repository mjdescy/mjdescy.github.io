---
layout: post
title: "Apple Didn't Kill Appkit..."
microblog: false
audio: 
date: 2018-06-19 17:02:43 -0400
guid: http://mjdescy.micro.blog/2018/06/19/apple-didnt-kill.html
---

This [article](http://subfurther.com/blog/2018/06/17/apple-didnt-kill-appkit-millenials-did/), quite rightly, made me feel bad about not pushing through the troubles I had porting SwiftoDo to the Mac—a project I haven't touched in over a year now. 

> Is it really that hard to share a codebase between Mac and iOS? I just sent off the “other platforms” chapter of Xcode Treasures, and one of the sections is about creating multi-platform projects. The book shows how to add tvOS to an iOS project from earlier in the book, but the idea is the same regardless of which platforms you support: portion off the code you can into cross-platform frameworks, ideally leaving only platform-specific UI code in each platform’s targets. 

I modularized a lot of my code to allow it to happen someday, but found out that it would require a lot of work to ramp up my AppKit skills. All the data manipulation code is in a well-contained library. That's just a small part of the app, though. The features are all in UI code, and porting it to AppKit resembles a 90% rewrite of my app.  

If I was doing development professionally, I would have done it. But as a hobbyist, it's hard to want to dive deep into AppKit when there are a million things to create or fix on iOS, which feels like Apple's future platform anyway. Maybe I'm lazy, and maybe Apple is going to help me out with UIKit on the Mac twelve months from now.
