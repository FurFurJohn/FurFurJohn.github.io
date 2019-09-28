---
layout: post
title: Ordinary Least Squares
---

Today, in this blog post, I will talk about a very useful regression method: Ordinary Least Squares. It is frequently used in economics, statistics, and data science. It is simple to use, but it is also the foundation of some of the more advanced regression methods. So you may ask: what is ordinary least squares? What is a regression? And why am I learning this? What am I gonna use it for? Just bear with me, and I will provide examples of why regressions are very useful in today’s world. And keep in mind, because this blog is just an elementary introduction for ordinary least squares, so I will not dive into the difficult math equations to prove its assumptions and merits. Nor will I go over specific codes to calculate it. It is beyond the scope of this blog.
   
## What is regression analysis?
   
OK. First, what is regression analysis? What is it for?      

Wikipedia gives a very technical definition:      

"*regression analysis is a set of statistical processes for estimating the relationships among variables. It includes many techniques for modeling and analyzing several variables, when the focus is on the relationship between a dependent variable and one or more independent variables (or 'predictors')*"<sub>1</sub>.
   
The focus for regression analysis is "relationships among variables". So what kind of relationships are we looking for here? Let’s see an example. We often see in crime/detective movies, when the detectives see the footprints of a suspect, they can instantly tell roughly how tall the suspect is. How did they do that? Is that some kind of magic? Of course not! They know that because there is a relationship between a person’s height and foot size. According to a study by the University of Rhode Island Department of Electrical, Computer and Biomedical Engineering, the normal height-to-foot ratio is about 6.6:1<sub>2</sub>.
