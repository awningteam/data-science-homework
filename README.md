# Awning Data Science Challenge
This is the assessment for Data Science roles at Awning.

The following exercise should be completed using `python`, but you are free to use any
packages you see fit. Expected completion time is 3-4 hours. This is not a limit, but 
rather a suggestion. Feel free to spend more time if you need it. 

## How to take assessment
1. Pull this repository down locally.
2. Train a model on the data provided in the `data` directory against 
the target variable `saleprice`.
    * The data is comprised of a time series of property sales and metadata about
      those real estate properties.
    * The model will be used to predict real estate property valuations based on
      their metadata and date.
    * `data_dictionary.xlsx` gives descriptions of the labels in `properties.csv`.
3. Store your model's output along with the code used to train it.
4. Provide a CLI that takes in a property and transaction file (same shapes as training data),
   and returns statistics on the goodness of your model's predictions.
   * The testing dataset is comprised of an additional 30 days of transactions from the end of the training set.
5. Answer the follow up questions listed below.

### Follow Up Questions
1. What insights can you learn about the dataset from your model?
2. What additional data would you like to incorporate into your model and why?
3. Explain how you would design a pipeline that leverages new property and transaction data. You can
 assume that property data will enter the pipeline before the associated valuation transaction does. What
 considerations would you take into account as the number of properties and transactions grows
 to a large N?
 
## Submission Instructions
Please email a zip of your repo `shri@awningcre.com` and `eli@awningcre.com`.
Send us a writeup for the follow up questions via a Google Drive link, Dropbox Paper link, 
or by letting us know where a Markdown file is located in your git repo.

## Evaluation
Your application should be able to be setup into a virtual environment on any Linux/Unix machine.
We will evaluate the exercise by looking at the result of your model on our testing dataset, 
your written responses, and the code itself.

## Coding at Awning
At Awning, we aim for writing simple, maintainable, and clean code.

We prefer simplicity over complexity.

We comment our code and commit often.

We encourage out of the box thinking and we love to be impressed!
