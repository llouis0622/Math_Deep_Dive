# 1. 이중급수와 무한급수

### 이중실수열

$\{a_{ij} \mid i, j \in \mathbb{N}\}$을 이중실수열이라 하고 다음 급수가 수렴한다고 가정

$\sum_{i=1}^\infty \sum_{j=1}^\infty |a_{ij}|$

- 무한급수 $\sum_{i=1}^\infty \sum_{j=1}^\infty a_{ij}$와 $\sum_{j=1}^\infty \sum_{i=1}^\infty a_{ij}$가 모두 같은 값으로 수렴
- $\lim_{n \rarr \infty} s_{nn} = \sum_{i=1}^\infty \sum_{j=1}^\infty a_{ij} = \sum_{j=1}^\infty \sum_{i=1}^\infty a_{ij}$ 성립

이때 $s_{nn} = \sum_{i=1}^\infty \sum_{j=1}^\infty a_{ij}$

# 2. 무한급수의 곱

### 코시 곱

- $\begin{aligned} (\sum_{i=1}^\infty a_i)(\sum_{j=1}^\infty b_j) &= (a_1 + a_2 + a_3 + \cdots)(b_1 + b_2 + b_3 + \cdots) \\ &= a_1b_1 + (a_1b_2 + a_2b_1) + (a_3b_1 + a_2b_2 + a_1b_3) + \cdots \\ &= \sum_{k=2}^\infty d_k \end{aligned}$
- $d_k = a_1b_{k-1} + a_2b_{k-2} + \cdots + a_{k-1}b_1$