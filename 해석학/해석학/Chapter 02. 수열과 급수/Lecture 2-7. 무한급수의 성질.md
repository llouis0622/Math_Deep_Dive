# 1. 무한급수

### 무한급수

무한급수 $\sum_{k=1}^\infty a_k$에서

- 수열의 항 : $a_1, a_2, a_3, \cdots$
- 부분합의 수열 : $s_1, s_2, s_3, \cdots(s_n = a_1 + a_2 + \cdots + a_n)$
- $\sum_{k=1}^\infty a_k = A \Leftrightarrow \lim s_n = A$

### 무한급수와 사칙연산

$\sum_{k=1}^\infty a_k = A, \sum_{k=1}^\infty b_k = B$일 때 다음이 성립

- 모든 $c \in \mathbb{R}$에 대해 $\sum_{k=1}^\infty ca_k = cA$
- $\sum_{k=1}^\infty (a_k + b_k) = A + B$

### 무한급수에 대한 코시 수렴 판정법

- 무한급수 $\sum_{k=1}^\infty a_k$가 수렴할 필요충분조건은 $\epsilon > 0$이 주어질 때 $n > m \geq N$이면 다음을 만족하는 $N \in \mathbb{N}$이 존재
    
    $|a_{m + 1} + a_{m + 2} + \cdots + a_n| < \epsilon$
    

### 무한급수에 대한 코시 수렴 판정법 명제

- 무한급수 $\sum_{k=1}^\infty a_k$가 수렴하면 $(a_k) \rarr 0$

### 비교판정법

수열 $(a_k)$와 $(b_k)$가 모든 $k \in \mathbb{N}$에 대해 $0 \leq a_k \leq b_k$를 만족한다고 가정하면

- $\sum_{k=1}^\infty b_k$가 수렴하면 $\sum_{k=1}^\infty a_k$도 수렴
- $\sum_{k=1}^\infty a_k$가 발산하면 $\sum_{k=1}^\infty b_k$도 발산

### 등비급수

- $\sum_{k=0}^\infty ar^k = a + ar + ar^2 + ar^3 + \cdots$
- $r = 1$이고 $a \neq 0$일 때 급수는 명백히 발산
- $r \neq 1$인 경우 다음 항등식 사용
    
    $(1 - r)(1 + r + r^2 + r^3 + \cdots + r^{m-1}) = 1 - r^m$
    
- 등비급수 부분합 : $s_m = a + ar + ar^2 + ar^3 + \cdots + ar^{m-1} = \frac{a(1 - r^m)}{1 - r}$

### 절대수렴 판정법

- 무한급수 $\sum_{n=1}^\infty |a_n|$이 수렴하면 $\sum_{n=1}^\infty a_n$도 수렴

### 교대급수 판정법

수열 $(a_n)$이 다음 조건을 만족한다고 할 때

- $a_1 \geq a_2 \geq a_3 \geq \cdots \geq a_n \geq a_{n+1} \geq \cdots$
- $(a_n) \rarr 0$

이때 교대급수 $\sum_{n=1}^\infty (-1)^{n + 1}a_n$은 수렴

### 절대수렴과 조건수렴

- 절대수렴 : 급수 $\sum_{n=1}^\infty |a_n|$이 수렴할 때, 급수 $\sum_{n=1}^\infty a_n$
- 조건수렴 : 급수 $\sum_{n=1}^\infty a_n$은 수렴하지만 절댓값을 취한 급수 $\sum_{n=1}^\infty |a_n|$이 수렴하지 않을 때, 원래 급수 $\sum_{n=1}^\infty a_n$

# 2. 재배열

### 재배열

- 무한급수 $\sum_{k=1}^\infty a_k$에서 모든 $k \in \mathbb{N}$에 대해 $b_{f(k)} = a_k$이도록 하는 일대일 대응 $f : \mathbb{N} \rarr \mathbb{N}$이 존재할 때, 무한급수 $\sum_{k=1}^\infty b_k$를 $\sum_{k=1}^\infty a_k$의 재배열

### 재배열 명제

- 절대수렴하는 급수의 재배열은 모두 원래 급수의 극한값이 같음