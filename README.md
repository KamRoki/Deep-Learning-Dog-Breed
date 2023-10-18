# Dog Breed Identification 🐶
Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?
This notebook builds a multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.


## 1. Problem
> Dog breed identification based on a given image.


## 2. Data
> I'm using data from Kaggle's dog breed identification competition, available on: https://www.kaggle.com/competitions/dog-breed-identification/overview


## 3. Evaluation
> The evaluation is a file with predictions probabilities for each dog breed of each test image.


## 4. Features
> Info about the data:
* I'm dealing with images (unstructured data) so probably I'll use deep learning/transfer learning.
* There are 120 breeds of dogs (120 different classes).
* There are around 10,000+ images in the training set.
* There are around 10,000+ images in the test set (these images haven't labels, because I'll want to predict them).
