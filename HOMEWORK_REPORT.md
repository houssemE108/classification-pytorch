# PyTorch Classification with DVC & MLflow - Homework Report

## Student Progress Summary

This report documents the steps taken to complete the PyTorch classification homework assignment and the roadblock encountered.

## Steps Completed Successfully

### 1. Repository Setup

- Forked the original repository: `https://github.com/besmaguesmi/classification-pytorch`

![alt text](<Capture d'écran 2026-01-12 232401.png>)

- Cloned the forked repository to local machine
- Set up Python virtual environment (`.venv`)

### 2. Dependencies Installation

- Installed required packages:
  ```bash
  pip install dvc dvc-gdrive
  pip install torch torchvision scikit-learn mlflow pillow numpy matplotlib seaborn pandas
  ```

#### 2.1 Setup up Google Service

Succeffully setup the google service account and the shared drive
![alt text](<Capture d'écran 2026-01-12 232058.png>)
![alt text](<Capture d'écran 2026-01-12 232123.png>)
![alt text](<Capture d'écran 2026-01-12 232136.png>)

### 3. DVC Configuration Attempts

- Successfully configured DVC remotes:
  - Found existing Google Drive remote: `gdrive://0AOwhfnYtOjdFUk9PVA`
- Attempted data pull: `dvc pull` succefull

![alt text](<Capture d'écran 2026-01-12 233813.png>)

### 4. MLflow Setup

- Installed MLflow
- Successfully started MLflow UI

  ![alt text](image.png)

  4.1 MLflow runs: training the models was successfuk through mlflow as shows in this attachment:
  ![alt text](image-1.png)
  ![alt text](image-2.png)
  also testing the runs was also successful:
  ![alt text](image-3.png)

### 5. Code Analysis

- Examined project structure and dependencies
- Understood expected data structure:
  ```
  data/
  ├── train/
  │   ├── sea/     (image files)
  │   └── forest/  (image files)
  └── test/
      ├── sea/
      └── forest/
  ```
