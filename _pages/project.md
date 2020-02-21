---
layout: page
title: Project
description: EURECOM
permalink: /project
---

One of the main goals of this course is to prepare you to apply machine learning algorithms to real-world tasks, or to leave you well-qualified to start machine learning research. The final project is intended to start you in these directions.

### Project Topics
Your first task is to choose a problem to work on. You can find some inspiration in the list of projects from previous sessions [here](#previous-projects). 

### Project Deliverables: Proposal, progress report, final deliverable and presentation
This section contains the detailed instructions for the different parts of your project.

#### Evaluation
The breakdown of the 30% that the final project is worth amongst the different parts will not be disclosed. Final presentation and report will combine to be the majority of the grade. Projects will be evaluated based on:

* The technical quality of the work: Does the technical content makes sense? Is the proposed work interesting and reasonable? Is your work proposing novel insight on the problem?
* Significance: Is the chosen problem a "real" and interesting one? or is it just a toy problem? Could this work be useful and have an impact? 
* The novelty of the work: Doe sthe project applies a common technique to a well-studied problem, or are any of these relatively unexplored? 

In order to highlight these components, it is important you present a discussion regarding the learnings from the development of your method, and summarizing how your work compares to existing approaches.


#### Project Proposals
In the project proposal, you'll pick a project idea to work on early and receive feedback. If your proposed project will be done jointly with a different class' project, you should obtain approval from the other instructor and approval from me. 

In the proposal, below your project title, include the project category. The category can be one of:

*Format*: Your proposal should be a PDF document, giving the title of the project, the full names of all of your team members, and a 300-500 word description of what you plan to do.

*Content*: Your project proposal should include the following information:
* Motivation: What problem are you tackling? Is this an application or a theoretical result?
* Method: What machine learning techniques are you planning to apply or improve upon?
* Intended experiments: What experiments are you planning to run? How do you plan to evaluate your machine learning algorithm? Presenting pointers to one relevant dataset and one example of prior research on the topic are a valuable (optional) addition.

*Grading:* The project proposal is mainly intended to make sure you decide on a project topic and get feedback from TAs early. As long as your proposal follows the instructions above and the project seems to have been thought out with a reasonable plan, you should do well on the proposal.

#### Progress report
The progress report will help you make sure you are on track, and should describe what you've accomplished so far, and very briefly say what else you plan to do. You should write it as if it's an “early draft" of what will turn into your final project. You can write it as if you're writing the first few pages of your final project report, so that you can re-use most of the milestone text in your final report. Please write the progress report (and final one) keeping in mind that the intended audience are the jury members and myself. Your progress report should include the full names of all your team members and state the full title of your project. 

*Contributions:* Please include a section that describes what each team member worked on and contributed to the project. This is to make sure team members are carrying a fair share of the work for projects. 

*Grading:* The progress report is mostly intended to get feedback to make sure you are making reasonable progress. As long as your milestone follows the instructions above and you seem to have tested any assumptions which might prevent your team from completing the project, you should do well.

*Format:* Your progress report should be at most 3 pages, excluding references. Similar to to the proposal, it should include:
* Motivation: What problem are you tackling, and what is the setting you are considering?
* Method: What machine learning techniques have you tried and why?
* Preliminary experiments: Describe the experiments that you have run, the outcomes, and any error analysis that you have done. It is expected to have tried at least one baseline.
* Next steps: Given your preliminary results, what are the next steps that you are considering?

#### Final deliverable 
Your final deliverable will include the project report as well as the code produced during the project. Using a github for the latter is strongly recommended.

*Format*: Final project report can be at most 5 pages long (including appendices and figures). Extra pages are allowed only if they contain only references. If you did this work in collaboration with someone else, or if someone else (such as another professor) had advised you on this work, your write-up must fully acknowledge their contributions. For shared projects, it is required that you submit the final report from the class/project you are sharing the project with. You can use the guidelines from Standford's ML course on how to write the final report ([link](http://cs229.stanford.edu/final-report-guidelines.pdf)).

*Contributions*: Please include a section that describes what each team member worked on and contributed to the project. I might reach out and factor in contributions and evaluations when assigning project grades.

*Code*:	Please include a link to a Github repository or zip file with the code for your final project. You do not have to include the data or additional libraries.

*Grading*: The final report will be judged based off of the clarity of the report, the relevance of the project to topics taught in MALIS, the novelty of the problem, and the technical quality and significance of the work.


### Final Presentations
The projects will be presented at a session with 3 invited external jury members that will assess the projects'quality. Each team should prepare a slide, and be prepared to give a 3 minutes presentation  about their work. This will give you all the opportunity to see what everyone else did for their projects. You will  need to submit your presentation as a PDF two days before the presentation.

*Grading:* Presentations will be graded based on their quality and clarity, the technical content, and the knowledge demonstrated by the team when discussing the work with the jury members.

### Previous Projects

<ul style="list-style:none;padding:0rem 0;">
<ul class="homepage-list" style="list-style:none;padding:0rem 0;">
{% for post in site.posts %}
  <li>
    <a style="display:inline-block;width:60%;" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <time style="float:right;font-size:90%;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
  </li>
{% endfor %}
</ul>
<br>
<b>Acknowledgments:</b> The project format and the content of this page are inspired by <a href="http://cs229.stanford.edu/projects.html">Stanford's ML Course (CS229)</a>
