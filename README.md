# ACM Research Coding Challenge (Spring 2022)

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#no-collaboration-policy)No Collaboration Policy

**You may not collaborate with anyone on this challenge.**  You  _are_  allowed to use Internet documentation. If you  _do_  use existing code (either from Github, Stack Overflow, or other sources),  **please cite your sources in the README**.

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#submission-procedure)Submission Procedure

Please follow the below instructions on how to submit your answers.

1.  Create a  **public**  fork of this repo and name it  `ACM-Research-Coding-Challenge-S22`. To fork this repo, click the button on the top right and click the "Fork" button.

2.  Clone the fork of the repo to your computer using  `git clone [the URL of your clone]`. You may need to install Git for this (Google it).

3.  Complete the Challenge based on the instructions below.

4.  Submit your solution by filling out this [form](https://acmutd.typeform.com/to/uTpjeA8G).

## Assessment Criteria 

Submissions will be evaluated holistically and based on a combination of effort, validity of approach, analysis, adherence to the prompt, use of outside resources (encouraged), promptness of your submission, and other factors. Your approach and explanation (detailed below) is the most weighted criteria, and partial solutions are accepted. 

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#question-one)Question One

[Binary classification](https://en.wikipedia.org/wiki/Binary_classification) is a type of classification task that labels elements of a set (i.e. dataset) into two different groups. An example of this type of classification would be identifying if people had a specific disease or not based on certain health characteristics. The dataset found in `mushrooms.csv` holds data (22 different characteristics, specifically) about different types of mushrooms, including a mushroom's cap shape, cap surface texture, cap color, bruising, odor, and more. Remember to split the data into test and training sets (you can choose your own percent split). Information about the meaning of the letters under each column can be found within the file `attributelegend.txt`.

**With the file `mushrooms.csv`, use an algorithm of your choice to classify whether a mushroom is poisonous or edible.**

**You may use any programming language you feel most comfortable. We recommend Python because it is the easiest to implement. You're allowed to use any library or API you want to implement this, just document which ones you used in this README file.** Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file. However, we highly recommend giving the challenge a try, you just might learn something new!

Attempt 1 (Could not get the model to output data due to not having certain libraries installed so I decided to give an overview of what I would do)

This process begins by identifying the true and false values. In this case, we would have to identify which state is the normal state, and assigned value 0, and which state is the abnormal state, and assigned the value 1. In this problem, we can assign the edible mushrooms to the normal state with a value or 0 and we can assign poisonous mushrooms to the abnormal state with a value of 1. This type of classification uses the Bernoulli distribution, a distribution in which the event will have have a binary outcome, in this case, being poisonous or edible. The model will assign values of 0 or 1 to each mushroom depending on a variety of different variables which include, cap shape, cap color, gill color, etc. The dataset in this project assigns 23 unique features to distinguish each mushroom, therefore we must assign a predictive model to identify the edible and poisonous mushrooms. The libraries that I would use are as follows:

NumPy
Pandas
Seaborn
Matplotlib
Graphviz
Scikit-learn

The model will learn to use variables like cap shape, cap color and gill color to distinguish between edible and poisonous mushrooms




