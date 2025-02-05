# Loan-Status-Prediction-Project

## Overview
Loan Status Prediction is a machine learning project that predicts whether a loan applicant is likely to be approved or rejected based on given input features. This project utilizes **Machine Learning (ML)** techniques, specifically **Support Vector Machine (SVM)**, and leverages **Python** along with **Seaborn** for data visualization.

## Technologies Used
- **Python**: Programming language for data processing and model implementation.
- **Machine Learning**: Used to build a predictive model for loan status classification.
- **Support Vector Machine (SVM)**: A classification algorithm applied to predict loan approval status.
- **Seaborn**: Used for effective data visualization and analysis.

## Dataset
The dataset used for this project contains multiple features such as:
- Applicant Income
- Loan Amount
- Credit History
- Employment Status
- Marital Status
- Loan Purpose
- And other relevant financial and demographic attributes

## Project Structure
```
Loan_Status_Prediction/
│-- data/                     # Contains the dataset files
│-- notebooks/                 # Jupyter Notebooks for exploratory data analysis (EDA) and model training
│-- src/                       # Source code for data preprocessing and model training
│   │-- data_preprocessing.py  # Data cleaning and transformation
│   │-- model_training.py      # Model building and evaluation
│   │-- visualization.py       # Data visualization using Seaborn
│-- README.md                  # Project documentation (this file)
│-- requirements.txt           # Required Python libraries
│-- main.py                    # Script to run the model
```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Loan_Status_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Loan_Status_Prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script to execute the prediction model:
   ```bash
   python main.py
   ```

## Usage
- Load the dataset and preprocess it using `data_preprocessing.py`.
- Perform Exploratory Data Analysis (EDA) using `visualization.py`.
- Train the SVM model using `model_training.py`.
- Predict loan status for new applicants using the trained model.

## Results & Visualization
- The project includes various **data visualizations** created with **Seaborn**, such as:
  - Correlation heatmaps
  - Distribution plots of loan-related features
  - Box plots for outlier detection
- The trained **SVM model** classifies loan applications into **approved** or **rejected** categories with optimal accuracy.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Author
**Ariz Iqbal**  
GitHub: [Aiiqbal1881](https://github.com/Aiiqbal1881)

