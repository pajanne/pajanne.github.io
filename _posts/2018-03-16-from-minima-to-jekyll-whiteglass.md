---
layout: post
title:  "From minima to jekyll-whiteglass theme"
date:   2018-03-16 17:24:00
categories: jekyll update
---

Using [GitHub - yous/whiteglass: Minimal, responsive Jekyll theme for hackers](https://github.com/yous/whiteglass)

```bash
cd pajanne.github.io/

sudo gem install jekyll-whiteglass

curl -L -O "https://github.com/yous/whiteglass/raw/master/{index.html,about.md,archives.md,feed.xml}"
curl -L --create-dirs -o _data/navigation.yml https://github.com/yous/whiteglass/raw/master/_data/navigation.yml

bundle install
bundle exec jekyll serve
```

Simple Customisation:
- change `archives/` into `posts/` in menu and on disk
- add link to latest post on home page
- add `author:` in `_config.yml` to appear in footer
