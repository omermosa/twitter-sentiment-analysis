# twitter-sentiment-analysis

this repo includes my effort (alighazal) with my friend Omer Moussa (omermosa) on implementing twitter sentiment analysis. 

we combined two datasets (a total of 2.6 Million tweets): 

    1. TwitterSentiment1.6M from Kaggle: https://www.kaggle.com/kazanova/sentiment140
    2. 1.04M tweets Dataset: https://github.com/vineetdhanawat/twitter-sentiment-analysis

We went through the regular ML pipline:
    - Collecting the data and preprocessing it using regular NLP techniques (removing stop words, building BOW, etc). The details can be found in phase 1 notebook.
    - Trying different models to compare their performance on the dataset in order to choose the best one for tweaking and final production. The details can be found in phase 2        notebook and its report.
    - 

we reached an accuracy of 78% when we implemented the model using logistic regression combined with doc2vec embedding for tweets.
we experimneted with other models (read ml_project_phase3).


you can read all the details of the process from the reports in this google drive: 
    https://drive.google.com/drive/folders/1gCPUUukrpl6zu4QzFoHcvheF1mpIcj-K?usp=sharing
    
for any inquiry, email me: alighazal@aucegypt.edu and omermosa@aucegypt.edu

