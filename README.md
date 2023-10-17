# ML2-Mini-Project_TsaiYunLi

This is a project for the course "DTSA 5510 Unsupervised Algorithms in Machine Learning." In this project I will predict BBC news article categories using Kaggle datasets (see section 8 for reference) through machine learning techniques, including:

TFIDF_NMF_LR model: a combination of (1) a natural language processing vectorizer, term frequency–inverse document frequency (TF-IDF), (2) an unsupervised dimension reduction approach, none-negative matrix factorization (NMF), as required, and (3) a supervised classifier, logistic regression (LR)

TFIDF_LR model: a combination of (1) a natural language processing vectorizer, term frequency–inverse document frequency (TF-IDF), and (2) a supervised classifier, logistic regression (LR)

Conclusion:
1. I have completed the category prediction task described in section 1. Please refer to sections 4 and 5 for examples.
2. I found out that actually the hybrid model TFIDF_LR, using a purely supervised approach, performs better than the hybrid model TFIDF_NMF_LR with the unsupervised dimension reduction approach NMF.

Discussion/Limitations:
1. Could the very high overall accuracy and scores of the two models indicate an issue of overfitting?
Since the texts much longer and much shorter than average are published news article, they should not contain repetitive or irrelevant information, and thus should not be removed as outliers. Please kindly point out if my reasoning is incorrect, and if there is any aspect that I have ignored which causes overfitting.
2. Limited computer resource and a long run time:
To deal with this issue, I cherry picked and tuned the most common hyperparmeters for the hybrid modles. Even though the performace of the models are pretty good, please kindly advice me with advanced techniques to overcome computer resource problem, shorten model run time, and at the same time tune more hyperparamters.

This is my very first machine learning project using an unsupervised approach, as well as using nlp techniques. Your suggestions for improvements are more than welcome! And please do not present my work as your own without proper citation, thank you!
