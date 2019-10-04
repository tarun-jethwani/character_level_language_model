#Building Character level language with RNN
A Character Level Language Model built using RNN from Scratch (without any framework), just with the help of Numpy

This tutorial is the perfect demonstration of what RNN's are capable of, Please visit my [Blog Page to know more about this project](https://leakyrelu.com/2019/10/03/generating-people-names-by-building-character-level-language-model-rnn-from-scratch/), otherwise this Ipython Notebook is self explainatory

Building the Character Language Model from scratch, just by using Numpy. like, I have said earlier in my tutorials, building any Machine Learning and Deep Learning Model can give you a great insight about how these bit and pieces come together to make a complete model, you could visualize yourself how the Data might be going in getting processed and how RNN ( Recurrent Neural Network ) will be generating predictions, so in a way these so called Deep Learning Models are not mere black box for you.

The underlying model used is RNN which stands for Recurrent Neural Network, it generates prediction for the current time step on the basis of the previous time step

We are going to train the language model with data containing people names, the dataset is there in the file names.txt, for now I have uploaded the file in my Github Repo.

After Training the Model, we will expect the model to sample random names on the basis of what it has learnt.

We are going to code the following Steps,

store text data for processing using an RNN
to synthesize data, by sampling predictions at each time step and passing it to the next RNN-cell unit
build a character-level text generation recurrent neural network
clip gradients ( to prevent it from exploding) 
