# PD_CTESM: EEG-Based Parkinson's Disease Classification

This repository contains the Python implementation of the methodology used in the research article focused on **Parkinson's Disease (PD) classification using EEG signals** and a deep learning-based architecture called **CTESM (Convolutional Temporal Encoding and Spatial Modeling)**.

## Repository Structure

The original Jupyter notebook has been modularized into the following standalone Python scripts for better readability and reproducibility:

- **1_data_loading_and_preprocessing.py**  
  Loads EEG datasets, performs preprocessing including normalization and artifact handling.

- **2_feature_extraction.py**  
  Extracts temporal and spectral features from the EEG signals for downstream modeling.

- **3_model_architecture.py**  
  Defines the CTESM deep learning architecture, integrating convolutional layers with temporal and spatial encoding modules.

- **4_training_loop_and_callbacks.py**  
  Implements the model training logic, loss functions, and callback mechanisms like early stopping and checkpointing.

- **5_evaluation_and_metrics.py**  
  Evaluates the trained model using accuracy, F1-score, confusion matrix, and other classification metrics.

- **6_visualization_and_results.py**  
  Visualizes training history, plots EEG signal patterns, and generates result summaries for interpretation.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/PD_CTESM.git
   cd PD_CTESM
