## Diabetes Detection using Machine Learning and Django
This is a web application that uses machine learning to predict whether a person has diabetes or not. It's built using Python, Django, and the Logistic Regression algorithm.

![first_page](https://github.com/user-attachments/assets/12b18746-557c-4c61-93a7-8244ac29c823)

## Usage
The web application allows users to input values for various health parameters such as glucose level, blood pressure, and BMI, and then predicts whether they have diabetes or not based on these inputs.

## To use the web application, follow these steps:
1. Enter the values for the health parameters on the web form.
2. Click the "Predict" button to submit the form.
3. The web application will display the prediction result as either "Positive" (indicating the presence of diabetes) or "Negative" (indicating the absence of diabetes).

![second_page](https://github.com/user-attachments/assets/9600049f-e93c-48a6-b6a3-3e229c4e3afc)

## How it Works
The machine learning model used by the web application is a Logistic Regression algorithm that's trained on a dataset of diabetes patients. The model takes in the values of various health parameters as input and predicts the likelihood of a person having diabetes based on these inputs.

The web application uses the Django web framework to build the user interface and handle user input. The inputs are then passed to the machine learning model, which makes the prediction and returns the result to the web application. The result is then displayed to the user on the web page.

## Credits
The machine learning model used in this project was trained on the Pima Indians Diabetes Dataset, which is publicly available on the UCI Machine Learning Repository.


