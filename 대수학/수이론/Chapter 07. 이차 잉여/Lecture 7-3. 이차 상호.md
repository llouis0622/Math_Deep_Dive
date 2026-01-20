# 1. 가우스의 보조정리

### 이차 잉여 보조정리

- $p$가 홀수인 소수이고 $a$가 $p \nmid a$인 정수일 때, 다음 잉여들은 서로 합동이 아님
    
    $a, 2a, 3a, \cdots, (\frac{p - 1}{2})a \pmod p$
    
- $p$가 홀수인 소수이고 $a$가 $p \nmid a$인 정수일 때, 다음이 성립
    
    $a, 2a, 3a, \cdots, (\frac{p - 1}{2})a \not\equiv 0 \pmod p$
    

### 가우스의 보조정리

- $p$가 홀수인 소수이고 $a$가 $p \nmid a$인 정수일 때, $p$에 대한 최소의 양수 잉여의 앞부분 절반과 $a$의 곱에 대한 집합을 생각해보자
    
    $S = \{a, 2a, 3a, \cdots, (\frac{p - 1}{2})a\}$
    
- $g$를 이 목록에 있는 음수 잉여의 개수라 하면 음수 잉여들은 $\frac{p - 1}{2}$보다 큰 수들이며, 이때 르장드르 기호 $\left(\frac{a}{p}\right) = (-1)^g$가 성립

# 2. 2가 이차 잉여인지 확인하기

### 이차 잉여 확인

- $p$가 홀수인 소수이면 다음이 성립
    
    $\left(\frac{2}{p}\right) = \begin{cases}1 & p \equiv \pm 1 \pmod 8 \\ -1 & p \equiv \pm 3 \pmod 8\end{cases}$
    

# 3. 이차 상호 법칙

### 이차 상호 법칙(LQR)

- $p, q$를 서로 다른 홀수인 소수라 하면 다음이 성립
    
    $\left(\frac{p}{q}\right) \times \left(\frac{q}{p}\right) = (-1)^{(\frac{p - 1}{2}) \times (\frac{q - 1}{2})}$
    

### 이차 상호 법칙 따름정리

- $p, q$를 서로 다른 홀수인 소수라 하면 다음이 성립
    
    $\left(\frac{p}{q}\right) = \begin{cases}(\frac{q}{p}) & p \equiv 1 \pmod 4 \ \text{or} \ q \equiv 1 \pmod 4 \\ -(\frac{q}{p}) & p \equiv 3 \pmod 4 \ \text{or} \ q \equiv 3 \pmod 4\end{cases}$
    
- 홀수인 소수 $p$에 대해 $\left(\frac{2}{p}\right) = (-1)^{\frac{p^2 - 1}{8}}$ 성립