# Mutual Information

Mutual Information (MI) is a concept from information theory that measures the amount of information obtained about one random variable through another random variable. In other words, it quantifies the reduction in uncertainty about on variable given knowedge of another. Mathematically, mutual information between two variables $X$ and $Y$ is defined as:

<p align="center">
$I(X, Y) = \sum_{x\in X}\sum_{y\in Y}p(x,y)log(\frac{p(x,y)}{p(x),p(y)})$
</p>

Where:
- $p(x,y)$ is the joint probability distribution of $X$ and $Y$
- $p(x)$ and $p(y)$ are the marginal probability distributions of $X$ and $Y$

MI is use to:
- Feature Selection: It is commonly used in machine learning to measure the dependency between variables, particularly for feature selection to determine the most relevant features for a predictive model.
- Information Theory: MI is widely used in areas like signal processing, data transmission, and clustering.
