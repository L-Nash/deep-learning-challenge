# deep-learning-challenge

## Overview
In this challenge, I used date from a non-profit organization, Alphabet Soup, which provides funding for various ventures. The task was to build a model to predict which applicatnts would be the most succsessful. 

## Results

    ### Data Preprocessing:
    I used the IS_SUCCESSFUL column as the target for my model, the remaining cloumns were the features. There were a couple of columns that needed to be removed because the didn't work as targets or features and those were EIN and Name.

    ### Compiling, Training, and Evaluating the Model

    I intially had three layers: the inital layer, one hidden layer an the output layer.  I chose to use Relu and Sigmoid because they both work well with classification models. But, I used sigmoid in the final layer becasue its the most complex of the two and it's best practice to add it at the end so it doesn't overpower the others. I started with 80 neurons in the first layer and reduced from there because the dataset is large and complicated. 

    When I optimized the data I added neurons to the first two layers, increased epochs and removed some outliers in the Ask_Amount column.  I also experimented with changing the activation functions


## Summary
Overall, I was able to slightly improved the accuracy of the model. I think that a logistic regression model might be another option for predicting if an applicant will be successful.