# 1. 오일러 정리 소개

### 법 $n$에 대한 기약 잉여계

다음을 만족하는 정수들의 집합 $\{r_1, r_2, \cdots, r_{\phi(n)}\}$

- $i = 1, 2, 3, \cdots, \phi(n)$에 대해 $\gcd(r_i, n) = 1$
- $i \neq j$에 대해 $r_i \not\equiv r_j \pmod n$

# 2. 오일러 정리의 증명

### 기약 잉여계 보조정리

- $\gcd(a, n_1) = \gcd(a, n_2) = \cdots = \gcd(a, n_k) = 1$이면 다음이 성립
    
    $\gcd(a, n_1 \times n_2 \times \cdots \times n_k) = 1$
    
- $n > 1$이고 $\gcd(a, n) = 1$일 때 $\{r_1, r_2, r_3, \cdots, r_{\phi(n)}\}$이 법 $n$에 대한 기약 잉여계라면 다음 집합도 기약 잉여계
    
    $S = \{ar_1, ar_2, ar_3, \cdots, ar_{\phi(n)}\}$
    

### 오일러 정리

- $n$이 1보다 큰 정수이고 $\gcd(a, n) = 1$이면 다음이 성립
    
    $a^{\phi(n)} \equiv 1 \pmod n$
    

### 페르마의 소정리

- 정수 $a$와 소수 $p$에 대해 $p$가 $a$를 나누지 않으면 다음이 성립
    
    $a^{p - 1} \equiv 1 \pmod p$