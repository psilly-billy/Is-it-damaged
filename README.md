# Damage Detection with YOLOv8 and Roboflow

This Jupyter Notebook demonstrates the process of training a YOLOv8 model for damage detection. It utilizes Roboflow for dataset management and preprocessing, aiming to streamline the workflow from dataset preparation to model training and evaluation.

## Overview

The script performs several key operations:
- Checks GPU availability using `nvidia-smi`.
- Installs YOLOv8 and Roboflow packages.
- Downloads a specific dataset version from Roboflow.
- Trains a YOLOv8 model on the dataset.
- Evaluates the model, generating a confusion matrix and other metrics.
- Deploys the trained model for inference.
- Runs inference on random images from the test set.
- Exports the model in TensorFlow Lite format for optimized deployment.
- Optionally, performs model optimization using `tensorflow-model-optimization`.

## Key Metrics

After training, the script generates various metrics to evaluate model performance, including a confusion matrix and other visualizations found in `runs/detect/train/`. These metrics are crucial for understanding the model's accuracy, precision, and recall.

## Prerequisites

- Python 3.x
- Access to a GPU for model training and inference.
- An API key from Roboflow for accessing the dataset.

## Setup and Usage

1. Ensure you have Python and the necessary packages installed. The script will automatically install YOLOv8 and Roboflow via pip.
2. Replace `""` with your Roboflow API key.
3. Adjust the dataset version and project name according to your Roboflow account.
4. Run the script in a Python environment with GPU support to commence training and evaluation.
5. View the status of the deployment at: https://app.roboflow.com/martin-rpfil/is_it_damaged/8


## Contributing

Your contributions to improve the script or extend its functionalities are welcome. Please feel free to fork the project, make your changes, and submit a pull request.

