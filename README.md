# Predicting Chicago Housing Prices to teach Linear and Logistic Regression (Modeling):

This repository houses the data and jupyter notebooks associated with a revision to Data Science pedagogy at UC Berkeley. Taking Cook County, IL housing sales data, we ask students to predict housing prices on a test data set using both linear and logistic regression models. As part of this process, we also include critical lines of questioning that consider the nature of the given data and associate current housing data with the history of redlining in Chicago, IL.

This project is intended to change Homework 5 and 6 in UC Berkeley's intermediate Data Science course, Data Science 100. Many questions have been adapted from previous homework versions.

# Using the Cook County Assesor's Office open dataset:

Historically, the course had used a cleaned dataset of housing prices and characteristic from Ames, Iowa that is popularly used to teach linear and logistic regression. While this dataset does work well for education purposes, our team wanted to explore other datasets that were less clean and reflected a more realistic view of data in the world.

We found a new dataset, published in September 2019, that reflected one year's worth of housing data collected by the Cook County Assessor's Office (CCAO) on a triannual basis (for the first year, this is only the Northern suburbs outside of Chicago). This dataset had close to 80 unique features, so it had potential to allow for a fairly accurate model to be trained on it. What made this dataset even more interesting was that this dataset was actually used to train a model which to the Cook County Assessor's Office, under the supervision of Fritz Kaegi, actually deploys on houses and predicts housing value from. These predictions are assigned as the adjusted housing value for that year, and determine the property tax for the houses' owner(s).

[Access to their model (in R) can be found here](https://gitlab.com/ccao-data-science---modeling). Given that the data is publically accessible, the Cook County Assessor has solicited community member's input on the quality of the model. This effort includes soliciting comment on how their model may or may not reinforce biases that have been identified by many critics of the Cook County Assessors Office. This is a huge change from the previous practice of the Cook County Assessor's Office, which assigned house values manually with a team of assessors making decisions with little or no possible public oversight.

If you are interested in reading more about how this initiative is being presented by the CCAO, [you can read their Medium article](https://medium.com/@AssessorCook/why-the-cook-county-assessors-office-made-its-residential-assessment-code-and-data-public-c964acfa7b0f).

You can read more about the context of this data set from the [Cook Cook Assessor's Office Data Narrative](https://datacatalog.cookcountyil.gov/stories/s/Cook-County-Assessor-Valuation-Data-Release/p2kt-hk36).

# The Human Contexts and Ethics Approach:

This new dataset opened up many pedagogical options. First, because the dataset has real import, we challenged students to engage with the stakes of the model. For example: What does this data represent? What does error mean in this context? Would you be comfortable using the model you created to actually assign people taxes? After giving students the context around the numerous and ongoing civil rights lawsuits against the Cook County Assessor's Office we can ask them: How might this model be more effective than traditional approaches to assigning housing value? 

Second, the dataset also asked students to engage with what their role as a data scientist includes. By getting at the stakes of this particular case, we can show students that what they do cleaning, manipulating, and analyzing a dataset has a demonstrable impact. We will ask students to compare the models they make with the one the CCAO uses, and talk about the differences. Moreover, the CCAO has touted their model as a prime example of transparency and good governance. By publishing their training data and their model, they ask journalists, data scientists, and regular citizens to criticize them, and make them better. While many data scientists may feel that their work does not directly affect livelihoods, this homework provides an example to the contrary, and openly engages with questions of 'black boxing' and 'white boxing' that are often talked about.
