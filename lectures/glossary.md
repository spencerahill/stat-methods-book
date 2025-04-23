# Glossary
Note: unlike traditional glossaries, the entries here are not listed alphabetically.  They are organized by topic, and within each topic they are ordered in the sequence essentially that they appear in that topic.

```{glossary}
## Math and logic preliminaries

axiom 
  A statement that is regarded as self-evidently true.  As such, one doesn't have to "prove" that an axiom is true.  
  
  Axioms come up for us in the form of the Three Axioms of Probability: By assuming that the three axioms are correct, we can then derive all the other facts about probability from them.

continuous
  Something that does *not* have finite "jumps" between consecutive values.  For example, the {term}`real number`s.  There are uncountably infinitely many numbers in any finite segment.  As opposed to {term}`discrete`.

discrete
  Something that has finite "jumps" between consecutive values: there is a well-defined, finite space between any value and the next smallest or next largest.  As opposed to {term}`continuous`.

function

real number
  

## Probability theory

Bernoulli trial
  A random {term}`experiment` for which there are exactly two outcomes, one labeled "success" and the other "failure", and where the probability of success stays constant across all repetitions of the trial.

  For example, a coin flip is a Bernoulli trial, if as conventional we label "heads" as "success" and "tails" as "failure", and the coin is flipped in a fair way each time.

  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Bernoulli_trial)

elementary event
  An {term}`event` that consists of exactly one {term}`outcome` in the {term}`sample space`.

empirical probability
  For a given {term}`event`, the ratio of the number of outcomes in which that event occurs to the total number of trials.  It is also known as {term}`relative frequency` or *experimental probability*.

  Formally, denoting the number of outcomes in which the event occurs as $n$ and the total number of trials as $m$, this is $n/m$.

  The word *empirical* signifies that this ratio is taken directly from the actual experiment performed, rather than from an assumed *theoretical* distribution.

  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Empirical_probability).

experiment
  A procedure that can be *infinitely* repeated and has a well-defined set of possible outcomes.

  Also known as a {term}`trial`.

  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Experiment_(probability_theory)).

event
  A subset of the {term}`sample space` of an {term}`experiment`.

  For example, in the case of a single dice roll, one event could be "roll a 6".  Another could be "roll an odd number;" notice that this one consists of more than one possible {term}`outcome`.

mutually exclusive
  
  
  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Mutual_exclusivity)

outcome
  A possible result of an {term}`experiment`.  Each *outcome* is unique from all other possible outcomes.  (More formally, we say each outcome is {term}`mutually exclusive` of all other outcomes.)

  For example, for a single coin flip, there are exactly two outcomes: heads or tails.  For a single dice roll, there are exactly six outcomes: 1, 2, 3, 4, 5, or 6.

  An *outcome* differs from an {term}`event`, because an event can be *any* subset of the {term}`sample space`.  So e.g. for the dice roll "roll an even number" is a valid event, and it occurs if any of the three, mutually exclusive outcomes of rolling a 2, rolling a 4, or rolling a 6 occur.

  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Outcome_(probability))

probability distribution
  A {term}`function` that tells you the probabilities of different {term}`outcome`s of an {term}`experiment`.

  We can split this general term into two key types: the {term}`probability mass function` which is for {term}`discrete` quantities, and the {term}`probability density function` which is for {term}`continuous` quantities.

  For more: [Wikipedia page](https://en.wikipedia.org/wiki/Probability_distribution)

probability density function


probability mass function


relative frequency
  A synonym for {term}`empirical probability`.

sample space
  The set of all possible outcomes of an {term}`experiment`.

  Note that the "sample" in *sample space* has a different meaning than the term {term}`sample` when used in the context of {term}`population` vs. sample, e.g. in quantities such as the {term}`sample mean` and {term}`sample variance`.

  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Sample_space).

observation
   Each individual value in any dataset.

   (More generally in the Earth sciences, the word "observation" is commonly used in a different sense, to refer to *observational data*: data that is taken directly from the real Earth---whether *in situ* using our own eyes or an instrument like a thermometer, or conversely *remotely sensed* via a satellite---as opposed to data that comes from a *numerical model*, i.e. a *simulation*.  But in the context of statistical methods, an *observation* can be a data point from a computer simulation just the same as it could be from say a mass spectrometer.)

random variable
  For our purposes, a {term}`function` that takes as input any possible event in the sample size and returns a {term}`real number`.

  For example, consider the temperature measured by a thermometer at a weather station.  We consider the thermometer's output to be a {term}`random` process, in the sense that we can't predict its value perfectly at each time.  For our purposes, the *random variable* representing the temperature at the weather station would simply be the thermometer's output, in whatever fixed unit (Kelvin, degrees Celsius, degrees Fahrenheit).  Formally, if \(T\) is the temperature at the weather station and \(X\) is the random variable, then we have \(X(T)=T\).

  For a more nuanced example, a coin flip can either land `heads` or `tails`.  But `heads` is not a number, and neither is `tails`, and so the coin flip itself is not a *random variable*.  Instead, we *define* a random variable that *assigns* a number to each possible outcome, in this case one to `heads` and one to `tails`.  The most common choice for a coin flip is to assign `tails` a value of -1 and `heads` a value of +1.  We can write that symbolically as the function \(X(\omega)\), where \(X\) is the function, and \(\omega\) is either `heads` or `tails`, defined by
  $$
  X(\omega) = 
  \begin{cases}
  1, & \text{if } \omega = H \\
  -1, & \text{if } \omega = T
  \end{cases}
  $$
  
  [Beyond this course, a more general definition of a *random variable* is a mathematical formalization of a quantity or object which depends on random events, with the function]

  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Random_variable)

trial
  Another word for {term}`experiment`.

## Descriptive statistics

mean

variance

standard deviation

kurtosis

moment

median

percentile

quantile

## Samples vs. populations

Bessel's correction
  The use of $N-1$ rather than $N$ in the denominator of the {term}`sample variance`.  This makes it an {term}`unbiased estimator` of the {term}`population` {term}`variance`.  Whereas, if $N$ is used instead, it is a {term}`biased estimator`.  
  
  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Bessel%27s_correction)

sample
  A draw from a population

sample mean

sample variance
  An {term}`unbiased measure` of the {term}`population` {term}`variance`, denoted $s^2$, of a sample $x_1,\dots,x_N$ containing $N$ data points is given by $$s^2=\frac{1}{N-1}\sum_{i=1}^{N}\left(x_i-\overline{x}\right)^2$$.  
  
  For more: the [Wikipedia page](https://en.wikipedia.org/wiki/Variance#Sample_variance)

unbiased measure
```