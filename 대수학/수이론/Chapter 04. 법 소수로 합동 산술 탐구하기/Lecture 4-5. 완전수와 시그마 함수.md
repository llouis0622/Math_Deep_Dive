# 1. 완전수

### 뤼카-레머 메르센 소수 판별법

- 메르센 수 $M_p = 2^p - 1$이 소수 $\Leftrightarrow$ 정수 $k \geq 1$에 대해 $S_k$가 $S_0 = 4$$와 $S_k \equiv S_{k - 1}^2 - 2 \pmod {M_p}$를 만족하는 음이 아닌 최소의 잉여일 때, $S_{p - 2} \equiv 0 \pmod {M_p}$

### 진약수

- 자기 자신인 $n$을 제외한 $n$의 모든 양의 약수

### 완전수, 과잉수, 부족수

- 완전수 : 자연수 $n$의 모든 진약수 합이 $n$인 수
- 과잉수 : 자연수 $n$의 모든 진약수 합이 $n$보다 큰 수
- 부족수 : 자연수 $n$의 모든 진약수 합이 $n$보다 작은 수

### 완전수 명제

- $p$가 소수이고 메르센 수 $2^p - 1$이 소수라면 다음과 같음
    
    $N = 2^{p - 1}(2^p - 1)$은 완전수
    
- 짝수인 모든 완전수는 $N = 2^{p - 1}(2^p - 1)$ 형태
    
    이때 $(2^p - 1)$은 소수
    

# 2. 시그마 함수

### 시그마 함수

- $\sigma(n)$은 $n$의 모든 양의 약수의 합
    
    $n$의 모든 약수를 $d_1, d_2, \cdots, d_k$라 하면 다음과 같음
    
    $\sigma(n) = d_1 + d_2 + \cdots + d_k$
    

# 3. 시그마 함수의 성질

### 소수의 시그마 함수

- $p$는 소수 $\Leftrightarrow \sigma(p) = p + 1$

### 완전수의 시그마 함수

- $n$이 완전수이면 $\sigma(n) = 2n$

### 승법적

- 양의 정수 $n = a \times b$에 대해 일반적인 함수 $f(n)$가 다음을 만족하는 것
    
    $\gcd(a, b) = 1$일 때, $f(a \times b) = f(a) \times f(b)$
    
- $p_i(1 \leq i \leq m)$가 서로 다른 소수일 때, $n = p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_m^{k_m}$
    
    $\sigma(n) = \sigma(p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_m^{k_m}) = \sigma(p_1^{k_1}) \times \sigma(p_2^{k_2}) \times \sigma(p_3^{k_3}) \times \cdots \times \sigma(p_m^{k_m})$
    

### 시그마 함수 명제

- $p$가 소수이고 $k$가 양의 정수일 때 다음과 같음
    
    $\sigma(p^k) = \frac{p^{k + 1} - 1}{p - 1}$
    

# 4. 시그마 함수의 승법적 성질

### 시그마 함수의 승법적 성질

- 서로 다른 소수 $p, q$에 대해 $n = p^k \times q^m$이면 다음과 같음
    
    $\sigma(n) = \sigma(p^k \times q^m) = \sigma(p^k) \times \sigma(q^m)$
    

### 시그마 함수의 승법적 성질 명제

- 서로 다른 소수 $p_j$에 대해 자연수 $n$의 소인수분해를 $n = p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_m^{k_m}$라 하면 다음과 같음
    
    $\sigma(n) = \sigma(p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_m^{k_m}) = \sigma(p_1^{k_1}) \times \sigma(p_2^{k_2}) \times \sigma(p_3^{k_3}) \times \cdots \times \sigma(p_m^{k_m})$
    
- 시그마 함수 $\sigma(n)$은 승법적