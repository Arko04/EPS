# Engineering Probability & Statistics

Coursework for **Engineering Probability and Statistics** at the University of Tehran, Faculty of Electrical and Computer Engineering (Fall 2023). The computer assignments are Python notebooks that check probability theory by simulation and apply it to real data.

| # | Topics | Notebook |
|---|--------|----------|
| CA0 | **Naive Bayes text classifier** that assigns Persian book descriptions to categories: bag-of-words with hazm normalisation, lemmatisation and stop-word removal. Log-probabilities plus additive (Laplace) smoothing raise accuracy from 30.9% to **82.7%** | [ca0.ipynb](ca0-naive-bayes-book-classifier/ca0.ipynb) |
| CA1 | Building the binomial from Bernoulli trials; normal and Poisson approximations to the binomial; why the normal distribution matters | [ca1.ipynb](ca1-binomial-and-bernoulli/ca1.ipynb) |
| CA2 | Conditional distributions; moment-generating functions; **Bayesian estimation and inference** | [ca2.ipynb](ca2-conditional-distributions-and-mgf/ca2.ipynb) |
| CA3 | Mean squared error, and why autoencoder reconstructions of MNIST come out blurry; **regression and least squares** on FIFA 2020 player data (outliers, high-leverage points, R²); the **central limit theorem** and sampling | [ca3.ipynb](ca3-mse-autoencoders-and-regression/ca3.ipynb) |

## Homework

My handwritten solutions to the theory assignments are in [homework/](homework/): HW0–HW5 and HW7, with HW4 in two parts.

**Tech:** Python, NumPy, SciPy, pandas, Matplotlib, and TensorFlow/Keras (the pretrained MNIST autoencoder in CA3).

The datasets provided by the course (`books_train.csv`, `books_test.csv`, `digits.csv`, `Tarbiat.csv`, `FIFA2020.csv`, `mnist_AE.h5`) aren't included.
