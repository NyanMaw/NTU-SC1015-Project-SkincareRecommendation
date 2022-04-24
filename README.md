# Welcome to our NTU-SC1015-Project-Skincare Recommendation Repository

## About!

![image](https://user-images.githubusercontent.com/85445638/164944612-d9bd5723-d2fe-4763-90f8-b637a9e9de8b.png)

This is our mini project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on recommending skincare products by finding similar ingredients used. For a detailed walkthrough, please view the video presentation and source code in order from:

1. [Project Presentation Slides](https://github.com/NyanMaw/NTU-SC1015-Project-SkincareRecommendation/blob/main/Project%20Presentation%20Slides_Skincare%20Recommendation.pdf)
2. [Jupyter Notebook File]
  
## Contributors

- @amabellim - Amabel - Extracting and preprocessing data, exploratory data analysis, NLP model application, UMAP application, drawing conclusions and insights.
- @spillthebeanss - Kristine - Extracting and preprocessing data, exploratory data analysis, NLP model application, UMAP application, drawing conclusions and insights.
- @NyanMaw - Maw Htun - Extracting and preprocessing data, exploratory data analysis, NLP model application, UMAP application, drawing conclusions and insights.

## Problem Definition
Detection of patterns in the data to produce a personalized recommendation system for skincare products

- Is there any relationship between price and rank, within products of the same categories? (i.e. within Moisturizers, Cleansers, etc.)

- Are we able to recommend similar products by analysing the ingredients used?

## Models Used

Inspired by Natural Language Processing (NLP) models:
1. Lexical Analysis (a.k.a. Tokenisation)
2. UMAP - Uniform Manifold Approximation and Projection
3. Comparison of different cases using Euclidean distance

## Conclusion

- Little to no relationship between price and rank of products

- Possible to create a personalised recommendation system to suggest 5 products most similar to the user's choice of product
- Enables users to make more informed choices when purchasing skincare products according to skintype and ingredients, instead of recommendations from others


## What did we learn from this project?

- Collaborating using Google CoLab and GitHub
- Handling data and extracting key information relevant to the problem definition
- NLP models
- Usage of lexical analysis (tokenisation) to better extract relevant keywords (in our case, ingredients for skincare products)
- Representing data in a DTM, which has a high dimension, using one-hot encoding
- Using dimensionality reduction algorithms, such as Principal Component Analysis (PCA), t-distributed stochastic neighbor embedding (t-SNE), and UMAP, so as to be able to visualise key information
- limitations of dimensionality reduction algorithms
- Using bokeh to visualise data
- Finding similarities

## References

- https://umap-learn.readthedocs.io/en/latest/parameters.html#:~:text=provided%20by%20n_neighbors%20.-,min_dist,will%20result%20in%20clumpier%20embeddings.
- https://umap-learn.readthedocs.io/en/latest/reproducibility.html
- https://umap-learn.readthedocs.io/en/latest/
- https://livebook.manning.com/book/machine-learning-for-mortals-mere-and-otherwise/chapter-14/
- https://pair-code.github.io/understanding-umap/
- https://towardsdatascience.com/for-your-skin-beauty-mapping-cosmetic-items-with-bokeh-af7523ca68e5
- https://towardsdatascience.com/on-the-validating-umap-embeddings-2c8907588175
- https://github.com/awslabs/amazon-denseclus
- https://towardsdatascience.com/umap-dimensionality-reduction-an-incredibly-robust-machine-learning-algorithm-b5acb01de568
- https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html

