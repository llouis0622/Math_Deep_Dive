# 1. 최소공배수

### 최소공배수(Least Common Multiple)

- 0이 아닌 두 정수 $a$와 $b$의 양의 공배수들 중에서 가장 작은 수
    
    $[a, b] = m$
    
- $a|m, b|m$
- $a|n$이고 $b|n$이면 $m \leq n$

# 2. 최소공배수의 계산

### 최소공배수 명제

- $a, b$의 분해를 $a = p_1^{e_1} \times p_2^{e_2} \times \cdots \times p_k^{e_k}, b = p_1^{f_1} \times p_2^{f_2} \times \cdots \times p_k^{f_k}, e_j \geq 0, f_j \geq 0$일 때, $a$와 $b$의 최소공배수는 다음과 같음
    
    $[a, b] = p_1^{\max(e_1, f_1)} \times p_2^{\max(e_2, f_2)} \times \cdots \times p_k^{\max(e_k, f_k)}$
    

# 3. 최소공배수의 성질

### 최소공배수 성질 명제

- $a$와 $b$가 서로소이면 $[a, b] = a \times b$

# 4. 최대공약수와 최소공배수

### GCD와 LCM 명제

- 정수 $a, b$의 분해를 $a = p_1^{e_1} \times p_2^{e_2} \times \cdots \times p_k^{e_k}, b = p_1^{f_1} \times p_2^{f_2} \times \cdots \times p_k^{f_k}, e_j \geq 0, f_j \geq 0$라 하면, 최대공약수는 다음과 같음
    
    $\gcd(a, b) = p_1^{\min(e_1, f_1)} \times p_2^{\min(e_2, f_2)} \times \cdots \times p_k^{\min(e_k, f_k)}$
    
- $a, b$를 양의 정수라 할 때, 다음 식이 성립
    
    $\gcd(a, b) \times [a, b] = a \times b$
    

# 5. 세 개 이상인 정수의 최소공배수

### 최소공배수 일반화 명제

- $a_1, a_2, a_3, \cdots, a_n$을 0이 아닌 정수라 할 때, 다음이 성립
    
    $[a_1, a_2, a_3, \cdots, a_{n - 1}, a_n] = [[a_1, a_2, a_3, \cdots, a_{n - 1}], a_n]$
    

### 쌍마다 서로소

- 서로 다른 정수 쌍이 모두 서로소인 것
    
    $k \neq m$에 대해, $\gcd(a_k, a_m) = 1$
    

### 쌍마다 서로소 따름정리

- $a_1, a_2, a_3, \cdots, a_n$이 쌍마다 서로소인 정수라면 다음이 성립
    
    $[a_1, a_2, a_3, \cdots, a_n] = a_1 \times a_2 \times \cdots \times a_n$