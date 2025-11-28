This project implements a simple linear regression model from scratch to predict median house values in California based on median income data on google colab.
The implementation includes data preprocessing, gradient descent optimization, and visualization of results. Here I have used learning rate(alpha) = 0.1 and iteration = 3000 for final 
weight(w) and bias(b)

Datasets that has been used:
Source: California Housing Dataset from sklearn.datasets
Features: Median Income (MedInc) as the independent variable
Target: Median House Value (MedHouseVal) as the dependent variable
Samples: 20,640 housing districts

Core functions used:
compute_dw_db(): Computes gradients for weights and bias
compute_j_wb(): Calculates cost function (Mean Squared Error)
compute_final_w_b(): Performs gradient descent optimization

Visulaization:
1. Convex cost function vs w
   This plot visualizes the shape of the cost function when we vary w while keeping b constant.The cost curve forms a U-shaped parabola, proving that the mean squared error cost function is convex with respect to 
𝑤. The minimum point corresponds to wfinal.

2. Best-fitted line for visualization
   The plot shows how a trained linear regression fits the data.The scatter plot contains the actual data points, and the red line represents the predicted values using the learned parameters 
   w and b.This shows that a positive relation between the feature(median income) and target(housing price) which means model captire upward trend in the given data and learned well for the given data.

Run the Google Colab notebook sequentially to:
1.Load and preprocess the California housing data
2.Implement gradient descent for linear regression
3.Visualize the cost function and regression results
4.Analyze the model's performance



