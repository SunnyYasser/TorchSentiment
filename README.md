# Pytorch implementation of sentiment analyser
- A three layer architecture defined as follows:
>> First, a single embedding layer to convert words into word embeddings.used only for dimensionality reduction and not for learning semantic representations
>> Second, a LSTM layer which adds recurrent connections to the model
>> Final layer is a sigmoid which outputs a score between 0 (negative sentiment ) to 1 (positive sentiment)  

- Model is trained on a dataset of movie reviews