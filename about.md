---
layout: page
title: Course Info
description: >-
    Course policies and information.
permalink: /
---

<!-- <div class="about-hero"> -->
  <!-- <img src="{{ '/assets/images/' | relative_url }}" alt="Course banner image"> -->
<!-- </div> -->

# Course Information
{:.no_toc}
---

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## About
Covers the recent advances in computational biology brought about by modern machine learning and artificial intelligence, and in particular Generative AI. This course will center on a detailed understanding of generative AI models and will discuss representative applications to biology. Students will build and use a variety of deep learning models (e.g., VAEs, transformers, diffusion models) in the context of biological problems. This course is intended for students who are interested in the intersection of machine learning and biology but may have previous experience in only one of these topics. Problem sets throughout the semester will provide written and practical experience with model design and training. The course will culminate in a final project in which students will work in groups to apply generative AI to a novel problem in the life sciences. Builds on biology concepts from 6.8700/20.S900, but can be taken independently. Graduate subjects will include additional work on problem sets.


## Resources

Lecture slides and handouts will be made available to students at the respective links:
* [Canvas]({{ site.canvas }}) for assignment/project release
* [Gradescope]({{ site.gradescope }}) for assignment/project submission
* [Piazza]({{ site.piazza }}) for course questions

We also recommend [*Understanding Deep Learning*](https://udlbook.github.io/udlbook/), which is available free online, as an optional text. We strongly encourage students with limited background in ML to look through the relevant sections in conjunction with the lecture content to gain a deeper understanding of these methods.


## Grading Information

### Breakdown
{:.no_toc}

- [Assignments](#assignments): 50%
- [Final Project](#final-project): 50%

Each assignment question will be worth a specified number of points. Written responses will be graded on accuracy and thoughtfulness; implementations will be graded on correctness and, if applicable, output produced. We will provide more information about project grading during the semester.


### Assignments

There will be approximately **5-6 weekly assignments**. Each assignment will be **due on Tuesday at 12:30pm** and will cover the lectures from the previous week. There will be no assignments at the end of the semester to allow as much time as possible to work on projects. Any assignments that require coding will be distributed as Google Colab (.ipynb) notebooks. They may contain a mixture of written responses and implementation tasks. Each assignment should be submitted to the corresponding Gradescope assignment as a PDF of the notebook with all written responses and requested code or other output provided; other content, such as provided code, can be hidden in the final submission to improve readability. Please additionally select the pages of your submission that specifically contain your response to each question.
To generate PDFs, we suggest the use of ```nbconvert``` and have an example notebook. Another option is to use Print to PDF.


### Final Project

A substantial component of the course will be the completion of a course project applying concepts in deep learning to a biological application of your choosing. Projects will be completed in small groups of 2-4 students (with higher standards for larger groups) and will result in a **4-page workshop-style paper and final presentation to the class**. Regardless of the size of each project group, we expect that all group members will play a substantial role in the final result. A project proposal and project milestone will be due in advance (exact dates TBA, but no earlier than Lecture 10).


## Lecture/OH Times

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}


## Other policies

*Attendance and Absences*  
Please attend all lectures if possible. We will always aim to provide lecture slides/materials.

*Class Participation*  
Participation in class is an important component of success in this course. To help us hear from everyone in the class, and maintain an orderly learning environment, please raise your hand and wait for an instructor to call on you in whole-class settings unless told otherwise.

*Collaboration and Citation*  
**All written material you submit, and code, should be your own**. You are free to discuss homework questions with your classmates, provided that you subsequently write up your solutions independently and that you acknowledge your collaborators in your submissions. For the project, all work is to be shared with your group. In proposing and reporting your project, you will be expected to engage with and appropriately cite current research relevant to your selected topic.

*Late Work*  
Weekly assignments will be accepted for one week (168 hours) after the due date and will receive 50% of the credit that would have been awarded. **Late submissions will not be accepted** for the project proposal, project milestone, or final deliverables. In unforeseen circumstances, we may extend due dates without penalty in consultation with Student Services (S3).

*Regrade Requests*  
If you have questions about grading of, or expectations for, specific written-response questions, we encourage you to make a regrade request on Gradescope within one week of grades being released. If you do submit a regrade request asking us to reconsider your grade on a question, we will not re-evaluate your grade on other questions in the same assignment.

*Use of Technology*  
Please do not use ChatGPT or another LLM to write your written or coding responses on the problem sets. If you are stuck, you may consult online resources including LLMs to provide suggestions of ideas or appropriate libraries/methods to use. If you do so, please ensure your final responses are still your own, and please document what resources you used by providing links and/or transcripts of your chats. No documentation is required for using the [*Understanding Deep Learning*](https://udlbook.github.io/udlbook/) book or official documentation for PyTorch or other libraries.
