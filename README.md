# KNOVAK-Deep-Learning-Challenge-21

Hello,

Thank you for taking the time to review my Deep Learning Challenge 21!

Please review my code and results from my first run by opening the First Run_starter code_first HDF5 folder. There you will find the AlphabetSoupCharity_StarterCode.ipynb file and the file created via that code AlphabetSoupCharity.h5 that showcases the first results from the first training of the model.

The folder labeled Initial Starter Code is where you can find the initial ipynb file used to complete this assignment.

Opt Run .ipynbs folder contains the .ipynb code used for each optimization of the model. Whereas the folder labeled Optimalizations is where you can find each HDF5 file from each optimization of the model. Please note that you will most likely need to use Google Collab to run code and view the HDF5 Results files. Reviewing the code for each Opt run should still have the results saved.

Below you can find my Neural Network Model Analysis with answers to the questions provided. You can also find this document in the folder labeled Model Analysis.

Please reach out if you should have any questions and thank you again for reviewing my work.

Cheers,
Kyle

# Alphabet Soup Charity
# Neural Network Model Analysis

## Purpose of this Analysis:
- Our goal for this analysis is to share our findings when using machine learning and neural networks to help the not for profit foundation, Alphabet Soup.
- In order to help Alphabet Soup with their problem of finding applicants that will be of great success in their ventures, we created a binary classifier from the data provided to help predict if an applicant would be successful if they were backed by Alphabet Soup. 

## Questions and Answers

1.) What variables are the targets for your model?

- The target was the “IS_SUCCESSFUL” column since that is what our goal was to find.

2.) What variables are the features for your model?

- The features of our model were "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" (Basically everything but “IS_SUCCESSFUL)”

3.) What variables should be removed from the input data because they are neither targets nor features?

- I removed the variables EIN and NAME as they didn’t pose as target nor feature.

4.) How many neurons, layers, and activation functions did you select for your neural network model and why?

 For my first run I had 2 hidden nodes, which had 30 and 50 neurons. The target model performance was roughly 72.37 percent accurate

- The second run had 3 hidden nodes, which had 15, 25, and 25 neurons. The target model performance was about 72.7 percent accuracy

- My third run had 3 hidden nodes, which had 10, 20, and 20 neurons. The target model performance was similar to the last one with 72.7 percent accuracy

5.) Were you able to achieve the target model performance?

- I was not able to achieve the target model performance of 75%

6.) What steps did you take in your attempts to increase model performance?

- Lowering my neuron count and adding layers. Looking back I should've tried toying with the model by adding more layers but with low neuron counts. Maybe decrease the amount 
 
## Summary:
In order for us to achieve greater accuracy for determining if an applicant would be successful, we must consider other models.
We can also attempt a better clean up process to help increase the models performance.
If I were to use a different model it would be one with different functions that could bring greater accuracy.
