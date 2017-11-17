---
layout: post
title:  "Thoughts on pre-compiling of CSS and static site generators"
date:   2017-11-10 11:02:49 +1
categories: jekyll update
---

## Pre-compiled CSS
By pre-compiling your CSS you solve alot of the problems that make regular CSS a rather primitive and incomplete tool. When using regular CSS you often find that you have to write alot of code, often  repeating code you've already written, which results in large and hard-to-maintain codebases. Pre-compiled CSS work much more like a programming language having a much organized structure, utilizing variables and making it possible to make caluclations with code, things you simply can't to with regular CSS. There are of course downsides of utilzing pre-compiled CSS, mainly that is yet another language to learn, yet another tool to learn. It is another layer of abstraction in an already pretty complex process. It also makes the code harder to debug since the line numbers in the browser won't match the line numbers in the source code, though this can be solved with source mapping. On the whole though, I think the pros of nesting your code with a pre-processer out weighs the cons. 

Creating this site I didn't get too deep into the different techniques, but I used the basics, creating some $variables, @mixins and @imports.

## Static site generators
Static site generators take content stored in flat files as opposed to a dynamic website which stores files in databases. The content is applied against layouts or templates to generate a structure of purely static HTML files ready to be delivered to the users. This makes websites created in this way very fast and very resilient against big traffic surges since there are no processing whatsoever on every request, no database queries to run and no templating. It also makes the site very safe since there aren't alot of things to mess up when there's only a web server serving plain HTML files. The disadvantages of a static website is that the site lose the ability to have real-time data, such which stories are trending on the site or content thats changes for each user, like a "recommended for you" kind of thing. A static site will be the same for everyone. It can be a bit of a challenge to add user generated content to as static site, like a commenting system, but there are alot of third-party services that serve as a workaround. 

Static sites there for suitable for projects where you need a reliable, scalable site that can handle high volumes of traffic and that doesn't need to take alot of user input or show dynamic, real-time data. Such as a website for presenting a new product or development tool.