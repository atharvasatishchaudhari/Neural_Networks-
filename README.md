# First_Model
This repository will contain all the three modules of the assignment 7

MODULE-1
          ##TARGET##
1) Write the basic code
2) Set Transforms, Normalize the dataset by looking at the mean, median of the dataset
3) Check whether the CUDA is available for calculation of the parameters
4) Write down the basic skeleton of the Neural Network model
5) Use the BatchNormalization to increase the accuracy

        ##RESULTS##
1) Parameters are 10,970
2) Best Training Accuracy: 99.94%
3) Best Testing Accuracy:  99.32%


      ##ANALYSIS##
1) The model is using a lot of parameters, hence the model is very heavy
2) Training accuracy is greater than testing accuracy and also the difference between two is large, hence the model is overfitted
3) At the end of 20th epoch model's training accuracy is 99.94%, hence the testing accuracy will not increase even if we pushed our model further


MODULE-2


        ##TARGET##
1) Make model lighter by reducing the number of parameters 
2) Make the model under-fitted
3) Increase the accuracy of the model

       ##RESULTS##
1) Number of parameters used in the model: 7,432
2) Best Training Accuracy: 99.07%
3) Best Testing Accuracy: 99.44%

      ##ANALYSIS##
1) By using the less number of channels, the number of parameters are decreased but becuase of this at the same time the accuracy of the model also got decreased 
2) Dropout helps to reduce the number of parameters and also helps to train the model in less number of parameters
2) The model is under-fitted now
3) Accuracy is not consistent in every epoch
4) Model is taking to more epoch to show accuracy of 99.44%

MODULE-3

        ##TARGET##
1) To reach the accuracy 99.4%
2) This accuracy should be acheived by the model in maximum 15 epochs
3) Show the consistent result in the epoch

       ##RESULTS##
1) Number of parameters used in the model: 7,432
2) Best Training Accuracy: 98.74% (15th epoch)
3) Best Testing Accuracy: 99.3% (14th and 15th epoch)

      ##Analysis##
1) By looking at the dataset and by using slight rotation on it, the accuracy of the model is increased
2) By setting the Step_Size=1.5 and learning rate = 0.01, the model is learning quickly 
3) The model is under-fitted as well as the testing accuracy is consistent in last two epochs



