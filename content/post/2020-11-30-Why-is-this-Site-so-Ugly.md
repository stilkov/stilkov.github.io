---
title: 'Why is this Site so Ugly?'
date: '2020-11-30'
lang: 'en'
---

You might think the answer to this question is obvious: Because I don’t know CSS well enough to make it beautiful. And while technically, that’s 100% correct, there’s also a secondary reason: I wanted to reduce the effort to maintain things around here to an absolute minimum. I just wanted things to be clearly readable, and I think the current “design” serves that purpose quite well. 

Of course even the 20 or so lines of inline CSS (yes indeed) are stolen from the brilliant [perfect motherfucking website](https://perfectmotherfuckingwebsite.com). I inlined them because that means that if you’re reading a page like this one, your browser was served exactly that, a single page (unless I include an image or diagram because it makes sense for the content). It’s as design-free as I dare to make it. I think this works very well for single content pages.

Of course, design matters more on other pages, e.g. the home page itself. But I don’t really think that’s a problem either. Who would end up visiting that anyway? Chances are you arrived here because you followed a link from some social media post, or because something turned up in a Google search. Home pages are vastly overrated.

I also tried to opt for the (to me) simplest possible setup with regards to authoring posts and maintaing this site. So I decided to host this on [Netlify](https://www.netlify.com), based on a [Github repo](https://github.com/stilkov/netlify-site) containing a very minimalistic [Hugo](https://gohugo.io) setup (originally based on the [xmin theme](https://github.com/yihui/hugo-xmin), but there’s really nothing left of it). Create a post, add, commit, push, done. It’s simple and serves its purpose, but I’m not _completely_ happy with it: For my taste, Netlify is way too slow – probably unnoticable for many sites, but in this particular case, there is really almost no content to serve, and the fact that occasionally takes more than a second is pretty ridiculous. But I’ll deal with that another time.

My goal was to reduce friction, and make sure I have zero excuses left for not writing. With this and the last post out of the way, I think I may have to admit I have reached that goal.

_Update 2020-12-15_: Some things have changed, I’ll document them soon (e.g. this is now built with Hugo as a GitHub action, and the result is served by GitHub Pages).
