### Real-Time Image Caption Generator
This project involves a systematic analysis of deep neural networks-based image caption generation methods. With an image as the input, the method can output an English sentence describing the image's content. Analyzed three components of the method: convolutional neural network (CNN), recurrent neural network (RNN), and sentence generation. By replacing the CNN part with three state-of-the-art architectures, a proposal for a simplified version of the Gated Recurrent Units (GRU) as a new recurrent layer had been made, implementing both Python and Keras library in Jupyter Notebook. The simplified GRU achieves comparable results when compared with the long short-term memory (LSTM) method. But it has a few parameters which save memory and is faster in training. Finally, multiple sentences are generated using Beam Search. The experiments show that the modified method can generate captions comparable to the state-of-the-art methods with less training memory.


<p align = "center">
<img src = "/model/pipeline.png" alt="pipeline" height = 250 width = 350/>
<h5 align = "center"> Image Caption Generation Pipeline </h5> 
</p>


<h2 align = "center"> Problem Statement </h2> 
<p>
- In today’s world, technology plays a vital role, without technology, it is hard to imagine our day-to-day life. Every day an innovation is taking place in some part of the world. Image recognition and computer vision are such developments that are taking the world by storm.
- You saw an image and your brain can easily tell what the image is about, but can a computer tell what the image is representing? Computer vision researchers worked on this a lot and they considered it impossible until now! 
- With the advancement in Deep learning techniques, the availability of huge datasets, and the computing power of data science, we can build models that can tell what an image is, and what objects are seen. </p>
