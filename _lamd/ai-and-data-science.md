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
ipynb: False
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

\include{_ml/includes/what-are-large-language-models.md}


\include{_psychology/includes/selective-attention-bias.md}
\define{bmiStepsAnalysis}
\include{_data-science/includes/data-inattention-bias.md}
\notes{In today's lecture we've drilled down further on a difficult aspect of data science. By focusing too much on the data and the technical challenges we face, we can forget the context. But to do data science well, we must not forget the context of the data. We need to pay attention to domain experts and introduce their understanding to our analysis. Above all we must not forget that data is almost always (in the end) about people.}

\slides{* By focussing on the technical side of data science
* We tend to forget about the context of the data.
* Don't forget that data is almost always about people.}


<!--


\newslide{Background: Big Data}
\slides{
* Data is Pervasive phenomenon that affects all aspects of our activities

* Data diffusiveness is both a challenge and an opportunity
}
include{_data-science/includes/gartner-hype-cycle-ai-bd-dm-dl-ml.md}

include{_ml/includes/statistics-to-deep-learning.md}

include{_ml/includes/what-are-large-language-models.md}

\subsection{Conclusions}



include{_data-science/includes/societal-effects.md}
include{_data-science/includes/three-data-science-challenges.md}
\notes{You can also check this \addblog{Three Data Science Challenges}{2016/07/01/data-science-challenges}}

\subsection{Paradoxes of Data Society}

include{_ai/includes/bear-of-little-brain.md}
include{_data-science/includes/big-data-paradox.md}
include{_data-science/includes/breadth-or-depth.md}
include{_data-science/includes/big-model-paradox.md}
include{_policy/includes/diane-coyle-fitzwilliam-lecture.md}
include{_policy/includes/data-as-a-convener.md}


include{_data-science/includes/value-of-data.md}
include{_data-science/includes/privacy-intro.md}
include{_data-science/includes/hate-speech-or-political-dissent.md}
include{_data-science/includes/marketing-and-free-will.md}
include{_data-science/includes/digital-revolution-and-inequality.md}
include{_data-science/includes/privacy-amelioration.md}
\section{Delve}

include{_delve/includes/delve-report-list.md}

\notes{There is lots of hope for the role data science and AI could play, but we’re still a way off from being AI-ready. Further attention is needed on some of the foundational issues around data use – access, skills, culture – before we can begin to talk in earnest about deploying AI. [link here to data readiness]}

include{_delve/includes/delve-data-report.md}
include{_delve/includes/data-report-recommendations.md}

\notes{Delivering a rapid response requires the ability to quickly convene teams from across disciplines (and often institutions) around a key question. To facilitate this, we also used ideas from \addblog{open data science}{2014/07/01/open-data-science} to facilitate communication and understanding.}

include{_governance/includes/data-trusts.md}
include{_data-science/includes/data-science-africa.md}

\notes{We separated the challenges we face into three groups: (1) paradoxes of the odern data society, (2) quantifying the value of data and (3) privacy loss of control and marginalization. We've noted the origins of the paradoxes, speculating that it is based in a form of data (or modelling) inattention bias demonstrated through the Gorilla. We've drawn parallels between challenges of rewarding the addition of value and the credit assignment problem in reinforecement learning and we've looked at approaches to introduce the voice of marginalized societies and people into the conversation.}

\subsection{Conclusions}

\slides{* Bandwidth constraints of humans
* Big Data Paradox
* Big Model Paradox
* Data as a Convener
* Decomposition of Complex Models
}

\notes{The particular circumstances of the Covid-19 pandemic have highlighted the challenges of integrating scientific ideas to answer policy questions. In this talk, we've given a formal introduction to the problem, the difficulty of communicating between individuals (particularly from different domains) and reviewed the ideas and solutions we used in the Delve initiative.}

\notes{Recommendations from the DELVE Data report suggest that more effort needs to be placed into working in this manner in normal circumstances, so that when an emergency occurs we are better prepared to deal with the questions we face. Other approaches prosed include data trusts.}

\notes{When we combine these difficult challenges with complex models, we need to put more effort into decomposing our models so that they may be calibrated and re-integrated at appropriate fidelities.}

-->
\reading

\references

\thanks
