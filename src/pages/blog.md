---
layout: blog.njk
title: Articles
date: 2017-01-01
pagination:
  data: collections.post
  size: 20
permalink: "blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html"
metaDescription: All notes and blog posts.
subtitle: A collection of notes, blog posts and random thoughts.
eleventyNavigation:
  key: Blog
  order: 2
---
