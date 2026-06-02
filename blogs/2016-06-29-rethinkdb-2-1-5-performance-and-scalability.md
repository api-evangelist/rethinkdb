---
title: RethinkDB 2.1.5 performance & scalability
url: https://rethinkdb.com/blog/rethinkdb-performance-report
date: '2016-06-29'
author: Daniel Alan Miller
feed_url: https://rethinkdb.com/feed.xml
---
This report describes a recent effort that the RethinkDB team took to measure
our database product, RethinkDB, under different workloads and in different
clustering configurations. We seek to provide a general overview of RethinkDB’s
performance metrics for a variety of workloads and potential use cases. In this
report some of the questions we’ll address include: What sort of performance can I expect from a RethinkDB cluster? How well does RethinkDB scale? Can I trade consistency for performance? We’ll answer these questions by using different workloads from the YCSB
benchmark. You can learn more about YCSB here , and review the source
code here . Expanding beyond the YCSB workloads we selected, we
created an additional test which investigates scalability for analytic
workloads.
