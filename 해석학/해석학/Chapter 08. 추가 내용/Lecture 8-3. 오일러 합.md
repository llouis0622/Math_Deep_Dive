# 1. 월리스 곱

### 월리스 곱

- $\frac{\pi}{2} = \lim_{n \rarr \infty} (\frac{2 \cdot 2}{1 \cdot 3})(\frac{4 \cdot 4}{3 \cdot 5})(\frac{6 \cdot 6}{5 \cdot 7})\cdots(\frac{2n \cdot 2n}{(2n - 1) \cdot (2n + 1)})$
- $\sqrt{\pi} = \lim_{n \rarr \infty} \frac{2^{2n}(n!)^2}{(2n)!\sqrt(n)}$

# 2. 테일러 급수

### 테일러 급수

- $\sqrt{\pi} = \lim_{n \rarr \infty} \frac{1}{c_n\sqrt(n)}$
- $E_N(x) = \frac{1}{\sqrt{1 - x}} - \sum_{n=0}^N c_nx^n$

# 3. 나머지항의 적분 표현

### 적분 나머지항 정리

- $f$가 $(-R, R)$에서 $N + 1$번 미분가능하고 $f^{(N + 1)}$이 연속이라고 가정할 때, $n = 0, 1, \cdots, N$에 대해 $a_n = \frac{f^{(n)}(0)}{n!}$이라 정의하고 다음과 같이 부분합을 정의함
    
    $S_N(x) = a_0 + a_1x + a_2x^2 + \cdots + a_Nx^N$
    
- 모든 $x \in (-R, R)$에 대해 오차 함수 $E_N(x) = f(x) - S_N(x)$는 다음을 만족
    
    $E_N(x) = \frac{1}{N!}\int_0^x f^{(N + 1)}(t)(x - t)^N dt$
    

# 4. $\sum_{n=1}^\infty \frac{1}{n^2}$ 값 구하기

### 오일러 합

- $\theta = \arcsin(\sin(\theta)) = \sum_{n=0}^\infty \frac{c_n}{2n + 1} \sin^{2n + 1}(\theta)$

# 5. 리만-제타 함수

### 리만-제타 함수

- $\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s}$