# CNN-DNN
*Overview on convolutional Neural Network and Deep Neural Network*
## Neural Network
It has Interconnected input and output In which each connection has an associated weights
It will adjust the weight during the learning process
![image](https://user-images.githubusercontent.com/67863890/98467319-a9d85600-21fa-11eb-8424-add5f353778d.png)


## Perceptron
Only Input and output Layer no hidden layer
Simple decision making
![image](https://user-images.githubusercontent.com/67863890/98467182-0424e700-21fa-11eb-9890-83d468e52aca.png)

## ANN - Artificial Neural Network
Learns any Non-Linear Function, It is known as Universal Function Approximators

Activation Function introduce non linear property to network, so it will identify complex relationship between input & output

Output of each neuron is the activation of weighted sum of Input, If there is no Activation function, network can't learn non-linear function

Feed Forward Neural Network – Input processed in one direction

When hidden layer is more than one, that is Deep Neural Network


## RNN - Recurrent Neural Network
Looping system in hidden layer of ANN is known as RNN

It captures sequential info of input data, that is dependency between words to make prediction. Whereas, ANN cannot capture sequential information

RNN shares parameters across different time steps, so that there will be few parameter to train

It is the time series version of ANN. Common Recurrent layers are LSTM(Long Short Term Memory) & GRU (Grated Recurrent Units)

GRU is used to how much pass data needed to flow through model

It is mostly used in NLP (Natural Language Processing)

## CNN - Convolution Neural Network

CNN learns the filter automatically to extract the right features from the data

It captures spatial features (Arrangement of pixels) whereas ANN can’t.

It also follows parameter sharing like RNN, applies single filter in different part of single image. Whereas ANN can’t.

It don’t have recurrent connections like RNN, instead it has convolution type of hidden layers

Convolution and pooling functions are used as activation functions

CONVOLUTION: Input image and other as Filter on input image(Kernel) produces output image.
POOLING: picking maximum value from selected region is Max pooling and vice versa.


###### Architecture of CNN
![image](https://user-images.githubusercontent.com/67863890/98467416-28cd8e80-21fb-11eb-9bec-0a406c32b18b.png)
