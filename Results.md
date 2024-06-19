The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
IS_SUCCESSFUL --> target for my model
What variable(s) are the features for your model?

What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model
EIN and NAME columns were dropped.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
10 for hidden_nodes_layer1
6 for hidden_nodes_layer2
I used these numbers after a few attempts, random guesses.
Were you able to achieve the target model performance?
No, unfortunately I was unable to acheive the 75 percent model accuracy target, my last attempt was 73 percent. 

What steps did you take in your attempts to increase model performance?
Adding layers and removing columns seemed to improve my accuracy rate. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The accuracy of the model was 73 percent in predicting the classification problem. A few recommendations include, Random Forest Model, in which they are good at capturing non-linear relationships in the data; they are less prone to overfitting compared to a single decision tree; lastly, they are an ensemble learning method that combines multiple decision trees to improve the overall performance. 