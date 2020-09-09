---
title: Incorporating Ethics into A Data Science Course
author: Shannon Ellis
date: '2020-07-06'
slug: incorporating-ethics-into-a-data-science-course
categories:
  - education
tags:
  - ethics
---

A [recent report](https://thenextweb.com/neural/2020/07/03/study-only-18-of-data-scientists-are-learning-about-ai-ethics/) based on a [survey by Anaconda](https://www.globenewswire.com/news-release/2020/06/30/2055578/0/en/Anaconda-Releases-2020-State-of-Data-Science-Survey-Results.html) indicated that *only 18% of data science students are learning about AI ethics* [^1].

[^1]: I'd be happy to discuss the details of this survey and how valid this particular figure is or is not. However, even if this survey is off by a bit and doesn't capture the true value, it's still a staggeringly low number.


In response I tweeted:

<center>{{< tweet 1279449402134818816 >}}</center>

Among the responses, there was a short thread from a data science educator arguing that tweeting what educators must do is less helpful than having a nuanced discussion about how to approach this:

<center>{{< tweet 1279514114511892480 >}}</center>

This educator's exasperation boils down to (hopefully this paraphrasing is OK) "Yes ethics are important, but my syllabus/course is chock full. What am I supposed to cut?"

This reaction happens often in courses across fields. It's a totally valid and reasonable response. A lot is asked of educators, and, often, courses don't stand alone, with upper level courses expecting prerequisite courses to teach certain concepts. While this approach ultimately allowing for students to deepen their understanding throughout their studies, it can limit an educator's freedom in changing what's taught in a course.

With this in mind, I figured I'd write a blog post trying to add some nuance to my initial tweet, in case it's helpful for educators trying to figure out how to incorporate ethics into their data science courses.

I'll note that my initial thread urged educators to specifically read *[Integrating data science ethics into an
undergraduate major](https://arxiv.org/pdf/2001.07649.pdf)* and the work of [Casey Fiesler](https://caseyfiesler.com/publications/). And, while I add my thoughts here, I'm still urging people start with these resources.

## Data Science Curricula

As I explain to my students early on in any data science course, the simultaneously awesome and frustrating thing about data science is that it's new and changing. For example, there is not a definitive text for an "Intro to Data Science" course the same way there is say for ["Intro to Biology"](https://www.pearson.com/us/higher-education/program/Urry-Modified-Mastering-Biology-with-Pearson-e-Text-Access-Card-for-Campbell-Biology-12th-Edition/PGM2842336.html). 

This evolving nature provides me with flexibility in what I teach in an intro data science course. Each iteration of a course I'm able to swap the order around, add topics, remove topics, and change assignments, while adding in new examples, new technologies, and new ideas. But, it requires constant maintenance and updating. 

Each quarter I start from the same notes and make adjustments. In my experience, the changes I make to my data science courses are probably 2-3x more than the changes I make to more "stable" or "historical" classes. To me, this keeps data science interesting to teach. But, I understand there is limited incentive for educators to constantly change their materials.

The nebulous nature of data science has its downsides as well, of course. Two students who take a course called "Introduction to Data Science" could learn *vastly* different things, depending on the program, university, or professor. While I imagine this will level out over time (evidence of which we've already seen in data science's short history), given the current cross-course variability, it difficult for me to tell an educator what to remove from their syllabus...without, as was requested in the response thread to my initial tweet, looking specifically at their syllabus[^2].

[^2]: I'd be happy to take a look at any educator's data science syllabus though and give my two cents as to what I'd cut, if anyone thinks that would be helpful. I'm sure this would also give me additional ideas for my own courses!

What I can do, however, is discuss how and where I incorporate data science ethics into my data science courses, explain what I do to keep materials (reasonably) up-to-date, and share some student responses to my approach.


### First Week: Ethics

I teach data science ethics during the first week of my data science courses.

On many data science syllabi, I've seen ethics relegated to the end of the course. Whether we like it or not, students are stressed out about finals and skipping out on classes more frequently at the end of the term, which limits how much students get out of material at the end of the course. Further, regardless of intent, putting data science at the end of a course signals that the material is less important.

By including ethics in the first week of class, not only do these lessons reach students when they're quite receptive to new material and establishes the importance of ethics in data science, but in doing so, I'm able to refer back to the ethical tenets discussed in the first week throughout the course, as I discuss subsequent data science concepts.

I figured sharing slides that I use to demonstrate how I approach explaining ethics and giving students a framework from which to work through the rest of the quarter may be helpful to those trying to figure out where to start. I include a few bullet points about what is covered in each:

**COGS 9** Introduction to Data Science (Day 2) |  [slides](https://docs.google.com/presentation/d/1D1tlREOa73f6ko1Jxq9HYhfC47-Inxe-ALuz0rJUBLQ/edit?usp=sharing) [^3]

[^3]: I discuss what worked well from teaching ethics in COGS9 in [this post](http://www.shanellis.com/blog/cogs9-introduction-to-data-science/).

- clicker questions (warm-up)
- introduction of places where data science has veered off course
- in-depth presentation of *Experimental evidence of massive-scale emotional contagion through social networks* (PNAS 2014) with discussion of ethical debate
- introduction to first principles: Belmont Report & the Common Rule
- discussion of how data scientists should proceed
- clicker questions (follow-up) [^4]

[^4]: I present how students changed their opinions on these statements from the beginning to the end of class the following day in lecture.

**COGS 108** Data Science In Practice (Day 1) |  [slides](https://docs.google.com/presentation/d/1JKINC90K1laZRHdM1F-ZRBDWCBp73VmFh7W4sjh5Jno/edit?usp=sharing) [^5]

[^5]: Ethics start at slide 45; These slides were adapted from slides initially developed by [Tom Donoghue](https://tomdonoghue.github.io/)

- brief explanation of where things have done "wrong" in data science
- definitions/intro
- 9 things to consider to not ruin people's lives with data science
- wrap up




### Beyond the First Week: Ethics Throughout

By discussing ethics in the first week, students understand the importance of ethics and have the vocabulary to start considering this work throughout the course *while* teaching other concepts. This helps to demonstrate that ethics is important throughout the entire data science process and allows students to get practice in their ethical thinking.

#### Lectures

I incorporate ethics into future lectures in a handful of ways, but I'll explain one concrete example. In "Introduction to Data Science" we discuss machine learning. After providing students with the core concepts they need to know to understand machine learning and a few examples, I use an example of how biased data can perpetuate historical biases. | (slides available [here](https://docs.google.com/presentation/d/1S6yCZp1wNXJ86OjClhoYESO4L4Lj6aGPUeOaVrM9gPo/edit?usp=sharing))

To summarize here, I use data that I've collected from students (surveys, exams scores, etc.) to build a predictive model about their future success. Now, I tell them I don't know who will or will not go on to be successful, so I generated that data. But, all other data, came from students directly. We have a discussion about what features to incorporate in the model, which to not, which will be most predictive. I first build the model without ethnicity and gender. The model is no better than flipping a coin. I then regenerate the model including ethnicity and gender. The model is perfectly predictive. I delve deeper and find that only Asian females go onto be successful. We then have a discussion about whether, if this occurred, I should only meet with Asian females, only read their projects carefully, etc. (Spoiler: I should not.) We then discuss the fact that Asian females have historically _not_ been the group that has benefited from predictive models.

These sorts of examples allow me to teach both the concept for that lecture (machine learning) while also discussing ethics and helping students to make connections across topics covered on different days in the course.

#### Assignments

Within assignments, we can also have students practice a skill while also considering ethics. For example, in COGS 108 Data Science In Practice, we use an assignment where students have to wrangle a number of datasets, and in doing so are able to identify individuals in the dataset. Then, we ask students to de-anonymize the data. This allows us to, in a very real way, discuss data privacy. We explicitly demonstrate how "anonymized" data are not always as anonymous as we intend, while also getting students a lot of practice with data wrangling.

#### Readings 

There are *tons* of great articles that students could read with respect to data science ethics. My two favorites to assign to students are *[Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)*, from Propublica and *[A Mulching Proposal](https://ironholds.org/resources/papers/mulching.pdf)*, by Keyes et al. 

Typically, students read these, take a reading quiz to check understanding, and then discuss these in smaller discussion sections. By working through material in this tiered approach, students get experience reading and processing on their own while also getting the chance to deepen their thinking with guided discussion among their peers (and with the help of instructional staff).

#### Projects

In both COGS 9 and COGS 108, students have to carry out a data science project as a group. In COGS 9, as this is a survey course, students have to propose a project and write a report. In COGS 108, as it is a technical, hands-on course, students have to propose and carry out the entire project. In both courses student write a project proposal. In this, they have to consider the ethical implications of their work. In student proposals, often students are initially limited in their ethical thinking, such that they struggle to consider anything beyond "data privacy." We provide specific feedback to each group, asking them to consider the entire data science process (i.e. "Should this question be asked?", "Are there unintended consequences?", "Who could be harmed?", etc.) for their final project report. With this feedback, readings, and discussions throughout the course, final reports regularly demonstrate much deeper ethical thinking than proposals submitted earlier on in the course.

## How To: Organization

While others likely have better strategies, I have two approaches to keeping material up-to-date:

1. I use [Pocket](https://getpocket.com/explore/?utm_source=homepage_explore_test) to save readings throughout the year. I have an "ethics" tag. When I prep lectures each quarter, I look through that tag to see what I want to use to update my materials. (Note: I have similar tags for other concepts I cover across my courses.)
2. I add "comments" on my Google Slides any time I think of something I want to add/remove/changes. This way, if I don't have the time to generate/fix the slides at that moment, I have a reminder to myself for when I am focused on content updates.

## Student Responses

To finish, I'll include just a few student comments from different iterations of these courses (**emphasis** my own) to highlight that students appreciate the inclusion of this content in their data science courses and often feel as though it's not covered enough in their other technical courses.

In response to "What topics do you wish we would cover OR cover in more depth?"

> _ethics! I thought it was really cool looking at studies, would like to look at more._ - COGS 9, Fall 2019

In response to "What was/were your MOST favorite thing(s) (i.e. topics, course logistics, assignments, etc.)?"

> _Learning how the information we were learned has been applied to real-life scenarios. An example of this was when we were learning about ethics, Professor Ellis mentioned instances where ethics were not fully taken into account and the repercussions of doing so._ - COGS 108, Spring 2020

Additional Post-Course Student Comments:

> _I really appreciate how much the course and the project are focusing on the ethical questions. **Most of my CS/DS classes don't discuss these issues as thoroughly as this class does. After taking this class, I learned to critically analyze a research not only by its technical details, but also by its ethical saliency.**_ - COGS 9, Winter 2018

> _I just wanted to send you a thank you email because I found that a lot of the way I conduct myself in the workplace was greatly inspired from your class. I was fortunate enough to land an internship this summer at Northrop Grumman, and although it is a software engineering internship, many of the things I learned in COGS 108 is still applicable. My newfound background knowledge of Python and **the ethics and values you preach in class are things that I often find the most valuable**. Although the assignments were where I made the most progress "technically" (i.e writing the code, debugging the code, etc;), I enjoyed your lectures the most. Your ability to curate both informative and interesting topics that kept me engaged and made it easy to understand complex ideas are greatly appreciated. Once again, thank you for having me in your class and thank you for teaching a class that I found had **much more value than just some understanding of code, but instead on ethics and good practices**._ - COGS 108, Spring 2019

## Conclusion

While I very much sympathize with the tweet thread I got in response and agree with the sentiments, I hope this blog post can help spark some ideas in data science educators as to how they incorporate ethics early and often without having to change too much of what they cover in their courses. I very much believe that discussing ethics early on in a course and then having ethical discussions/examples sprinkled throughout a data science course can be incredibly effective and accomplished without removing too much content from one's current course. 

And, I would, of course, love to see examples of what others have done and read blog posts or tweets about what people cut or changed to make this possible as they go through the process!

