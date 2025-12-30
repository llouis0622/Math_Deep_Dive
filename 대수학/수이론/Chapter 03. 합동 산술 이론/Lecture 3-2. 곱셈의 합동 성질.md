# 1. 합동에서 소거하기

### 합동 소거 명제

- $ac \equiv bc \pmod n$이면 $g = \gcd(c, n)$에 대해 $a \equiv b (\bmod\frac{n}{g})$

### 소거법칙

- $ac \equiv bc \pmod n$이고 $\gcd(c, n) = 1$이면 $a \equiv b \pmod n$
- 소수 $p$에 대해 $ac \equiv bc \pmod p$이고 $p \nmid c$이면 다음과 같음
    
    $a \equiv b \pmod p$
    

# 2. 법 $n$에 대하여 0과 관련된 합동의 성질

### 법 $n$에 대한 합동 명제

- $a \times b \equiv 0 \pmod n$이고 $\gcd(a, n) = 1$이면 $b \equiv 0 \pmod n$

$p$를 소수라 할 때, 다음이 성립

- $a \times b \equiv 0 \pmod p \Rightarrow a \equiv 0 \pmod p \ \text{or} \ b \equiv 0 \pmod p$
- $a^2 \equiv b^2 \pmod p \Leftrightarrow a \equiv \pm b \pmod p$