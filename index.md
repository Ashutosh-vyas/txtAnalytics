---
title       :   Text Analytics
subtitle    :   analyzing your text
author      :   Ashutosh
job         :   Senior Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

Text Analytics/mining is gaining importance in data analytics products 
For example  a lot of social data is generated everyday, which can be used in a veriety of ways to predict or generate patterns.

the Application which I shared in the shiny is just a simplw demo of how can do analytics on paragraphs.

it only just calculate the number of words we enter and also calculate ASCII chahracters in the input text.

To perform a good level on analysis it is recommended to have a basic understanding of language on which you are trying to do analysis.

following quiz will give you a brief idea.

---  &checkbox

## Simple Example

What is root  word in the following text :
"a quick brown fox jump right over a lazy dog" ?

1.  _"fox"_
2.  "jump"
3.  "dog"
4.  "brown"

*** .hint
  the root word is the word for which the sentence is written
*** .explanation
  the root word is the word for which the sentence is written

--- 

## R example Creating a simple scatter plot

  
  ```r
  require(ggplot2)
  ```
  
  ```
  ## Warning: package 'ggplot2' was built under R version 3.2.2
  ```
  
  ```r
  qplot(wt, mpg, data = mtcars)
  ```
  
  <img src="assets/fig/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />
---

---

## R in Text mining

    We can use inbuilt r packages to perform text mining
  such as 
  1. tm for creating matrices and performing analytics
  2. openNLP to  perform natual language processing
  3. StanfordCoreNLP to perform dependecy tree building, NLP and perform Sematic analysis
  
---
  
  
  
  
  

