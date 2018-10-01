---
title: 'MOOC Development: It Takes a Village'
author: Shannon Ellis
date: '2018-10-01'
slug: mooc-development-it-takes-a-village
categories:
  - education
tags:
  - MOOCs
  - diversity
---

## Chromebook Data Science

We're finally able to announce the official launch of our newest MOOC, [Chromebook Data Science](https://leanpub.com/universities/set/jhu/chromebookdatascience), a set of 12 courses offered on the Leanpub platform. Jeff Leek has explained this program in a [separate blog post](https://simplystatistics.org/2018/10/01/chromebook-data-science-an-online-data-science-program-for-anyone-with-a-web-browser/) in detail, but briefly here,  these MOOCs are our attempt to [minimize all barriers of entry into data science](http://jhudatascience.org/chromebookdatascience). These courses are pay what you want, so the entire course set can be taken at no cost. All the learning happens through a web browser, so any laptop or Chromebook can be used to complete the material. And, the content has been developed without the requirement for any background knowledge in computing. 

The point of *this* blog post, however, is to **thank and note all of the people outside of our group whose work helped make the development of this content possible**. 

## Thank You

In addition to content developed by members of our group, we have built upon the work of others to generate the content in these courses. As we worked to develop the content, I did my best to keep an exhaustive list of everyone's work we leaned on to develop this content. This post is my humble attempt to thank all these people.

### Big Thanks

It probably goes without saying that much of the content generated has been either directly influenced or indirectly inspired by the work of **[Hadley Wickham](http://hadley.nz/)** and **[Jenny Bryan](https://www.stat.ubc.ca/~jenny/)**. Specifically, however, we would be remiss not to thank Hadley for both writing [R for Data Science](http://r4ds.had.co.nz) and for his contributions to the [`tidyverse`](https://www.tidyverse.org/) packages. Additionally, we rely heavily on Jenny Bryan's  [instructional approach to teaching version control](http://happygitwithr.com/) and the [`googlesheets`](https://cran.r-project.org/web/packages/googlesheets/vignettes/basic-usage.html) package throughout the Course Set.

Beyond this, I think the best way to give individual thanks would be by course in our MOOC. This way, each of you knows where your work has been used and can most easily see how we've used and attributed your work.

### Data Tidying

In the [Data Tidying](https://leanpub.com/universities/courses/jhu/cbds-tidying) course, learners in this course set are taught within the tidy data framework. These concepts would not be easily accessible and programatically-relatable to new learners without Hadley's (and others'!) contributions to the `tidyverse` set of packages. 

Additionally, we used examples of data tidying in this course from **[Miles McBain](https://milesmcbain.xyz/)** and **[Sharla Gelfand](https://sharlagelfand.netlify.com/)** to demonstrate what untidy data are and what it looks like once those data have been tidied. Thank you to Sharla and Miles for their wonderful blog posts demonstrating data tidying:

* *[Tidying the Australian Same Sex Marriage Postal Survey Data with R](https://medium.com/@miles.mcbain/tidying-the-australian-same-sex-marriage-postal-survey-data-with-r-5d35cea07962)*, by [Miles McBain](https://milesmcbain.xyz/)
* *[Tidying and mapping Toronto open data](https://sharlagelfand.netlify.com/posts/tidying-toronto-open-data/)*, by [Sharla Gelfand](https://sharlagelfand.netlify.com/)

Lastly, in this course we relied *heavily* on **[Suzan Baert's](https://suzan.rbind.io/)** four *amazing* `dplyr` tutorials. I've attributed her work throughout the lessons and have linked to her blog posts in our courses. If you haven't looked through them yet, I highly recommend it: [Part 1](https://suzan.rbind.io/2018/01/dplyr-tutorial-1/) [Part 2](https://suzan.rbind.io/2018/02/dplyr-tutorial-2/) [Part 3](https://suzan.rbind.io/2018/02/dplyr-tutorial-3/) [Part 4](https://suzan.rbind.io/2018/04/dplyr-tutorial-4/)


### Data Visualization

[Data Visualziation](https://leanpub.com/universities/courses/jhu/cbds-visualization) is taught in this course set using `ggplot2` exclusively, so more thanks to [Hadley](http://hadley.nz/) for his work and all contributors to the `ggplot2` package! 

Additionally, we used a graph from a [blog post](https://blog.datawrapper.de/better-charts/) by **[Lisa Charlotte Rost](http://lisacharlotterost.de/)** to demonstrate how to take a plot from exploratory and unpolished to polished and ready for publication. If you're unfamiliar with Lisa Charlotte Rost's work in data visualization (spoiler: she's amazing!), check out the [Datawrapper](https://www.datawrapper.de/) and their [blog](https://blog.datawrapper.de/).

### Getting Data

In the [Getting Data](https://leanpub.com/universities/courses/jhu/cbds-getting-data) course, we owe thanks to: 

* **[Jenny Bryan](https://twitter.com/JennyBryan)** for her [`googlesheets`](https://cran.r-project.org/web/packages/googlesheets/vignettes/basic-usage.html) package and incredible ability to write helpful documentation
* **[Tyler Clavelle](https://www.tylerclavelle.com)** for his blogpost [Using R to extract data from web APIs](https://www.tylerclavelle.com/code/2017/randapis/)
* **[Kan Nishida](https://blog.exploratory.io/@kanaugust)**, for his blogpost [Working with JSON data in very simple way](https://blog.exploratory.io/working-with-json-data-in-very-simple-way-ad7ebcc0bb89)
* **[Jose Roberto Ayala Solares](https://towardsdatascience.com/@jroberayalas)**, for his [Web Scraping Tutorial in R](https://towardsdatascience.com/web-scraping-tutorial-in-r-5e71fd107f32)


### Data Analysis

In the [Data Analysis](https://leanpub.com/universities/courses/jhu/cbds-analysis) course, we relied heavily on **[David Robinson](http://varianceexplained.org/)**'s blogpost, *[Text analysis of Trump's tweets confirms he writes only the (angrier) Android half](http://varianceexplained.org/r/trump-tweets/)*, as a wonderful example of how to formulate a data science question and determine if you have the data you need, and for his contributions to the `tidytext` package.

These lessons in this course also benefitted from:

* **[Nick Tierney](https://www.njtierney.com/)**'s awesome work, in particular his `neato` package for visualizing missing data.
* **[Max Kuhn](https://twitter.com/topepos?lang=en)**'s incredible [`caret`](http://topepo.github.io/caret/index.html) package, for predictive modeling
- **[Michael Hoffman](https://twitter.com/michaelhoffman?lang=en)** and **[Carl de Boer](https://twitter.com/CarldeBoerPhD?lang=en)**'s helpful [Twitter discussion](https://twitter.com/michaelhoffman/status/989251677646704641) about predictive modeling terminology

### Written & Oral Communication in Data Science

In [Written and Oral Communication in Data Science](https://leanpub.com/universities/courses/jhu/cbds-communication), we utilized the work of others as examples of how to communicate effectively as a data scientist:

* **[Julia Silge](https://juliasilge.com/about/)**'s *Text Mining the tidy Way* presentation - [video](https://www.rstudio.com/resources/videos/text-mining-the-tidy-way/) [visuals](https://speakerd.s3.amazonaws.com/presentations/d6041c6b704d4bf7bfa9d0973ae2d006/rstudio_conf.pdf) (and for her contributions to the `tidytext` package)
* **[Lucy D'Agostino McGowan](https://www.lucymcgowan.com/)**'s *[Harnessing the Power of the Web via R Clients for Web APIs](https://www.lucymcgowan.com/talk/asa_joint_statistical_meeting_2018/)* presentation
* **[Suzan Baert](https://suzan.rbind.io/)**'s [four-part](https://suzan.rbind.io/2018/01/dplyr-tutorial-1/) [data](https://suzan.rbind.io/2018/02/dplyr-tutorial-2/) [wrangling](https://suzan.rbind.io/2018/02/dplyr-tutorial-3/) [series](https://suzan.rbind.io/2018/04/dplyr-tutorial-4/), as an example of how to write a "How-To" blog post
* **[Hilary Parker](https://hilaryparker.com/)**'s ["Writing an R package from Scratch"](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/), as an example of how to write a "How-To" blog post
* **[Greg Wilson](http://third-bit.com/)**'s [Twitter Thread on Meetings](https://twitter.com/gvwilson/status/994553693772099589), as guidelines for when and how to have meetings.


### Getting a Job in Data Science

In [Getting a Job in Data Science](https://leanpub.com/universities/courses/jhu/cbds-getting-jobs) we're thankful for contributions from:

* **[Yihui Xie](https://yihui.name/)**, for the [`blogdown`](https://bookdown.org/yihui/blogdown/) package and his blogpost [You Do Not Need to Tell Me I have a Typo in My Documentation](https://yihui.name/en/2013/06/fix-typo-in-documentation/)
* **[Renee Teate](http://www.becomingadatascientist.com/)**, for being supportive of and helpful to others on [Twitter](https://twitter.com/BecomingDataSci?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) who are interested in getting a job in data science
* **[Emily Robinson](http://hookedondata.org/)**, for her blogpost [Advice For Applying to Data Science jobs](http://hookedondata.org/Advice-for-Applying-to-Data-Science-Jobs/) among *many* helpful blopost
* **[Mona Chalabi](https://monachalabi.com/)**, for having a project galery on her website (and for her stunning art & data visualizations)
* **[David Robinson](http://varianceexplained.org/)**, for his website, which we used as an example 
* **[Nathan Yau](https://flowingdata.com/about-nathan/)**, for [Flowing Data](https://flowingdata.com), which we used as an example
* **[Kyle Scot Shank](https://twitter.com/KyleScotShank)**, for helping us out and providing an example of a data science interview take-home 
* **[Mikhail Popov](https://people.wikimedia.org/~bearloga/)**, from the Wikimedia Foundation for contributing  [Data Analysis Task](https://github.com/wikimedia-research/Discovery-Hiring-Analyst-2016) publicly, as an example of a task one may have to complete during an interivew

