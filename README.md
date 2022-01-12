# Lyrics-Text-Generator-Deep-Learning-Project
A RNN model that generates songs depending on a few words given by the user.
This project is a step towards a future where both humans and machines can create art that humans would enjoy. It was made as part of Samsung Innovation Campus III (SIC III) internship, where we were tasked with making a project on any topic.

My teammate, Hesham Ahmed El-Hawash, and I, Ali Mohamed Hashish, decided that it would be really fun to see what songs a machine can generate, so we chose this topic.
Sadly though, due to lack of funds, and restrictions on memory as well as GPU while using either kaggle or collab, we had to take a very small portion of the dataset, to train our model on (around 0.38%). This resulted in a low accuracy (69% in our best trial) but this can be drastically improved if the model is trained on the whole dataset instead.

Finally, the project showcases the vast difference between the SimpleRNN model and the LSTM one. Where the Simple one simply cannot learn any useful data, and fails to construct a meaningful sentence. On the other hand, the LSTM model quickly improves its accuracy, despite the small size of the data. This is due to the vanishing gradient problem, which is further explained in our presentation.
