# 1. 지수에 대한 표

### 법 $n$에 대한 표

- 법 $n$에 대한 최소의 양수 잉여 $n - 1$까지의 제곱을 계산한 결과를 표로 나타냄

### 페르마의 마지막 정리(FLT)

- $n \geq 3$에 대해 $x^n + y^n = z^n$을 만족하는 양의 정수 $x, y, z$는 존재하지 않음

# 2. 페르마의 소정리 증명

### 페르마의 소정리(FlT)

- 정수 $a$와 소수 $p$에 대해 $p$가 $a$를 나누지 않으면 다음이 성립
    
    $a^{p - 1} \equiv 1 \pmod p$
    

### 페르마의 소정리 증명

- $1 \leq k < m \leq p - 1$에 대해 $k \times a \equiv m \times a \pmod p$
- $a \times c \equiv b \times c \pmod p$이고 $p \nmid c$이면 $a \equiv b \pmod p$
- $a \times 2a \times 3a \times \cdots \times (p - 1)a \equiv (p - 1)! \times a^{p - 1} \pmod p$
- $(p - 1)! \times a^{p - 1} \equiv (p - 1)!\pmod p$
- $a^{p - 1} \equiv 1 \pmod p$

# 3. 페르마의 소정리 적용

### 페르마의 소정리 따름정리

- 임의의 정수 $a$와 소수 $p$에 대해 $a^p \equiv a \pmod p$

### 합성수 판단

- $a^{n - 1} \not\equiv 1 \pmod n$이면 $n$은 합성수

# 4. 유사소수

### 유사소수

- 합성수이지만 $a^{n - 1} \equiv 1 \pmod n$ 성립하는 수

### 카마이클 수

- $\gcd(a, n) = 1$이며, $a^{n - 1} \equiv 1 \pmod n$이 성립하는 수