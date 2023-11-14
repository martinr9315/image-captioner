# image-captioner

*Final Project for Math 156: Machine Learning at UCLA in Winter 2023*

Abstract. This project aims to develop an image caption generation model that uses a pre-trained
convolutional neural network (CNN) as an image encoder and a recurrent neural network (RNN) as a text
encoder, followed by a concatenating decoder. The model generates captions for input images by learning
the relationship between image features and corresponding textual descriptions. Cosine proximity and
BLEU scores are used to evaluate the accuracy of generated captions by measuring the similarity between
generated and ground-truth captions. Different pre-trained CNNs such as InceptionV3, EfficientNetB0,
and ConvNeXtTiny are used to extract image features, and the architectures of the RNNs are adjusted to
optimize the model's performance. The results show that while the model's performance does not see
significant change when varying the size and choice of RNN layers, it is dependent on the choice of the
pre-trained CNN. The final proposed model achieves a cosine similarity score of 0.7812 and 0.0479
BLEU accuracy on the Flickr8k dataset, which is implemented with an InceptionV3 CNN and a two-layer
LSTM network
