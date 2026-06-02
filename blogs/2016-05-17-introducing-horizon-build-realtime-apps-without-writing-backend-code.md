---
title: 'Introducing Horizon: build realtime apps without writing backend code'
url: https://rethinkdb.com/blog/horizon-release
date: '2016-05-17'
author: Ryan Paul
feed_url: https://rethinkdb.com/feed.xml
---
Today we are pleased to announce the first official release of Horizon , an open-source backend that lets developers build and
scale realtime web applications. Horizon includes: A backend server built with Node.js and RethinkDB that supports data persistence, realtime streams, input validation, user authentication, and permissions A JavaScript client library that developers can use on the frontend to store JSON documents in the database, perform queries, and subscribe to live updates A command-line tool that can generate project templates, start up a local Horizon development server, and help you deploy your Horizon application to the cloud The Horizon server is a complete backend that developers can use to power their
applications. It’s great for rapid prototyping: simply run the Horizon server
from the command-line and develop your frontend user experience with the Horizon
 client library. Frontend developers can use Horizon to create full applications
 without writing any backend code. Horizon is open-source software, which means that you can use and modify it as
you see fit. Run a local instance on your laptop during development and then
deploy your application anywhere you want: low-cost VPS hosting environments,
scalable public cloud platforms, or your own bare metal. Horizon takes advantage
 of RethinkDB’s battle-tested clustering , which makes it easy to scale as
your audience grows.
