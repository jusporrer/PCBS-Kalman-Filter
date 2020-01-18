[Kalman-TD Model](https://jusporrer.github.io/PCBS-Kalman-Filter/)
================

This program in Python allows to fit the **Kalman-TD Model** to behavioral data.

The initial code in Matlab is based on the previous work of **Samuel Gershman**, at the Department of Psychology and Center for Brain Science, Harvard University [(See his GitHub here)](https://github.com/sjgershm/KF-learning). This model is introduced in his paper [*A Unifying Probabilistic View of Associative Learning*](https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1004567&type=printable) which describes a framework encompassing Bayesian and Reinforcement Learning theories of associative learning. 

For more information please contact me at <juliana.sporrer.18@ucl.ac.uk>.


### Table of Contents

1. [Kalman-TD Model](#Kalman---TD-Model)
    1. [What is the Kalman-TD Model?](#What-is-the-Kalman---TD-Model-?)
        1. [Associative Learning](#Associative-Learning)
        1. [Unifying Model](#Unifying-Model)  
    1. [Conclusion](#Conclusion)
    1. [PBCS Feedback](#Programming-for-Brain-and-Cognitive-Sciences)



## What is the Kalman-TD Model?

### Associative Learning 

The ability to learn is essential to the survival of animals. Two recent concepts have allowed us to have a better understanding of how this learning is occurring. 
- An agent estimates the strength of associations and tracks its uncertainty using **Bayesian principles** and embodied by the **Kalman Filter**. 
- An agent learns about long-term cumulative future reward using **Reinforcement Learning (RL) principles** and represented by **Temporal Difference, TD**. 

Bayesian and RL theories are derived from different, but not exclusive, assumptions about the target and uncertainty representation of the learning task. The Kalman-filter learns the posterior distribution of expected immediate reward in contrast to the TD that learns a single value of expected future reward.   

<img src="https://github.com/jusporrer/PCBS-Kalman-Filter/blob/master/FIG1.JPG" alt="alt text" width="186.8" height="123.2">

### Unifying Model 

These two theoretical models can be brought together in the form of the **Kalman-TD Model** and be constructed as a point estimator (TD) of expected immediate reward (Kalman). 



 



## Conclusion 

## Programming for Brain and Cognitive Sciences

This code was part of the course PBCS from the Cogmaster at the ENS (Paris, France). 

### Differences between Python and Matlab 

Sam Gersham made available his codes written in Matlab which allowed me to have a better understanding of the mathematics behind the model. Even if Matlab and Python are similar, the transition from one to the other is made difficult by a few major differences. Amongst those, zero-based indexing is easily ajusted for but the lack of true forms of matrices in Python and the data ordering of arrays which is row-major compared to column-major in Matlab requires more adjustements. 

### Previous Experience in Coding 

I had previous experience in coding using JavaScript, HTML and CSS. I also used MATLAB to analyse my data. However, these skills were self-thought, so I never learned how to optimise and write a clean code.

I think that through this course I gained proficiency using Python, which is a language I never programmed in before. This is especially useful as nowadays, more and more Cognitive Neuroscience lab use Python to code their experiments and analyse their data. 

It also encouraged me to use more GitHub to organise my code (especially through literate programming of which I am now a fan), and to allow more reproducible science. It also opened my eyes on the benefits of open source, and I am considering switching to Linux. 

### Feedback

Nonetheless, I still wish that we would have been able to do more language (I know it is difficult to implement MATLAB, but the reality is still that most labs are using it). I also wish that we would have been able to learn more optimisation of our codes rather than the coding of experiment itself. Even though it is great to have a wide variety of levels, I think that it can results in frustration in both those with lower levels and those with strong coding abilities. Two classes with different levels would benefit most of the students. 







