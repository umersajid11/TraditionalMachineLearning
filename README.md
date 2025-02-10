# TraditionalMachineLearning
Traditional Machine Learning Technique on Hand Digit dataset
Traditional Machine Learning (ML) models typically don't use raw images directly. Instead, they rely on feature extraction techniques to transform the images into a more suitable format for training.

Here's why:

1. Images are high-dimensional data: Images are made up of pixels, which can result in a large number of features (e.g., 224x224x3 for a 224x224 RGB image). This can lead to the curse of dimensionality.
2. Images require preprocessing: Images often require preprocessing techniques like resizing, normalization, and data augmentation to prepare them for training.

To address these challenges, traditional ML models use feature extraction techniques to transform the images into a more compact and meaningful representation. Some common feature extraction techniques include:

1. Handcrafted features: Techniques like edge detection, corner detection, and texture analysis are used to extract relevant features from images.
2. Feature descriptors: Methods like SIFT (Scale-Invariant Feature Transform), SURF (Speeded-Up Robust Features), and HOG (Histogram of Oriented Gradients) are used to describe the distribution of pixels in an image.

These extracted features are then fed into a traditional ML model, such as a Support Vector Machine (SVM), Random Forest, or k-Nearest Neighbors (k-NN), for classification or regression tasks.

In contrast, Deep Learning (DL) models, particularly Convolutional Neural Networks (CNNs), can directly take raw images as input and learn to extract relevant features automatically.
