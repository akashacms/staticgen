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

It is easily extended by "plugins" that are easy to implement.  AkashaCMS was designed so every template can be easily overridden, so a website can customize its appearance precisely.

The initial idea in developing AkashaCMS was to avoid the overhead of a dynamic CMS that rebuilds every page on every page view.  Systems like Drupal are very powerful, but even when you turn on full caching support the server resources required to support a modestly popular website are significant.  

There are plenty of potential website publishers whose needs are modest.  The modern Internet dictates that all websites must now use HTML5, CSS3 and responsive web design techniques.  AkashaCMS embraces that model, while sticking with static HTML as the result.

Static websites are easy to host and typically very fast.
