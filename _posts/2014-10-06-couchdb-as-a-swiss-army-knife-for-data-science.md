---
layout: post
title: "CouchDB as a swiss army knife for data science"
modified: 2014-10-06 23:22:34 -0700
tags: []
image:
  feature:
  credit:
  creditlink:
comments: true
share: true
---

In looking for a lightweight NoSQL store for stashing semi-structured data intermediates and analysis results, I stumbled upon [CouchDB](http://couchdb.apache.org/).  Toted as a 'database for web developers', I'm finding that it equally suited for serving the casual data science project.  In addition to its main function as a key-value json document store, CouchDB also makes heavy use of JavaScript for MapReduce based querying and has a built in HTTP server along with RESTful API for serving documents.  It can even serve static html/css/javascript content, including D3 visualizations with ready access to CouchDB's data.  This arsenal of features effectively offers data collection, transformation, querying and visualization all from within the same platform.  Quite handy for rapidly developing prototypes and reports!  Go check it out at http://couchdb.apache.org/, or rapidly deploy an instance using [docker](https://registry.hub.docker.com/u/klaemo/couchdb/).
