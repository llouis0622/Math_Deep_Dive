# 1. 지수함수

### 지수함수

- $E(x) = \sum_{n=0}^\infty \frac{x^n}{n!} = 1 + x + \frac{x^2}{2!} + \frac{x^3}{e!} + \cdots$

### 지수함수 명제

- 함수 $f : [a, \infty] \rarr \mathbb{R}$에 대해 모든 $\epsilon > 0$에 대해 다음 조건을 만족하는 $M > a$이 존재하면 $\lim_{x \rarr \infty} f(x) = L$이라 함
    
    $x \geq M$이면 항상 $|f(x) - L| < \epsilon$
    

# 2. 밑이 다른 지수함수

### 지수함수

- $t > 0$이 주어질 때 지수함수를 $t^x = e^{x \log t}$로 정의함

# 3. 함수방정식

### 함수방정식

- $x! = x(x -1)!$

# 4. 이상적분

### 이상적분

- $\int_0^\infty e^{-t}dt$
- $[0, \infty)$와 같이 유계가 아닌 영역에서의 적분
- 정상 적분의 극한값

### 수렴

- $f$가 $[0, \infty)$에서 정의되고 $[a, b]$ 꼴의 모든 구간에서 적분가능하다고 가정할 때, $\int_a^\infty f$를 다음과 같이 정의
    
    $\lim_{b \rarr \infty} \int_a^b f$
    
- 이때 이상적분 $f$는 수렴

# 5. 적분 기호 속 미분

### 연속

- 모든 $\epsilon > 0$에 대해 다음을 만족하는 $\delta > 0$이 존재할 때, 함수 $f : D \rarr \mathbb{R}$는 점 $(x_0, t_0)$에서 연속
    
    $||(x, t) - (x_0, t_0)|| < \delta \Rightarrow |f(x, t) - f(x_0, t_0)| < \epsilon$
    

### 고른 연속

- $f(x, t)$가 $D$에서 연속이면 $F(x) = \int_c^d f(x, t)dt$는 $[a, b]$에서 고른 연속

### 도함수

- $f(x, t)$와 $f_x(x, t)$가 $D$에서 연속이면 함수 $F(x) = \int_c^d f(x, t)dt$는 미분가능하며 그 도함수는 다음과 같음
    
    $F'(x) = \int_c^d f_x(x, t)dt$
    

# 6. 이상적분 확장

### 고른 수렴

- $D = \{(x, t) \mid x \in A, c \leq t\}$에서 정의된 $f(x, t)$가 주어질 때 모든 $x \in A$에 대해 $F(x) = \int_c^\infty f(x, t)dt$가 존재한다고 가정하면, 모든 $\epsilon > 0$에 대해 $M > c$이 존재하여 모든 $d \geq M$와 $x \in A$에 대해 다음이 성립할 때, 이상적분이 $A$에서 $F(x)$로 고르게 수렴함
    
    $|F(x) - \int_c^d f(x, t)dt| < \epsilon$
    

### 고른 연속

- $f(x, t)$가 $D = \{(x, t) \mid a \leq x \leq b, c \leq t\}$에서 연속이면 다음 $F(x)$는 적분이 고르게 수렴하는 경우 $[a, b]$에서 고른 연속
    
    $F(x) = \int_c^\infty f(x, t)dt$
    

### 도함수

- 함수 $f(x, t)$가 $D = \{(x, t) \mid a \leq x \leq b, c \leq t\}$에서 연속이고 각 $x \in [a, b]$에 대해 $F(x) = \int_c^\infty f(x, t)dt$가 존재한다고 가정할 때, 도함수 $f_x(x, t)$가 존재하고 연속이면 적분이 고르게 수렴할 때 다음이 성립
    
    $F'(x) = \int_c^\infty f_x(x, t)dt$
    

# 7. 팩토리얼 함수

### 팩토리얼 함수

- $x \geq 0$에 대해 팩토리얼 함수(계승 함수)는 다음과 같음
    
    $x! = \int_0^\infty t^xe^{-t}dt$
    

### 보어-몰레럽 정리

$x \geq 0$에서 정의된 양의 함수 $f$ 중 다음을 만족하는 함수는 단 하나뿐임

- $f(0) = 1$
- $f(x + 1) = (x + 1)f(x)$
- $\log(f(x))$는 볼록함수
- $x!$은 위 조건을 모두 만족 → $f(x) = x!$

### 가우스 곱셈 공식

- $x! = \int_0^\infty t^xe^{-t}dt = \lim_{n \rarr \infty} \frac{n^xn!}{(x + 1)(x + 2)\cdots(x + n)}$

# 8. 감마함수

### 감마함수

- $\Gamma(x) = (x - 1)! = \int_0^\infty t^{x - 1}e^{-t}dt$