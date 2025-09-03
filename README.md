# Risk Calculator Documentation

## Introduction
The Risk Calculator is a web application designed to assess various risks based on user input data. It calculates risks across different categories such as educational challenges, social environmental risks, lifestyle, transportation risk, technology access risk, food security, housing challenges, climate risk, disease risk, financial risk, and healthcare access risk.

## Code Structure
The code consists of several parts:

### Imports
Import necessary libraries and modules such as Streamlit, Altair, pandas, etc.

### Page Configuration
Sets the page layout and background color for the Streamlit app.

### Main Function
Defines the main functionality of the Streamlit application, including user interface and risk calculation.

### Risk Calculation Function
Defines the logic for calculating risks based on user inputs.

### Display Risks Function
Displays the calculated risks along with suggested actions and services.

### Utility Functions
Includes helper functions for generating donut charts and retrieving life expectancy and health data.

## Key Components
- **User Interface:** The user interface allows users to input their details such as zip code, age, address, income, gender, race, veteran status, and education through input fields and dropdown menus.
  
- **Risk Calculation:** Once the user inputs their details and clicks on the "Calculate Risks" button, the application calculates risks across various categories using the provided inputs.

- **Display of Risks:** The calculated risks are displayed in a structured manner, organized into categories. Each category of risk is represented with an icon, risk level indicator, and corresponding actions and services.

- **Suggested Actions and Services:** For each category of risk, the application suggests relevant actions and services that the user can take to mitigate those risks. These suggestions are displayed in expandable sections along with the respective risk categories.

- **Life Expectancy and Disease Risks:** The application also provides information on life expectancy risks based on the user's zip code and highlights any major health risks associated with the provided data.

## Conclusion
The Risk Calculator application provides users with a comprehensive assessment of various risks based on their input data, along with actionable insights to address those risks effectively. The intuitive user interface and informative display of risks make it a valuable tool for individuals seeking to understand and manage their risks better.

## To run the UI Interface on your local machine, run the following commands in your project's root directory. Use a stable internet connection while running the script
- ```
  streamlit run app.py
  
```
Dataset - https://drive.google.com/uc?export=download&id=1jzlP6_LitBiZrlGYguLx95n16cgJIRor


