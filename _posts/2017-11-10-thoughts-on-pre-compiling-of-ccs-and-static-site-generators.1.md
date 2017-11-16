---
layout: post
title:  "Thoughts on pre-compiling of CSS and static site generators"
date:   2017-11-10 11:02:49 +1
categories: jekyll update
---

## Pre-compiled CSS
By pre-compiling your CSS you solve alot of the problems that make regular CSS a rather primitive and incomplete tool. When using regular CSS you often find that you have to write alot of code, often  repeating code you've already written, which results in large and hard-to-maintain codebases. Pre-compiled CSS work much more like a programming language having a much organized structure,utilizing variables and making it possible to make caluclations with code, things you simply can't to with regular CSS. There are of course downsides of utilzing pre-compiled CSS, mainly that is yet another language to learn, yet another tool to learn. It is another layer of abstraction in an already pretty complex process. On the whole though, I think the pros of nesting your code with a pre-processer out weighs the cons. 

Creating this site I didn't get too deep into the different techniques, but I used the basics, creating some $variables, @mixins and @imports.

## Static site generators

