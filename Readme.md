BMI Calculator

This project is a simple Body Mass Index (BMI) calculator written in Python.
It allows users to input their weight and height, calculates their BMI, and provides tailored health tips based on the result.

Features

Accepts user input for weight (kg) and height (cm)

Validates input to ensure values are positive numbers

Calculates BMI using the standard formula

Categorizes BMI into:

Underweight

Healthy weight

Overweight

Obesity Class I

Obesity Class II

Obesity Class III

Provides health tips depending on the BMI category

Handles invalid input gracefully


📂 Code Overview
get_health_tip(bmi)

A function that:

Takes a BMI value

Determines the user’s BMI category

Returns category-specific health advice

bmi_calculator()

A function that:

Prompts the user for weight and height

Validates the input

Computes BMI

Prints the BMI and the health guidance

Handles errors such as non-numeric input