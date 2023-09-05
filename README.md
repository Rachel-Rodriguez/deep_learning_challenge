# deep_learning_challenge


![download](https://github.com/Rachel-Rodriguez/deep_learning_challenge/assets/124642442/84466f98-e6fc-41c6-bcf2-a954d28e2cbd)


# Overview of the analysis
The purpose of this analysis is to develop a machine learning model that predicts the success of organizations applying for funding from Alphabet Soup, a nonprofit foundation. By doing so, it aims to improve the efficiency of funding decisions, enhance decision-making processes, and streamline the application process, ultimately enabling Alphabet Soup to allocate resources more effectively and make a greater impact through its philanthropic efforts.

# Results
    Data Preprocessing
  *  Target variable for this model: 
  
 -IS_SUCESSFUL 

  *  Feature variables for this model were:
  
  -APPLICATION_TYPE
  
  -AFFILIATION
  
  -CLASSIFICATION
  
  -USE_CASE
  
  -ORGANIZATION
  
  -STATUS
  
  -INCOME_AMT
  
  -SPECIAL_CONSIDERATIONS
  
  -ASK_AMT

  *  Variable that were removed: 
 
  -EIN
 
  -NAME
  

    Compiling, Training, and Evaluating the Model
    
  * MODEL 1:
    The initial model consisted of two layers: the first layer with 80 neurons and the second layer with 30 neurons. I employed a combination of activation functions, starting with ReLU for the hidden layers and sigmoid for the output layer. The model was trained for 100 epochs.
* MODEL 2:
      The second model featured three hidden layers: the first with 120 neurons, the second with 80 neurons, and the last with 30 neurons. I applied a combination of activation functions, starting with ReLU, followed by Tanh, and then ReLU again. The output layer utilized the sigmoid activation function, and the model was trained for 100 epochs.
* MODEL 3:
    The final model incorporated four hidden layers, with the following configurations: the first layer with 300 neurons, the second with 100 neurons, the third with 50 neurons, and the fourth with 30 neurons. I implemented a combination of activation functions, commencing with ReLU, followed by Tanh, and concluded with ReLU for the last two layers. The output layer utilized the sigmoid activation function, and the model underwent training for 100 epochs.
    
# Summary
All three models fell short of achieving a 75% accuracy threshold. In the first model, despite a loss of 55%, I achieved an accuracy of 72.5%. For the second model, I introduced additional hidden layers in an attempt to boost accuracy; however, it resulted in a loss of 56.7% and an accuracy of 72.7%. The last model, in which I added more hidden layers and significantly increased the number of neurons, failed to deliver the desired accuracy improvement, resulting in a loss of 56% and an accuracy of 72.8%
