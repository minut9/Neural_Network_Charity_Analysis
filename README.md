# Neural_Network_Charity_Analysis

An exercise for Deep Learning and Neural Networks, utilizing pandas libraries in Python and TensorFlow to process data and produce a predictive binary classifier.

## Overview
  The end goal of this project was to explore and implement neural networks using TensorFlow in Python. Neural Networks is a form of Machine Learning that cna search and find patterns and particular features in a dataset. This type of learning is modeled after a brain which has many layers of neurons. As information goes in through the layers, the information is pushed through identifying features into the final output of data. A good analogy would be a car wash. Dirty car goes in and after multiple layers of cleaning, water, waxing, and drying - the car comes out clean as a final product. The project was to find data driven results to analyze which companys money would be used most effectively and to use a machine learning code to find over 75% accuracy. The data set contained over 34000 organizations that had recieved funding from AlphabetSoup. The challenge was to analyze the dataset with each column containing different info :
  * EIN and NAME—Identification columns
  * APPLICATION_TYPE—Alphabet Soup application type
  * AFFILIATION—Affiliated classification of industry
  * CLASSIFICATION—Government organization classification
  * USE_CASE—Use case for funding
  * ORGANIZATION—Organization type
  * STATUS—Active status (compared to inactive status)
  * INCOME_AMT—Income classification
  * SPECIAL_CONSIDERATIONS—Special consideration for application submission
  * ASK_AMT—Funding amount requested from Alpha
  * IS_SUCCESSFUL—If the money is used effectively
 
 
 ## Results
 Once the data set, to evaluate the model we compiled, trained, and evaluated. 

  * The original model had a parameter of 5981. As well as, 43 inputs, 2 hidden layers and an output layer.
      * The first hidden layer had 43 inputs, 80 neurons and 80 bias terms
      * the seocnd hidden layer 80 inputs, 30 neurons and 30 bias terms.
      * the output layer had 30 inputs, 1 neuron and 1 bias term.
  * The goal accuracy rate is anything greater than 75%. The model found was 72.5%.
<img width="928" alt="Screen Shot 2022-03-08 at 3 43 52 PM" src="https://user-images.githubusercontent.com/86068655/157322508-743a929d-8dfc-4e7e-8883-8a6874e7ff3d.png">


### Optimization to improve the Accuracy
The first 2 optimizations were failures, featuring drop methods and attempts to optimize the model by adding another neural layer. Both failures. On the third attempt we added parameters and neurons which in term gave more information to analyze which made our accuracy better once the code ran. 
However, on the third attempt. We used the RandomForestClassifier to increase our optimization accuracy as well as increasing the amount of neurons to give over 2million parameters. The third attempt sent the accuracy the almost 79%. 

<img width="657" alt="Screen Shot 2022-03-08 at 3 56 54 PM" src="https://user-images.githubusercontent.com/86068655/157323742-941a3730-38af-4c01-81bd-b06cd649c149.png">

To optimize any model performance, resetting parameters and adjust layer neurons is key. And it does not hurt to bring in other tools to assist in making a model more accurate.

## Conclusion
After using Neural Networks, it is apparent that trial and error need to be incorporated to find various parameters, neuron layers, and accuracy scores for predictions with any future project utilizing this model.
