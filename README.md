# Intel-Image-Classification

**Authors:** <br>
Ryan Johnston (https://github.com/astroryan97) <br>
Scott Pellegrino (https://www.linkedin.com/in/rspellegrino/) <br>
Troy Stolz (https://github.com/Salsasharkz) <br>

## DATA 607 Group Project

### Introduction and Background
Moravec’s Paradox states that it is difficult to train a computer to do a task that humans find
relatively easy, such as image recognition. But it is easy to train a computer to do a task that
humans find difficult, such as math (Moravec 1988). The development of deep learning has
made this process much easier over the past two decades. Deep learning uses artificial neural
networks, a collection of nodes that are connected like neurons to process data (LeCun et al.
2015). In image classification, convolutional neural network (CNN) models work incredibly
well.

### The Data
In this project we will be using the Intel Image Classification dataset. The data contains 25,000
150px by 150px images that fall into 6 main categories that focus on natural scenes and landscapes.
The categories are: buildings, forest, glacier, mountain, sea, and street. The data is available
from Kaggle and is roughly 350 mb in size. The data was originally created by Intel as part of
the Intel Scene Classification Challenge (Intel Challenge 2018).

### Topics of Investigation
Our goal is to train a model to be able to reliably determine the different image categories.
Presently, we are brainstorming methods to both qualify and quantify the differences between
the image categories. This may include general image color and color distribution, image patterns,
and presence of geometry. This will likely be an iterative process. Once we feel a sufficient
number of measurable characteristics have been defined, a model will be produced.
Once we have landed on a finalized model, as an exercise, we wish to compare our results to
professionally constructed models. As those models generally have teams of people working on
them over years of time, it is not expected that our model be as detailed in terms of output. A
benefit, but also limitation, of our model is that only the 6 main categories would be predictable,
limiting the versatility relative to most professional models, but also having a higher likelihood
of correct classification due to the limited options.

### Libraries and Methods
To construct this model, python/ jupyter will be used primarily. Presently, the machine learning
packages which we anticipate using are Tensor Flow and Keras along with Scikitlearn. In
addition to these libraries; Numpy, Pandas, Matplotlib, and Pillow will also be used to varying
extents.

Presently, the approach to construct the prediction model has not been concretely established.
We will likely begin with a random forest approach and begin to transition to deep learning and
neural networks as they become more appropriate and our familiarity grows. Depending on the
computation intensity, we may try to optimize our code to be able to utilize the GPU for faster
prediction.

### References
Intel Challenge (2018), ‘Intel scene classification challenge’. data retrieved from Kaggle, https://www.kaggle.com/puneet6060/intel-image-classification.

LeCun, Y., Bengio, Y. & Hinton, G. (2015), ‘Deep learning’, Nature 521(7553), 436–444.
URL: https://doi.org/10.1038/nature14539

Moravec, H. (1988), Mind Children: The Future of Robot and Human Intelligence, Harvard
University Press, USA.
