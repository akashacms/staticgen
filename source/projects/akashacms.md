---
title: AkashaCMS
repo: akashacms/akashacms
homepage: http://akashacms.com
language: Node.js
license: Apache2
templates: EJS, jQuery
description: Static site generator written in Node.js, utilizing server-side jQuery during page rendering
---

AkashaCMS is a simple but powerful static website generator using Node.js.  It has a flexible system of chained template pages and "partials" to make it easy to develop any page layout desired.  During page rendering the page DOM can be manipulated with jQuery functions, allowing even more flexibility.  With AkashaCMS, it's easy to develop and preview a website locally, then deploy your site to a webserver.  

The system was initially designed to build general-purpose websites using any navigational hierarchy you desire.  Eventually this was extended, and AkashaCMS now supports blogging, can potentially support podcasting, and can even be used to build electronic books (supporting the EPUB3 format).


Cactus is based on the idea that most dynamicness on websites these days can be done using Javascript while the actual site can stay static. Static websites are easy to host and typically very fast.

I developed Cactus because I wanted a standard, easy system that designers at [Sofa](http://www.madebysofa.com) could use to build and deploy fast websites. So typical users would be designers that are tech-savvy, want to use templates, but don't like to mess with setting up django or S3.

Since then it has evolved quite a bit with a plugin system that supports blogging, spriting, versioning and is extensible.

You can find more discussion about static site generators in this [Hacker News discussion](http://news.ycombinator.com/item?id=2233620).
