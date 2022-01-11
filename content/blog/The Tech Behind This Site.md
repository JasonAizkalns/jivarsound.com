---
title: The Tech Behind This Site
date: 2018-05-26
tags: [the making of, tech, code]
---
[Hello World!](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) 😜

Be forewarned, this is *not* the typical theme/genre behind these posts, but my
inner geek feels obligated to share some of the technologies
being leveraged "behind-the-scenes" which make this site possible.

Most of the heavy lifting is done by [hugo](https://gohugo.io/). Hugo is an
open-source static site generator. I chose to use it because I wanted something
fast, I wanted to learn something new, and I wanted to have complete control
and ownership over all the moving parts (i.e., I did not want to use platform).

I purchased my domain from [namecheap](https://www.namecheap.com/) for about $10
and that's about the extent of the investment required (barring your time) to
keep something like this up and running.

Hosting and continuous integration is handled via [netlify](https://www.netlify.com/)
which has been incredible. It truly is as simple as (1) connect a repository,
(2) add build settings, and (3) deploy. Their support is equally fantastic -- I
had a few noob DNS questions and they responded quickly and comprehensively.

As far as the actual *code*, all of this is primarily HTML, CSS, Markdown, and a
few sprinkles of JavaScript. All of the source code is available in [this GitHub repo](https://github.com/JasonAizkalns/jivarsound.com).
Granted, this code is pretty messy -- I am not a web developer and I (stubbornly)
chose *not* use a [hugo theme](https://themes.gohugo.io/). I wanted to better
understand all the ins-and-outs, but in retrospect, I probably should have just used a
pre-built theme. As a result, if you explore the code, you'll likely observe a lot
of bad practices and less-than-ideal utilization of [templates](https://gohugo.io/templates/)
and [partials](https://gohugo.io/templates/partials/).

Any non-branded (e.g. SoundCloud, clyp.it, etc.) sound bits are made possible
by [plyr.io](https://plyr.io/) -- a simple, accessible, and customizable media
player for video, audio, YouTube, and Vimeo.

Finally, I did use another piece of tech worth calling out. Specifically, this
site leverages [tachyons](https://tachyons.io/) for its CSS. In the past, I have
used [bootstrap](https://getbootstrap.com/), but I wanted to try something
new/different and I wanted something a little less bloated/heavy. I'm still not sure
if I like it better or worse than heavy stylesheets. Like most new skills/tech, things
were rough at first, but after memorizing a few class names (I still need to [check this out](https://tachyons.pro/)),
things started to come together with less hair-pulling. What drew me to tachyons was the fact that
it is *functional* which tugs at my heart strings given its similarities to my
day-to-day programming language of choice, [R](https://www.r-project.org/).
