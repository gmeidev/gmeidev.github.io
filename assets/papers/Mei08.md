# Papers of Guobiao Mei
## Dimensionality Reduction Algorithms With Applications to Collaborative Data and Images (2008)
by [Guobiao Mei](/)

**Abstract**: General dimensionality reduction techniques play important roles in various fields in machine learning. As a well studied problem, many existing algorithms have achieved wide success in specific fields. In this work, we view this problem from a different viewpoint.
We first focuses on collaborative data, which consist of ratings relating two distinct sets of objects: users and items. Much of the work with such data focuses on filtering: predicting unknown ratings for pairs of users and items. In this work, we propose a well-structured Bayesian network to model the collaborative data, and employ loopy belief propagation to estimate parameters of the network and perform filtering tasks. In addition, we are interested in the problem of visualizing the information in the collaborative data. Given all of the ratings, our task is to embed all of the users and items as points in the same Euclidean space. We would like to place users near items that they have rated (or would rate) high, and far away from those they would give low ratings. We pose this problem as a real-valued non-linear Bayesian network and employ Markov chain Monte Carlo and expectation maximization to find an embedding. We present a metric by which to judge the quality of a visualization.

We then extend the visualization framework to images, specifically to embed images. Embedding images into a low dimensional space has a wide range of applications: visualization, clustering, and preprocessing for supervised learning. Traditional dimension reduction algorithms assume that the examples densely populate the manifold. Image databases tend to break this assumption, having isolated islands of similar images instead. Here we extend our framework to achieve the embedding goal of preserving local image similarities based on their scale invariant feature transform (SIFT) vectors. We make no neighborhood assumptions in our embedding. Our algorithm can also embed the images in a discrete grid, useful for many visualization tasks.

## Download Information
Guobiao Mei (2008). "**Dimensionality Reduction Algorithms With Applications to Collaborative Data and Images.**" _Doctoral dissertation_, University of California at Riverside. [![PDF](/assets/images/pdf.gif)](/assets/papers/dissertation.pdf)

## Bibtex Citation
```
@phdthesis{Mei08,
    author = "Guobiao Mei",
    title = "Dimensionality Reduction Algorithms With Applications to Collaborative Data and Images",
    school = "University of California at Riverside",
    schoolabbr = "UC Riverside",
    year = 2008,
    month = Aug,
}
```
---
[Homepage of Guobiao Mei](/)
