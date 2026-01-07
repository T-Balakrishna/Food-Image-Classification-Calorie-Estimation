# Food Image Classification and Calorie Estimation

## Description

This project combines deep learning and computer vision techniques to classify food items from images and estimate their calorie content. The system is designed to support dietary monitoring through image-based analysis.

## Objective

To develop an intelligent model that identifies food categories from images and predicts approximate calorie values for each item.

## Dataset

Source: Kaggle – NutritionVerse Real Dataset
[https://www.kaggle.com/datasets/nutritionverse/nutritionverse-real](https://www.kaggle.com/datasets/nutritionverse/nutritionverse-real)

The dataset includes food images along with corresponding calorie information across multiple categories.

## Workflow

* Data preprocessing and image augmentation
* CNN model architecture design and compilation
* Model training and validation
* Calorie estimation using regression-based mapping
* Visualization of predictions and evaluation metrics

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install required dependencies:

   ```bash
   pip install tensorflow keras numpy pandas opencv-python pillow matplotlib
   ```
3. Download the dataset from Kaggle and place it in the project directory.
4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
5. Open the notebook and run all cells sequentially to train the model and generate predictions.

## Results

The model achieved accurate food classification across multiple categories, with calorie estimates close to expected nutritional values.

## Tech Stack

* Python (TensorFlow, Keras, NumPy, Pandas)
* OpenCV, PIL
* CNN-based deep learning model
* Jupyter Notebook

## Future Enhancements

* Mobile integration for real-time food recognition
* Expansion of the dataset with regional and localized cuisines
