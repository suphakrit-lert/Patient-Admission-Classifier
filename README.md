# Patient Admission Classification from the Blood Test

## Problem:
Describe a persona of whether the next patient that is administered basic laboratory tests would require to be admitted in to the hospital (incare patient) or can be treated within the out-patient department of the hospital itself.

## Aims and Methods: 
For this classification we aim to test a suite of supervisory classification algorithms, namely:
1. Logistic Regression
2. Support Vector Machine
3. K-Nearest Neighbour
4. Random Forest

## Data Set Information
The dataset is Electronic Health Record Predicting collected from a private Hospital in Indonesia. It contains the patients laboratory test results used to determine next patient treatment whether in care or out care patient. The task embedded to the dataset is classification prediction. 
Attribute Information:
Given is the attribute name, attribute type, the measurement unit and a brief description. The number of rings is the value to predict: either as a continuous value or as a classification problem. 

| Name         | Data Type           | Value Sample | Description                                           |
|--------------|---------------------|--------------|-------------------------------------------------------|
| HAEMATOCRIT  | Continuous          | 35.1         | Patient laboratory test result of haematocrit          |
| HAEMOGLOBINS | Continuous          | 11.8         | Patient laboratory test result of haemoglobins         |
| ERYTHROCYTE  | Continuous          | 4.65         | Patient laboratory test result of erythrocyte          |
| LEUCOCYTE    | Continuous          | 6.3          | Patient laboratory test result of leucocyte            |
| THROMBOCYTE  | Continuous          | 310          | Patient laboratory test result of thrombocyte          |
| MCH          | Continuous          | 25.4         | Patient laboratory test result of MCH                  |
| MCHC         | Continuous          | 33.6         | Patient laboratory test result of MCHC                 |
| MCV          | Continuous          | 75.5         | Patient laboratory test result of MCV                  |
| AGE          | Continuous          | 12           | Patient age                                            |
| SEX          | Nominal – Binary    | F            | Patient gender                                         |
| SOURCE       | Nominal             | {in, out}    | The class target: in = in-care patient, out = out-care patient |

## Dependencies
List of dependencies used in this project
1. `python 3.9`
2. `numpy==1.26.1`
3. `pandas==2.1.4`
4. `statsmodels==0.14.2`
5. `matplotlib==3.9.2`
6. `seaborn==0.13.2`
7. `scipy==1.11.4`
8. `plotly==5.22.0`
9. `scikit-learn==1.4.2`

## Installation

_Step to setup_

1. Create a virtual environment
   ```sh
   py -3.12 -m venv .venv
   ```

2. Enter the newly created virtual environment
   ```sh
   .venv\Scripts\activate
   ```

3. Install all the dependencies in the requirements.txt
   ```sh
   py -m pip install -r requirements.txt
   ```

## Usage
1. Go to the Jupyter notebook file [main.ipynb](main.ipynb) and follow the instructions in the file. The data is located in the [blood_test_result](./data/blood_test_result.csv).
2. After running the `main.ipynb`, the results will be generated in file. Read the report in the `Patient Administration Prediction Using Blood Test Result.pdf` file.
   
## Author
* Name: Suphakrit Lertkitcharoenvong
* Email: sl3355@cornell.edu
* Tel: 5517995082
