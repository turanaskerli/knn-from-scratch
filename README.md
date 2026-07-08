# K-Nearest Neighbors (KNN) From Scratch 🧬📊

A custom, ground-up implementation of the K-Nearest Neighbors classification algorithm built entirely without relying on high-level machine learning libraries like `scikit-learn`. 

This project aims to demonstrate a deep understanding of core machine learning mechanics by manually implementing data preprocessing, feature scaling, distance metrics, and prediction logic. The model is trained and tested on the **Breast Cancer Wisconsin Diagnostic Dataset** to predict whether a tumor is benign or malignant.

## 🚀 Key Features

*   **Custom Distance Metrics:** Fully vectorized calculation of Euclidean distance between data points.
*   **From-Scratch Preprocessing:** Manual implementation of Z-score feature scaling to standardize data.
*   **Native Train/Test Split:** Custom logic for shuffling indices and dividing the dataset for training and evaluation.
*   **Performance Evaluation:** Includes a custom-built confusion matrix to evaluate the accuracy, precision, and recall of the model's predictions.
*   **Jupyter Notebook Workflow:** Clear, step-by-step documentation of the algorithmic process directly alongside the code.

## 🛠️ Tech Stack

*   **Language:** Python 3
*   **Environment:** Jupyter Notebook (`.ipynb`)
*   **Libraries:** 
    *   `NumPy` (Vectorized mathematical operations)
    *   `Pandas` (Data manipulation and structuring)
    *   `Matplotlib` (Data visualization)

## 📊 Dataset

The model utilizes the **Breast Cancer Wisconsin (Diagnostic) Dataset**. 
*   **Features:** Computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing characteristics of the cell nuclei.
*   **Target:** Diagnosis (M = Malignant, B = Benign).

## 💻 Getting Started

To explore this project locally, clone the repository and run the Jupyter Notebook:

```bash
# Clone the repository
git clone [https://github.com/turanaskerli/knn-from-scratch.git](https://github.com/turanaskerli/knn-from-scratch.git)

# Navigate to the project directory
cd knn-from-scratch

# Launch Jupyter Notebook
jupyter notebook main.ipynb