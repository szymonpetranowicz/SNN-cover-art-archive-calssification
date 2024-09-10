This notebook has been written as a technical part of my master's degree diploma project, about Siamese Neural Networks with triplet loss function.

The analysis is based on 10k vinyl covert art. The core goal was to train SNN to check whether cover art is in the collection.

The analysis contains 108 resnet_v2 models in a combination of:

image preprocessing [resnet preprocess, diy preprocess]
version of the model [50,101,152]
epoch [1,3,5]
triplet per image [1,10]
