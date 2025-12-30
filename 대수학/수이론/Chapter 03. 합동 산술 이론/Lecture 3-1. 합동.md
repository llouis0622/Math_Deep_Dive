# 1. 합동

### 합동

- $n$을 고정된 양의 정수, $a, b$를 정수라 할 때 다음을 만족하면 $a$와 $b$는 법 $n$에 대해 합동
    
    $a \equiv b\pmod n \Leftrightarrow a - b$가 $n$의 배수이거나 정수 $k$가 존재하여 $a - b = kn$ 만족
    

### 합동 명제

- $a$를 정수라고 할 때 다음이 성립
    
    $a \equiv 0 \pmod n \Leftrightarrow n \mid a$
    

# 2. 완전 잉여계

### 잉여

- $a = (n \times q) + r, 0 \leq r < n \Leftrightarrow a \equiv r \pmod n$에서 나머지 $r$ 지칭

### 완전 잉여 집합과 완전 잉여계

- 모든 정수가 집합 $\{r_1, r_2, r_3, \cdots, r_{n - 1}, r_n\}$에서 단 하나의 $r_k$와 합동인 경우
- 집합이 모든 지점을 포함
- 집합이 각 지점에서 단 한 번씩만 멈춤

### 합동과 잉여 명제

- 임의의 정수 $a, b$에 대해 다음이 성립
    
    $a \equiv b \pmod n \Leftrightarrow a$와 $b$를 $n$으로 나누었을 때, 음이 아닌 나머지가 동일
    

### 합동이 아님

- 법 $n$에 대해 $a$와 $b$가 합동이 아님
    
    $a \not\equiv b \pmod n$
    

# 3. 합동의 성질

### 합동의 성질

- $a \equiv a \pmod n$
- $a \equiv b \pmod n$이면 $b \equiv a \pmod n$
- $a \equiv b \pmod n$이고 $b \equiv c \pmod n$이면 $a \equiv c \pmod n$

$a \equiv b \pmod n, c \equiv d \pmod n$일 때

- $a + c \equiv b + d \pmod n$
- $ac \equiv bd \pmod n$

# 4. 정수 적용

### 합동의 성질 따름정리

$a \equiv b \pmod n$일 때, 임의의 정수 $c$에 대해 다음이 성립

- $a + c \equiv b + c \pmod n$
- $ac \equiv bc \pmod n$

# 5. 지수 적용

### 합동의 성질

- $a \equiv b \pmod n$이면 자연수 $k$에 대해 $a^k \equiv b^k \pmod n$

# 6. 나누어떨어짐의 판별

### 합동과 나눗셈 명제

- $P(x) = c_0 + c_1x + c_2x^2 + \cdots + c_{m - 1}x^{m - 1} + c_mx^m$을 $m$차 다항식이라 할 때 다음이 성립
    
    $c_m \not\equiv 0 \pmod n$
    
    $a \equiv b \pmod n$이면 $P(a) \equiv P(b) \pmod n$