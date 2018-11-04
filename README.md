# NOTE: Implementation hidden due to Coursera Terms of Service.

# Character Level RNN for Dinosaur Name Generation
Implementation of a multi-layer [Recurrent Neural Network (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network) for training a character level language model to generate dinosaur names using numpy. The model processes a corpus of dinosaur names, trains the character level language model, and generates text character by character that's similar to the original data (dinosaur names).   

# What was learned:  
How to store text data for processing using an RNN  
How to synthesize data, by sampling predictions at each time step and passing it to the next RNN-cell unit  
How to build a character-level text generation recurrent neural network  
Why clipping the gradients is important for avoiding exploding gradients  
How to use numpy and keras for quick model implementation  

# Shakespeare Poem Generator  
Shakespearian poem generator using Keras. [Long Short Term Memory](https://en.wikipedia.org/wiki/Long_short-term_memory) cells are used to ensure long-term dependencies within a sentence are captured when training the model. 

# Implementation
A model was trained for ~1000 epochs on a collection of Shakespearian poems called "The Sonnets". The LSTM is deeper, stacked LSTM model (2 layers). Uses Keras for quick model creation.  

# Credit:
[Sequence Models Course for Deep Learning Specialization](https://www.coursera.org/learn/nlp-sequence-models)
