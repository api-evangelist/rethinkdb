---
title: RethinkDB 2.4.2 Released
url: https://rethinkdb.com/blog/2.4.2-release
date: '2022-04-25'
author: Sam Hughes
feed_url: https://rethinkdb.com/feed.xml
---
RethinkDB 2.4.2 has been released.  This update provides compilation
and bug fixes for the latest Linux and MacOS systems and includes one
notable change: r.js now uses QuickJS instead of V8 3.30.33. QuickJS supports a much newer version of JavaScript, and this update
will both reduce RethinkDB’s future maintenance burden and make it
easier for new contributors to work on the project.  If you use r.js , your queries’ behavior could hypothetically change. For a complete list of changes in this update, you can refer to
the release
notes . Packages Packages are available for x86-64 Debian, Ubuntu, CentOS 7, AlmaLinux
8, RockyLinux 8, and MacOS.  Linux ARM builds are supposed to be
released soon.  While RethinkDB does build on Apple M1 systems, a dmg
will only be available for x86-64.  If you want a package made
available for your system, find us on Slack , Discord , or GitHub and make your
needs known. Update (April 30): A Windows executable is not available, but
RethinkDB 2.4.2 is reported to run successfully on WSL 2.
