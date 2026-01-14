# 1. 평균값 정리

### 롤의 정리

- 구간 $[a, b]$에서 연속이고 구간 $(a, b)$에서 미분가능한 함수 $f : [a, b] \rarr \mathbb{R}$에 대해 $f(a) = f(b)$이면 $f'(c) = 0$인 점 $c \in (a, b)$가 존재

### 평균값 정리

- $[a, b]$에서 연속이고 $(a, b)$에서 미분가능한 $f : [a, b] \rarr \mathbb{R}$에 대해 다음을 만족하는 $c \in (a, b)$가 존재
    
    $f'(c) = \frac{f(b) - f(a)}{b - a}$
    

### 평균값 정리 따름정리

- 함수 $g : A \rarr \mathbb{R}$가 구간 $A$에서 미분가능하고 모든 $x \in A$에 대해 $g'(x) = 0$이면 $g(x) = k$
- $f$와 $g$가 구간 $A$에서 미분가능한 함수고 모든 $x \in A$에 대해 $f'(x) = g'(x)$이면 $f(x) = g(x) + k$

### 코시 평균값 정리

- 닫힌 구간 $[a, b]$에서 연속이고 열린 구간 $(a, b)$에서 미분가능한 함수 $f$와 $g$에 대해 다음을 만족하는 점 $c \in (a, b)$가 존재
    
    $[f(b) - f(a)]g'(c) = [g(b) - g(a)]f'(c)$
    
- 만약 $g'$이 구간 $(a, b)$에서 절대 0이 되지 않으면 다음과 같이 나타낼 수 있음
    
    $\frac{f'(c)}{g'(c)} = \frac{f(b) - f(a)}{g(b) - g(a)}$
    

# 2. 로피탈 정리

### $\frac{0}{0}$꼴 로피탈 정리

- 점 $a$를 포함하는 구간에서 연속이고 점 $a$를 제외한 이 구간에서 미분가능한 두 함수 $f$와 $g$를 생각할 때, $f(a) = g(a) = 0$이고 모든 $x \neq a$에 대해 $g'(x) \neq 0$이고 $\lim_{x \rarr a} \frac{f'(x)}{g'(x)} = L$이면 $\lim_{x \rarr a} \frac{f(x)}{g(x)} = L$

### 로피탈 정리 발산 적용

- $g : A \rarr \mathbb{R}$와 $A$의 극한점 $c$를 생각할 때 임의의 $M > 0$에 대해 $0 < |x - c| < \delta$이면 $g(x) \geq M$이도록 하는 $\delta > 0$이 존재할 때, $\lim_{x \rarr c} g(x) = \infty$

### $\frac{\infty}{\infty}$꼴 로피탈 정리

- 두 함수 $f$와 $g$가 $(a, b)$에서 미분가능하고 모든 $x \in (a, b)$에 대해 $g'(x) \neq 0$이라 가정하면 $\lim_{x \rarr a} g(x) = \infty$이고 $\lim_{x \rarr a} \frac{f'(x)}{g'(x)} = L$이면 $\lim_{x \rarr a} \frac{f(x)}{g(x)} = L$