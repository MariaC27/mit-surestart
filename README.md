# MIT SureStart Program Responses

### Day 1 - July 6
learned of lambda function for iteration in python

### Day 2 - July 7
connected with team for the first time

### Day 3 - July 8
learned distinctions between AI, ML, and neural networks
- responses:
  - in supervised learning, the training data has labels and the model learns from feedback. in unsupervised learning, the training data doesn't include labels and the model instead groups similar items without labeling them
  - scikit needs data visualization libraries such as graphviz in order to properly visualize data

### Day 4 - July 9
a dataset I found interesting was the MNIST dataset of handwritten digits. I think this could be useful for software that automatically transfers handwritten text in pictures into typed text (like a scanner that turns handwritten documents into text documents). This would use ML algorithms to correctly identify handwritten letters. I think a supervised ML algorithm would work best for this as the model can compare it's predictions to a "key" document with the correct labels and learn from its mistakes
- http://yann.lecun.com/exdb/mnist/

### Day 7 - July 12
- tensors are multi-dimensional arrays with a uniform type which allow for storage of data for subsequent analysis using libraries such as tensorflow and pytorch
- in the tutorials, I noticed that the data needs to be manipulated/standardized first (such as making all images the same size and greyscale) before giving them to the model

### Day 8 & 9 (July 13 & 14)
see code folders. reflections: what really made an impression on me these two days was exploring the kaggle website. I had no idea it existed before this and I thought it was super cool that so many people publish their code and steps in great detail to help others. I found the kaggle notebooks super useful and informative and I also liked exploring around and searching for other useful notebooks.

### Day 10 - July 15
survival of the best fit game
- the game talks about machine learning and how the company decided to speed up the hiring processing using an ML algorithm trained on the limited database of decisions the user of the game makes about hiring people. the concepts of training a model based on existing data to increase efficiency were mentioned. ultimately, the lesson was that the training data in itself was biased and not a large enough dataset, resulting in the model making discriminatory decisions about hiring
- an example of a biased machine learning model would be one that seeks to identify patients in the healthcare system who require extra care. since there may be more data on white patients or just inherent bias in thinking that white people have privilege, the model identifies more white people as needing care, which results in other racial groups receiving inadequate care

### Day 11 - July 16
convolutional neural network vs. fully connected neural network
- in a fully connected neural network, every neuron in each layer is connected to every neuron in the next layer. this is useful in that no assumptions need to be made about the input. meanwhile, in CNNs, the inputs are always assumed to be images, so the layers are connected through differentiable functions rather than connecting every single neuron. 
- fully connected networks have very broad applications, but are generally weaker than specialized networks. CNNs on the other hand are more tuned to the special purpose of using images in a model, and are therefore stronger in that respect
