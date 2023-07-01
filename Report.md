# Report
### Overview of Analysis 
Explain the purpose of this analysis.

- The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup, that can help it select applicants for funding with the best chance of success in their ventures. 

### Results: Using bulleted lists and images to support your answers, address the following questions:

**Data Preprocessing**

What variable(s) are the target(s) for your model?
- The target for this model is X, or all of the columns in the new_application_df, excluding the "IS_SUCCESSFUL" column.
  
What variable(s) are the features for your model?
- The feature for this model is the y, or the "IS_SUCCESSFUL" colunn in the new_application_df.
  
<img width="1675" alt="Screenshot 2023-06-30 at 9 46 13 PM" src="https://github.com/margaretkhendre/Nonprofit-Funding-vs-Deep-Learning-Challenge-/assets/121995835/23d633de-b256-43cd-8870-50b888274b3a">

What variable(s) should be removed from the input data because they are neither targets nor features?
- The X_train_scaled variable should be removed
  
  <img width="785" alt="Screenshot 2023-06-30 at 9 53 00 PM" src="https://github.com/margaretkhendre/Nonprofit-Funding-vs-Deep-Learning-Challenge-/assets/121995835/3f097dcb-3cd7-4ab6-a23a-da200c67aff2">

**Compiling, Training, and Evaluating the Model**

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - A sequential model with 3 layers (First Hidden, Second Hidden, and Output layer), 'relu' actvation functions for each, and 80, 30, and 1 units, respectively. 
- Were you able to achieve the target model performance?
- What steps did you take in your attempts to increase model performance?
  
###Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
