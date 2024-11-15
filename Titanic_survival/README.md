# EDA and Feature Engineering on Titanic survival prediction dataset  
This project shows how powerful data analysis is by predicting the chances of survival of a passenger in the titanic.  
Initial performance was not good so we engineered some new features to make the model perform better.  
In case of feature importances a feature engineered came out on top.  
We generated features such as:
* __Age category__ as the correlation of age with survival showed some loaclised behavior patterns.
* **is_alone** and __relatives__ as we saw that the variables SibSp and Parch could be combined to extract better meaning.
* __Titles__ were extracted from the names of the passengers which came on top in case of feature importances.   

Various models were trained for the task and the Random Forest Classifier came on top with accuracy of 90 percent.