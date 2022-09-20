# Data-science Cheet-sheet

1. [Probability](#prob)
2. [Statistics](#stats)

## 1) <a id='prob'></a> Probability

### 1.1) Conditional Probability

### 1.2) Counting

#### 1.2.1) Permutation

``` python
from itertools import permutations

a = [1,2,3]
perm = permutations(a)
print(list(perm))

# [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]

```

#### 1.2.1) Combination

``` python
from itertools import combinations

a = [1,2,3,4]
comb = combinations(a, 2)
print(list(comb))

# [(1, 2), (1, 3), (1, 4), (2, 3), (2, 4), (3, 4)]

```

### 1.3) Probability Distributions

#### 1.3.1) Discrete Probability Distributions

| Num   | Distribution   | Definition | Usage |
|---:|:-------------|------------:|---------:|
|  1 | Binomial distribution |  Probability of *k* number of successes in *n* independent trial              |  Coin flips (number of heads in *n* flips)                  | 
|  2 | Poisson distribution  |  Number of events occurring within a particular fixed interval \( $\lambda$ \)    |  Number of visits to a website in a certain period of time    | 


#### 1.3.2) Continuous Probability Distributions

| Num   | Distribution   | Definition | Usage |
|---:|:-------------|------------:|---------:|
|  1 | Uniform distribution     | Constant probability of *X* falling between *a* and *b*      | In sampling and hypothesis testing cases  | 
|  2 | Exponential distribution | Poisson for continous data                                   | The time until a credit defaul occurs     |
|  3 | Normal distribution      | Probability according to the bell curve over a range of *Xs* | The Central Limit Theorem                 |


### 1.4) Markov Chains

## 2) <a id='stats'></a> Statistics

### 2.1) Random Variables

### 2.2) Central Limit Theorem

### 2.3) Hypothesis Testing

#### 2.3.1) General Information

#### 2.3.2) Type I and Type II Errors

#### 2.3.3) *p-values* & Confidence Intervals

#### 2.3.4) Test Statistics

### 2.4) MLE & MAP

Maximum Likelihood Estimation (MLE) and Maximum A Posteriori (MAP) estimation. The difference among them is the inclusion of the prior in MAP. Moreover, MLE can be seen as a special case of MAP with a uniform prior. 

