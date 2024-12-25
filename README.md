
----------

# **Flight Price Predictor**

A Data Science project to predict flight prices and analyze key factors affecting them. This project was completed as part of my Data Science module and follows the seven stages of the Data Science Lifecycle.

----------
![enter image description here](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIeBSjx6rD5Kin06hAOOpD631g3lBaH3sXpg&s)
## **Project Overview**

Flight prices often fluctuate based on various factors such as the number of stops, airline, and departure time. This project aims to:

1.  Predict flight prices for journeys from **Dublin to Sydney**.
2.  Identify patterns and insights to help travelers find the best time to book cheap flights.

----------

## **Key Questions Answered**

1.  How do the number of stops impact the price of a flight?
2.  Is there a relationship between the airline (flight name) and the price of a flight?
3.  Does the month affect flight duration, and how does that influence the price?
4.  What is the effect of departure time on flight price?

----------

## **Data Science Lifecycle**

### **1. Business Understanding**

The problem was broken into clear, actionable questions to target practical insights for travelers and airlines.

### **2. Data Mining**

Data was scraped from **[Kayak.ie](https://kayak.ie)** between **November and January**, focusing on flights from Dublin to Sydney. The data was stored in a CSV file.

### **3. Data Cleaning**

-   Characterized variables as numerical or categorical.
-   Cleaned data by handling missing values and ensuring all variables were useful for further analysis.

### **4. Data Exploration**

-   Conducted **univariate**, **bivariate**, and **multivariate** analysis.
-   Explored relationships between predictor and response variables through visualizations.

### **5. Feature Engineering**

-   Removed unnecessary variables using a heatmap to identify correlations.
-   Converted categorical variables into numerical formats for modeling.

### **6. Predictive Modeling**

Built three different models:

1.  **Linear Regression**
2.  **Neural Network (1 hidden layer with 13 neurons)**
3.  **Neural Network (2 hidden layers with 13 neurons)**

**Data Split**:

-   Training: 60%
-   Validation: 20%
-   Testing: 20%

Evaluated each model and used the best-performing one for predictions.

### **7. Findings**

-   The models didn’t perform well overall but provided insights into the key factors affecting flight prices.
-   Detailed results for each question were documented.

----------

## **Technologies Used**

-   **Python**: For data analysis and modeling.
-   **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
-   **Tools**: Jupyter Notebook.

----------

## **How to Run**

1.  Clone this repository.
2.  Install the necessary Python libraries: 

    `pip install pandas numpy matplotlib seaborn scikit-learn` 
    
3.  Open the Jupyter Notebook and run the cells step-by-step.

----------

## **Learnings**

-   **Practical Applications of Data Science**: Applied the lifecycle to solve a real-world problem.
-   **Predictive Modeling**: Explored how different models work and their limitations.
-   **Feature Engineering**: Gained insights into the importance of cleaning and preparing data.

----------

### **Future Work**

-   Use a larger dataset to improve model performance.


----------
