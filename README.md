# twitter-sentiment-analysis

this repo includes my effort (alighazal) with my friend Omer Moussa (omermosa) on implementing twitter sentiment analysis. 

we combined two datasets (a total of 2.6 Million tweets): 

    1. TwitterSentiment1.6M from Kaggle: https://www.kaggle.com/kazanova/sentiment140
    2. 1.04M tweets Dataset: https://github.com/vineetdhanawat/twitter-sentiment-analysis

We went through the regular ML pipline:

    1. Collecting the data and preprocessing it using regular NLP techniques (removing stop words, building BOW, etc). The details can be found in phase 2 notebook.
    2. Trying different models to compare their performance on the dataset in order to choose the best one for tweaking and final production. 
    The details can be found in phase 3 notebook and its report. We also tried document word embedding representations (Doc2Vec) on different models from SKLearn.
     The dataset size of the doc2vec was about 4 GB.
    3. We implemented the best performing model (Logistic Regression) from scratch and tweaked it to increase the accuracy, percision, and recall.  
    The details can be found in phase 4 and its report.
    4. We finalized the model and deployed it using django to build a local server and user interface to accept a tweet as input, predicts its sentiment and displayed it.  
    This was phase 5 of ther project.
    
The summary of the work can be found in the research paper.

you can read all the details of the process from the reports in this google drive: 
    https://drive.google.com/drive/folders/1gCPUUukrpl6zu4QzFoHcvheF1mpIcj-K?usp=sharing
    
for any inquiry, email me: alighazal@aucegypt.edu and omermosa@aucegypt.edu

