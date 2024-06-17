[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tJRTZ1CT)
# Week 2 HW

The purpose of this assignment is to get exercise some basic sampling skills, focusing on rejection and importance sampling.

Take the following probability density function:
```math
p(x) = 0.164\exp{\left(-\frac{(x-10)^4}{2\cdot 8^2}\right)}
```

1. Use _rejection sampling_ to draw 1000 samples from this distribution.  Show that the samples you've drawn are correctly distributed according to this probability density function.

1. Use _importance sampling_ to estimate the expectation value of $x$, and compare it to the mean of the samples you drew in part 1.

1. Calculate the expectation value of $x^2$.

## Grad students:

Revisit the importance sampling example from the Intro to Sampling notebook.  There we demonstrated the use of importance sampling to estimate the expectation value of some function of our random variable.  We could also use the weights we computed to probabilistically choose samples from the sampling distribution to keep, in an effort to "reweigh" the sampling distribution to correspond to the target distribution.  Try to implement this, and see if your resampled distribution's histogram matches the target distribution's probability density function.
