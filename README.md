# Heart Failure Prediction

This project aims to predict heart failure events using a dataset of clinical records.

- **Heart Failure Prediction.ipynb**: Jupyter notebook containing the analysis and prediction models.
- **heart_failure_clinical_records_dataset.csv**: Dataset used for training and testing the models.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook Heart Failure Prediction.ipynb
    ```

2. Run the cells in the notebook to perform the analysis and make predictions.

## Dataset

The dataset contains clinical records of heart failure patients. The columns are:
- `age`
- `anaemia`
- `creatinine_phosphokinase`
- `diabetes`
- `ejection_fraction`
- `high_blood_pressure`
- `platelets`
- `serum_creatinine`
- `serum_sodium`
- `sex`
- `smoking`
- `time`
- `DEATH_EVENT`

## Models

The following models are used for prediction:
- Logistic Regression
- Random Forest
- Gradient Boosting
