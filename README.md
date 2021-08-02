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

### Day 14 - July 19
loss functions
- one thing I noticed today is that the mean squared error loss (MSE) is exactly like a least-sqaures regression line in statistics. I also thought it was interesting that there is also a mean squared log error loss for minimizing the impact of incorrect predictions and accounting for unscaled data. Also thought "gradient descent" is aptly named as it evokes a visual of the model progressing down a curve or gradient to find the lowest point

### Day 15 - July 20
ReLU functions are advantageous in that they are more efficient and faster to compute than other activation functions such as sigmoid functions, and ReLU avoids vanishing gradients. they are also more biologically similar to the way neurons work in the brain. ReLU functions are mostly used in hidden layers and they can be used for speech recognition and natural language processing.

### Day 16 - July 21
ethics in AI - reflection: it is important for us to realize that the data that the models is trained on should not be regarded as "objective truth" - there can be factors such as exclusion, over-representation, and biased labeling which all influence the predictions that the model makes. transparency is also important in the development and usage of AI algorithms.

### Day 17 - July 22
image classification - reflection: image processing has the same general structure as other ML algorthims, except there needs tobe image preprocessing before the training cycle. this preprocessing includes standardization, class balance, and image augmentation. also learned about the difference between object detection (is it there at all) vs. object localization (not only detects and labels object, but makes bounding box around the position of the object in the image

### Day 18 - July 23
regularization - reflection: learned about overfitting / underfitting - overfitting is essentially when the model is overtrained and the error cannot be narrowed no matter what. underfitting is basically when the model is under-trained and we cannot obtain a sufficiently low error on the training set. to reduce overfitting, we use regularization, of which there are several types including L1, L2, drop-out, and early stopping

### Day 21 - July 26
upsampling and autoencoders - learned about autoencoders: neural network that learns data in an upsupervised manner (encoder learns compressed representations, decoder reconstructs the inputs). I thought the most interesting application of autoencoders to me was the ability to correct corrupted data or de-noise images. It makes sense that autoencoders would be used for this because they have the ability to reconstruct the input data in a more succinet (de-noised) manner after learning the features from the input data. I thought it was especially cool to see this in the action item where the model was able to identify numbers from very blurry/noisy images and then show the output as the correct number on a completely black and noiseless background. 

### Day 22 - July 27
affective computing - learned about ML algorithms that try to analyze and identify human emotions. I think this would be one of the hardest parts of ML, since different people may express different emotions differently on their faces, and their faces may not always reflect their true state of emotion. Although I thought the demos analyzing the face of a driver were interesting, I'm not sure they would have any realistic applications yet given the variability in people's expressions.

### Day 23 - July 28
natural language processing - reflection: this was probably my favorite topic so far. I've always wanted to learn more about linguistics and I like that NLP combines CS, stats, and linguistics together. one application of nlp I see every day is the iMessage predictive text generator. I find it generally pretty helpful although it could use some improvement. However, language model GPT-2 raises ethical concerns because, despite its wide usage, the source code has never been made available to the public, which demonstrates a lack of transparency. If there were biases in the model, the public would have no way to know and acknowledge them.

### Day 24 - July 29
computer vision - reflection: thought that the re-colorization of greyscale images is super cool, would like to do more independent research about how this works
