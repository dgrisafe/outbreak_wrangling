# outbreak_wrangling

Introduction to basic data wrangling in R using example data on outbreaks


## Dataset

We will be using the [Outbreaks](https://urldefense.com/v3/__https://cran.r-project.org/web/packages/outbreaks/outbreaks.pdf__;!!LIr3w8kk_Xxm!upqova8xo2BulfSiLrpFgR8tg2JMwO2bJCJbXafwaO7OZES2_d4WFSHGddRQ039RDXxOuPPErqB0ktPe6cx_$) package as example data to address the following questions.


## Book

I will be referencing readings and explinations from the wonderful book [R for Data Science (R4DS)](https://r4ds.had.co.nz/index.html). This book is freely available online. I will link to sections when trying to answer specific questions.


## Asking the Internet

A large part of learning data science is searching the internet for specific questions that others have already asked before. Many times I will be stumped and have to ask my question to a search engine. They almost always have the answer on [Stack Overflow](https://stackoverflow.com/) or some other forum. Often writing out my question or simply [speaking to an imaginary rubber duck on my desk](https://en.wikipedia.org/wiki/Rubber_duck_debugging) helps me articulate my question. Sometimes I find I already knew the answer once I am able to coherently describe the problem.


## Growing in Data Science

There are many ways to become better at R and data science in general. The best way is to do a large number of projects, but many of us don't have the time to do that. Other approaches might be learning specific skills online.

[UCLA Statistical Methods and Data Analytics](https://stats.oarc.ucla.edu/) has excellent statistical analyst resources, many of which are publicly available. They have a page dedicated to [learning R](https://stats.oarc.ucla.edu/r/). Note, they also have excellent resources for learning other statistical softwares: SAS, Stata, SPSS, etc.

[Coursera](https://www.coursera.org/search?query=R programming) has many classes in R programming. These can be purchased, which provides a certificate. But you can also audit the courses for free if you just want to develop your skills and do not care about getting a virtual certificate for your resume. 

[edX](https://www.edx.org/search?q=r+programming) website also has courses, similar to Coursera. If you're interested in computer programming in general, Harvard's [Intro to Computer Science](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x) is a great place to start. edX courses can also be audited for free.

[Data Camp](https://www.datacamp.com/learn/r) has many online courses that are "snackable" and can be done once per day to improve analyst skills. Imagine this as DuoLingo, but for R. This does cost money however.


## Questions
 
1. I have a data set that has the date format as: 11/4/2021  7:00:00 AM. I’d like to get it to just month and year: MM/YY like this. Answer: [1. Lubridate for Dates](https://github.com/dgrisafe/outbreak_wrangling/blob/main/1.-Lubridate-for-Dates.md)
2. Getting the date in the right format (See "DOB" variable)
3. Getting time in the right format (see "date_vaccinated")
4. How to change individual answers to get them in alignment with each other (see "state" variable)
5. How to create a new variable that lumps other variables together (lump "state" variable into regions)
6. How to change variable names to something more user friendly (See "Last Name")
7. Considerations when dealing with "Other" -- see "role" variable
8. How to deal with dashes and slashes in the answer (see "race" variable)
9. How to deal with multiple responses to a question - switching from vertical to horizontal (see "activities" with a comma, * "mode" with a semi colon, "symptoms" with a comma)
10. Horizontal to vertical (combining breakfast and lunch foods into one variable for examples)
11. How to deal with N/A (see "vaccinated" variable)
12. How to deal with missing values (see "occupation", "date_exposure" among others)
