# JPMorgan-finance-data

This repository contains code for the J P Morgan financial data analysis virtual internship offered by Forage.

In teh first part, future gas prices are forecased.  A function takes in as input dates within a range defined
by training and predicted data.  Prediction and interpolation are used to find the price for any date given
data points for end of month.
In the next part, option prices are modeled from gas price.
In the third part, default is predicted from given loan data.  Then credit scores are split into meaningful bins
by optimizing log likelihood.
