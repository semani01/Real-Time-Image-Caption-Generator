<h1 align = "center"> Real-Time Image Caption Generator </h1>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>

This project involves a systematic analysis of deep neural networks-based image caption generation methods. With an image as the input, the method can output an English sentence describing the image's content. Analyzed three components of the method: convolutional neural network (CNN), recurrent neural network (RNN), and sentence generation. By replacing the CNN part with three state-of-the-art architectures, a proposal for a simplified version of the Gated Recurrent Units (GRU) as a new recurrent layer had been made, implementing both Python and Keras library in Jupyter Notebook. The simplified GRU achieves comparable results when compared with the long short-term memory (LSTM) method. But it has a few parameters which save memory and is faster in training. Finally, multiple sentences are generated using Beam Search. The experiments show that the modified method can generate captions comparable to the state-of-the-art methods with less training memory.


<p align = "center">
<img src = "/model/pipeline.png" alt="pipeline" height = 250 width = 350/>
<h5 align = "center"> Image Caption Generation Pipeline </h5> 
</p>


<h2 align = "center"> Problem Statement </h2> 
Automatically describing the content of images using natural languages is a fundamental and challenging task. It has a great potential impact. For example, it could help visually impaired people better understand the content of images on the web. Also, it could provide more accurate and compact information on images/videos in scenarios such as image sharing in social networks or video surveillance systems. This project accomplishes this task using deep neural networks. By learning knowledge from image and caption pairs, the method can generate image captions that are usually semantically descriptive and grammatically correct.


<h2 align = "left"> Screenshots </h2>
<h4 align = "left"> Captions for Images </h4> 

<p align = "center">
<img src = "/Project_Snips/Image1.png" alt="Image1" height = 300 width = 500/>
<h5 align = "center"> Image1: image fed into the model as input </h5> 
</p>
<br>
<p align = "center">
<img src = "/Project_Snips/Image1-caption.png" alt="Image1-caption" height = 300 width = 600/>
<h5 align = "center"> Caption for Image 1: "motorcycle racer is riding on the track"</h5> 
</p>
<br>
<br>

<p align = "center">
<img src = "/Project_Snips/Image2.png" alt="Image1" height = 300 width = 500/>
<h5 align = "center"> Image2: image fed into the model as input </h5> 
</p>
<br>
<p align = "center">
<img src = "/Project_Snips/Image2-caption.png" alt="Image2-caption" height = 300 width = 600/>
<h5 align = "center"> Caption for Image 2: "black dog is running through the water"</h5> 
</p>
<br>
<br>

<h4 align = "left">More Generated Captions</h4> 
<p align = "center">
<img src = "/Project_Snips/Sample_captions1.png" alt="Sample captions1" height = 300 width = 600/> </p>
<p align = "center">
<img src = "/Project_Snips/Sample_captions2.png" alt="Sample captions2" height = 300 width = 600/> </p>
<p align = "center">
<img src = "/Project_Snips/Sample_captions3.png" alt="Sample captions3" height = 500 width = 600/> </p>
<br>
<br>

# License
```xml
Designed and developed by 2021 semani01 (Sai Emani)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```



