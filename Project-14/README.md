# Introduction
Junky Union Film, a new community for classic film enthusiasts, is developing a system to filter and categorize movie reviews. The main mission is to train a model to automatically detect negative reviews. You will use the IMBD movie review dataset with polarity labeling to build a model that can classify positive and negative reviews. The model must have an F1 score of at least 0.85.

Project Instructions:
- Load the data.
- Perform data preprocessing if necessary.
- Perform EDA and draw conclusions about class imbalance.
- Perform data preprocessing to build a model.
- Train at least three models on the existing train dataset.
- Test the model on the existing test dataset.
- Write some of your own reviews and classify them with all models.
- Check the differences between the test model results from the two points above. Try to explain the results.
- Show your findings.

# Objectives
The main task in this case is to build and evaluate the model independently.

# Stages
The researcher has data stored in the file */datasets/imdb_reviews.tsv*

This data is obtained from Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011). Here are the descriptions for the selected columns:
- review: review text
- pos: target, '0' for negative and '1' for positive
- ds_part: 'train'/'test' for the train/test part of the dataset

There is no information regarding the quality of the data, so it needs to be checked first before further analysis.

First, the data quality will be evaluated and see if there are any significant things that need to be followed up before the analysis process is carried out.

The project will consist of four steps:
- Data Overview
- Data Pre-processing
- Analysis
- Testing