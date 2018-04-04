---
layout: post
title: "Maintainer Repository Audits and Open Collective"
date: 2018-04-04T16:49:23Z
image: /assets/img/logo.png
---

[Maintainer Mountaineer](https://maintainer.io) offers repository audits. These are manually done; I go through a checklist and see if I can make sense of the repository, if there are any issues in the README, or package manifests, or Contribute files, and so on. They generally take around 45 minutes, but often take longer as I get distracted and spend time fiddling with things. I bill them through Maintainer at $75 each.

Today, I did my first one that I've done in a while, for [octobox](https://github.com/octobox/octobox), which I was scheduled to do since [@teabass](https://twitter.com/teabass) asked me to do some for him a couple of weeks ago.

You can see what a finished audit looks like, [here](https://github.com/octobox/octobox/issues/585). If you're interested in getting one, do [get in touch](mailto:richard@burntfen.com)!


I spent some time working on my process, and logging some issues in an internal repository I use to keep track of the shell scripts and templates I use to make this work fast. These are the kind of issues I opened:

```sh
5: [audit] Add a way to automatically post gist
4: [audit] Generate js fields with flag or omit them
3: [audit] Have audit copy name and gh-description into template
2: [audit] automatically point out all spellchecked words
```

I also opened a PR for [git-extras](https://github.com/tj/git-extras/pull/707) to add documentation around the `--org` option for `git fork`, which is a handy way to fork a repository from your CLI.

I have a few more of these coming, too.

For billing, instead of billing by email, I used [Open Collective](https://opencollective.com). I have a profile for [Maintainer](https://opencollective.com/maintainer) there, but wasn't able to figure out how to invoice from a collective to another collective - we'll figure that out later. For now, I've submitted an invoice manually by PDF through OpenCollective, and it's already been approved.

Good work, team!

