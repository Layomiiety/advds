---
week: 4
session: 2
title: "AI and Data Science"
featured_image: assets/images/the-challenges-of-data-science.png
abstract:  >
  In the first lecture, we laid out the underpinning phenomena that give us the landscape of data science. In this lecture we unpick the challenges that landscape presents us with. The material gives you context for why data science is very different from standard software engineering, and how data science problems need to be approached including the many different aspects that need to be considered. We will look at the challenges of deploying data science solutions in practice. We categorize them into three groups.
layout: lecture
venue: LT2, William Gates Building
author:
- family: Lawrence
  given: Neil D.
  gscholar: r3SJcvoAAAAJ
  institute: University of Cambridge
  twitter: lawrennd
  url: http://inverseprobability.com
youtube: BQKfIJHPiCQ
oldyoutube: 
- code: BQKfIJHPiCQ
  year: 2022
- code: KXnZ4nj-ahA
  year: 2021
time: "10:00"
date: 2024-11-04
transition: None
reveal: true
ipynb: true
---

<!--

* AI and Data Science
  * Machine Learning Definition
  * Prediction Example from DSA
  * Deep Learning
  * LLMs – Probability Conversations
* The Challenges of Data Science I
  * Complexity in Action
  * Selective Attention Bias
  * Data Theatre
  * The Art of Statistics

-->

\section{Introduction}

\notes{Data science is an emerging discipline. That makes it harder to make clean decisions about what any given individual will need to know to become a data scientist. Those of you who are studying now will be those that define the discipline. As we deploy more data driven decision making in the world, the role will be refined. Until we achieve that refinement, your knowledge needs to be broad based.}

\notes{In this lecture we will first continue our theme of how our limitations as humans mean that our analysis of data can be affected, and I will introduce an analogy that should help you understand *how* data science differs significantly from traditional software engineering.}

\include{_ml/includes/technical-edition.md}

\include{_ml/includes/statistics-to-deep-learning.md}

\subsection{What are Large Language Models?}
\include{_ai/includes/conversation-probability.md}
\define{donaldMackayBrain}
\define{humanAnalogueMachinesShort}

\include{_ml/includes/what-are-large-language-models.md}


\notes{But if we can avoid the pitfalls of counterfeit people, this also offers us an opportunity to *psychologically represent* [@Heider:interpersonal58] the machine in a manner where humans can communicate without special training. This in turn offers the opportunity to overcome the challenge of *intellectual debt*.}

\notes{Despite the lack of interpretability of machine learning models, they allow us access to what the machine is doing in a way that bypasses many of the traditional techniques developed in statistics. But understanding this new route for access is a major new challenge.}

\include{_data-science/includes/new-flow-of-information-ham.md}

\include{_psychology/includes/selective-attention-bias.md}
\define{bmiStepsAnalysis}
\include{_data-science/includes/data-inattention-bias.md}
\notes{In today's lecture we've drilled down further on a difficult aspect of data science. By focusing too much on the data and the technical challenges we face, we can forget the context. But to do data science well, we must not forget the context of the data. We need to pay attention to domain experts and introduce their understanding to our analysis. Above all we must not forget that data is almost always (in the end) about people.}

\slides{* By focussing on the technical side of data science
* We tend to forget about the context of the data.
* Don't forget that data is almost always about people.}


\reading

\references

\thanks
