---
title: "Review and Refresher"
practical: 1
featured_image: assets/images/review-and-refresher.png
abstract:  >
  In this review and refresher notebook we mix some review work with some of the concepts we'd like you to develop and understand as you progress through the course. The review work focuses on the use of probability, correlation, pandas and the jupyter notebook. Most of the code you need is provided in the notebook, there are a few exercises to help develop your understanding. 
layout: practical
venue: In your own time
author:
- family: Lawrence
  given: Neil D.
  gscholar: r3SJcvoAAAAJ
  institute: University of Cambridge
  twitter: lawrennd
  url: http://inverseprobability.com
- family: Cabrera
  given: Christian
  institute: University of Cambridge
  url: https://www.cst.cam.ac.uk/people/chc79
- family: Sendyka
  given: Radzim
  institute: University of Cambridge
  url: https://www.cst.cam.ac.uk/people/rs2071
postsdir: ../../../mlatcl/advds/_practicals/
date: 2024-11-01
transition: None
reveal: false
ipynb: true
---

\section{Introduction}

\notes{Welcome to the review and refresh practical. This work is for you to remind yourself about the ways of using the notebook. You will have a chance to ask us questions about the content on 9th of November. Within the material you will find exercises. If you are confident with probability you can likely ignore the reading and exercises which are listed from @Rogers:book11 and @Bishop:book06. There should be *no need* to purchase these books for this course. The suggestions of sections are there just as a reminder.}

\notes{We suggest you run these labs in *Google colab*, there's a link to doing that on the main lab page at the top. We also suggest that the first thing you do is click `View`->`Expand sections` to make all parts of the lab visibile.}

\notes{- This session should prepare you for different parts of the course practicals and final assignment.

- We will use the fynesse library through the course. You will create your own library and will update it as the course progress. The library will also contain your work for the final assignment.}

\notes{We suggest you complete at least Exercises 4-9.}

\include{_advds/includes/advds-notebook-setup.md}

\include{_datasets/includes/nigeria-nmis-data.md}
\include{_ml/includes/nigeria-nmis-data-explore.md}
\include{_ml/includes/probability-intro.md}

\newslide{}

\figure{\includeyoutube{GX8VLYUYScM}{600}{450}}{MLAI Lecture 2 from 2012.}{mlai-lecture-2012}


\addreading{@Rogers:book11}{Section 2.2 (pg 41–53)}
\addreading{@Rogers:book11}{Section 2.4 (pg 55–58)}
\addreading{@Rogers:book11}{Section 2.5.1 (pg 58–60)}
\addreading{@Rogers:book11}{Section 2.5.3 (pg 61–62)}


\addreading{@Bishop:book06}{Probability densities: Section 1.2.1 (Pages 17–19)}
\addreading{@Bishop:book06}{Expectations and Covariances: Section 1.2.2 (Pages 19–20)}

\addreading{@Bishop:book06}{The Gaussian density: Section 1.2.4 (Pages 24–28) (don’t worry about material on bias)}
\addreading{@Bishop:book06}{For material on information theory and KL divergence try Section 1.6 & 1.6.1 (pg 48 onwards)}

\reading 

\addexercise{@Bishop:book06}{Exercise 1.7}
\addexercise{@Bishop:book06}{Exercise 1.8}
\addexercise{@Bishop:book06}{Exercise 1.9}

\exercises


\include{_data-science/includes/correlation-coefficients.md}
\include{_data-science/includes/structure-fynesse-template.md}


\thanks

\reading

\exercises

\references
