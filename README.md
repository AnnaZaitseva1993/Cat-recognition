# Cat recognition
Developent of Android application that estimates probability of presence of a domestic cat in the picture

Structure:
1. Dataset (both train and test) : https://yadi.sk/d/_mPGtFAyGJH44A
2. train model : code of Keras model training based on kernel https://www.kaggle.com/uysimty/keras-cnn-dog-or-cat-classification
   (obtained validation accuracy - 88%)
3. Android application project (Kotlin) : https://yadi.sk/d/maOCjg0MQwX-eA
4. ImageClassifierActivity.kt : "cat" probability estimation of chosen image from application gallery
5. Classifier.kt : classification function = image scaling + prediction
6. TF-Lite converted model : https://yadi.sk/d/ADKNEMXnef0o5A
7. Android application for model infering: results representation (test set images recognition)
