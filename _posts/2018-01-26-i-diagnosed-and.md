---
layout: post
microblog: true
audio: 
photo: 
date: 2018-01-25 23:37:34 -0500
guid: http://mjdescy.micro.blog/2018/01/26/i-diagnosed-and.html
---
I diagnosed and fixed a memory leak in my iOS app using Instruments and Xcode's memory debugger for the first time tonight. It _almost_ made sense to me. My fix involved removing retain cycles by getting rid of a closure and turning one of my classes into a struct.
