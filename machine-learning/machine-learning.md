# Machine Learning

$$ 
\sum_{t=1}^T(c(q_t-q_{t-1})+n)\mathbb{1}\{q_{t-1}<D^*\} +P \mathbb{1}\{q_T<D^*\}
$$

## Semi-supservised
Learn dist of x s + relation of (x,y)
## InteractiveML Active learning
Decide which xs to get labels for

# Probability

P(x,y) is the joint prob dist of (x,y)
$$P_N(x,y) = \frac{1}{N}\sum_{j =1}^N \mathbb{1}_{x= x_i} \mathbb{1}_{y = y_i}$$
## Training set n<<N
$\{(x_i,y_i)\}_{i=1}^n$ iid $P_N(x,y)$
pick (xi, yi) uniformly at random from ${(xj,yj)}_{j= 1}^N$ with replacement

## Empirical Dists

marginal 
$$ p_h = \frac{1}{n}\sum_{i = 1}^n \mathbb{1}_{x= _i} = \sum_{y\in Y}p_h(x,y)$$
cond dists 
$$
p_h(y|x) = \frac{p_h(x,y)}{p_h(x)}
$$

Expectation
