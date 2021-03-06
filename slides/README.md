---
title: "Tools for Reproducible Research"
author: "Isaac Jenkins and Shripad Sinari"
date: "October 22, 2014"
output: ioslides_presentation
---

## The Tools

- [R](http://www.r-project.org/) 
  (and [RStudio](http://www.rstudio.com/))
    - Learn R: [Try R](http://tryr.codeschool.com/) and 
      [DataCamp](https://www.datacamp.com/)
- [knitr](http://yihui.name/knitr/) 
  (and [LaTeX](http://www.latex-project.org/), 
  [markdown](http://daringfireball.net/projects/markdown/syntax) 
  and [pandoc](http://johnmacfarlane.net/pandoc/))
    - Learn R Markdown: [Basics](http://rmarkdown.rstudio.com/)
- [git](http://git-scm.com/book/en/Getting-Started-Git-Basics) 
  (and [GitHub](https://github.com/about) or 
  [Bitbucket](https://bitbucket.org/features))
    - Learn git: [tryGit](https://try.github.io/)
    
![alt text](http://www.thegreenhead.com/imgs/xl/giant-swiss-army-knife-xl.jpg)

## The Mentality

- I'm tired of Word's formatting quirks
- I'm tired of copying and pasting results
- I no longer want to email files back and forth
- I want a __record of what I did__
- I want a ___more efficient workflow___

![alt text](http://nmsp6.files.wordpress.com/2014/01/borat-thumbs-up.jpg)

## R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Slide with R Code and Output


```r
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```

## Slide with Plot

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

## Setting Up Git...Caution, FRUSTRATION Awaits

This can be challenging, but these resources should help:

- Mac/Linux: [Set Up Git](https://help.github.com/articles/set-up-git/)
- Windows: [GUI](https://help.github.com/articles/getting-started-with-github-for-windows/)
  or [Command Line](http://guides.beanstalkapp.com/version-control/git-on-windows.html)
  
Note: I have no experience working with git on Windows. I would try using the 
command line help above. It looks pretty good. It uses Beanstalk as the remote 
host, but setup for GitHub should be similar. Just replace Beanstalk with GitHub.

## Demo


```r
if (slide == "Demo") {
  do_demo()
} else {
  continue_presentation()
}
```

## Stop getting stuck...

![movie reel](http://i.giphy.com/jVQTFvl8HbEOI.gif)

## Jump out of the box...

![movie reel](http://i.giphy.com/hkC9qHkrrfdqE.gif)

## and Do Work!

![movie reel](http://i.giphy.com/ue5ZwFCaxy64M.gif)

Thank you...[slides are here](https://github.com/icj/reproducible_talk/tree/master/slides)
