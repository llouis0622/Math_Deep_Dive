# 1. 오일러 피 함수의 정의

### 오일러 피 함수

- $n$을 자연수라 할 때 $\phi(n)$은 다음과 같음
    
    $\phi(n) = \text{card}\{a \mid \gcd(a, n) = 1, 1 \leq a \leq n\}$
    

# 2. 소수에 대한 오일러 피 함수

### 소수에 대한 오일러 피 함수 명제

- $n$이 소수 $\Leftrightarrow \phi(n) = n - 1$
- 자연수 $n$에 대해 다음이 성립
    
    $\phi(n) = n - 1 \Leftrightarrow n$이 소수
    

# 3. 소수의 거듭제곱에 대한 오일러 피 함수

### 소수의 거듭제곱에 대한 오일러 피 함수 명제

- $p$가 소수, $k$가 자연수라 할 때, 다음이 성립
    
    $\phi(p^k) = p^k - p^{k - 1} = p^{k - 1}(p - 1)$
    

# 4. 임의의 자연수에 대한 오일러 피 함수

### 임의의 자연수에 대한 오일러 피 함수 명제

- $m$과 $n$이 자연수일 때, 오일러 피 함수 $\phi(m \times n)$은 다음과 같이 승법적임
    
    $\gcd(m, n) = 1$일 때, $\phi(m \times n) = \phi(m) \times \phi(n)$
    

### 임의의 자연수에 대한 오일러 피 함수 따름정리

- 정수 $m_j$들이 쌍마다 서로소이면 다음과 같음
    
    $\phi(m_1 \times m_2 \times \cdots \times m_k) = \phi(m_1) \times \phi(m_2) \times \cdots \times \phi(m_k)$
    

### 임의의 자연수에 대한 오일러 피 함수 보조정리

- $p_1, p_2, \cdots, p_r$이 서로 다른 소수이고 $k_1, k_2, \cdots, k_r$이 자연수라 하면 다음과 같음
    
    $\phi(p_1^{k_1} \times p_2^{k_2} \times \cdots \times p_r^{k_r}) = \phi(p_1^{k_1}) \times \phi(p_2^{k_2})\times \cdots \times \phi(p_r^{k_r})$
    
- $n > 1$일 때 $n$을 소인수분해하면 다음과 같음
    
    $p_i$들이 서로 다른 소수일 때, $n = p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_r^{k_r}$
    
    이때 $\phi(n) = (p_1^{k_1} - p_1^{k_1 - 1}) \times (p_2^{k_2} - p_2^{k_2 - 1}) \times (p_3^{k_3} - p_3^{k_3 - 1})  \times \cdots \times (p_r^{k_r} - p_r^{k_r - 1})$
    

### 오일러 피 함수 공식

- $n = p_1^{k_1} \times p_2^{k_2} \times p_3^{k_3} \times \cdots \times p_r^{k_r}$일 때, 다음 결과가 성립
    
    $\phi(n) = n(1 - \frac{1}{p_1})(1 - \frac{1}{p_2})\cdots(1 - \frac{1}{p_r})$
    

### 오일러 피 함수 공식 명제

- $n > 2$에 대해 $\phi(n)$은 짝수