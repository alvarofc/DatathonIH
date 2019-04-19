# Cookie Flea Analysis - DatathonIH


### Overview

We want to define a model that predicts the quality of a cookie. 

We would like to classify the cookies given a set of features. The outcome is the quality of the cookie. 

Short List of ML models:

- Linear SVC
- K-Nearest Neighbors
- SVC 
- Ensemble Classifiers


Success metrics:
It's more critical to predict a good cookie that is actually bad than the other way arround and in general we want a good accuracy. For this reasons we will consider the following measures.

- Confusion matrix. 
     - Accuracy. Target Accuracy > 80%
     - False Positive Rate < 10%




### Data Preparation


The dataset provies features of cookies and its quality. The dataset was obtain trough the Datathon organization. 
It has 5198 instances for 15 features and 1 outcome (quality).

Features: 
- sugar to flour ratio: The fraction of sugar to flour, expressed as a decimal (sugar/flour).
- sugar index : Modified glycemic index.
- bake temp : Baking temperature, in degrees fahrenheit.
- chill time : Time necessary for the cookies to rest in the fridge, expressed in minutes.
- calories: Unit of heat equal to the heat needed to raise the temperature of 1,000 grams of water by one degree Celsius.
- density: Expressed in grams/cm3.
- pH : pH of cookie.
- grams baking soda: Grams of leavening agent (from recipe).
- bake time: how long the cookies need to bake, in minutes.
- quality: ‘Goodness’ of cookie.
- butter: type Form of butter used.
- weight: In grams.
- diameter: In centimeters.
- mixins: Elements added to the batter, as additions.
- crunch factor: Index of chrispiness.
- aesthetic appeal: Appearance, based on color, regularity, and form.


---
TO DO

### Data Wrangling and Cleaning
Your full process of data wrangling and cleaning.
* Document your workflow and thinking process.

### Data Analysis
* Overview the general steps you will go through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Print charts to demonstrate the effect of your work. Charts make your presentation look good too.
* If you use ML in your final project, also describe your feature selection process.

### Model Training and Evaluation
* Train your ML model, produce results, and evaluate.
* This is an iterative process. Try your best to improve your model performance by:
  * Try different models and select one that is the simplest yet produce the best result.
  * Try advanced techniques and see if they improve the result.

### Conclusion
* Summarize your data analysis result.
* State your conclusion of your hypothesis testing.
* Interpret your findings in terms of the human-understandable question you try to answer.

### What are the next steps?














## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
