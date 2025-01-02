# Multimodal Generative Model for Lung Nodule Detection and Diagnosis

## Project Overview
This project aims to develop a multimodal AI-based model for the detection and diagnosis of pulmonary nodules. The goal is to create an efficient, accurate system that can assist healthcare professionals in the early detection of lung cancer.

## Project Structure
- `/docs`: Documentation files, including reports, references, and papers related to the project.
- `/src`: Source code for the model and utility functions.
  - `/models`: Architecture of the AI model.
  - `/preprocessing`: Scripts for data preprocessing.
  - `/utils`: Helper functions and utility scripts.
- `/data`: Raw and processed datasets used in the project.
  - `/raw`: Raw data (unprocessed).
  - `/processed`: Cleaned and transformed data.
- `/notebooks`: Jupyter notebooks for experimentation and analysis.
  - `/experiments`: Notebooks used for testing and initial experimentation.
  - `/analysis`: Notebooks for results analysis and final experiments.
- `/results`: Outputs, graphs, logs, and evaluation metrics.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/cristianoeoliveira/sb-thesis
   cd sb-thesis
   ```
2. Create and activate a Python virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. For dataset access, follow the instructions in `/data` to obtain the necessary files.

## Future Goals and Improvements
- Explore additional model architectures for better performance (e.g., U-Net, ResNet).
- Integrate external datasets for more diverse training data.
- Improve model interpretability and explainability for medical professionals.
