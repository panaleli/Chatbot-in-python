# Chatbot-in-python

In this Demo we will build a “chatbot”. A “chatbot” is a conversational model, which in its simplest form
predicts the next sentence given the previous sentence or sentences in a conversation.
We are provided with a dataset of movie dialogs: The Movie dialog corpus from Cornell University:
https://www.kaggle.com/Cornell-University/movie-dialog-corpus#README.txt

The corpus contains:
- 220,579 conversational exchanges between 10,292 pairs of movie characters
- involves 9,035 characters from 617 movies
- in total 304,713 utterances
The utterances are contained in file “movie_lines.txt”.
The corpus can be downloaded from:
https://s3.amazonaws.com/pytorch-tutorial-assets/cornell_movie_dialogs_corpus.zip (original corpus)
https://www.kaggle.com/Cornell-University/movie-dialog-corpus/downloads/movie-dialog-corpus.zip/1
(pre-processed)

The goals of this exercise are:
1. Extract pairs of utterances from the provided dataset.
2. Select a neural network architecture that can adequately model this problem
3. Decide on the choice of activation and loss functions
4. Train you model, on pairs of utterances ([input, output])
5. Do some “discussions” with your chatbot (like the ones shown here:
https://github.com/chiphuyen/stanford-tensorflowtutorials/blob/master/assignments/chatbot/output_convo.txt )
