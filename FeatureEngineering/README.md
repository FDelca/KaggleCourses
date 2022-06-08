# Feature Engineering Course
Provided by [kaggle](https://www.kaggle.com/code/ryanholbrook/what-is-feature-engineering)

## Content:
- Use **Mutual Information** to determine the most important features;
- Create **new features** in different real-world problems scenarios;
- Use **Target Encoding** to encode *high-cardinality* categoricals;
- Use **Principal Component Analysis** to decompose dataset's variation into features.

### Goal of Feature Engineering
1. Improve model's predictive performance;
2. Reduce computational or data needs;
3. Improve interpretability of the results.

#### Guiding Principle

For feature engineering to be useful it must have a relationship to the target. For instance, Linear models are only able to learn linear relationships. So, when using one, the goal is to transform features to make the relationship to the target linear.

Whatever relationships your model can't learn, you can provide yourself through transformations. As you develop your feature set, think about what information your model could use to achieve its best performance.

Go to [00-ConcreteExample](FeatureEngineering/00-ConcreteExample.ipynb) to check a concrete example, about concrete's compressive strength prediction.