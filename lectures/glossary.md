# Glossary
```{glossary}
Bessel's correction
  The use of $N-1$ rather than $N$ in the denominator of the {term}`sample variance`.  This makes it an {term}`unbiased estimator` of the {term}`population` {term}`variance`.  Whereas, if $N$ is used instead, it is a {term}`biased estimator`.  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Bessel%27s_correction)

observation
   Each individual value in any dataset.

   (More generally in the Earth sciences, the word "observation" is commonly used in a different sense, to refer to *observational data*: data that is taken directly from the real Earth---whether *in situ* using our own eyes or an instrument like a thermometer, or conversely *remotely sensed* via a satellite---as opposed to data that comes from a *numerical model*, i.e. a *simulation*.  But in the context of statistical methods, an *observation* can be a data point from a computer simulation just the same as it could be from say a mass spectrometer.)

random variable
  A mathematical formalization of a quantity or object which depends on random events

  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Random_variable)

sample variance
  An {term}`unbiased measure` of the sample variance, denoted $s^2$, of a sample $x_1,\dots,x_N$ containing $N$ data points is given by $$s^2=\frac{1}{N-1}\sum_{i=1}^{N}\left(x_i-\overline{x}\right)^2$$.  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Variance#Sample_variance)


```