# ANN with MLFlow

## Project Overview
This project demonstrates the development of an Artificial Neural Network (ANN) using Python and MLFlow for tracking experiments, logging metrics, and managing trained models. The directory contains scripts, notebooks, and MLFlow artifacts to streamline the training and deployment of ANN models.

### Key Components
1. **`requirements.txt`**: Lists the Python dependencies needed for the project.
2. **`ANN with MLFLOW/Ann.ipynb`**: Jupyter notebook containing the ANN training script with MLFlow integration.
3. **`mlruns/`**: Contains all MLFlow experiment runs, metadata, metrics, parameters, and artifacts.
4. **`models/`**: Stores finalized models for specific tasks, versioned for reproducibility.

---

## Installation
To set up the environment:
1. Clone the repository:
   ```bash
   git clone https://github.com/piyushbhavsar22/ann-with-mlflow.git
   cd ann-with-mlflow
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure MLFlow is installed and configured:
   ```bash
   pip install mlflow
   ```

---

## How to Use
### Training the ANN
1. Open the `ANN with MLFLOW/Ann.ipynb` notebook.
2. Run the notebook cells to:
   - Load and preprocess data.
   - Train the ANN model.
   - Log experiments and models to MLFlow.

### Experiment Tracking with MLFlow
1. Start the MLFlow UI to visualize experiments:
   ```bash
   mlflow ui
   ```
2. Open your browser and navigate to `http://localhost:5000`.

### Accessing Trained Models
- Trained models and their metadata can be found under the `mlruns/` directory.
- Finalized models are stored in the `models/` directory for deployment.

---

## Key Features
- **Experiment Tracking**: Logs parameters, metrics, and models using MLFlow.
- **Versioned Models**: Ensures reproducibility with organized storage and metadata.
- **Jupyter Notebook Integration**: Easy-to-follow workflow for ANN development.

---

## Dependencies
The project relies on the following libraries:
- Python 3.x
- TensorFlow/Keras
- MLFlow
- Pandas
- NumPy

Refer to `requirements.txt` for a complete list.

---

## Models
- **Final-Model**: Finalized model with versioning.
- **Wine-Quality-Model**: Specific model trained on the wine quality dataset.

---
