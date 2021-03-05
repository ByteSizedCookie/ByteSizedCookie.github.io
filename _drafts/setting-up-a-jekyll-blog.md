---
layout: post
title: "Creating a blog with Jekyll and Github Pages"
tags: jekyll github gnu/linux linux static-site
excerpt_separator: <!--END-->
---

In this very first post, we will tackle the process of creating a blog with Jekyll (a static site generator) and Github Pages.<!--END--> But first, let's ask ourselves: why bother creating a blog? And why, specifically, build a blog with a static site generator?

If you're reading this article, there's a great chance you already know why you want to create a blog. Maybe you'd like to share tips from your profession. Maybe you just love a hobby like gardening, and want to write about that. Whatever the reason, blogs provide a great way to share your experiences and knowledge with an audience. As a plus, writing about your knowledge or experiences may help you yourself straighten them out in your own mind.

So, you're going to make a blog. Your heart is set on it. Good. Now, I recommend a static site for most blogs, for a couple of reasons:

* They're easy to set up and host
* They're reliable
* They're secure
* They're fast and lightweight

I gotta say, those are some pretty good reasons. Now, explanations (which pertain to Jekyll, I can't make guarantees for any other static site generator):

* It's easy to set up and host *because* it just consists of running a couple of text-based commands on a terminal, and then setting up a web server that can serve static files. We're even skipping the web server since we'll be using Github Pages to host.
* It's reliable *because* the static site generator (Jekyll) will take your blog posts and spit out HTML files and resources (like images and CSS) that will form a set of webpages for your website, which you could view locally in a web browser if you wanted to. **No moving parts. No databases. No scripts.** Just webpages and weblinks.
* It's secure *because* any potential attackers cannot get into your site, because **there are no entry points!**. Normal "Content Management Systems" (CMS's) present many attack points to intruders, which you have to then secure. If securing a CMS site/blog is like locking a door or barring up windows, a static site is like a brick wall to any potential attacker.
* It's fast and lightweight *because* it is not dynamic. Any webpages containing content are only generated once by a static site generator until the content is updated by you. In the meantime, they sit on a server. When you ask that server for a webpage, it gives you one. When you ask for an image, it gives you one. On a dynamic website, the server has to (usually) build the page from several components **every time you ask for it.**

For the aspiring bloggist, the static site also presents several advantages. Blog posts can usually be written in lightweight "markup" format, which allow the writer to concentrate on writing their articles, and not on formatting titles, headers, and paragraphs. For example, I write all my notes in the popular [Markdown](http://markdownguide.org/) format. Hosting a static blog can be done wherever you wish: on your own virtual server if you have the expertise, or on a service like Github Pages, and then it can be forgotten about until you write a new post.




