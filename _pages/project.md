---
layout: page
title: Project
description: EURECOM
permalink: /project
---

#### Format
This year the MALIS project will follow two formats: standard and advanced

#### Organization
You will work in groups of two, maximum three. The group you choose at the beginning of the term cannot be changed. Choose your partner carefully.

#### Standard Project
The standard project will require you to propose a solution to a given problem that should be solved using machine learning. You will be given some constraintrs that you need to respect.

#### Advanced Project
In the advanced project, you will need to identify a problem that can be solved using machine learning. You will need to design and implement your own solution.

#### ChatGPT Usage Policy
Students are strongly encouraged to work on the projects on their own. If ChatGPT is used, it is necessary to include 1 paragraph (in the one page document) explaining how it was used, if it was useful (e.g. it helped us because X reason) 
and/or if there were any encountered problems (e.g. it was not useful for X reason).

**IMPORTANT**: Using ChatGPT does not affect your grade positively of negatively, as long as its use is properly reported and documented. Instead, failing to report the use of ChatGPT will have a negative impact on your grade. 




### Previous Year's Projects

<ul style="list-style:none;padding:0rem 0;">
<ul class="homepage-list" style="list-style:none;padding:0rem 0;">
{% for post in site.posts %}
  <li>
    <a style="display:inline-block;width:60%;" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <time style="float:right;font-size:90%;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
  </li>
{% endfor %}
</ul>
