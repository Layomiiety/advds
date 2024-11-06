---
title: "Practical 2"
practical: 2
featured_image: assets/images/practical-two.png
abstract: >
  In this lab session we look at working with geospatial data, in conjunction with the house prices dataset you created in the previous practicals.
layout: practical
venue: Intel Lab, William Gates Building
author:
- family: Sendyka
  given: Radzim
  institute: University of Cambridge
  url: https://www.cst.cam.ac.uk/people/rs2071
- family: Cabrera
  given: Christian  
  institute: University of Cambridge
  url: https://www.cst.cam.ac.uk/people/chc79
- family: Ek
  given: Carl Henrik
  institute: University of Cambridge
  url: http://carlhenrik.com
- family: Lawrence
  given: Neil D.
  institute: University of Cambridge
  url: http://inverseprobability.com
time: "15:00"  
postsdir: ../../../mlatcl/advds/_practicals/
date: 2024-11-07
transition: None
ipynb: true
---

\notes{**The check Session for this Practical is 12th November 2024.**}
\notes{Prerequisite: practical 1, and a working database with tables price paid data (i.e., `pp_data`) and postcodes(i.e., `postcode_data`)}

\notes{In this lab session we look at working with geospacial data, in conjunction with the house prices dataset you created in the previous practicals. The goal is to enrich the data from the first practical with geographic data enabling better informed data analysis. Access to the price paid database is needed to complete some of the below exercises. You are asked to write reusable code that will help you in the assessment.}

\include{_datasets/includes/accessing-osm.md} 
\include{_datasets/includes/assessing-osm.md} 
\include{_access/includes/spatial-join.md}

\thanks

\references
