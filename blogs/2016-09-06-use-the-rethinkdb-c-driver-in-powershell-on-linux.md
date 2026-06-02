---
title: Use the RethinkDB C# driver in PowerShell on Linux
url: https://rethinkdb.com/blog/powershell
date: '2016-09-06'
author: Ryan Paul
feed_url: https://rethinkdb.com/feed.xml
---
PowerShell is a scripting and command line shell built on top of the .NET
runtime. Although it was originally created for Windows, Microsoft recently
introduced an open source version of PowerShell powered by the cross-platform
compatible .NET Core. Users can now download and run PowerShell on Linux and Mac
OS X. One of PowerShell’s strengths is its interoperability with the .NET ecosystem.
PowerShell can load types and methods from .NET assemblies, making it possible
for PowerShell scripts to incorporate functionality that is implemented in
practically any C# library. That capability also makes PowerShell a great
environment for interactively exploring C# APIs. When Microsoft announced the availability of PowerShell on Linux earlier this
month, I tried it out in a Docker container on my home Ubuntu server. As an
experiment, I had it load up the C# RethinkDB driver developed by Brian Chavez . Using the driver, I was able to instantiate a RethinkDB
database connection and perform queries from the comfortable confines of the
interactive PowerShell command line environment.
