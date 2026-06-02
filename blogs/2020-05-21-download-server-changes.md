---
title: Download server changes
url: https://rethinkdb.com/blog/download-server-changes
date: '2020-05-21'
author: Gábor Boros
feed_url: https://rethinkdb.com/feed.xml
---
We are continuously working to improve our infrastructure and make it easier for you to use RethinkDB. Today, we would like to announce the replacement of the download server. This change will affect every Docker image, Virtual Machines, and every platform, so please stay with us and read this post carefully . The download server will be at the same location ( https://download.rethinkdb.com ), but the repository structure of it will change. Changes Generally speaking, the new repository schema will look like https://download.rethinkdb.com/repository/<DISTRIBUTION>/ , where <DISTRIBUTION> can be centos , ubuntu-bionic , raw and so on. Below you can find the changes for every distribution we currently support.
