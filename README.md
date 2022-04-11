# Finding_Donors_for_CharityML. Project Overview:
First project for [Introduction to ML with TensorFlow Nanodegree Program at Udacity](https://www.udacity.com/course/intro-to-machine-learning-with-tensorflow-nanodegree--nd230)

Optimized several different supervised learners to predict highest donation yield (3.7x fscore (0.75 vs 0.2 naive predictor) +15% accuracy (0.869 vs 0.752 naive predictor). 
- **Business Understanding**
- **Data Understanding**: Explored data collected from the 1994 US Census with 45222 observations and 13 variables + target. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).
- **Data Preparation**: Normalized numerical features, transformed skewed continuous features plus one-hot encoded categorical variables.
- **Data Modeling**: Compared and Optimized different ensemble methods using GridCV.
- **Results Evaluation**: Discussed effects of feature selection.


## Code and Resources Used
- Python Version: 3.8.5
- Packages: pandas, numpy, sklearn, matplotlib, seaborn


## Repo Walk-Through
- [visuals.py:](https://github.com/montsebenito/Finding_Donors_for_CharityML/blob/main/visuals.py) A few auxiliary plot functions.
- [finding_donors.ipynb:](https://github.com/montsebenito/Finding_Donors_for_CharityML/blob/main/finding_donors.ipynb) Main and only notebook.

