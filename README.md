[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Victor-Palacios/Using_Pipeline/blob/main/smote_and_stroke.ipynb)

----
About Me
----

My name is Victor Palacios. I'm receiving a Master's Degree in Data Science at the University of San Francisco.

----
Project Description
----

This repository is about classifying stroke (an imbalanced class) with high recall. We consider two techniques: SMOTE and adjusting Class Weight.

----
Importance
----

Because SMOTE creates synthetic samples it is computationally slower than simply adjusting Class Weight. Does SMOTE provide enough of an advantage over Class Weight such that the speed reduction is worth the cost for hospitals, businesses, and machine learning practioners?

----
Outcome
----

1. For detecting the minority class (stroke) with extremely high recall, SMOTE (recall 1.00) outperformed Class Weight (recall: 0.69).
1. If balance between precision, recall, and computational speed are required, Class Weight is preferred over SMOTE.
