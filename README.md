# Quantified_Self
This analysis predicts, whether an individual is performing a weight lifting excercise in a correct or incorrect way. Triple axis accelerometer data is analyized which is based on the performance of six young and healthy participants. Each participant was asked to do 10 repititions of Unilateral Dumbbell Biceps Curls in five different fashions. Four of the fashions represent common mistakes whereas one fashion represents the correct way.

## Model
Following Machine Learning techniques are used in order to get the best predictive outcome:

* Decision Tree
* Linear Discriminant Analysis
* Naive Bayes
* Random Forest

## Environment
This research is conducted in R. Packages that are being used are:
* [caret](http://caret.r-forge.r-project.org/)
* [randomForest](https://cran.r-project.org/web/packages/randomForest/index.html)
* [doParallel](https://cran.r-project.org/web/packages/doParallel/index.html)
* [klaR](https://cran.r-project.org/web/packages/klaR/index.html)
* [MASS](https://cran.r-project.org/web/packages/MASS/index.html)
* [gbm](https://cran.r-project.org/web/packages/gbm/index.html)
* [plyr](https://cran.r-project.org/web/packages/plyr/index.html)

## Files
* *index.html*: Summary of findings and documentation of research.
* *Quantified Self.Rmd*: Contains all code and descriptive elements to research.
* *files/*:
	* **pml-training.csv**: All training data
	* **pml-testing.csv**: All testing data