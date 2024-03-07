# deep-learning-challenge

Purpose of the Analysis is to see what changes we made to create a binary classifier that can predict whether the applicants would be successful if funded by Alphabet Soup.



I preprocessed the data by:

Dropping non-necessary columns EIN and NAME,
For the columns APPLICATION_TYPE and CLASSIFICATION, choosing a cutoff point to bin the rarer values into a new value called "Other",
Dividing data into a target array (IS_SUCCESSFUL) and features arrays,
Applying train_test_split,
And scaling both the training and testing data with StandardScaler.
and finally, using StandardScaler to scale the training and testing sets

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarise the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
