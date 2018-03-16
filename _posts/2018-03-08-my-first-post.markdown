---
layout: post
title:  "My first post!"
date:   2018-03-08 18:21:00
categories: jekyll update
---

This is my first post using [Jekyll][jekyll]. Setting it up is easy. Next step will be to look into **themes**.

To install Jekyll locally into an existing directory:
```shell
sudo gem install -n /usr/local/bin jekyll bundler
jekyll new . --force
```

To view you site locally:
```shell
bundle exec jekyll serve
```
and go to http://127.0.0.1:4000/

To push it to GitHub:
```shell
git add .; git commit -m 'new posts'
git push
```

[jekyll]: https://jekyllrb.com/
