# Speed dating with PCA

![A married couple cake toping](https://imgur.com/NpXLq5o.jpg)<br>
<a href="https://www.kaggle.com/annavictoria/speed-dating-experiment"> Image courtesy of Kaggle</a>

Principal component analysis (PCA) is often used to simplify data, reduce noise, and find unmeasured latent variables.

**In the following, I:**

- Explore how PCA relates to correlation.
- Use PCA to perform dimensionality reduction.
- Predict whether or not a speed dater likes reading based on the dater's other likes.

### The dataset

The dataset we're using is a subset of this [much more detailed speed dating data set](https://www.kaggle.com/annavictoria/speed-dating-experiment). In particular, this contains no information on the actual speed dating itself (i.e., successes with or opinions of other individuals). 

It also contains no follow-up information where individuals are asked the same questions about themselves again. It only contains information about what an individual enjoys doing, their self-ratings on how desirable they are, and how they think others rate them based on desirability.
