---
layout: post
title:  "Welcome to Anorak"
date:   2014-11-10 21:12:28
categories: blog news
author: james
---
Since I've previously blogged about Anorak on [my own blog](http://james-brooks.uk/sneak-peek-at-anorak/), I figured that any of my writing regarding Anorak should be done in a consistent place. This post is a quick update on Anorak and where I'm currently at.

## What's going on?

Although I've not been working on Anorak directly, I've been spending a lot of my free time working on a project which is key to making Anorak a success.

[HippoPHP](https://github.com/HippoPHP) is a GitHub organisation setup to house some of the core Anorak code, including a PHP standards checker which is:

- Fast
- Almost a Rubocop for PHP
- Easy to write checks for
- More flexible than *PHP_CodeSniffer*
- Includes an AST for more complicated checks
- Doesn't only support the CLI interface *without obscene hacks*

So far we've written a [Tokenizer](https://github.com/HippoPHP/Tokenizer) and integrated that into [Hippo](https://github.com/HippoPHP/Hippo) itself.

HippoPHP is made up of myself and [@rr-](https://github.com/rr-) and we're open to Pull Requests, so feel free to join in.

**No, don't worry Hippo is not something that is only usable by Anorak. It's an independent library, which can be used by anyone. Plus, it'll remain open source.**

## What's next?

Here's what is left:

1. More work on Hippo is needed. We have two checks that can be configured so far and there is more left to do internally.
2. I want to rewrite the client side of things with Angular.js (and maybe React, for kicks) so that it's easy to use and super fast.
3. After that I need to finish a few implementation bugs on the server side itself. Some of these are related to PHPCheckstyle (the previous library I used), whilst others are just things which are broken.

And that's it really.

I'm also working on some client projects as well as Anorak and Hippo, so unfortunately my personal launch time of Christmas is unlikely. However, this isn't a problem.

## Also....

Yes, this blog is using the default Jekyll theme, I know. I'm aiming to port the [Anorak](http://anorakci.com) theme I've made over to the blog so that it's consistent.
