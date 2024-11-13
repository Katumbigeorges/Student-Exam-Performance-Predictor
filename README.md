# Predicting Student Performance Using Machine Learning

## Introduction

In today's educational landscape, understanding the factors that contribute to a student's academic performance is crucial for educators, parents, and policymakers. This project leverages machine learning techniques to predict a student's performance in mathematics based on various factors. By providing accurate predictions, this tool can help identify students who may need additional support and tailor educational strategies accordingly.

> Important Note: This project is developed for educational purposes only. The predictions should not be considered as definitive indicators for real-world academic decisions.

## Project Overview

The Student Exam Performance Predictor demonstrates the application of machine learning techniques in predicting student performance. The results are based on a specific dataset and machine learning model, showcasing the end-to-end process of developing a predictive model and providing insights into factors influencing student performance.

## Features

1. Predicts student performance in mathematics based on multiple factors:
   - Gender
   - Ethnicity
   - Parental level of education
   - Lunch type
   - Test preparation course
   - Previous exam scores

2. Provides detailed insights into how various factors influence academic performance
3. User-friendly interface for data input and prediction retrieval

## Dataset

The model is trained using the "Students Performance in Exams" dataset from Kaggle, which includes:
- Student demographic information
- Parental education details
- Lunch type categories
- Test preparation course participation
- Mathematics scores

## Model Training

The prediction model:
- Uses supervised learning algorithms (decision tree/random forest)
- Splits data into training and testing sets
- Evaluates performance through various metrics
- Predicts math scores based on input features

## Technology Stack

1. Python 3.7.0
2. Machine Learning Libraries
   - Scikit-learn
   - Pandas
   - Numpy
3. Web Framework
   - Flask
4. Frontend
   - HTML
   - CSS

## Installation Steps

1. Ensure Python 3.7.0 is installed on your system
2. Install required packages:
    bash
   python -m pip install --user -r requirements.txt
   
3. Run the application:
    bash
   python app.py
   

## Usage

1. Launch the application following the installation steps
2. Input student information through the web interface
3. Submit the form to receive performance predictions
4. Review the predicted results and factor influences

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For questions, feedback, or issues, please open an issue in this repository.

## License

This project is licensed under the MIT License.

---
⭐ If you find this project helpful, please consider giving it a star!