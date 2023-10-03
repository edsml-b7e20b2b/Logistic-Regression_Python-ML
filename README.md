# Logistic Regression Project

This project involves building a logistic regression model to predict whether or not a particular internet user will click on an advertisement based on various features.

## Data Description

The dataset contains the following features:

- 'Daily Time Spent on Site': consumer time on site in minutes
- 'Age': customer age in years
- 'Area Income': Average income of the geographical area of the consumer
- 'Daily Internet Usage': Average minutes a day consumer is on the internet
- 'Ad Topic Line': Headline of the advertisement
- 'City': City of the consumer
- 'Male': Whether or not the consumer is male
- 'Country': Country of the consumer
- 'Timestamp': Time at which the consumer clicked on Ad or closed the window
- 'Clicked on Ad': Binary indicator (0 or 1) representing clicking on the Ad

## Libraries Used

- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Getting Started

To run this project, you will need to have Python installed on your system. Additionally, make sure you have the necessary libraries installed, which are listed in the previous section.

## Data Exploration

- Explored the dataset using histograms, joint plots, and pair plots to understand the relationships between different features.

## Logistic Regression

- Performed a train-test split to prepare the data for training the logistic regression model.
- Selected relevant features ('Daily Time Spent on Site', 'Age', 'Area Income', 'Daily Internet Usage', 'Male') for training the model.
- Trained a logistic regression model using scikit-learn.

## Model Evaluation

- Predicted values for the testing data.
- Generated a classification report and a confusion matrix to evaluate the performance of the model.

## Conclusion

The logistic regression model showed promising results in predicting whether a user will click on an advertisement. Further fine-tuning and feature engineering could potentially improve the model's performance.

Feel free to reach out if you have any questions or suggestions!

## Author

[Barin Odusi](https://github.com/edsml-b7e20b2b/)

## Acknowledgments

- This project was inspired by the need to understand user behavior with online advertisements.

