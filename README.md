# Plant_Disease_Recognition
Image Classification for coursework; Check the results, it is useful.

Kaggle Dataset: https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset

#Result Analysis:

Simpler Dataset or Small sample size of the dataset.
Traditional methods like KNN and SVM can perform surprisingly well. CNNs need more data to generalize properly.
CNN might be overfitting.
Results suggests some overfitting, though not extreme.
KNN is non-parametric.
If image classes are visually distinct and data is well-preprocessed (e.g., resized and normalized), KNN can do really well.
KNN also benefits from data similarity, not learned features.
![image](https://github.com/user-attachments/assets/65f99455-8621-4117-a3cc-139aef590473)


SVM shows underfitting but decent generalization.
Low training accuracy (61.67%) but higher test accuracy (69.33%).
May suggest underfitting (model too simple), but also robustness to overfitting.
SVMs work well with linearly separable features, especially with dimensionality reduction or handcrafted features.
RNN IS NOT SUITABLE FOR IMAGE CLASSIFICATION.
RNNs are designed for sequential data (e.g., text, time series).
They don’t learn spatial hierarchies well.
Reshaping images into sequences can break spatial structure → poor performance.
Hence, 71% train / 66% test shows it’s not learning much.
![image](https://github.com/user-attachments/assets/a9cc4ff4-18fb-4554-9cf3-e65f990a63ce)

