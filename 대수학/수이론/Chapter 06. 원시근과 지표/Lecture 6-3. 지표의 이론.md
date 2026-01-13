# 1. 원시근

### 원시근

- $a \pmod n$의 위수가 $\phi(n)$이면 $a$를 법 $n$에 대한 원시근이라 함

### 원시근 명제

- $\gcd(r, n) = 1$이고 $r_1, r_2, r_3, \cdots, r_{\phi(n)}$을 $n$과 서로소인 정수라 할 때, 만약 $r$이 $n$의 원시근이라면 $r, r^2, r^3, \cdots, r^{\phi(n)}$은 법 $n$에 대해 $r_1, r_2, r_3, \cdots, r_{\phi(n)}$과 어떤 순서로 합동

# 2. 지표의 정리

### 지표

- $r$이 법 $n$의 원시근일 때, $\gcd(a, n) = 1$이면 다음을 만족하는 가장 작은 양의 지수 $k$를 $r$에 대한 $a$의 지표
    
    $r^k \equiv a \pmod n$
    
- k를 $\text{ind}_r(a), \text{ind}(a)$라 함

# 3. 지표의 성질

### 지표 명제

- $r$이 $n$의 원시근이면 $\text{ind}_r(r) = 1$
- $r$이 $n$의 원시근일 때 $a \equiv b \pmod n$이면 다음과 같음
    
    $\text{ind}_r(a) \equiv \text{ind}_r(b)$
    

### 지표의 성질

$r$이 $n$의 원시근이고 $\text{ind}_r(a)$는 $r$에 대한 $a$의 지표라 하면 다음 결과가 성립

- $\text{ind}_r(ab) \equiv \text{ind}_r(a) + \text{ind}_r(b) \pmod {\phi(n)}$
- $\text{ind}_r(a^k) \equiv \text{ind}_r(a) \pmod {\phi(n)}$
- $\text{ind}_r(1) \equiv 0 \pmod {\phi(n)}, \text{ind}_r(r) \equiv 1 \pmod {\phi(n)}$

# 4. 비선형 디오판토스 합동방정식 풀기

### 합동식 변형

- $x^d \equiv a \pmod n \Leftrightarrow d \text{ind}(x) \equiv \text{ind}(a) \pmod {\phi(n)}$

# 5. $x^m \equiv a \pmod n$의 해 판별법

### 해 판별법

- $n$이 원시근을 갖고 $a$와 $n$이 서로소라고 할 때 다음이 성립
    
    합동식 $x^m \equiv a \pmod n$은 해를 가짐
    
- $g = \gcd(m, \phi(n))$이라 할 때, $a^{\frac{\phi(n)}{g}} \equiv 1 \pmod n$
    
    이 합동식은 합동이 아닌 $g$개의 해를 가짐