# crown

A collaborative blog amongst brothers.


#### To run locally:
- clone this repo
- cd into your local repo and install bundler
```
gem install bundler
```
- Install jekyll via bundler
```
bundle install
```
- Serve the site locally
```
bundle exec jekyll serve
``` 


#### To contribute as a collaborator
- Assuming you've already cloned the repo
- checkout branch `gh-pages`
- Add a .markdown file into the directory _posts in the following format
```
---
layout: post
title:  "My post title" <--- CHANGE THIS
date:   2015-08-03 7:37:00
categories: crown
author: Ed <--- CHANGE THIS
---
Hello World  <--- CHANGE THIS
```
- pull origin `gh-pages` 
- Commit and push to remote branch `gh-pages`


