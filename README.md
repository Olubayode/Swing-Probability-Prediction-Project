# Swing-Probability-Prediction-Project

## Project Overview
This repository contains the materials for the research project titled "Swing Probability Prediction in Baseball using Pitch Characteristics and Game Context", led by Olubayode Ebenezer. This project applies advanced machine learning techniques, specifically a hybrid ensemble of LGBM and XGBCatboost classifiers, to predict baseball swing probabilities. The focus is on enhancing the understanding of player decisions during games and providing insights that can be used to improve training strategies and player performance.

## Repository Contents
main.tex: LaTeX source file for the research paper.

Paper Writing DS.pdf: Compiled research paper detailing the methodologies, results, and implications of the study.

Olubayode_Ebenezer_marlins_Updated.ipynb:  the code used for data processing and analysis and model,buidling. 
data: (Note: This folder is private and accessible to project contributors only due to the sensitivity of the data.)

README.md: This file, providing an overview and instructions for the repository.

It also contains images and figures from the training model and evaluations
## Data
The dataset includes comprehensive pitch data from the Miami Marlins over three seasons, which is detailed and used under strict confidentiality agreements. The data is not publicly available and is hosted in a private section of this GitHub repository.

## Data Description
Training Data: First two seasons of pitch data used to train the predictive models.
Validation Data: Third season of data, serving as the validation set to test model generalizability and performance.
Key Data Columns
pitch_type
release_speed
batter
pitcher
stand
p_throws
plate_x, plate_z
sz_top, sz_bot

## Methodology
The project employs a two-phase approach:

Machine Learning Phase: Development of predictive models using historical data to estimate swing probabilities based on various game situations and pitch characteristics. After buidling the model, I went ahead to do some other insights like fisning the middle middle Pitches and as well Swing Decision Efficiency (SDE). But these are not reported in the Paper Writing DS

Econometric Analysis Phase: (Upcoming) To assess the economic implications of swing decisions using econometric models.
Model Development

## Feature engineering to enhance model inputs.
Use of ensemble methods combining LGBM and XGBCatboost classifiers to improve prediction accuracy and handle class imbalance.
Extensive validation and testing to ensure robustness and effectiveness of the predictive models.

## Usage
To replicate the analysis or test the models:

Clone the repository.
Ensure that you have access to the private datasets (for authorized users only).
Run the analysis scripts located in the Olubayode_Ebenezer_marlins_Updated.ipynb to perform the feature engineering, model training, and validation.
Contributing
Contributions to this project are welcome. Please send pull requests or open an issue if you have suggestions or improvements.

## Requirements and Installation
This project is implemented in Python and requires the following libraries:
pip install numpy pandas seaborn matplotlib sklearn catboost xgboost lightgbm optuna
Note: All code is written in Python and will require installation of several machine learning and data science libraries as listed above. You might also want to set up a virtual environment to manage these dependencies.


## Citation
If you use the data, code, or methodologies of this project in your work, please cite the associated research paper.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Olubayode Ebenezer - Project Lead (olubayodeeben@gmail.com)
