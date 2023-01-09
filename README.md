# Notebook #4: Scikit Learn with Spotify Data

For this notebook, you are going to demonstrate how to use the scikit-learn library (https://scikit-learn.org) to perform machine learning experiments. 
## The Data :bar_chart: 
You will use a new dataset, the [Dataset of Spotify Songs](https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify/versions/1?resource=download) from Kaggle (available in the "Datasets" section of the blackboard website). 

The goal for this machine learning exercise is to use the scikit-learn library implementation of **k-Nearest-Neighbors**, **Decision Trees**, and **Random Forests** to make predictions on the "Danceability" of Spotify songs. 

## The Exercises:
**Part 1: [3 points]** You must run at least 6 variations of the algorithms and display their results using an __appropriate regression metric__ (again, use the scikit-learn modules). I will be looking for the following to be included in your comparison:

* weighted k-Nearest-Neighbor with a small value of k (the same one you used for the unweighted version)
* weighted k-Nearest-Neighbor with a large value of k (the same one you used for the unweighted version)
* a decision tree with default parameter values
* a decision tree, setting some kind of parameter that results in a smaller tree 
* a Random Forest, with a small number of trees
* a Random Forest, with a large number of trees

**Part 2: [1 point]** Normalize the data and run a weighted k-Nearest Neighbors algorithm on it (from sklearn,  not the one we wrote from scratch). You can choose the k value. To Normalize, use the StandardScalar from sklearn.

**Part 3: [1 point]** Use a Markup cell to answer the following questions:
* What algorithm performed better? w-kNN, Decision Trees, or Random Forests? Why do you think this was the case?
* What effect did normalizing the data have on your results? Explain. 

Lastly, as always, use a Markup cell to put your name at the top of the file. Rename your file Notebook4_lastname.ipynb and submit it to this submission form. You do not need to submit a copy of the data.

## Rubric :ballot_box_with_check:

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 1.1: wknn           |        |    |
| 1.2: Decision Tree         |        |    | 
| 1.3: Random Forest |        |    |
| 2: Normalize       |        |    | 
| 3: Conclusions     |        |    |
| <b>Total           |    /5 | </b>   |
