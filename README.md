# Statistical Methods for Physics

This class is an introduction to:
- the Bayesian interpretation of probability;
- the basics of Bayesian statistics applied to parametric model inference, including model selection and hierarchical inference of hypermodels;
- best practices in data analysis, such as properly using a validation set to assess model performance;
- tools for data analysis, including libraries for parameter estimation and machine learning.

All topics are presented through simple examples designed to illustrate the fundamental principles behind each concept.

## Resources
[Statistics, Data Mining, and Machine Learning in Astronomy](https://press.princeton.edu/books/hardcover/9780691198309/statistics-data-mining-and-machine-learning-in-astronomy-pdf): Texbook with theory, examples, and code snippets in Python. Good if you want to learn by hands-on problems.

[Jayne's book on Probability Theory](http://www.med.mcgill.ca/epidemiology/hanley/bios601/GaussianModel/JaynesProbabilityTheory.pdf): Textbook on the foundations of the Bayesian interpretation of probability.

## Lectures

[Lecture 1](https://colab.research.google.com/drive/1dessi5cj9aB_SETffMiVFGqbJ1lYLTh7) **Probabilities and probability densities:** histograms; density estimation and KDE; change of variables, mean, medians and quantiles; cumulative distribution function; conditional probability and marginal probability; the Monty Hall problem.

[Lecture 2](https://colab.research.google.com/drive/1vZ2CcNJG1BY6ZOlA8i5ZH38YvU7q7hsI?usp=sharing) **Parameter estimation:** The likelihood function; example: tossing an unfair coin; stochastic sampling with the `dynesty` library; evidence and Bayes factors; credible intervals for bounded distributions railing towards the bounds.

[Lecture 3](https://colab.research.google.com/drive/1-q4EfZQaIHi1OtWSfdACEV0I_Ni6-UOw?usp=sharing) **Parametric models:** Byesian regression; model selection; model predictive distribution and posterior predictive distribution; Savage-Dickey ratio.

[Lecture 4](https://colab.research.google.com/drive/1uMjlfV1GPue-8SFQNHri_6nJdlRg2nut?usp=sharing) **Combining multiple events:** Hierarchical Bayesian inference; likelihood multiplication; multiplication of the Bayes factors.

[Exercise](https://colab.research.google.com/drive/1bZsmKpwvqTVmCSzNpjTzlcQghwI8AE-A?usp=sharing) on hierarchical Bayesian inference.

[Lecture 5](https://colab.research.google.com/drive/19MAIk_t97TzB5i6RYjI-vRzp4YQqgXtk?usp=sharing) **Training, validating, and testing:** test set; validation set; K-fold cross-validation; application to least squares regression; maximum-likelihood optimization of parametric models with the `sklearn` library; weight regularization; kernel trick and kernel ridge regression; gaussian process regression.

[Lecture 6](https://colab.research.google.com/drive/1vR8uXuYnS4hgjphoB5O_4ZiW0ktw2XHF?usp=sharing) **Miscellanea:** the Fisher information matrix; p-p plots as a diagnostic of a stochastic sampler; Monte-Carlo integration.
