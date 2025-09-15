+++
title = "The web hasn’t changed"
date = 2025-09-15
[taxonomies]
tags = ["web", "zola", "obsidian"]
+++

{{ image(path="img/original-next-computer.webp", caption="This [NeXT Computer](https://en.wikipedia.org/wiki/NeXT_Computer "NeXT Computer") was used by Berners-Lee at CERN and became the world’s first web server. Photo: [Coolcaesar at the English-language Wikipedia, CC BY-SA 3.0](https://commons.wikimedia.org/w/index.php?curid=395096)") }}

[Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) and Norwegian [Håkon Wium Lie](https://en.wikipedia.org/wiki/Håkon_Wium_Lie) (alongside [Bert Bos](https://en.wikipedia.org/wiki/Bert_Bos)), laid the bricks and mortar of the World Wide Web back in 1991 and 1994, respectively, when they drew up their specifications for html and CSS. And, like a sturdy old Victorian house, the web has stood the test of time.

This site, publishink, has survived more or less intact since 2002. It has done so as a simple html file and a CSS file, dumped in a folder and uploaded to my host. Not all that different from Berners-Lee et al. No PHP, Javascript, or database were involved in the building of this site. 

Don’t get me wrong, there have been a couple of times over the years when I’ve found myself with time on my hands and popped a version of this site into WordPress, added a blog element, then realised I didn’t really need one. Work was going well – mostly by word of mouth – so why bother? Why create more work? So I reverted to html and CSS files and the happy times returned. In that time, all that changed was the CSS file when I thought the site could do with a fresh lick of paint.

## Something to say

Then around 2018 I discovered SSGs, or static site generators[^1]. Using an SSG allowed me to keep my site simple, without all the bloat and overhead that comes with a WordPress installation. That makes this site quicker to load, among other things. Better still, [Zola](https://getzola.org), the SSG I settled on, allows me to write all the pages and posts in [Markdown](https://en.wikipedia.org/wiki/Markdown),[^2] an easy-to-read and easy-to-write plaintext format that I’ve been using since the late Noughties.

So, in the past couple of months I decided to add a blog[^3] and a few more pages, not because work wasn’t going well, but because I had something to say.  

But, guess what? Still, all this site comprises is a bunch of html files (a few more than my original) and a CSS file dumped in a folder and uploaded to the host.

So, has the web changed? No, it hasn’t.

[^1]: While this site has never had a blog element, I’ve been getting my writing fix over on [Wordius.com](https://wordius.com) since 2012.
[^2]: I’ve been using [Obsidian](https://obsidian.md), a markdown editor, since 2022 when version 1.0.0 was released. I’ve been writing in markdown since 2007.
[^3]: Static site generators use text input files to generate static web pages. Unlike dynamic websites – WordPress, etc. – these static pages do not change based on the request. This simplifies backend and allows the site to be distributed via content delivery networks. The simple design also protects the site, making it harder for attackers to modify the website due to the smaller attack surface of these relatively simple backends. Some of the most popular static site generators are Jekyll, Hugo, Eleventy, Gatsby, and Next.