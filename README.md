# Amazon-review-analysis
## Data preprocessing
There are reviews of the product in this data which is in English format thus to analyze this data and for making an accurate model we are using NLP to convert data into a format machine can understand.
## Algorithm 
    o	Logistic regression 
    o	GridSearchCV + Logistic regression
    o	Multinomial Bayes
    o	TfidfVectorizer
    o	NMF(Term frequency)
    o	Lda
## Logistic regression 
    	Accuracy: 0.890
    	Training set score: 0.907 
    	Test set score: 0.890
    	Logistic Reg - F1 score: 0.938
## GridSearchCV + Logistic regression
    	Best cross-validation score: 0.891 
    	Best parameters: {'C': 0.1}
    	Accuracy: 0.890
    	Grid Logistic Reg - F1 score: 0.938
## Multinomial Bayes
    	Accuracy: 0.865
    	Training set score: 0.883 
    	Test set score: 0.865
    	Multinomial NB - F1 score: 0.921
## TfidfVectorizer
    	Accuracy: 0.856
    	Training set score: 0.861
    	Test set score: 0.856
    	Multinomial NB - F1 score: 0.922
## NMF
    	Counter({0: 52626, 1: 18374, 2: 14866, 3: 14056, 4: 25615, 5: 15183, 6: 66406, 7: 47307, 8: 12275, 9: 29629})
## Lda
    	Counter({0: 113757, 1: 30429, 2: 38344, 3: 38588, 4: 29083, 5: 869, 6: 24005, 7: 2616, 8: 10653, 9: 7993})
## NMF(Term frequency-inverse document frequency)
    	Counter({0: 109098, 1: 21925, 2: 26765, 3: 22902, 4: 24061, 5: 23085, 6: 11945, 7: 14761, 8: 28261, 9: 13534})
## Lda(Term frequency-inverse document frequency)
    	Counter({0: 295709, 1: 48, 2: 48, 3: 26, 4: 30, 5: 232, 6: 119, 7: 33, 8: 46, 9: 46})
