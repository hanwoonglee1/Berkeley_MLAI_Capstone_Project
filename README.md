## Using Binary Classification to Predict Clicks on Ads 
**Han Lee**

### Executive summary

**Project overview and goals:** A business problem many of us face in the digital advertising industry centers on the question of what drives clicks.  Across Facebook, Google, Tiktok, and many other tech giants, advertising is the main source of revenue.  It is, therefore, paramount to understand what drives clicks and capitalize on these triggers to maximize clicks and ultimate conversions.  In this capstone project, I would like to perform exploratory data analysis and predictive modeling to algorithmically identify customers who are likely to click.

**Findings:** Of the three models explored, we can easily drop k-nearest neighbors due to the low evaluation scores. Between logistic regression and random forest, however, it is a bit more nuanced. Given the limited data set, they both returned perfect evaluation scores - 100% across accuracy, recall, and precision. Nonetheless, I would select the logistic regression model, given far superior model interpretability, computational efficiency, scalability, and probabilistic predictions.

**Future research and development:** The perfect evaluation scores are likely due to limited sample size.  Hence, in the long term, I would gather richer data and re-run the models to re-evaluate model performance.

**Dataset:** The dataset used in this project is from Kaggle and can be accessed at https://www.kaggle.com/datasets/gabrielsantello/advertisement-click-on-ad/data.  This is a collection of 1,000 sanitized individual data.

**Methodology:** Given the nature of this project is a binary classification, I deployed logistic regression, K-nearest neighbors, and random forest models.  For each modeling technique, a GridSearchCV was run to identify the optimal parameters.
