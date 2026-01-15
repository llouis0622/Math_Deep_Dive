# 1. 연속성

### 함수급수의 수렴

각 $n \in \mathbb{N}$에 대해 $f_n$과 $f$가 집합 $A \subseteq \mathbb{R}$에서 정의된 함수라 하고 부분합의 수열 $s_k(x)$를 다음과 같이 정의함

$s_k(x) = f_1(x) + f_2(x) + \cdots + f_k(x)$

- $s_k(x)$가 $f(x)$로 점별수렴하면 다음 무한급수가 $A$에서 $f(x)$로 점별수렴
    
    $\sum_{n=1}^\infty f_n(x) = f_1(x) + f_2(x) + f_3(x) + \cdots$
    
- 수열 $s_k(x)$가 $A$에서 $f(x)$로 고르게 수렴하면 함수급수가 $A$에서 $f(x)$로 고르게 수렴
- 점별수렴, 고르게 수렴 모두 $f = \sum_{n=1}^\infty f_n$ 또는 $f(x) = \sum_{n=1}^\infty f_n(x)$로 씀

### 연속과 함수급수

- $f_n$이 집합 $A \subseteq \mathbb{R}$에서 정의된 연속함수이고 $\sum_{n=1}^\infty f_n$이 $A$에서 함수 $f$로 고르게 수렴한다고 가정하면 $f$는 $A$에서 연속

### 미분가능성과 함수급수

- $f_n$이 집합 $A$에서 정의된 미분가능한 함수라고 하고, $\sum_{n=1}^\infty f'_n(x)$가 $A$에서 함수 $g(x)$로 고르게 수렴한다고 가정하면 어떤 점 $x_0 \in [a, b]$에서 $\sum_{n=1}^\infty f_n(x_0)$가 수렴하면 함수급수 $\sum_{n=1}^\infty f_n(x)$는 미분가능한 함수 $f(x)$로 고르게 수렴하며 $A$에서 $f'(x) = g(x)$
    
    $f(x) = \sum_{n=1}^\infty f_n(x), f'(x) = \sum_{n=1}^\infty f'_n(x)$
    

### 함수급수에 대한 코시 판정법

- 함수급수 $\sum_{n=1}^\infty f_n$이 $A \subseteq \mathbb{R}$에서 고르게 수렴할 필요충분조건은 모든 $\epsilon > 0$에 대해 $N \in \mathbb{N}$이 있어 $n > m \geq N$이고 $x \in A$이면 다음 부등식을 만족함
    
    $|f_{m+1}(x) + f_{m+2}(x) + f_{m+3}(x) + \cdots + f_n(x)| < \epsilon$
    

### 바이어슈트라스 $M$-판정법

- 각 $n \in \mathbb{N}$에 대해 $f_n$이 집합 $A \subseteq \mathbb{R}$에서 정의된 함수라 하고 모든 $x \in A$에 대해 실수 $M_n > 0$이 다음을 만족함
    
    $|f_n(x)| \leq M_n$
    
- 무한급수 $\sum_{n=1}^\infty M_n$이 수렴하면 함수급수 $\sum_{n=1}^\infty f_n$은 $A$에서 고르게 수렴