# credit-risk-scoring-model

### This project was an attempt to understand how credit decisions are made in practice and how a model can support that process. I worked through the entire pipeline, starting from raw data all the way to building and evaluating a model.

At the beginning, the dataset required a fair amount of cleaning. I handled missing values and explored the distribution of each variable to identify issues such as skewness and outliers. After that, I transformed the features using Weight of Evidence (WOE), which helps improve interpretability in logistic regression. I also used Information Value (IV) to understand which variables were more useful in distinguishing between good and bad borrowers.

Once the data was prepared, I trained a logistic regression model and evaluated its performance using ROC curve, AUC, and Gini. These metrics helped me assess how well the model can separate high-risk and low-risk customers.

After obtaining the predictions, I converted them into Probability of Default (PD) and grouped customers into risk grades from A to G. This step was important because, in practice, model outputs are often translated into risk levels to support decision-making rather than being used as raw probabilities.

Through this project, I gained a clearer understanding of how credit scoring works beyond just model building. It highlighted the importance of connecting data preparation, modeling, and practical business interpretation.

#### This project was developed as part of a course, but I aimed to follow an approach similar to what is used in real-world credit risk modeling.
