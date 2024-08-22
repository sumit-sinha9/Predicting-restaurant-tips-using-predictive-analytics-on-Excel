# Predicting restaurant tips using predictive analytics on Excel

I have used Regression Analysis for the prediction of tips.

The dependent variable to be predicted was tips and independent variables which may impact the tips prediction were sex, smoker, day, time, size and total bill.

Data cleaning was done for checking missing values,duplicate values etc. (Luckily the data was already clean).

I started by plotting graphs to observe any correlation.

Size and total_bill showed a positive correlation with the tips.
It was unclear to conclude if sex, smoker, day, time impact tips based on the graphs.

Getting data ready for the multi linear regression.
The categorical variables were converted to dummy(numeric) variables.

Multi linear regression were performed using the data analysis toolpak.

sex, smoker, day, time were excluded from the analysis as their p value was larger than 5% which could be explained by randomness.

Multi linear regression was performed again on the independent variables(size and total_bill) with p value less or close to 5%.

Prediction calculator was built to calculate tips based on size and total_bill.

Predicted Tips= intercept +(coefficient of size * size) + (coefficient of total_bill* total_bill) 

Y=Constant +B1*(X1)+B2*(X2)+....BnXn.

Root mean square error was calculated which could be used to evaluate the quality of predictions.
