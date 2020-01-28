# lending_club
This model is able to generate returns of 7.25% on heldout test data consisting of one year of the most recent complete loan data. Assuming a portfolio of 100 loans invested in, the model had 95% confidence interval returns of 7.25% +- 3.5%. This is compared to the test set average returns of only 1.7%!

[API-how_to:](https://github.com/Johnnyd113/lending_club/blob/master/API-how_to.ipynb) Brief overview of how you can use your api key to access lendingclub data.

Notebooks 1 to 7 take you thru each step to go from cleaning the data, training the model, evaluating on held out test data, and finally retraining on all data to predict returns on live loans

To get started, you need to download all historical loan data from https://www.lendingclub.com/info/download-data.action (you may need to create an account before you can download the data). Then follow along notebooks 1 thru 7 to build the model.
