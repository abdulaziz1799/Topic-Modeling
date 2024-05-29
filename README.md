# miniproject3_group-6

### Members: 

#### Manish Rawat (UHID: 2084696)
#### Temidara Agbesnawa (UHID: 1456965)
#### Abdul Aziz Mohammed (UHID: 2215231 )


# Miniproject 3: Topic Models

**Overview**

Your task is to help a journalist with a study of how terrorist organizations are portrayed in traditional media outlets. The analysis should be done using topic modeling.

**Instructions**

This assignment uses a data that had been downloaded from a large Global News database called Factiva. The data has been collected in 2017 and contains articles from Wall Street Journal and the New York Times. A folder with the data will be provided to you in BB. For your submission you are required to do the following:

1. Preprocessing and exploratory data analysis

* Find a way to build a corpus (e.g. load the data as large character, split up the input data into individual articles and build a corpus object containing all splitted articles)

* clean up the corpus, make sure you separate meta-data from the actual articles

* extract features

* create summaries on the features as exploration

* create some plots for exploration

You will need to preprocess the documents having in mind that they represent newspaper articles. One of the things you will need to do is tokenize the text. And this will probably be a trial and error task. For instance, you will need to separate punctuation marks from words. There may also be special headers, tags, dates, or other nuances that need to be handled properly. We will be looking into how clean your post-processed data is as part of the grading for this assignment.

2. Topic modeling

* create a topic model using your cleaned corpus (you may have to go back into preprocessing steps to make modifications)

* re-run the topic modeling multiple times with different parameters and store summaries into output files

* discuss the different results in the context described in the overview statement

* support your findings with relevant model outputs and visualizations

It is not expected from you to have full domain knowledge but please treat the analysis as you would support the journalist.

**Deliverables**

You will need to turn in the following:

1. Your code, properly documented (via GitHub classroom assignment).

2. A thorough written up report that explains your thoughts, why you choose a certain way to process and model the data (methods) and explanation and discussion of results in detail. Upload the report into Blackboard. Follow the guidelines to submit the assignment, the template for the report, and the guidelines for the source code (same as for Miniproject 1).

**Using Github Classroom to setup the remote repo for this assignment**

The groups for this assignment have been set up in BB. Please use the My Groups panel to find out which group you belong to. The groups for Miniproject 3 are not the same as the groups for Miniproject 1 or 2. Please check your group based on BB groups before you accept the assignment via GitHub classroom!

We are using Github Classroom to set up the remote repo for this assignment. Accept the link, create or join your group (see details below) and an empty GitHub repository will be created for your team.

You must use the same group name as listed in BB without the space, e.g. Miniproject3_Group 1 would be the team name used when group members of Miniproject3_Group 1 are joining the assignment in GitHub.


**NOTE**

You can write your code in R or Python. There are many tutorials and blog posts out there to discuss how to create topic models in either R or Python (e.g. https://www.r-bloggers.com/training-evaluating-and-interpreting-topic-models/ and https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/).
