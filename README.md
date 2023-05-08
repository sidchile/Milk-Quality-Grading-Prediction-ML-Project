# Milk-Quality-Grading-Prediction-ML-Project
The Dataset Milk Quality Prediction is a Classification Dataset.


About dataset :-



> This dataset is manually collected from observations. 

> It helps us to build machine learning models to predict the quality of milk.
 
> This dataset consists of 7 independent variables ie pH, Temperature, Taste, Odor, Fat, Turbidity, and Color.
 
> Generally, the Grade or Quality of the milk depends on these parameters. 
 
> These parameters play a vital role in the predictive analysis of the milk.




Usage:-

> The target variable is nothing but the Grade of the milk. Which is :-
 
  >>1) Low (Bad)
  
  >>2) Medium (Moderate)
  
  >>3) High (Good)




 There are 7 Columns:-

  1) pH = A measure of how acidic or basic a substance or solution is PH, it is measured on a scale of 0 to 14.
  
  2) Temperature = Temperature is the degree of hotness or coldness of an object.
  
  3) Taste = The sensation of flavour perceived in the mouth and throat on contact with a substance.
  
  4) Odor = An odor is also called a "Smell" or a "Scent".
  
  5) Fat = The fat content of milk is the proportion of milk, by weight, made up by butterfat.
  
  6) Turbidity = The quality of being cloudy, opaque, or thick with suspended matter.
  
  7) Colour = The appearance of milk is White.
  



> If Taste, Odor, Fat, and Turbidity are satisfied with optimal conditions then they will assign 1 otherwise 0.
 
> Temperature and ph are given their actual values in the dataset.

> We have to perform data preprocessing, and data augmentation techniques to build statistical and predictive models to predict the quality of the milk.











CONCLUSION :-

In this project of Milk Quality Prediction (Classiification) we have to predict the Grade of the Milk.

First we clean the data by checking if there are no null values or columns are in the correct datatype form.

Then we Visualize the dataset by the using of various tool like countplot,distplot,histplot,heatmap and pie diagram.

Then we Encode the Columns in int form which are in object form.

Then we do Scaling of the Data.

After All this we build the model by applying algorithms.

All the models are working properly and the Decision Tree Classifier gives the Highest Accuracy Score.

So we predict New Observation by using Decision Tree Classifier.
