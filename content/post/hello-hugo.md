---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
lastmod: {{ .Date }}
draft: true
keywords: []
description: ""
tags: ["XXX", "XXX"]
categories: ["XXX", "XXX"]
author: "Rajiv Abraham"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: false
autoCollapseToc: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
---

Well nearly…

Check out my first Hugo website, [Rajiv Abraham Nela](https://eager-brown-0291a7.netlify.com/). I initially set this up for the domain at [Abraham.Red](https://abraham.red/), but then moved the site back to WordPress as CMS. It's not a blog, it's a static site and yet **yes I moved a static site from Hugo over to WordPress**.

I was able to read through the [Hugo tutorials](https://gohugo.io/getting-started/quick-start/) as well as watch an entire playlist of [Hugo videos](https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3) in a few hours, and I was also able to be up and running with a Hugo website, all in under 24 hours.

This proves a couple of points, Hugo is mature enough for rapid deployment and more importantly has a ton of tutorials and guides and an active community that is willing to share and help.

Now personally I'm more of a DIY guy, and so I don't really visit support forums and ask around, and instead rely on Google and YouTube for all fixes, but do note that Hugo has an active [discussion forum for support](https://discourse.gohugo.io/) that will help you get moving should you ever find yourself stuck or in a fix.

But here are my main issues with Hugo.

*   It's not as intuitive or out of the box easy-peasy as WordPress. There is no fire up the post WYSIWYG editor and speak into the microphone (or hack away at the keyboard).
*   Hugo does a lot of weird things (call them bugs or design choice if you will), but they are there. For instance, it would not publish because I [did not create a post](https://discourse.gohugo.io/t/build-fails-error-error-building-site-no-source-directory-found-expecting-to-find-it-at-opt-build-repo-content/5716), or [would not deploy](https://discourse.gohugo.io/t/production-failed-build-script-returned-non-zero-exit-code-255/8320) because I did not mention the Hugo version number, and this one is a personal favorite because it took a while to find the fix, Hugo will [break the theme and the CSS](https://github.com/gohugoio/hugo/issues/1421) if you don't [put the baseURL correct](https://discourse.gohugo.io/t/hugo-static-styling-not-working-whereas-hugo-server-works/2916) in the configuration file.
*   You need to know (or learn) the command line interface to use Hugo.
*   You will also need to learn and use GitHub to actually deploy a website, or find a web host where you can simply and easily upload static files.
*   No on the go or mobile blogging. Easily done with WordPress via an app or sending an email. Even works for blog content like photographs.Couldn't find much information about getting IndieWeb to work with Hugo. There isn't even a Slack channel for Hugo on IndieWebCamp though they have dedicated channels for WordPress and Known.
*   Lots of missing information like metadata, search engine optimization, rel="me" links, etc. that I couldn't find easily, but extremely important for websites/blogs… especially if they want to be seen and read.
*   And finally, should you get everything working, [beware](https://github.com/ruby/psych/issues/190) the [syntax error](https://stackoverflow.com/questions/31104917/how-to-fix-the-yaml-syntax-error-did-not-find-expected-indicator-while-pars) will get you. This cost me more than a day, and after finding no fix, I decided to go with WordPress for this website.

There were some more minor issues, but thankfully all of them have been fixed by simply using Google search.

So now you might be wondering why Hugo at all? Well for starters, I'm a geek and I like to keep trying out new things for size. It also probably means I have a lot of free time on my hands. Also, I have begun work on a linkblog [Abraham's Linkblog](https://abraham.link/) that will have hundreds and even thousands of individual posts (I plan to move all my bookmarks over here eventually), and I am not sure WordPress will be light and sprightly on its feet with thousands of individual posts. I needed to start exploring the option of a static website for my linkblog and that's how and why I got into Hugo (if you're wondering).

But honestly, the much-touted advantage of a CDN over traditional hosting in terms of speed was also not very much evident for me when hosting via Netlify. Using WordPress with the free tier of Cloudflare will get you the same results as well as additional benefits like HTTPS for all of your domains.

These are early days still, and there is a lot I still need to learn about Hugo. For now I plan to continue with Hugo and dig even deeper, and hopefully, I'll have more to write on this matter over the coming days.