---
author: Cameron Dumas
title: "New Horizons"
date: 2023-11-02T20:57:06-06:00
featured_image: /images/posts/starting-a-blog/hero.jpg
summary: As a developer I would rather be coding and solving problems. The problem is that I quickly forget everything after I am done. Today that changes as I endevor to write a blog.
description: As a developer I would rather be coding and solving problems. The problem is that I quickly forget everything after I am done. Today that changes as I endevor to write a blog.
categories:
  - development
tags:
  - Blog
---

One day I decided that there was too much that I do that I never document. I have many projects that never get shared with anyone unless I actually talk to someone. As a developer I often decide that it is just too much work to keep a record of things that I do. **_Today that changes..._** At least for now 😉.

# Starting a blog

The internet is full of blog platforms. I wanted one that would allow for a few specific features.

1. Was easy to write posts
1. Generated static content (AKA serverless)
1. Allowed for endless customization of the look and feel
1. Was something new!

## Hugo won out

### I chose [Hugo](https://gohugo.io/)

![GoHugo](/images/posts/starting-a-blog/hugo-logo-wide.svg)

It only took a few minutes using the Hugo CLI to get a blog started. Once that was done it was just a matter of picking a theme.

There are thousands to choose from. I ended up with a simple one from NusserStudios called [Hugo-Tailwind-3.0](https://github.com/4044ever/Hugo-Tailwind-3.0.git).

This theme is frontend focused using tailwind and had simple layouts already setup.

Only some time with it will show if this will work for me. The great part is it <span class="font-red">hits</span> my requirement of being endlessly customizable! If I don't like something it is an easy change to a template.

## Deployment

I have long been a fan of [Cloudflare Tunnels](https://www.cloudflare.com/products/tunnel/). I just them extensively for personal projects.

While looking into Hugo I found that Cloudflare offers a service called [Cloudflare Pages](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/). My domain is already hosted through Cloudflare so the setup was about 3 minutes.
This setup was able to connect the Github for this blog and my Cloudflare account. Now whenever I push to the `main` branch a build is triggered that deploys the blog to Cloudflare.
It couldn't have been simpler! 😎
