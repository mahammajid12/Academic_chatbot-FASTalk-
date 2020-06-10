# Academic_chatbot-FASTalk-

We have worked on different models based on Question Answering System (a university chatbot). 

The first one is doc2vec model, that works on similarity basis, the code for which can be found on Doc2VecModel.ipynb. The system answers to the question of user by choosing the answer of most similar question placed in the data.

Our second model is an end to end memory netwok, a generative model that is based on two sub-models. The first part of this model takes query as input from user and finds relevant answer keywords , while the other part generates a complete sentence from the extracted answer keywords, which is our final output. The code for this model can be found on endToEndMemoryNetwork.ipynb.

Our final model, that outperformed the previous models is a combination of two models, doc2vec and LSTM. The first model (doc2vec) extracts keywords from the question asked by the user, which are passed to the second model. The second model (LSTM) generates a sentence from the extracted keywords. The code for this model can be found on doc2vec+final.ipynb.

