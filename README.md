# Neural_Network_Charity_Analysis

## Overview of the analysis: 

With my background in machine learning and neural networks, I'll utilise the attributes in the dataset to assist Beks in developing a binary classifier that can predict whether applications would be successful if they are financed by Alphabet Soup. Beks got a CSV comprising more than 34,000 groups that have received financing from Alphabet Soup throughout the years from Alphabet Soup's business team. 

## Results: 

### What variable(s) are considered the target(s) for your model?

The "IS SUCCESSFUL" column is used as the model's aim. 

### What variable(s) are considered to be the features for your model?

The below variables are considered to be the features of the optimized model:

- APPLICATION_TYPE

- CLASSIFICATION

- AFFILIATION

- ORGANIZATION

- STATUS

- INCOME_AMT 

- ASK_AMT

### What variable(s) are neither targets nor features, and should be removed from the input data?

The below variables are neither targets nor features, and should be removed from the input data:

- EIN 

- NAME 

- USE_CASE

- SPECIAL CONSIDERATIONS

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

For my neural network, I chose the following neurons, layers, and activation functions. 

- Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

- Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

- Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs

In order to boost the predicted accuracy to 75%.  Initially, I just raised the number of neurons to test whether a simple solution would result in a higher degree of prediction accuracy, but the problem was not simple enough to be linearly separated, as was thought.As a result, in each successive effort, I decided to increase the layers, nodes, and epochs, based on the principle of "going for depth," which claims that "Empirically, more depth does tend to result in better generalisation for a wide range of tasks." 

### Were you able to achieve the target model performance?

I was unable to meet the 75 percent model performance goal in all my 3 attempts. 


### What steps did you take to try and increase model performance?

To improve the model's performance, I did the following steps:

- For all subsequent model setups, remove any extra features (noisy variables).

- Increase the number of layers

- Increase or reduce the number of neurons in the extra layers

Each effort may be broken down into the following categories 

- Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

- Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

- Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs


Below is a screenshots of **Attempt 3** code:

<img width="935" alt="image" src="https://github.com/Akin-Olusuyi/Neural_Network_Charity_Analysis/blob/main/Resources/Attempt%203%20Code.png">



## Summary:

- Attempt 1: Predictive Accuracy Percentage: 72% Loss Metric: 56%

- Attempt 2: Predictive Accuracy Percentage: 72% Loss Metric: 56%

- Attempt 3: Predictive Accuracy Percentage: 72% Loss Metric: 57%

## Recommendation: 

While none of these models attained a predicted accuracy of 75%, I would propose increasing the amount of hidden layers to add more depth in the model to tackle the categorization problem in future tries. Increasing the depth (layers) of the model would allow for a greater creation of predictability shapes and patterns; increasing the layers by a large margin may create an upper bound, from which I could fine tune the model by varying the number of nodes, or by decreasing the number of layers from the upper bound, using a trial-and-error method, to achieve a predictive accuracy of 75%.
