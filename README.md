# Sonara_Rock_Vs_Mine_Prediction_Using_ML

# Sonar Rock vs. Mine Prediction Model  sonar-rock-vs-mine-prediction

This is a machine learning project that builds a supervised learning model to classify sonar signals as either a rock or a mine.

## 🎯 About The Project

The goal of this project is to build a binary classification model that can accurately distinguish between sonar returns from a metal cylinder (a "mine") and a rock. This is a classic machine learning problem that demonstrates the power of classification algorithms on non-image data.

This project follows the tutorial and concepts from the video: [https://youtu.be/fiz1ORTBGpY](https://youtu.be/fiz1ORTBGpY)

---

## 🛠️ Built With

* [Python](https://www.python.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Google Colab](https://colab.research.google.com/)

---

## 📊 Dataset

The model was trained on the **"Sonar, Mines vs. Rocks" dataset**, which contains 208 patterns obtained by bouncing sonar signals off a metal cylinder and a rock at various angles and under various conditions.

* Each pattern is a set of 60 numbers in the range 0.0 to 1.0.
* The output label is "R" for Rock and "M" for Mine.

---

## 🤖 Model Used

A [**INSERT YOUR MODEL NAME, e.g., Logistic Regression**] classifier was used for this task.

The model was trained on preprocessed and scaled data, achieving an accuracy of **[76.1%]** on the test data. This demonstrates its effectiveness in distinguishing between the two materials based on their sonar signatures.

---
