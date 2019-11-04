# Problem Set 4: Dimension Reduction
Submit your assignment here (see workflow in the syllabus for help).

Remember to submit a **single rendered PDF** (either from `.Rmd` or a Jupyter Notebook) to this repo by **Monday, November 11 at 5 pm**.

For the following questions, use the world indicators data from class (`countries.csv`). _Be sure to prepare the data appropriately (e.g., standardize)._

## Factor Analysis

1.	How do CFA and EFA differ?
2.	Fit three exploratory factor analysis models initialized at 2, 3, and 4 factors. Present the loadings from these solutions and discuss in substantive terms. How does each fit? What sense does this give you of the underlying dimensionality of the space? And so on.
3.	Rotate the 3-factor solution using any oblique method you would like and present a visual of the unrotated and rotated versions side-by-side. How do these differ and why does this matter (or not)?

## Principal Components Analysis

1.	What is the statistical difference between PCA and FA? Describe the basic construction of each approach using equations and then point to differences that exist across these two widely used methods for reducing dimensionality.
2.	Fit a PCA model. Present the proportion of explained variance across the first 10 components. What do these values tell you substantively (e.g., how many components likely characterize these data?)?
3.	Present a biplot of the PCA fit from the previous question. Describe what you see (e.g., which countries are clustered together? Which input features are doing the bulk of the explaining? How do you know this?

## Bonus Question (5 points):

1.	Fit a sparse PCA model and a probabilistic PCA model. Compare these results substantively. What does each tell you and why do these distinctions matter in terms of inference (or not)?
