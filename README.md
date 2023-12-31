

# Diabetes Prediction using Logistic Regression



This project is a web application that predicts whether an individual is likely to have diabetes or not based on certain health-related features. We've implemented a logistic regression model and deployed it using Flask. Users can interact with the model through a user-friendly web interface.

## Table of Contents

- [Demo](#demo)
- [Logistic Regression](#logistic-regression)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo

![Demo](/images/demo.gif)

Check out the live demo [here](https://your-demo-link.com).

## Logistic Regression

Logistic Regression is a statistical method used for binary classification problems, such as predicting whether a patient has a disease (1) or not (0) based on one or more predictor variables (features). In this project, Logistic Regression is used as the predictive model.

### How Logistic Regression Works

Logistic Regression works by modeling the probability of the binary outcome using a logistic function. It takes a linear combination of the predictor variables and applies the logistic function to it. The logistic function maps any real-valued number into a value between 0 and 1, representing the probability of the positive class. The model is trained to optimize its coefficients so that it best fits the training data.

### Logistic Regression in the Project

In this project, we've trained a Logistic Regression model using a dataset of health-related features such as glucose levels, BMI, and age. The model has learned to predict the likelihood of a patient having diabetes based on these features.

## Technologies Used

- Python
- Flask
- HTML
- CSS

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com//diabetes-prediction.git
   ```

2. Change into the project directory:

   ```bash
   cd diabetes-prediction
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the Flask app:

   ```bash
   python app.py
   ```

7. Open your web browser and go to `http://localhost:5000` to access the application.

## Usage

1. Fill in the required health-related information on the web page.
2. Click the "Predict" button to get the prediction result.
3. The result will be displayed on the page, indicating whether the individual is likely to have diabetes or not.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push your changes to your fork: `git push origin feature/your-feature-name`
5. Create a pull request to the main repository.

## License

This project is licensed under the [MIT License](LICENSE).

-
