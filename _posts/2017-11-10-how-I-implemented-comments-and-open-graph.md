---
layout: post
title:  "How I implemented comments and Open Graph"
date:   2017-11-10 10:50:49 +1
---

## Comments
Creating the comment section for these blog posts I used the comment hosting service Disqus. It was really simple to install, you just register on their site and fill out a form for the website you want to have a comment section on then you get a universal code snippet you copy and paste where ever you want a comment section on your site. Which for this site would be at the bottom of the post.html file in the _layouts folder.

## Open Graph
Open Graph is a technology first introduced by Facebook in 2010 and is a method of including meta information in a web page to allow an accurate represention of the page's content when it is linked to or posted on a social network. I works by placing meta-tags in the head section of the html file. The tags specify what should be used as title, description, image etc. when the page is linked on a social network. If nothing is specified the social network itself chooses what title, description or image to use which can result in random and unwanted results.

I created Open Grapgh information for site name, title, type, description, url and image.