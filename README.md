# Recommender-Systems-Collaborative-Filter

In this project, I will be working towards creating a recommender system, suggesting which unit the student should tackle next. The recommender system is based on item-based and user-based collaborative filtering methods and an algorithm of cosine similarity.

## Goals for this Project

* Discuss different uses for recommender systems in learning applications
* Discuss the theory behind item-based and user-based collaborative filtering methods and the role of cosine similarity 
* Build a basic recommender system using an item-based collaborative filter and cosine similarity in R

## Background
As the amount of available educational data keeps growing, organizing and making use of the data has become increasingly insightful. [Duval (2011)] saw recommender systems as a way to deal with the "paradox of choice", the dilemma of determining what information to feed back to learners about their learning. An idealized recommender system provides a limited number of suggested metrics or new content based on the learner's past behavior and the patterns of all other learners in the sample. Recommender systems may provide behavioral cues, new content, insights or suggested behavioral changes based on a comparison of the learner to all other learners in the system.

Collaborative filters are a class of algorithm used to suggest content to a given user (filtering) by leveraging information about many users (collaboration). There are many flavors of collaborative filter and they are very commonly used in scenarios where there is incomplete information about a user's preferences such as Netflix suggestions or product recommendations on Amazon.

## Data
Data used in this project were collected from 44 students in the class, who gave their "Difficulty" and "Interest" ratings on 2 randomly selected topics out of the total 6 topics in a course. The ratings were on a Likert-scale from 1 to 5, with 1 representing "I think this topic sounds very easy"/"I have very little interest in this topic" and 5 representing "I think this topic sounds very difficult"/"I am very interested in this topic."

## Packages Required
```
install.packages("lsa") 
install.packages("tidyr")
install.packages("dplyr")
```

### References

[Drachsler, H., Verbert, K., Santos, O. C., & Manouselis, N. (2015). Panorama of recommender systems to support learning. In *Recommender Systems Handbook* (pp. 421-451). Springer: New York, NY.](https://lirias.kuleuven.be/bitstream/123456789/476545/1/TEL_RecSys.pdf)

[Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In *The Adaptive Web* (pp. 291-324). Springer: Berlin, Heidelberg.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)


[Leskovec, J., Rajaraman, A. & Ullman, J. (2017). Recommender systems: Collaborative filtering. In *Mining of Massive Data Sets*. Coursera: Stanford, CA](https://www.youtube.com/watch?v=h9gpufJFF-0)

Brinton, C. & Chiang, M. (2013). Cosine similarity. In *Networks Illustrated: Principals without Calculus*  
[Part A](https://www.youtube.com/watch?v=C-JauEnlSlM)  
[Part B](https://www.youtube.com/watch?v=-gz1qdsM0tk)  


* [Fazeli, S., Drachsler, H. & Sloep, P. (2017). Applying recommender systems for learning analytics: A tutorial. In *The Handbook of Learning Analytics* (pp. 235-240). SOLAR: Vancouver, BC](https://solaresearch.org/hla-17/hla17-chapter20/) 

* [Principal Compononent Analysis - Visually Explained](http://setosa.io/ev/principal-component-analysis/)