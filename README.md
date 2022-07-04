# Image-Captioning
### A deep learning model to generate captions for images.
### Flickr 8K dataset is used for training of this model.
### This project uses VGG16, a CNN model for Image feature extraction.
### Pickle is used to store and load the extracted features.
### A Map is used to store the Captions for the Images.
### Data is Tokenized to be availabe in chunks
### Encoding of the tokenized data is done in batches.
### We'll be adding required Dense & Dropout Layers for Both Image & Captions features
### Then, we'll be using LSTM encoder decoder model (i.e., RNN) to integrate the above features.
### Finally, train the model & test it on the data! 

