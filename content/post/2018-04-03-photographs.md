---
title: "Photographs from WordPress to Micro.Blog"
tags: ["IndieWeb", "Micro.Blog", "WordPress"]
author: Rajiv Abraham
type: post
date: 2018-04-03T00:19:52+00:00
aliases: [
    "/517/517/",
    "/93/photographs-from-wordpress-to-micro.blog/"
]
categories:
  - Musings
format: aside

---
<p style="text-align: left;">
  Posting photographs to Micro.Blog from self-hosted WordPress blog.
</p>

<p style="text-align: left;">
  I was having some trouble in having my photographs from my WordPress blogs show up on my Micro.Blog timeline, so putting this out here in case it might help/come in handy for someone with similar issues.
</p>

<ol style="text-align: left;">
  <li style="text-align: justify;">
    For starters, if your microblog post has a title then only that will be posted on Micro.Blog with a link back to your blog. Only content without a title like the body content or a photograph will be posted on Micro.Blog. Think of microblogging as posting to Twitter and Facebook, in other words, status updates without a title. Your content will be 2 to 4 lines, but not having the title.
  </li>
  <li style="text-align: justify;">
    Enable hotlinking of images if you&#8217;re using a CDN service or a service like Cloudflare. In Cloudflare > Scrape Shield, make sure the Hotlink Protection is turned off.
  </li>
  <li style="text-align: justify;">
    In WordPress Settings > Reading set the feed to Full Text.
  </li>
  <li style="text-align: justify;">
    Upload the images to the WordPress Media folder, don&#8217;t use a third-party service like Google Photos, or a cloud service like Google Drive or Dropbox to host the photographs.
  </li>
</ol>