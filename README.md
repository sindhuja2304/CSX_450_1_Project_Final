
## 1. The domain of the problem
The problem is drawn from the analysis of Abalone which is a shelled sea creature and nutritious food resource.The data set contains the measurements of Abalone. 
## 2. A problem statement 
The purpose is to predict the age of the abalone given various descriptive attributes of the abalone.The problem associated with this dataset is that these descriptive attributes are all heavily correlated.

Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and
	Wes B Ford (1994) "The Population Biology of Abalone (_Haliotis_
	species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North
	Coast and Islands of Bass Strait", Sea Fisheries Division, Technical
	Report No. 48 (ISSN 1034-3288)
  
## 3. Data set Description
The data set consists of 4177 rows and 9 Attributes.The data set consumes memory of about 269 Kb.
The data types of the 9 attributes are 7 numeric,1 integer and 1 category.One of the 9 Attributes is the Sex which consists of 3 classes(F,I,M)
Number of Attributes: 9
The attribute information consists of the below.
1. Attribute name
2. Attribute type
3. Measurement unit
4. Brief Description
The 9 attributes in this data set are Sex,Length,Diameter,Height,Whole weight,Shucked,Viscera,Shell and Rings.

We measured the minimum value, maximum value, median value, mean value like below

![statistics](https://user-images.githubusercontent.com/35319815/35492202-4aaf3992-0460-11e8-91ef-6a6a53844694.JPG)


## 4. A proposed solution
A solution to this model would be a Multiple Regression model.
## 5. A benchmark model
A good benchmark model would be a naive Linear Regression model.
## 6. A performance Metric
The performance would be the mean square error(MSE).The MSE would be small if the predicted responses are close to the true.So the smaller MSE,the more accurate model.

