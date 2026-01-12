# 1. 위수의 정의

### 위수

- $n > 1$이고 $\gcd(a, n) = 1$일 때, 법 $n$에 대해 $a$의 위수는 $a^k \equiv 1 \pmod n$을 만족하는 가장 작은 양의 정수 $k$

# 2. 위수의 성질

### 위수의 성질

- $a \equiv b \pmod n$이면 $\bmod \ n$에 대해 $a$와 $b$의 위수가 동일
- $\gcd(a, n) > 1$이면 임의의 양의 정수 $k$에 대해 $a^k \not\equiv 1 \pmod n$

# 3. 위수의 또 다른 성질

### 위수의 성질 명제

- 법 $n$에 대해 $a$의 위수가 $k$이면 다음과 같음
    
    $a^h \equiv 1 \pmod n \Leftrightarrow k \mid h$
    
- 법 $n$에 대해 $a$의 위수를 $k$라 하면 $k \mid \phi(n)$

# 4. 지수 간의 관계

### 위수와 지수

- 법 $n$에 대해 $a$의 위수를 $k$라 하면 양의 정수 $j, m$에 대해 다음이 성립
    
    $a^j \equiv a^m \pmod n \Leftrightarrow j \equiv m \pmod k$