# 1. 선형합동식 풀기

### 선형합동식

- $ax \equiv b \pmod n$
- 음이 아닌 최소 잉여에 대해서만 고려

# 2. 선형합동식의 해

### 선형합동식 명제

- 선형합동식 $ax \equiv b \pmod n$의 해가 존재 $\Leftrightarrow g = \gcd(a, n)$에 대해 $g \mid b$
- 선형방정식 $ax \equiv b \pmod n$이 $g = \gcd(a, n)$에 대해 $g \mid b$라면 법 $n$에 대해 정확히 $g$개의 합동이 아닌 해를 가짐

# 3. 선형합동식 풀기

### 선형합동식 풀기

- 합동식에서 공통 인수로 나누기
- 나머지 해 찾기

# 4. 유일한 해

### 선형합동식 따름정리

- $\gcd(a, n) = 1$이면 선형합동식 $ax \equiv b \pmod n$은 법 $n$에 대해 유일한 해를 가짐

# 5. 곱셈에 대한 역원

### 곱셈에 대한 역원

- $ax \equiv 1 \pmod n$일 때, 이 합동식의 유일한 해 $x$를 법 $n$에 대해 $a$의 곱셈에 대한 역원이라 함
    
    $a^{-1} \pmod n$
    

### 곱셈에 대한 역원 명제

- $a \pmod n$의 역원 존재 $\Leftrightarrow \gcd(a, n) = 1$
- 자기 가역적 : $a^{-1} \equiv a \pmod n$