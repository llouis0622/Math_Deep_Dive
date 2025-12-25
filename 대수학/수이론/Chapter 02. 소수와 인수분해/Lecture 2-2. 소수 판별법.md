# 1. 바닥함수와 천장함수

### 바닥함수

- $x$와 같거나 작은 정수 중에서 가장 큰 값
    
    $\lfloor x \rfloor = \max\{n|n \leq x, n \in \mathbb{N}\}$
    

### 천장함수

- $x$와 같거나 큰 정수 중에서 가장 작은 값
    
    $\lceil x \rceil = \min\{n|n \geq x, n \in \mathbb{N}\}$
    

# 2. 합성수의 판별

### 합성수의 판별법

- $n$이 합성수라면 약수 $d$가 존재하며 $1 < d \leq \lfloor \sqrt{n}\rfloor$ 만족
- $1 < d \leq \lfloor \sqrt{n}\rfloor$을 만족하는 $n$의 약수 $d$가 존재하지 않는다면 $n$은 소수

### 합성수의 판별법 따름정리

- $n$이 합성수라면 $p \leq \lfloor \sqrt{n}\rfloor$을 만족하는 소인수 $p$를 가짐

# 3. 에라토스테네스의 체

### 에라토스테네스의 체

- 주어진 수 이하의 소수를 찾는 방법
- 처음 등장하는 소수를 제외하고 나머지를 지워나가며 찾는 방법