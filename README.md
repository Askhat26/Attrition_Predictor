

## Dataset 
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Features

- Data Preprocessing and EDA
- Model Training and Evaluation (Logistic Regression, MLP, XG-Boost)
- Training Pipeline
- Inference Pipeline
- Data Ingestion and Transformation
- Model Trainer
- Hyperparameter Tuning
- Automatic Data Augmentation
- Docker Image Creation Script
- CI/CD Workflow (GitHub Actions to Amazon ECR to Amazon EC2)
- Reverse Proxy Setup for HTTPS Requests
- SSL & TLS Certificates

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Askhat26/Attrition_Predictor
    ```
2. Navigate to the project directory:
    ```sh
    cd IBM_Attrition_Predictor
    ```
3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Data Preprocessing and EDA

1. Open the Jupyter notebook for EDA:
    ```sh
    jupyter notebook src/notebooks/EDA.ipynb
    ```
2. Run the cells to preprocess the data and perform exploratory data analysis.

### Model Training

1. Open the Jupyter notebook for model training:
    ```sh
    jupyter notebook src/notebooks/models.ipynb
    ```
2. Run the cells to train the models and evaluate their performance.





## License

This project is licensed under the MIT License.
