##[ External data sources](../../wiki/External-data-sources)



LODA-Lecture Notes on Data Analysis
===================================

Lecture notes (in form of slides) and excercises in Python using ipython-notebook for teaching data and media analysis.
It includes introductions to Python, Numpy, Scipy, Scikit-Learn, SimpleCV.
It covers the topics Supervised/Unsupervised Learning, Signal Analysis, Image Analysis, Text and Web-Media Analysis.




[Sites Using React](../../wiki/External-data-sources)



Presentation
============
The lecture notes are optimized for presentation. In order to use them, invoke

  ipython nbconvert --to=slides --post serve path-to-lecture-notes

to start the presentation (a browser window should open automatically).

you can also try to get [livereveal.js](https://github.com/damianavila/live_reveal) up and running in your ipython environment.

Acknowledgment
==============

This work is largely based on a number of great tutorials and resources all over the web, compiled by great people from very different domains. Without their effort and their will to make their hard work open access, i would have not been able to compile this tutorial. The individual contributions are listed in the beginning of every part.


Outline
=======

0. Introduction - Why, What, Who, How
   1. The point of view of [Web Mining (Course Web Mining
      Project@University Passau)](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/0.INTRO/Course-Web%20Mining%20Project%20(5944P).ipynb)

1. Part I: Scientific Programming in Python

   1. [Introduction](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-1-Introduction.ipynb)
   2. [Programming Basics](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-2-Python-Programing-Basics.ipynb)
       1. [Exercise 2.1.: Python Standard Data Structures](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-2-1-Python%20Standard%20Data%20Structures.ipynb)
   3. [Numpy in a Nutshell](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-3-Numpy.ipynb)
	  1. [Exercise 3.1. Data Structures and Operations in Numpy] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I.Data-Science-in-Python/exercises/Exercise%20DSiP-3-1-Numpy.ipynb)
   4. Scipy in a Nutshell
   5. [Mathplotlib in a Nutshell](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-5-Matplotlib.ipynb)
	   1. [Exercise DSiP-5-1-Analysing the Iris Dataset with Mathplotlib] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-5-1-Analysing%20the%20Iris%20Dataset%20with%20Mathplotlib-.ipynb)
   6. [Pandas based Data Analysis](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-6-Pandas.ipynb)
       1. [Exercise 6.1. Analysing New York Open Data with Pandas] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-6-1-Pandas-NYC-Open-Data.ipynb)
2. Part II: Machine Learning and Data Mining \[in Python\]
   1. Machine Learning in a Nutshell with scikit-learn

        1. [Overview and Preprocessing](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-overview-and-preprocessing.ipynb)
        2.[Supervised Learning: Classification and Regression](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-Supervised-Learning.ipynb)
        3.[Unsupervised Learning: Clustering](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-clustering.ipynb)
        4.[Unsupervised Learning: Projections and Manifolds](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-projections-and-manifold-learning.ipynb)

   2. Machine Learning Basics

      1. On the Data
      2. Regression
        - [A simple Example](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/2.ML-DM-Simple-Regression.ipynb)
        - [Least Mean Square Algorithm - a Gradient Descent approach to regression](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-LMS.ipynb)
        - [Regression and Classification - using the analytical solution](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-Regression.ipynb)
      3. Concept Learning
      4. Measuring Performance

   3. Decision Trees
      1.  Decision Tree Basics
      2.  Impurity Functions
      3.  Decision Tree Algorithms
      	  1. [ID 3 in Python](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-DecisionTree.ipynb)
      4.  Decision Tree Pruning


   4. Statistical Learning

      1.   Probability Basics
      2.  Bayes Classification
      3. Graphical Models

   5. Linear Models
   6. Kernel Models
   7. Neuronal Networks

      1.   Perceptron Learning
      2.  Multilayer Perceptrons
      3. Deep Learning

   8. Ensemble Classifiers
   9. Cluster Analysis
      1. [Clustering with scikit-learn](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Clustering-with-scikit-learn.ipynb)
   10. Dimensiontality Reduction and Manifold Learning
      1. [Dimensionality Reduction and Manifold Learning with scikit-learn](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Projection-and-Manifold-Learning-with-scikit-learn.ipynb)
   11. Association Rules
   12. Reinforcement Learning
   13. Deep Learning
      1. [Single Layered Autoencoder](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Stacked-Denoising-Autoencoders.ipynb)

3. Part III: Natural Language Processing \[in Python\]
   1. [An Introduction to NLTK](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/III.NLP/III.NLP-with-NLTK-Short-Intro.ipynb)
       1. [NLTK Exercise](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/III.NLP/exercise/III.NLTK-Intro-Exercise.ipynb)

4. Part IV: Visual Analytics
   1. [Information Visualisation with JavaScript and D3JS](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/IV.Visual-Analytics/IV.VA-InformationVisualisation-with-JavaScript-and-3DJs.ipynb)

5. Part V. Web Mining Applications
    1. [Crawling and Analysing Twitter](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/V.WMA-Crawling-Twitter.ipynb)
	     1. [Exercise: Crawling and Analysing Twitter](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/exercises/Exercises%20Crawling%20Twitter%20with%20Python.ipynb)
		 2. [Project: Shitstorm Detection](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/projects/twitter/V.WMA-Project-Shitstorm-Detection-on-Twitter.ipynb)
		 2. [Project: Topic Detection](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/projects/twitter/V.WMA-Project-Topic-Detection.ipynb)
		 2. [Project: Web Crawling - Genre Classification](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/projects/web-crawling/V.WMA-Project-Web-Page-Genre-Classification.ipynb)


Helpful Links
-

* [Python 101 Cheatsheet](http://nbviewer.ipython.org/urls/bitbucket.org/hrojas/learn-pandas/raw/master/lessons/Python_101.ipynb)


License
=======
<mxfile userAgent="Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87 Safari/537.36" version="6.6.2" editor="www.draw.io" type="device"><diagram name="Page-1">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</diagram></mxfile>
This work is licesend under a Creative-Commons 3.0 license.
