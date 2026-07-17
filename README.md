# Machine Learning on CT-Scans of Breast Cancer

#### Description:
### Introduction
This Project is about a small Machine Learning (ML) model that uses a dataset from Pythons sklearn library to predict wether a given sample of features of a CT-Scan of Breast Cancer is classified as beningn or malignant. \
I used several well known Python libraries such as numpy, sklearn, pandas, seaborn, matplotlib. \
Moreover I use a classic Machine Learning classifier called Gaussian Naive Bayes because its easily understandable with a bit of maths and basic knowledge of statistics and really just Bayes Theorem. \
Also it is pretty easy translated into code and I wanted to see how I can do it. 

### Project Overview
#### Getting a look
First we load the data and get a good look on it, we use sklearns dataset of breast cancer CT-scans with various features ("mean radius, perimeter, area" etc) and we look at those as well as the labels (benign and malignant) and get a good overview on what we're working with
#### Prep
Next step is preprocessing the data and splitting it into training and testing data, this is pretty standard and we use a 80/20 training/testing split so we can train the model on what it sees in features and classifications and then use new data for actually seeing how well it performs.
#### Implementation
Then we get into the real machine learning and basically just implement gaussian naive bayes (gnb) from scratch by calculating all the means and variances and priors and putting in all together in our predict function (it basically just is bayes theorem with independet variables and gaussian distribution) all of it is explained in the commented code. 
#### Evaluation
At the end, we evaluate by seeing the predicted labels vs the actual labels and using a percentage outcome as our accuray, it should be above 90%. 
#### Visualization
Because it can help to visualize data and results, we use some nice libraries like matplotlib to visaulize our data and what happens in the model. Histograms, Boxplots and a Confusion Matrix help us to understand everything. 


### Conclusion
All in all, this is a nice little project showing some basics of Machine Learning with simple statistical approaches on open Datasets. The world of AI in Medicine is a big topic and I can't wait to implement more projects in this ever expanding domain. Machine Learning in Radiology especially is my area of interest. 
This project could further be improved by larger datasets, cross-validation and some more parameters, maybe some other classifiers besides GNB. \
But as this is a Final Project for an Introduction to Computer Science by Harvard University Course (CS50), I will leave it at this and work on other projects in my freetime. 
