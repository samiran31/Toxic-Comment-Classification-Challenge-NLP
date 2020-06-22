# Toxic-Comment-Classification-Challenge-NLP
In this repository we have explored NLP, attempted to solve the problem in hand using Keras, LR, SVM.

In this repository we have below kernals:

1)[For Beginners] Tackling Toxic Using Keras:This notebook attempts to tackle this classification problem by using Keras LSTM.

2)Logistic regression with words and char n-grams:Used TfidfVectorizer to first convert the words into vectors and then LR to finally solve the problem in hand.

3)NB-SVM strong linear baseline:Used TfidfVectorizer to first convert the words into vectors and then SVM to finally solve the problem.

4)Stop the S@#$ - Toxic Comments EDA:- Extensive EDA and Feature engineering has been done in this notebook followed by SVm to solve the issue.

5)Toxic_comment_analysis:- Extensive EDA , feature Enginering and use of spacy has been explored.

PROBLEM DESCRIPTION:

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing
themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many 
communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help 
improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that
are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available 
models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users
to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other
types of toxic content).

In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like
threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments 
from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and 
respectful.

Disclaimer: the dataset for this competition contains text that may be considered profane, vulgar, or offensive.
