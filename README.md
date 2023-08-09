# Artificial-Intelligence-Coursework
AI Coursework 2023.

cw1 - 
For this submission I will be following and citing frequently Deep Learning With Python (F. Chollet, Deep Learning with Python. Shelter Island (New York, Estados Unidos): Manning, Cop, 2018.)
Using the Boston Housing Pricing dataset shipped with Keras. I will create a regression model that allows the user to make predictions on housing prices given a list of features.

cw2 - 

For this submission I will be exploriing the use of the DeepDream technique, similar to what we have encountered in the reading of chapter 12 in Deep Learning with Python[1].
What is DeepDream?
DeepDream is an artistic image-modifiation technique[2] that uses a convolutional neural network to draw it's representation. First released by Google in the summer of 2015[2]. It is notorious for it's style - enveloping it's input image within a 'dream-like' psychedelia; full of pareidolic artificates: bird feathers, dog eyes, and other such things – a byproduct of of the fact it was trained on the ImageNet dataset[3], which has a overarching presence of dog breed and bird images.
How does it work?
Starting from a noisy input, the model will begin to latch onto to patterns learned within the noise, distorting the image overtime. Input images are processed at different octaves (scales), smaller octave images are 'dreamt' upscaled, and immediately reinjected with the features learnt from the the following octave, to preserve detail and minimise unwanted noise. And lastly on a layer to layer occurence; activations of functions are maximised, so that visual patterns are enhanced, as features are mixed in together and amplified unto the output.


