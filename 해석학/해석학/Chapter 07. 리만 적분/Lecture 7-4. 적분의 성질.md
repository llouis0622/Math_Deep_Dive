# 1. 미분적분학

### 미분적분학 기본성질

- 유계 함수 $f : [a, b] \rarr \mathbb{R}$와 점 $c \in (a, b)$에 대해 $f$가 $[a, b]$에서 적분가능하기 위한 필요충분조건은 $f$가 $[a, c]$와 $[c, b]$에서 적분가능
    
    $\int_a^b f = \int_a^c f + \int_c^b f$
    

### 적분의 기본 성질

$f$와 $g$가 구간 $[a, b]$에서 적분가능한 함수라고 가정

- 함수 $f + g$는 $[a, b]$에서 적분가능하고 $\int_a^b (f + g) = \int_a^b f + \int_a^b g$
- $k \in \mathbb{R}$에 대해 함수 $kf$는 적분가능하고 $\int_a^b kf = k \int_a^b f$
- $[a, b]$에서 $m \leq f(x) \leq M$이면 $m(b - a) \leq \int_a^b f \leq M(b - a)$
- $[a, b]$에서 $f(x) \leq g(x)$이면 $\int_a^b f \leq \int_a^b g$
- 함수 $|f|$는 적분가능하고 $|\int_a^b f| \leq \int_a^b |f|$

### 적분의 기본 성질 명제

- $f$가 구간 $[a, b]$에서 적분가능할 때, 다음과 같이 정의
    
    $\int_b^a f = -\int_a^b f$
    
- $c \in [a, b]$에 대해 다음과 같이 정의
    
    $\int_c^c f = 0$
    

# 2. 고른 수렴과 적분

### 적분과 고른 수렴

- $[a, b]$에서 $f_n$이 고르게 수렴하고 각 $f_n$이 적분가능하다고 가정할 때 $f$는 적분가능하며 다음이 성립
    
    $\lim_{n \rarr \infty} \int_a^b f_n = \int_a^b f$