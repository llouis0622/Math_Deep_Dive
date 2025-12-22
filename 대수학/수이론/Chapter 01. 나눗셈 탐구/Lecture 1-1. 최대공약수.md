# 1. 나눗셈

### 나눗셈

- 나눗셈 : $a \times m = b$를 만족하는 정수 $m$이 존재하는 것, $a|b$
- 약수(인수) : $a$는 $b$의 약수
- 배수 : $b$는 $a$의 배수

### 약수의 성질

- $a | 1 \Leftrightarrow a = \pm 1$
- $a|b, b|c \Rightarrow a|c$
- $a|b, c|d \Rightarrow (a \times c) | (b \times d)$
- $a|b, b|a \Leftrightarrow a = \pm b$
- $a|b, b \neq 0 \Rightarrow |a| \leq |b|$

# 2. 일차결합

### 일차결합

- $bx + cy$ 형태의 정수

### 일차결합 정리

- $a|b, a|c \Rightarrow$ 임의의 정수 $x, y$에 대해 $a|(bx + cy)$
- $a|b_1, a|b_2, a|b_3, \cdots, a|b_n \Rightarrow a|(b_1x_1 + b_2x_2 + b_3x_3 + \cdots + b_nx_n)$

# 3. 최대공약수

### 최대공약수(Greatest Common Divisor)

- 양의 정수 $g$가 0이 아닌 두 정수 $a$와 $b$의 최대공약수
    
    $\Leftrightarrow g|a, g|b$
    
    $\Leftrightarrow$ 임의의 $c$에 대해 $c|a, c|b \Rightarrow c \leq g$
    

### 최대공약수 명제

- $\gcd(a, b) = g \Rightarrow \gcd(\frac{a}{g}, \frac{b}{g}) = 1$

### 2개 이상의 정수에 대한 최대공약수

- 양의 정수 $g$가 모든 원소가 0이 아닌 정수 집합 $S = \{a_1, a_2, a_3, \cdots, a_n\}$의 최대공약수
    
    $\Leftrightarrow g$는 집합 $S$의 모든 정수를 나누는 가장 큰 정수
    
- 일반적으로 $g = \gcd(a_1, a_2, a_3, \cdots, a_n)$
- 0이 아닌 정수 $a, b, c \Rightarrow \gcd(a, b, c) = \gcd(a, \gcd(b, c))$