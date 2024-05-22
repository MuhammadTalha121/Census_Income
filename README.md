# Adult Income Classification

This project aims to predict whether a person earns more than 50K annually using the Adult Income dataset. The dataset contains various demographic and employment-related attributes.

## Dataset

The dataset used in this project is the Adult Income dataset. It contains the following columns:

- `age`: Age of the individual
- `workclass`: Type of work class
- `fnlwgt`: Final weight
- `education`: Level of education
- `education-num`: Number of years of education
- `marital-status`: Marital status
- `occupation`: Type of occupation
- `relationship`: Relationship status
- `race`: Race of the individual
- `sex`: Gender of the individual
- `capital-gain`: Capital gain
- `capital-loss`: Capital loss
- `hours-per-week`: Number of hours worked per week
- `native-country`: Country of origin
- `class`: Income class (<=50K or >50K)
- `salary`: Binary representation of the income class (0 for <=50K and 1 for >50K)

## Project Structure

The project contains the following files:

- `adult.train`: Training dataset
- `adult.test`: Test dataset
- `train_model.py`: Script to train the model
- `test_model.py`: Script to test the model
- `requirements.txt`: List of dependencies
- `README.md`: Project documentation

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/adult-income-classification.git
cd adult-income-classification
pip install -r requirements.txt
