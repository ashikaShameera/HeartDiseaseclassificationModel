# Heart Disease Prediction Model

This project involves creating a machine learning model to predict the presence of heart disease based on a set of medical attributes. This is a classification model that determines whether a patient has heart disease or not.The model is built using Jupyter Notebook, Python, NumPy, Pandas, Scikit-learn, and Matplotlib.

## Dataset

The dataset used for this project contains 14 attributes that are crucial for predicting heart disease. Below is the data dictionary describing each attribute:

1. **age:** Age in years.
2. **sex:** Gender (1 = male; 0 = female).
3. **cp:** Chest pain type:
    - 0: Typical angina (chest pain related to decreased blood supply to the heart).
    - 1: Atypical angina (chest pain not related to the heart).
    - 2: Non-anginal pain (typically esophageal spasms, non-heart related).
    - 3: Asymptomatic (chest pain not showing signs of disease).
4. **trestbps:** Resting blood pressure (mm Hg) on admission to the hospital. Anything above 130-140 is typically cause for concern.
5. **chol:** Serum cholesterol in mg/dl. Above 200 is cause for concern.
6. **fbs:** Fasting blood sugar (> 120 mg/dl) (1 = true; 0 = false). '>126' mg/dL signals diabetes.
7. **restecg:** Resting electrocardiographic results:
    - 0: Nothing to note.
    - 1: ST-T Wave abnormality (signals non-normal heart beat).
    - 2: Possible or definite left ventricular hypertrophy (enlarged heart's main pumping chamber).
8. **thalach:** Maximum heart rate achieved.
9. **exang:** Exercise-induced angina (1 = yes; 0 = no).
10. **oldpeak:** ST depression induced by exercise relative to rest. Looks at stress of heart during exercise (unhealthy heart will stress more).
11. **slope:** The slope of the peak exercise ST segment:
    - 0: Upsloping (better heart rate with exercise, uncommon).
    - 1: Flatsloping (typical healthy heart, minimal change).
    - 2: Downsloping (signs of unhealthy heart).
12. **ca:** Number of major vessels (0-3) colored by fluoroscopy. Colored vessel means the doctor can see the blood passing through (more blood movement is better, no clots).
13. **thal:** Thalium stress result:
    - 1, 3: Normal.
    - 6: Fixed defect (used to be a defect but now okay).
    - 7: Reversible defect (no proper blood movement when exercising).
14. **target:** Presence of heart disease (1 = yes, 0 = no, predicted attribute).

The dataset can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease).

# Project Setup

This guide will help you set up Python using Miniconda, clone the repository, create environment variables, and install the necessary libraries.

## Prerequisites

Make sure you have the following installed on your system:
- Git
- Miniconda (or Anaconda)
- Python

**This project includes Jupyter Notebooks using Python libraries:**

- NumPy
- Pandas
- Jupyter
- Scikit-learn
- Matplotlib

## Setup Instructions

### 1. Install Miniconda

If you don't have Miniconda installed, download and install it from the official website: [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

### 2. Clone the Repository

Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/your-username/your-repo.git](https://github.com/ashikaShameera/HeartDiseaseclassificationModel.git
```

To run the code in this repository, follow these steps to create a virtual environment and install the required libraries:

### 3. Create a virtual environment: 
```
cd your-repo
  conda create --name myenv python=3.8
```

### 4. Active the virtual environment: 
```
conda activate myenv
```

### 5. Install the required libraries using conda:
```
conda install numpy pandas jupyter scikit-learn matplotlib
```

### 6. Run Jupyter Notebook
```
jupyter notebook
```
