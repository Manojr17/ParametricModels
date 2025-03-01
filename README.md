What is a Parametric Model?

 * A parametric model is a type of model in machine learning and statistics that is defined by a fixed number of parameters. 
 *These parameters summarize the data and allow the model to make predictions.

Key Characteristics of Parametric Models:

     1)Fixed Number of Parameters:
             -The complexity of the model does not change with the size of the dataset.
             -Example: A linear regression model with 2 parameters (slope and intercept) remains the same regardless of the number of data points.
     2)Simpler and Faster to Train:
            -Since parametric models have a predetermined structure, they usually require less computational power.
     3)Assumptions About Data:
             -Parametric models assume a specific form of the data distribution (e.g., normal distribution, linear relationship).
     4)Easier to Interpret:
              -Because they have fewer parameters, parametric models are more interpretable compared to non-parametric models.
What is Linear Regression?

      *Linear Regression is a supervised learning algorithm used for predicting a continuous value based on input features.
       *It assumes a linear relationship between the independent variable(s) (input) and the dependent variable (output).

Example:

       i)Predicting House Prices:
                -Given features like square footage, number of rooms, and location, linear regression can predict the price of a house.
       ii)Predicting Sales:
                -Based on past sales data, a company can predict future sales trends.

What is Multiple Regression?

           -Multiple Regression (also called Multiple Linear Regression) is an extension of Simple Linear Regression where there are multiple independent variables
           (features) used to predict a single dependent variable (target).

          -It is used when the output depends on multiple factors instead of just one.

Example of Multiple Regression:

       -Scenario: Predicting House Prices
        Suppose we want to predict house prices based on:

           *Square Footage (x1)
          *Number of Bedrooms (x2)
          *Distance to City Center (x3)

What is Polynomial Regression?

         -Polynomial Regression is an extension of Linear Regression where the relationship between the independent variable(s) and the dependent variable is non-linear
         -Instead of fitting a straight line, it fits a curved polynomial equation to the data.

When to Use Polynomial Regression?

        -When data is not well represented by a straight line.
        -When the relationship between variables follows a curve rather than a linear trend.

Example:

    Why Use Polynomial Regression?
    Scenario: Predicting Salary Based on Experience
    Suppose we have the following data on years of experience vs. salary:
