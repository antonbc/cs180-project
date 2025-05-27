# CS180 Computer Vision Project

This repository contains the implementation of our Computer Vision project for **CS 180: Artificial Intelligence**, a course under the Department of Computer Science, College of Engineering, University of the Philippines, Diliman. Developed under the guidance of **Associate Professor Carlo Raquel**, this project was completed during the academic year **2024-2025**.

## Team Members
- Andres, Lance Leo
- Chio, Mikhail Anton B.
- Tuan, Hamdi
  
## How to Run the Project

### Step 1: Clone the Repository
```zsh
git clone git@github.com:antonbc/cs180-project.git
```

### Step 2: Navigate to the Project Directory
```zsh
cd cs180-project
```

### Step 3: Download Pre-Trained Models
Download the required pre-trained models from this [Google Drive Link of Pre-Trained Models](https://drive.google.com/drive/folders/1vO8MprVQdztSgorqvVyTRAQZL_XACgEh?usp=sharing)

### Step 4: Place Downloaded Pre-Trained Models in Project Directory
After Downloading **`CNN_transfer_learning/`** and **`VIT_transfer_learning/`** add them to the project directory.


### Step 5: Install Required Dependencies for the Model
```
pip install numpy matplotlib torch torchvision tensorboard timm pandas openpyxl
```

### Step 6: Open Jupyter Notebook and Run the Demo Notebook
```
jupyter notebook Demo+predictions.ipynb
```

## Code Structure
- **`outputs/`**: Contains the outputs of each model.
- **`train/`**: Contains the training set for both models.
- **`test/`**: Contains the test set for both models.
- **`training_results/`**: Contains the accuracy graphs of each model used.
- **`CNN_train.ipynb`**: Contains the solution for deep learning-based approaches that do not employ transformer architectures.
- **`VIT_train.ipynb`**: Contains the solution for deep learning-based approaches underpinned by transformer architectures.
- **`Demo+predictions.ipynb`**: Contains our Demo Model which contains both the VIT model and CNN model.

