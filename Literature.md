---
title: Literature Review
nav_include: 2
---

## Contents
{:.no_toc}
*  
{: toc}

## Li's Book Recommender System
Li explains how she used a kNN and a Matrix Factorization model to find similarities among book readers in order to predict what a reader would review a new book. This is obviously very similar in structure to our project, as we also were looking at user, or restaurant attendee, in order to predict what he or she would rate a restaurant.
>Li, Susan. "How Did We Build Book Recommender Systems in An Hour Part 2 — k Nearest Neighbors and Matrix Factorization." Towards Data Science, Medium, Sept. 2017, https://towardsdatascience.com/how-did-we-build-book-recommender-systems-in-an-hour-part-2-k-nearest-neighbors-and-matrix-c04b3c2ef55c.

## Yeung's Intro to Matrix Factorization
Yeung's blog post gave us an introduction to the theory behind matrix factorization as well as the methodology to implementing such a model in Python. Yeung explains very clearly how matrix factorization can be used to find latent factors underlying the interactions between users and and items. It is essentially allowing us to find what is hidden underneath the data that we could not otherwise quantify or use words to explain.  
>Au Yeung, Anthony. "Matrix Factorization: A Simple Tutorial and Implementation in Python." Quuxlabs, Sept. 2010, http://www.quuxlabs.com/blog/2010/09/matrix-factorization-a-simple-tutorial-and-implementation-in-python/#source-code.

## Rosenthal's Matrix Factorization for Movie Recommendations
Rosenthal shows how to use Matrix Factorization to predict movie ratings. This is where we learned about both the alternating least squares method and the stochastic gradient descent method. Rosenthal explains both the math behind the method and how to further implement the math in code. We ended up adopting his gradient descent method in order to train our matrix factorization model.
>Rosenthal, Ethan. "Explicit Matrix Factorization: ALS, SGD, and All That Jazz". Insight Data Science, Medium, Mar. 2016, https://blog.insightdatascience.com/explicit-matrix-factorization-als-sgd-and-all-that-jazz-b00e4d9b21ea.
