---
layout: page
title: "Planning better social media integration for posts"
date: 2018-04-04T11:27:39Z
image: /assets/img/logo.png
---

This morning I spent twenty minutes over coffee finishing up _The Physics of Star Trek_, a little book I'd been reading off and on for the past few months. Then, completely against my current process of ignoring my own process, I did what I ought to do: I sat down and immediately transcribed and wrote a review for the book. The whole process - light for this book, as I only took a handful of notes that weren't worth transcribing to my electronic notes - took around twenty minutes, give or take. That's from starting the review to sending it out on the website, on Buffer to Twitter, and through Mailchimp.

You can read the review, [here](https://www.burntfen.com/the-litt-review/the-physics-of-star-trek/).

In the process, I realised once again that I am under-utilising my programming skills and marketing skills. While this wasn't a particularly illuminating review, it did reflect thoughtful content that I put out on a daily basis. I ought to be posting this to a few venues, every time. For instance, I'd rather my Instagram feed had all of the books I read and review on it - that more perfectly captures how I would like to be seen and perceived, and the kind of audience I want, than random photos of cats in windows. I should also automatically tweet and mail out my reviews, and this blog, instead of manually running the process.

I wrote up an issue on my [knowledge repo](https://github.com/RichardLitt/knowledge/issues/23), where I keep public processes and notes I've written up. Here's the text below

---

Buffer is useful for Twitter, but it underperforms for Instagram, and it isn't connected to other social medias.

When I post a book review using [this process](https://github.com/RichardLitt/knowledge/blob/master/processes/publishing-book-review.md), I should also do the following:

- [ ] Post the URL to Twitter with the image and a specified comment
- [ ] Post the book title to Instagram with a link to the URL
- [ ] Post the review to Scuttlebutt
- [ ] Post the review to Facebook (if Facebook is something I'm interested in maintaining, which it isn't clear it is, as I have it disconnected most of the time)
- [ ] Post the review to Medium?
- [ ] Post the review to the Mailchimp list
- [ ] Post the review to my Tinyletter list
- [ ] Add the review to my weekly newsletter roundup
- [ ] Post to relevant Slacks

Right now, I post only to Mailchimp and Twitter - the former manually, the latter through the Buffer API. 

All of this is contingent on putting out high noise, medium signal messaging. Basically - if I write something, post it for people to see. I'm not entirely interested in high signal, low noise messaging: that's what my weekly newsletter is for. Twitter is high noise low signal by default, so I can push everything there with impunity. 

I'm not entirely convinced that my book reviews (among other types of content, like my [2018-april](https://github.com/RichardLitt/2018-april) blog going on right now) are actually low signal, anyway. I know people enjoy reading them, and measures of signal seem arbitrary. 

In any event: there ought to be a shell script or a webapp that I run which does all of this posting for me, or some way of setting up a non-brittle poster through various APIs and connected services - for instance, through RSS (something I'm [having issues doing](https://github.com/RichardLitt/richardlitt.github.com/issues/72) through the Jekyll RSS feed plugin). 

This probably isn't a solitary problem, and may help others.

---

This is related to my Jekyll scheduler, too. Right now, I have a backlog of book reviews to publish (and a massive backlog - around 40 books - of books to review which I've read in the past few months). I may be able to kill two birds with one stone, if I get the Jekyll scheduler up and integrate an API or automatic posting into it. Something to think about.
