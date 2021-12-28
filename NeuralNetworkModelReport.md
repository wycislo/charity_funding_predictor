The performance of the deep learning model created for AlphabetSoup. 



12/28/2021 

Henry Wycislo

The report should contain the following:

1. **Overview** of the analysis: Deep learning and neural networks were used to predict whether or not applicants for funding by Alphabet Soup will be successful.
2. **Results**: 

- Data Preprocessing

  - What variable(s) are considered the target(s) for your model?
    - Application_Type and classification were the target vairable for this model. 
  - What variable(s) are considered to be the features for your model?
    - The is_successful data is the target feature for this model. 
  - What variable(s) are neither targets nor features, and should be removed from the input data?
    - EIN, Name

- Compiling, Training, and Evaluating the Model

  - How many neurons, layers, and activation functions did you select for your neural network model, and why?

    - This study used three layers. (two hidden layers and one output layer). 

    ![image-20211228124313058](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228124313058.png)

     

  - Were you able to achieve the target model performance? Not on the first try. The accuracy = 73% but we need to be above 75%. 

  

  ![image-20211228124426732](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228124426732.png)

  

  I added 'NAME' back into the dataset only to get a lower accuracy.

  

  ![image-20211228130256014](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228130256014.png)

  

  The third time, I added EIN and NAME back to the dataset just to see what happens. It had no effect. 

  

  ![image-20211228155748295](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228155748295.png)

  

  The fourth time I changed both hidden models to sigmoid

  

  ![image-20211228161622932](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228161622932.png)

  

  That had no affect on the end result.. 

  

  ![image-20211228161929977](/Users/henrywycislo/Library/Application Support/typora-user-images/image-20211228161929977.png)

  

  