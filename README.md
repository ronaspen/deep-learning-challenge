# deep-learning-challenge

Repo: 
Starter_Code1.ipynb is the code for the first model, and AlphabetSoupCharity_Optimisation.ipynb is the code for the second model.

Purpose of the Analysis is to see what changes we made to create a binary classifier that can predict whether the applicants would be successful if funded by Alphabet Soup.



I preprocessed the data by:

Dropping non-necessary columns EIN and NAME,
For the columns APPLICATION_TYPE and CLASSIFICATION, choosing a cutoff point to bin the rarer values into a new value called "Other",
Dividing data into a target array (IS_SUCCESSFUL) and features arrays,
Applying train_test_split,
And scaling both the training and testing data with StandardScaler.
and finally, using StandardScaler to scale the training and testing sets

Compiling, Training, and Evaluating the Model

ATTEMPT 1

Hyperparameters used:

layers: 2
layer 1: 8 neurons : activation function = ‘relu’
layer 2: 5 neurons : activation function = ‘relu'
epochs: 100
Accuracy: 0.7245481014251709

ATTEMPT 2
Hyperparameters used:

layers: 3
layer 1: 10 neurons : activation function = ‘relu’
layer 2: 8 neurons : activation function = ‘sigmoid'
layer 3: 6 neurons : activation function = 'sigmoid

Also, I didn't drop the 'NAME' column for attempt 2, rather I created a cut off for rarer names and binned it as 'Other'.
epochs: 50
Accuracy: 0.758950412273407

Summary:
I am very pleased to report that I was able to achieve a model that scored over 75% accuracy. In my opinion, the including of name proved a crucial difference, as name seemed to be 
a factor that determined venture success. Also, adding another layer, adding more neurons on each layer, and changing the last 2 functions to 'sigmoid'. 
