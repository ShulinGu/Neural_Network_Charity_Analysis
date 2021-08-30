# Neural_Network_Charity_Analysis
## Overview of the analysis:
  - The purpose of this analysis is to use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Results:
  - Data Processing
    - "IS_SUSCESSFUL" is considered the target value of the model
    - Features are individual independent variables that act as the input in the system. Thus we use the rest column values in the merged table as the features
    - The non-beneficial ID columns, 'EIN' and 'NAME' are dropped since they are neither targets nor features
  - Compiling, Training, and Evaluating the Model
    - There are 81 neurons. 
    - There are 2 layers.  
    - Relu and Sigmoid function are used.
    - ![image](https://user-images.githubusercontent.com/82785321/131382626-74edddba-d567-44f4-8a27-ab6d41c6c642.png)
    - The accuracy is 0.7257, which did not reach the target model performance.
    - ![image](https://user-images.githubusercontent.com/82785321/131382562-e12f67ce-64ea-4fb9-a34f-5649d7441f4e.png)
    - Additional layer and neurons are added to increase the performance.
    - ![image](https://user-images.githubusercontent.com/82785321/131383049-e8fd53dd-ee2b-47f9-be58-fc88596f43ed.png)
    - Changing the activation function did not increase the accuracy of the model.
    - The accyract us 0.7256. Which is worse and still have not reached the target accuracy of the model.
    - ![image](https://user-images.githubusercontent.com/82785321/131383167-c2965b38-b3f4-4c2d-8e5a-7a16877f6ae6.png)
## Summary:
  - The first model we use did not reach the targe model performace. After we tried increase the number of layers and neurons, and change the activation function, the performace get worse. It is recommend to check the binning values and regroup. The reprocessed data in the training and testing datasets will change and the results might improved.
