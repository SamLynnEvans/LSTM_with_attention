# LSTM_with_attention

My interest in languages and deep learning found a natural intersection in Neural Machine Translation (NMT). This notebook represents my first attempt at coding a seq2seq model to build a fully functioning English-French translator.
<br><br>
I implemented the attention model as outlined by <a href="https://arxiv.org/abs/1508.04025">Luong et al</a>. Using just the small dataset provided, it will build a translator capable of quite basic tasks within two hours of training (on a single GPU).
<br><br>
However it seems RNN models are being taken over by novel approaches such as The Transformer and Temporal Convolutional Networks. I abandoned this approach eventually to build the Transformer as it trained far faster. See the program I created <a href=https://github.com/SamLynnEvans/Transformer>here</a>, which allows you to train the Transformer on your own datasets.
