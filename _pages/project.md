---
layout: page
title: Project
description: EURECOM
permalink: /project
---

### Format
Instead of working on a single big project, this year the MALIS project will consist of 4 smaller projects of shorter duration.

### Organization
You will work in groups of two. The group you choose at the beginning of the term cannot be changed. Choose your partner carefully.

### Deliverables
For every project you need to deliver:
1- The code associated to the project
2- A 1 page document briefly explaining what was done and how to run the code
3- In the document, it is **mandatory** to include a statement about the contributions of each of the team members (who did what)

### ChatGPT Usage Policy
Students are adviced to work on the projects on their own. **Using ChatGPT does not affect your grade positively of negatively, as long as its use is properly reported and documented**. 
If ChatGPT is used, it is necessary to include 1 paragraph (in the one page document) explaining how it was used, if it was useful (e.g. it helped us because X reason) 
and/or if there were any encountered problems (e.g. it was not useful for X reason).

**Failing to report the use of ChatGPT will have a negative impact on your grade**. 

### Grading
The best three grades will be considered and averaged into a single final project grade. 
While this means that you may skip one project, it is strongly encouraged to work on and deliver all projects. 

### Oral Presentation
In the lecture following the delivery of one of the projects, a group will be chosen at random to present in front of the class their project.


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
