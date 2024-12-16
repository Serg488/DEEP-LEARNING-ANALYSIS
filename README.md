# DEEP-LEARNING-ANALYSIS
## Neural Network Analysis Report
Write an analysis that includes a title and multiple sections, labeled with headers and subheaders (4 points)
Format images in the report so that they display correction (2)
Explain the purpose of the analysis (4)
Answer all 6 questions in the results section (10)
Summarize the overall results of your model (4)
Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)
### Purpose
The purpose of this analysis is to create the best binary classifier that would be able to reach the highest accuracy in selecting the applicants who will be successful if funded by Alphabet Soup.

### Questions
What variable(s) are the target(s) for your model?
Variable targets in this model are "Application_type, Affiliation, Classification, Use_case, Organization, Status, Income_Amt, Special_Considerations, Ask_amt".

What variable(s) are the features for your model?
The vaiable feature for the model is "Is_Successful"

What variable(s) should be removed from the input data because they are neither targets nor features?
The variable "Name" and "EIN"

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I selected Number of neurons:
Input layer: num_input_features (number of input features)
Hidden layers: 4 layers, each with num_input_features neurons
Output layer: 1 neuron
Number of layers:
Total: 6 layers (4 hidden layers + 1 output layer)
Activation functions:
Hidden layers: 4 instances of ReLU activation
Output layer: 1 instance of Sigmoid activation

Were you able to achieve the target model performance?
Yes i was able to achieve a good target performance.

What steps did you take in your attempts to increase model performance?
Steps i took to increase the model's performance were adding more hidden layers and using 100 epochs.

### Overal Results
The results of the deep learning model analysis showed that the neural network is very accurate in determining the applicants with the best chance of success in their ventures if funded by Alphabet Soup. The model had a passing accuracy, over 75%.

## Credits 
For this analysis i used Xpertlearning assistant and my professor for help.