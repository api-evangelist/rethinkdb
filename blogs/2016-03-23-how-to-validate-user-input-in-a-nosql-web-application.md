---
title: How to validate user input in a NoSQL web application
url: https://rethinkdb.com/blog/validation-techniques
date: '2016-03-23'
author: Ryan Paul
feed_url: https://rethinkdb.com/feed.xml
---
Like many other modern JSON databases, RethinkDB is schemaless: the
developer doesn’t have to define a fixed structure or specify field types
when creating a new table. In cases where validation is desirable, it’s up
to the developer to build it into their application. Shifting the responsibility for input validation from the persistence
layer to the application layer gives developers a lot of flexibility in
how they choose to implement the capability. This blog post demonstrates
several ways to validate input in Node.js web applications.
