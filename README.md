# RecycleCatDataSet

This is the dataset used for my dissertation project RecycleCat. RecyleCat  is  a  radar-based  system  which  is  able  to  
classify  11  different  types  of  recyclable  waste.   As presented, it is able to filter 6 different types of 
plastic resin, 3 types of glass, cardboard and paper. 


The dataset contains data for 11 different types of recyclable waste:
cardboard, paper, brown glass, 
clear glass, green glass, high-density polyethylene (HDPE), polyethylene terephthalate (PET), low-density polyethylene(LDPE), 
polypropylene (PP), polystyrene (PS) and recycled polyethylene (RPET). For each type there are 7 objects, split into 5 objects 
in the training set and 2 objects in the out of sample test set. For the training set, each object contains 60 readings 
each measured at a different angle when placed on the radar sensor. This gives a total of 300 readings for each 
material type producing 3300 readings for the entire training set. The out of sample test set contains just 20 readings
of each object, these were randomly placed on the radar chip producing a set of 440 readings. 

The best test performance I could produce 
was with a multi layer perceptron / neural network with a classification rate of 88%. The best out 
of sample test performance I could produce was with a support vector machine with a classification rate
of 23%. 

This repository has a MIT license which allows for complete freedom, so please feel free to use 
this data set and train a machine learning model that can classify waste hopefully to a better
degree than I was able to. 


