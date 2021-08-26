# Breast-cancer-classification

This study uses the classification complementarity of different regions of breast ultrasound to propose a classification method that uses pre-trained CNNs as a deep feature extractor and ensemble learning as a classifier.

1. Preprocess the data
2. Extract three different regions of interest through the segmentation algorithm
3. Use transfer learning to evaluate the performance of four convolutional neural networks
4. Select the Inception-V3 network as the feature extractor, and perform deep feature extraction on the original ultrasound image and the three regions of interest.
5. Use Stacking ensemble learning for fusion classification of deep features
