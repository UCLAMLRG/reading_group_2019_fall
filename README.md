# UCLA Astronomy Machine Learning Reading group - Fall 2019

## Goals
Machine learning is a topic that has risen in prominence recently as we get more and more data. We are seeing techniques from machine learning used more widely in astronomy. The goal of this reading group is to become more familiar with topics in machine learning and its connections to statistical tools that are in use in Astronomy. The plan is to go through a couple of textbooks on machine learning and discuss the basic underlying principles and methods. It would be in the style of a reading group where everyone would read the same topic, but a presenter would rotate each meeting and present a topic with associated code implementing the algorithm.

## Readings
- Fundamentals of Machine Learning for Predictive Data Analytics - Kelleher, J.; Namee, B.; D'Arcy, A.
- Deep Learning by Goodfellow, I.; Bengio, Y.;  Courville, A.
  - website: http://www.deeplearningbook.org/
- Python Data Science Handbook by VanderPlas, J.
  - website: https://github.com/jakevdp/PythonDataScienceHandbook
- Hands-On Machine Learning with Scikit-Learn and TensorFlow
  - Safari Books Online: http://proquest.safaribooksonline.com/book/programming/9781491962282
  - github page: https://github.com/ageron/handson-ml
- Machine Learning: A Probabilistic Prespective - Kevin P. Murphy
- Data Analysis: A Bayesian Tutorial - Sivia, D. & Skilling, J. - Not part of regular reading, but this is a useful reference for Bayesian statistics

## Quick-Getting started with SciServer Compute
SciServer.org is a computational cloud environment that Johns Hopkins University (IDIES group) has generously allowed us to use for our projects. Jupyter notebooks/terminal are the interfaces to access datasets such as SDSS. Here's how to clone this github repo into your SciServer account:
1. Create an account at sciserver.org and go to Compute
2. Create a new container (Docker container), choose the type to be Python, and a container Jupyter notebook interface will be created.
3. On the right hand side, go to New-> terminal and a black terminal interface will appear.
4. In this order in the terminal, type each of these at a time (separated by a comma) and hit enter:
5. ls, cd home, ls, cd idies, cd workspace, cd persistent, ls, git clone url-of-git-repository-here
6. the respository will now be in your folder.

-- SciServer cosmology and astronomy Jupyter Notebook code samples https://github.com/sciserver/Notebooks

Basic computer setup if using your own computer: https://github.com/UCLAMLRG/Basics


## Schedule
Meetings will take place on Fridays at 1-2 pm in **PAB-3-703**. Room changes will be sent via email.

**Organizer**: Tuan Do ([@followthesheep](https://github.com/followthesheep))

| Date | Topic | Readings | Presenter |
| --- | --- | --- | --- |
|2019-10-04 | Introductions  |  | T. Do|
|2019-10-11 | Intro to ML & Probability-Based Learning | Kelleher Ch 1 & 6  | T. Do|