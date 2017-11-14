---
layout: post
title:  "What robot.txt and human.txt is, and how I have configured them for this site"
date:   2017-11-10 10:53:49 +1
categories: jekyll update
---

## robot.txt
The robots exclusion standard is a standard used by websites to communicate with web crawlers and other web robots about which areas of the website that should not be processed or scanned. For example, maybe you don't want everything on the website to be indexed by search engines, this is solved by placing a text file called robot.txt in the root folder of the website specifying which directories should and shouldn't be allowed to be indexed. Specific robots can also be told to stay out of the website in the robot.txt file. Not all web robots cooperate with the standard; email harvesters, spambots, malware, and robots that scan for security vulnerabilities may even start with the areas of the website they have been told to stay out of.

My robot.txt file for this site looks like this:

User-agent: * <br>
Disallow: 

This means every web robot is allowed acces to every area of the website. I configured it like this because I felt I really didn't have anything I wanted to hide/keep private from web robots on this website. 

## human.txt
The human.txt file is a intiative for getting to know the people who worked with creating a website. It is a text file (placed in the root folder of the website just like robot.txt) containing general information about the each member of team behind the website. Things like the persons role in the project, location, contact info etc. The file also contains a "thanks"-section and information about what tools where used during the creation of the website.

Since this is an exercise and not a very extensive website, and I'm the only person creating the site, the human.txt file for this site doesn't contain that much information. Click the human.txt logo below to see what it looks like.


