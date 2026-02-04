# 1. 삼각급수

### 멱급수와 삼각급수

- 멱급수 : $f(x) = \sum_{n=0}^\infty a_nx^n = a_0 + a_1x + a_2x^2 + a_3x^3 + \cdots$
- 삼각급수 : $f(x) = a_0 + \sum_{n=1}^\infty a_n\cos(nx) + b_n\sin(nx)$

### 파동 방정식

- $u(x, t) = \sum_{n=1}^N b_n\sin(nx)\cos(nt)$
- 초기 변위 함수 : $f(x) = \sum{n=1}^N b_n\sin(nx)$

# 2. 주기함수

- 함수 $f(x)$는 값 또는 종좌표를 연달아 나타내는 것이고, 이때 각 값은 임의적임

# 3. 수렴의 유형

### $L^2$ 수렴

- $\int_{-\pi}^{\pi} |S_N(x) - f(x)|^2dx \rarr 0$

### 체사로 평균 수렴

- 부분합의 평균이 $f(x)$로 고르게 수렴함

# 3. 푸리에 계수

### 푸리에 계수

- $a_0 = \frac{1}{2\pi}\int_{-\pi}^{\pi} f(x)dx$

# 4. 리만-르베그 보조정리

### 리만-르베그 보조정리

- $h(x)$가 $$(-\pi, \pi]$$에서 연속이라고 가정하면 $n \rarr \infty$일 때 다음이 성립
    
    $\int_{-\pi}^{\pi} h(x)\sin(nx)dx \rarr 0, \int_{-\pi}^{\pi} h(x)\cos(nx)dx \rarr 0$
    

# 5. 점별수렴 증명

### 점별수렴

- $f(x)$가 $(-\pi, \pi]$에서 연속이라 하고, $S_N(x)$를 푸리에 급수의 $N$번째 부분합이라고 할 때, $f'(x)$가 존재하는 모든 $x \in (-\pi, \pi]$에서 다음과 같이 점별수렴함
    
    $\lim_{N \rarr \infty} S_N(x) = f(x)$
    

# 6. 체사로 평균 수렴

### 페예르 정리

- $S_N(x)$를 $(-\pi, \pi]$에서 함수 $f$에 대한 푸리에 급수의 $n$번째 부분합이라 할 때, 다음과 같이 함수를 정의함
    
    $\sigma_N(x) = \frac{1}{N + 1}\sum_{n=0}^N S_n(x)$
    
- $f$가 $(-\pi, \pi]$에서 연속이면 $\sigma_N(x)$는 $f(x)$로 고르게 수렴

### 페예르 핵

- $F_N(\theta) = \frac{\frac{1}{2} + D_1(\theta) + D_2(\theta) + \cdots + D_N(\theta)}{N + 1} = \frac{1}{2(N + 1)}[\frac{\sin((N + 1)\frac{\theta}{2})}{\sin(\frac{\theta}{2})}]^2$

# 7. 바이어슈트라스 근사 정리

### 바이어슈트라스 근사 정리

- $f : [a, b] \rarr \mathbb{R}$는 연속함수라 할 때, 상수 $\epsilon > 0$과 모든 $x \in [a, b]$에 대해 다음을 만족하는 다항함수 $p(x)$가 존재
    
    $|f(x) - p(x)| < \epsilon$