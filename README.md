# breast-cancer
# Breast Cancer Prediction using Machine Learning

## Project Overview

This project uses Machine Learning to predict whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)**. Early detection of breast cancer is extremely important in the medical field, and predictive models can help assist doctors in making faster and more accurate decisions.

In this project, I used the Breast Cancer dataset available in scikit-learn and built a classification model using the **Random Forest algorithm**.

---

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin dataset**, which is available directly in the scikit-learn library.

It contains measurements computed from digitized images of breast mass cell nuclei. These measurements describe characteristics such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry

The dataset contains:

* **569 samples**
* **30 numerical features**
* **Target classes:**

  * `0` → Malignant (Cancerous)
  * `1` → Benign (Non-cancerous)

---

## Technologies and Libraries Used

The project was implemented using Python and the following libraries:

* Python
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

---

## Machine Learning Model

I used the **Random Forest Classifier** for this project.

Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their predictions to produce a more accurate and stable result.

Steps followed in this project:

1. Load the dataset from scikit-learn
2. Convert the dataset into a pandas DataFrame
3. Perform basic data exploration
4. Split the dataset into training and testing sets
5. Train the Random Forest model
6. Evaluate model performance using accuracy and classification metrics
7. Test predictions on new input data

---

## Model Performance

After training the model, it achieved an accuracy of approximately **97% – 99%** on the test data.

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Example Prediction

The trained model can also be used to predict whether a new tumor measurement indicates cancer or not.

Example output:

* **Malignant (Cancer Detected)**
* **Benign (No Cancer Detected)**

---

## Project Structure

```
Breast-Cancer-Prediction
│
├── breast_cancer_prediction.ipynb
├── README.md
```

---

## Conclusion

This project demonstrates how machine learning can be applied to medical datasets to assist in disease prediction. Random Forest proved to be a powerful algorithm for this classification problem, achieving high accuracy while remaining easy to interpret and implement.

---

## Author

Swathi
Artificial Intelligence & Machine Learning Student
