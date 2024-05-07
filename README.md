This project web scrapped more than 50k reviews on Best Buy on the category of Play Station Game as the dataset.
Then, the scrapped reviews undergo unsupervised aspect extraction using LDA and BERTopic.
The topics and keyterms generated from the LDA and BERTopic models are analyze and restructure into 6 topics which are: genres,
mood, game experience, price, soundtrack and graphics.
Then, semi-supervised aspect extraction is performed using CorEx.
Next, sentiment analysis is performed on the reviews using BiLSTM-SkipGram Model.
Lastly, the table of top 5 products with the highest positive sentiment value of each category is outputted.

