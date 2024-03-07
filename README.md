# All These Games Website

This repository contains the website for the All These Games And Nothing To Play podcast, powered by the Jekyll static generator.

The primary purpose of this website is to generate a Podcast RSS feed for listing the show on podcast networks, but posts and other content can also be added.

## Adding episodes

* Add a new file to `_episodes` with filename `eXXX.md`.
* Add the required frontmatter per the example below.
* Upload show audio to `audio` with filename `eXXX.mp3`.
* Upload show art to `assets`, with filename `epXXXart.jpg`.

### Example episode frontmatter

```
---
layout: post
title:  "EXXX: A great podcast"
description: "What an episode!"
showArt: /podcast/epXXXart.jpg
date:   YYYY-MM-DD HH:MM:SS +0100
duration: <Length in seconds>
length: <Size in bytes>
category: episode
hidden: false
---
```

## Adding posts

* Add a new file to `_posts` with filename `YYYY-MM-DD-hyphenated-title.md`.
* Add the required frontmatter per the example below.

### Example post frontmatter

```
---
layout: post
title:  "Welcome to All These Games"
date:   2024-03-04 21:58:10 +0100
categories: update
---
```
