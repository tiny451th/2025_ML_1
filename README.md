## Term project 1 of Maching Learning 2025-1

In this project, you will train regression models to predict KOSPI. 

## Datasets
The [training dataset](data/kospi_train.csv) has KOSPI from 2019 to 2022. The [test dataset](data/kospi_test.csv) has KOSPI in 2023. See [load_data.ipynb](load_data.ipynb) to load the datasets.

## Part 1. Predict KOSPI of the next day. 

Train regression models to predict the next day's `close` using `Open`, `Low`, `High`, `Close`, `Volume` of previous days as predictors using *only* the training dataset. Cross-validate to select the best model. Evaluate the accuracy of your model using the test dataset.


## Part 2. Use more predictors to improve your model.
Extend the regression model by adding some extra predictors of your choice. You can use any statistics publicly available. 

## Report template
* Report must be a pdf file with filename `YOUR_STUDENT_ID.pdf`
* Summary (maximum 250 words): provide a brief overview, the problem statement, methodology, findings, and conclusions
* Introduction: provide background, define the problem, and state your objectives
* Methods: provide technical details (preproprocessing data, models used, details of experiments, how to analyze the results). Include the link to your `GitHub repository`. If you want to keep yor repository private, invite `ssuai` as a collaborator.
* Results: present findings (Use graphs or tables!)
* Discussion: interpret your findings and discuss implications
* Conclusion: summarize main findings, provide the main message, discuss future directions
* References: list of all the sources cited in the report
