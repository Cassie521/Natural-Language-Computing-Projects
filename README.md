# Natural-Language-Computing-Projects
This repository contain the projects that are relevant to the natural language computing / processing field. The project topics include but not limited to sentiment analysis, statistical & neural machine translation, and speech recognition analytics, etc. 

Considering some projects are course projects and the restriction of sharing those files as public, I will make the codes as private but I will give descriptions (Context + Mehodology + Result) for each project. 


##  Identify political persuasion on Reddit (Sentiment Analysis) 
In the 'Identify political persuasion on Reddit' project, I applied NLP techniques and conducted machine learning modeling to classify each Reddit post in the specific politcal party that it is affiliated. 

In the project, more specifically, I applied pre-processing, tokenizing, POS tagging and lemmatization on the corpus of 1.81 millions Reddit posts. Then I extract 173 features that is relevant to any politcal bias detection and conduct the feature analysis to select only 5 best features. Finally I trained, cross validated and tested 5 classifiers (SGD classifier, GuassianNB, RandomForestClassifier, MLPClassifier, AdaboostClassifier) on the data in order to predict the political persuasion of the specific Reddit post (E.g. Classify Reddit post into their support political party), achieved accuracy of 83.2%. 


## Neural Machine Translation 
In the ‘neural machine translation project, I implemented Seq2Seq (encoder – decoder) model without attention, with single-headed attention and with multi-headed attention on 1.4 million paired French and English sentences, trained the model with teacher-forcing, decode using beam search and achieved the bleu score of 0.57. 

I also tested the optimal Seq2Seq model and translated multiple sentences from French to English, achieving high adequacy and completeness of translation quality. 



