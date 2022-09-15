# Image_Captioning_Resnet50_LSTM
Generate an Image Captioning Model Using Resnet50 and LSTM for FlickR8K Dataset


Problem Statement: Image Captioning: Image Captioning is the process of generating a textual description of an image. It uses both Natural Language Processing and Computer Vision to generate the captions. The dataset will be in the form [image → captions]. The dataset consists of input images and their corresponding output captions.

Encoder

The Convolutional Neural Network(CNN) can be thought of as an encoder. The input image is given to CNN to extract the features. The last hidden state of the CNN is connected to the Decoder.

Decoder

The Decoder is a Recurrent Neural Network(RNN) which does language modeling up to the word level. The first time step receives the encoded output from the encoder and also the <START> vector.

Input Data Details
Add these path in your drive shortcut
Image Caption Data: https://drive.google.com/file/d/1A8g74ohdb_5d2fPjc72yF7GxufE9GRcu/view?usp=sharing

Image Data: https://drive.google.com/file/d/1-mPKMpphaKqtT26ZzbR5hCHGedkNyAf1/view?usp=sharing
