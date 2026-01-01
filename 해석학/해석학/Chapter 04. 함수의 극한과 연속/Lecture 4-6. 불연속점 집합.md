# 1. 단조함수에 대한 집합 $D_f$

### 단조함수

- 증가 : 함수 $f : A \rarr \mathbb{R}$가 $x < y$일 때 항상 $f(x) \leq f(y)$인 것
- 감소 : 함수 $f : A \rarr \mathbb{R}$가 $x < y$일 때 항상 $f(x) \geq f(y)$인 것
- 단조함수 : 증가함수와 감소함수 모두를 포함

### 우극한

- 집합 $A$의 극한점 $c$와 함수 $f : A \rarr \mathbb{R}$에 대해 모든 $\epsilon > 0$에 대해 $0 < x - c < \delta$일 때 $|f(x) - L| < \epsilon$이 되는 $\delta$가 존재하면 다음과 같이 씀
    
    $\lim_{x \rarr c^+} f(x) = L$
    
- $x_n > c$이고 $\lim (x_n) = c$인 모든 수열 $(x_n)$에 대해 $\lim f(x_n) = L$이면 다음과 같이 나타냄
    
    $\lim_{x \rarr c^+} f(x) = L$
    

### 극한점 명제

- 함수 $f : A \rarr \mathbb{R}$와 $A$의 극한점 $c$에 대해 $\lim_{x \rarr c} f(x) = L$인 필요충분조건은 다음과 같음
    
    $\lim_{x \rarr c^-} f(x) = L$이고 $\lim_{x \rarr c^+} f(x) = L$
    

### 불연속성

- 제거 가능한 불연속점 : 극한 $\lim_{x \rarr c} f(x)$가 존재하지만 $f(c)$와 다를 때의 $c$
- 비약 불연속점 : $\lim_{x \rarr c^+} f(x) \neq \lim_{x \rarr c^-} f(x)$일 때 $c$
- 본질적 불연속점 : 위 2개가 아닌 다른 이유로 극한 $\lim_{x \rarr c} f(x)$가 존재하지 않을 때의 $c$

# 2. 임의의 함수에 대한 집합 $D_f$

### $F_\sigma$ 집합

- 닫힌 집합의 셀 수 있는 합집합으로 나타낼 수 있는 집합

### $\alpha$-연속성

- 함수 $f$가 $\mathbb{R}$에서 정의되고 $\alpha > 0$이라 할 때 $y, z \in (x - \delta, x + \delta)$이면 항상 $|f(y) - f(z)| < \alpha$가 되게 하는 $\delta > 0$가 존재할 때 함수 $f$가 $x \in \mathbb{R}$에서 $\alpha$-연속

### 불연속점 집합

- $f : \mathbb{R} \rarr \mathbb{R}$가 임의의 함수라 할 때 $D_f$는 $F_\sigma$ 집합