---
title: An early look at three high-impact ES6 features coming soon to Node.js
url: https://rethinkdb.com/blog/v849-es6-features
date: '2016-02-22'
author: Ryan Paul
feed_url: https://rethinkdb.com/feed.xml
---
Google is currently developing V8 4.9 , which will ship in the
upcoming Chrome 49 release. V8 4.9 is a particularly exciting update,
because it includes support for 91% of the ECMAScript 2015 (ES6) standard.
When Node.js 6 launches with these V8 improvements, powerful new language
features like destructuring assignment and proxies will work out of the
box–without requiring special measures like command line flags or
transpilers. Although Node 6.0 isn’t scheduled for release until April, you can
experience a little bit of the future today by compiling Node’s vee-eight-4.9 branch from source code. The vee-eight branches are where Node’s maintainers do the heavy lifting to make Node
compatible with new versions of V8. The code from these branches is
understandably not suitable for use in production environments, but it’s a
fun a way to get an early look at coming improvements. In this blog post, I’m going to walk you through a handful of the new ES6
features that you can use out of the box in the vee-eight-4.9 branch. It’s
worth noting that many of these features are also available for testing in
Node 5.x by using Babel or command line flags if you want to follow
along without compiling.
