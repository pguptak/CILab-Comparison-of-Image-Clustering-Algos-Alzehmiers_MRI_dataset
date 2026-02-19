#  Alzheimer's Disease Analysis Project
This project is designed to analyze Alzheimer's disease using machine learning and deep learning techniques. The primary goal is to develop a comprehensive understanding of the disease by applying various models and clustering algorithms to a specific dataset. The project aims to identify patterns, groups, and labels change percentage within the data, which can inform future research directions or model selections.

## 🚀 Features
- Data preparation and preprocessing using `ImageDataGenerator` for image data augmentation
- Utilization of pre-trained models like `ResNet152`, `MobileNetV3Large`, `VGG19`, and `Xception` for feature extraction or fine-tuning
- Application of clustering algorithms, including HDBSCAN and Birch, for pattern identification
- Comparison of model accuracies using different approaches and datasets
- Integration of various libraries, including `numpy`, `pandas`, `matplotlib`, `sklearn`, `tensorflow`, and `keras`

## 🛠️ Tech Stack
- Backend: Python 3.x
- AI/ML Tools:
  - `tensorflow` for deep learning tasks
  - `sklearn` for machine learning tasks
  - `keras` for deep learning model construction and training
- Build Tools: Not applicable (Jupyter Notebooks)
- Libraries:
  - `numpy` for numerical computations
  - `pandas` for data manipulation and analysis
  - `matplotlib` for plotting
  - `scikit-learn-extra` for additional machine learning functionalities
  - `hdbscan` for hierarchical density-based clustering
  - `scikit-fuzzy` for fuzzy logic and clustering

## 📦 Installation
To set up the project, follow these steps:
1. Install the required libraries by running `pip install -r requirements.txt`
2. Download the dataset from a zip file named "alzehmier.zip" and extract it
3. Open the Jupyter Notebooks (`Alzehmier.ipynb`, `clustering_alzehmier.ipynb`, and `ACCURACY COMPARISON ALZEHMIER.ipynb`) and run the cells to execute the code

## 💻 Usage
1. Run the `Alzehmier.ipynb` notebook to prepare the data and train models
2. Run the `clustering_alzehmier.ipynb` notebook to apply clustering algorithms
3. Run the `ACCURACY COMPARISON ALZEHMIER.ipynb` notebook to compare model accuracies

## 📂 Project Structure
```
project/
|---- Alzehmier.ipynb
|---- clustering_alzehmier.ipynb
|---- ACCURACY COMPARISON ALZEHMIER.ipynb
|---- clustering results.csv
|----Extracted Features
|----clustering labels
|---original labels.csv

```
