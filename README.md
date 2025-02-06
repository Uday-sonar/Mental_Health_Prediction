# Mental Health Condition Prediction

This repository contains a machine learning project for predicting mental health conditions based on user-provided symptoms and other features. The project uses a dataset with 15 features to train and compare models, demonstrating how machine learning can assist in identifying potential mental health issues.

## Project Overview
The goal of this project is to develop a multi-class classification system that predicts whether an individual may require mental health treatment based on various personal and behavioral attributes. The repository includes:

1. **Data Preprocessing**: Label encoding for categorical variables and dataset splitting.
2. **Model Training**: Training and evaluation of Logistic Regression and Random Forest models.
3. **Model Comparison**: Metrics like accuracy, precision, recall, and F1-score are used to determine the better-performing model.
4. **User Input Prediction**: An interactive interface for users to input their symptoms and receive predictions.

## Dataset
The dataset contains 15 features:
- `gender`: Gender of the individual
- `country`: Country of residence
- `occupation`: Occupation type
- `self_employed`: Whether the individual is self-employed
- `family_history`: Family history of mental illness
- `treatment`: Target variable indicating if treatment is needed
- `days_indoors`: Time spent indoors
- `growing_stress`: Experience of growing stress
- `changes_habits`: Noticing changes in habits
- `mental_health_history`: Past mental health issues
- `mood_swings`: Experience of mood swings
- `coping_struggles`: Struggles to cope with daily tasks
- `work_interest`: Losing interest in work
- `social_weakness`: Feeling socially weak or isolated
- `mental_health_interview`: Discussing mental health in interviews
- `care_options`: Awareness of available mental health care options


## Installation and Usage

### Prerequisites
- Python 3.8 or higher
- Required libraries: `numpy`, `pandas`, `scikit-learn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mental-health-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mental-health-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
31. Run the entire interface:
   ```bash
   python Mental_Health_Prediction.py
   ```

## Model Comparison
The project compares two models:
- **Logistic Regression**: A simple linear model.
- **Random Forest**: An ensemble method using decision trees.

### Results
- Random Forest outperformed Logistic Regression in terms of accuracy and F1-score.
- The final model is Random Forest, which is used for predictions in the `predictor.py` script.

## Features and Functionality
- **Interactive User Input**: Users can answer questions corresponding to the dataset's features.
- **Prediction and Confidence Scores**: The model predicts the mental health condition and provides confidence levels.

## Example Input and Output
**Input**:
- Gender: Male
- Family History: Yes
- Growing Stress: Yes
- Mood Swings: Yes
- Coping Struggles: No and more..

**Output**:
- Predicted Condition: Likely to need treatment (1)
- Confidence: 85%

## Future Enhancements
- Expand the dataset to include more diverse features.
- Implement a web-based UI for easier user interaction.
- Integrate other machine learning models for improved performance.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The dataset used in this project.
- Inspiration from real-world mental health studies.

---

Feel free to explore the repository and adapt it for your use cases. Thank you for your interest in this project!

