---
title: "Photographs from WordPress to Micro.Blog"
tags: ["IndieWeb", "Micro.Blog", "WordPress"]
author: Rajiv Abraham
type: post
date: 2018-04-03T00:19:52+00:00
url: /517/517/
tcb2_ready:
  - 1
mf2_mp-syndicate-to:
  - 'a:1:{i:0;s:4:"none";}'
mf2_syndication:
  - 'a:0:{}'
geo_weather:
  - 'a:2:{s:5:"units";s:1:"C";s:4:"icon";s:4:"none";}'
geo_public:
  - 1
mastodonAutopostPublishedNoRetoot:
  - 1
mastodonAutopostLastSuccessfullPostURL:
  - https://mastodon.social/@unoabraham/99969677423205150
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