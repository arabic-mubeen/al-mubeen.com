---
title: Course
description: Mubeen Syllabus for beginner's Arabic course
layout: post.njk
tags: headerNav
hideTagsList: true
eleventyNavigation:
  key: 🎓 Course
  order: 0
---

Notations used in this website are included in the [convention page](/conventions). Check the [material page](/material) for slides and PDFs. This is your timeline as an Arabic learner:

## Beginner

<ul>
{%- for post in collections.beginner %}
<li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
{% endfor %}
</ul>


## Intermediate

*coming soon*

## Advanced

*coming soon*