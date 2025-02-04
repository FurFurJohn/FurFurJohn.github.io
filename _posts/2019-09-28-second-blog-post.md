---
layout: post
title: Ordinary Least Squares
---

Today, in this blog post, I will talk about a very useful regression method: Ordinary Least Squares. It is frequently used in economics, statistics, and data science. It is simple to use, but it is also the foundation of some of the more advanced regression methods. So you may ask: what is ordinary least squares? What is a regression? And why am I learning this? What am I gonna use it for? Just bear with me, and I will provide examples of why regressions are very useful in today’s world. And keep in mind, because this blog is just an elementary introduction for ordinary least squares, so I will not dive into the difficult math equations to prove its assumptions and merits. Nor will I go over specific codes to calculate it. It is beyond the scope of this blog.
   
## What is regression analysis?
   
OK. First, what is regression analysis? What is it for?      

Wikipedia gives a very technical definition:      

"*regression analysis is a set of statistical processes for estimating the relationships among variables. It includes many techniques for modeling and analyzing several variables, when the focus is on the relationship between a dependent variable and one or more independent variables (or 'predictors')*".<sup>(See source 1)</sup>
   
The focus for regression analysis is "relationships among variables". So what kind of relationships are we looking for here? Let’s see an example. We often see in crime/detective movies, when the detectives see the footprints of a suspect, they can instantly tell roughly how tall the suspect is. How did they do that? Is that some kind of magic? Of course not! They know that because there is a relationship between a person’s height and foot size. According to a study by the University of Rhode Island Department of Electrical, Computer and Biomedical Engineering, the normal height-to-foot ratio is about 6.6:1.(See source 2)   
    
In layman's terms, regression analysis is a method to study the relationship between variables. It can be the relationship between a person’s height and foot size (like the example above), or the relationship between the amount of sun light and corn production, or the relationship between the amount of cheese your mom put in your mac & cheese and how delicious it is. Just like people are connected with different relationships, variables can also be connected with certain relationships. Regression analysis helps us discover these relationships. It identifies one variable as a dependent variable, and other one or more variables as independent variables. Then it studies how the change of independent variables will affect the dependent variable. The relationships between dependent variables and independent variables help us better understand the world. Ordinary least squares (or OLS in short) is a way to discover this kind of relationship.    
    
## What is OLS?

Let’s go back to Wikipedia, and find the technical definition:  

“*In statistics, ordinary least squares (OLS) is a type of linear least squares method for estimating the unknown parameters in a linear regression model. OLS chooses the parameters of a linear function of a set of explanatory variables by the principle of least squares: minimizing the sum of the squares of the differences between the observed dependent variable (values of the variable being predicted) in the given dataset and those predicted by the linear function*.(See source 3)   

Let's understand this definition bit by bit. There are a few key words of OLS we should notice.       
     
### 1. Linear .   
     
For OLS to work properly, the relationship between a dependent variable and independent variables must be linear. Below is an example of a linear relationship. (See source 4) 

![linear](https://user-images.githubusercontent.com/44696601/65821098-fa9f1200-e1e5-11e9-8353-5dd2db2d6753.jpg)
  
[Source](http://www.360doc.com/content/18/0706/10/15930282_768242401.shtml)  
     
If the relationship is quadratic or in other forms, then we cannot use OLS. It would do a bad job estimating the relationship. Below is an example of a quadratic relationship. (See source 5) 
      
![quadratics](https://user-images.githubusercontent.com/44696601/65821113-2de1a100-e1e6-11e9-93ab-d450b3522077.gif)
     
[Source](http://mathcentral.uregina.ca/QQ/database/QQ.09.06/mike1.html)


#### Note:
Because Github does not support LaTex, and the following paragraphs contain a lot of math simbols and math fomulas, please click the link below and see the rest of this blog in a rendered Jupyter Notebook:

[Ordinary Least Squares](https://github.com/FurFurJohn/FurFurJohn.github.io/blob/master/_posts/Ordinary%20Least%20Squares.ipynb)




#### Sources:

1. Regression analysis. Wikipedia. (n.d.). Retrieved from https://en.wikipedia.org/wiki/Regression_analysis  
2. Tremblay, S. Height-to-Foot-Size Ratio. (n.d.). Retrived from https://www.livestrong.com/article/491821-height-to-foot-size-ratio/
3. Ordinary least squares. Wikipedia. (n.d.). Retrieved from https://en.wikipedia.org/wiki/Ordinary_least_squares
4. Fengjiutian88. How to understand OLS? (2018). Retrieved from http://www.360doc.com/content/18/0706/10/15930282_768242401.shtml 
5. Penny. Graphing quadratic equations. (n.d.). Retrieved from http://mathcentral.uregina.ca/QQ/database/QQ.09.06/mike1.html






