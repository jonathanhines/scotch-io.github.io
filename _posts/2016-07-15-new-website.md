---
layout: inner
title: 'Updated website'
date: 2016-07-15 13:26:34
categories: blog update
tags: html css javascript jekyll
lead_text: 'It started as a test of a static website generator and turned into a new personal website for me.'
---

So it tried out Jekyll as it seems to be becoming popular and here we are.

Jekyll seems to be pretty effective.  I've been enjoying building this particular site.  It is based on the [tutorial theme](https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme) provided by [scotch.io](http://scotch.io).

I've been working on Drupal sites for the past 3 years and the constant update process is starting to get old.  Some day I just want my sites to be ok on their own.  I want to be able to go on vacation without worrying about some new security flaw to be announced and then have some script kiddie compromise my webserver before I can run an update.  I've successfully use the [static generator](https://www.drupal.org/project/static) module to archive sites in the past and after a little bit of bash scripting I was able to upload a static version of a Drupal site to Amazon S3 to be served as a website without a database or web server.

This is all well and good but in the end, I'd really like to dispense with web servers entirely if I can help it, or at lease only use them for dynamic content.  Once I can get a static site generator I'm happy with, I think the next step will be to write a contact form web service that I'll use via javascript and then I can move everything to S3 and decommission my web server.
