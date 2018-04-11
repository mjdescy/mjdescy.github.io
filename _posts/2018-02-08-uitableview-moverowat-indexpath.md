---
layout: post
microblog: true
audio: 
date: 2018-02-07 22:45:35 -0400
guid: http://mjdescy.micro.blog/2018/02/08/uitableview-moverowat-indexpath.html
---
UITableView `moveRow(at: IndexPath, to: IndexPath)` works differently when `tableView.dragInteractionEnabled = true`, and causes my (dev) app to crash when a move (even when _not_ issued by drag-and-drop) completely empties a section of my table view. It's been frustrating!
