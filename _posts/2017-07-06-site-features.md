---
layout: post
comments: true
title: Site Features
summary: What I did to a Jekyll template
tags: site-features
---

This site is created using a [Jekyll](https://jekyllrb.com/) template called ***[Hyde](https://github.com/poole/hyde)*** which is a tool for generating static sites. I have a <a href="{% post_url 2017-07-06-jekyll %}">post on Jekyll </a> which also covers Hyde. The main reason for choosing Hyde was because it looked simple, and yet appealing. I like the layout with a sidebar which serves as a navigation bar. It becomes easy to move around the site, in this layout. On top of hyde, here are some of the small things I added to create this site:

* **Tags**, **Summary**: This was pretty easy. Simply adding a line to the yaml frontmatter achieved the purpose and runnign [Liquid](https://www.liquidmarkup.org/) code allowed me to create stuff like [listing by tags](/tags/).

* **Comments**: This site supports comments! I used [Disqus](https://www.disqus.com), a comment hosting service, for the same. With Jekyll, it was pretty easy and it was only a matter of getting things done.

* **[Chronological Ordering](/chronological/)**: This required some effort. However, an answer from stackexchange helped. Even so, it took me about a day to get the posts displayed in the manner I wanted. Partly because Liquid if-elses mixed up with HTML created a *sphagetti code* that was difficult to understand at once.

* **Fancy scrollbars**: Yep, that's right. If you haven't noticed yet, the scrollbars aren't your usual (and boring) ones. They had to be customized and it took a while getting that right.

* **Picture on sidebar**: Sounds small but had to get that done as well. Hyde does not have it by default but it can be easily included. The problem was positioning and size which needed to be sorted out.


That's all I could get done in about 4 days. The code is opensourced on <a href="divush.github.io" target="\_blank">github</a>. In case you want to know anything about implementation, you can comment on this post.
