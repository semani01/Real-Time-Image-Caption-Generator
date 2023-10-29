### Real-Time Image Caption Generator
This project involves a systematic analysis of deep neural networks-based image caption generation methods. With an image as the input, the method can output an English sentence describing the image's content. Analyzed three components of the method: convolutional neural network (CNN), recurrent neural network (RNN), and sentence generation. By replacing the CNN part with three state-of-the-art architectures, a proposal for a simplified version of the Gated Recurrent Units (GRU) as a new recurrent layer had been made, implementing both Python and Keras library in Jupyter Notebook. The simplified GRU achieves comparable results when compared with the long short-term memory (LSTM) method. But it has a few parameters which save memory and is faster in training. Finally, multiple sentences are generated using Beam Search. The experiments show that the modified method can generate captions comparable to the state-of-the-art methods with less training memory.


<p align = "center">
<img src = "/model/pipeline.png" alt="pipeline" width = 250/>
<h5 align = "center"> Image Caption Generation Pipeline </h5> 
</p>
