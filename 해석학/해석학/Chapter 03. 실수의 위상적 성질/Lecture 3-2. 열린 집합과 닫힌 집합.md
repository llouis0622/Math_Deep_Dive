# 1. 열린 집합

### 근방

- $a \in \mathbb{R}$과 $\epsilon > 0$에 대해 $\epsilon$-근방
    
    $V_\epsilon(a) = \{x \in \mathbb{R} \mid |x - a| < \epsilon\}$
    

### 개집합

- 모든 점 $a \in O$에 대해 $O$에 포함되는 $\epsilon$-근방 $V_\epsilon(a) \subseteq O$가 존재할 때 집합 $O \subseteq \mathbb{R}$

### 개집합 명제

- 열린 집합의 임의의 합집합은 열린 집합
- 열린 집합의 유한 교집합은 열린 집합

# 2. 닫힌 집합

### 극한점

- 점 $x$의 모든 $\epsilon$-근방 $V_\epsilon(x)$에 대해 $V_\epsilon(x)$의 집합 $A$의 교집합이 $x$ 이외의 다른 원소를 가질 때 점 $x$

### 극한점 명제

- 점 $x$가 집합 $A$의 극한점일 필요충분조건은 모든 $n \in \mathbb{N}$에 대해 $a_n \neq x$이면서 $A$에 포함되는 어떤 수열 $(a_n)$이 존재하여 $x = \lim a_n$

### 고립점

- 극한점이 아닌 점 $a \in A$

### 폐집합

- 자기 자신의 극한점을 모두 포함하는 집합 $F \subseteq \mathbb{R}$

### 폐집합 명제

- 집합 $F \subseteq \mathbb{R}$이 닫힌 집합일 필요충분조건은 $F$에 포함되는 모든 코시 수열이 $F$ 안에서 극한값을 가지는 것

### 유리수 집합 $\mathbb{Q}$에서의 조밀성

- 모든 $y \in \mathbb{R}$에 대해 $y$로 수렴하는 유리수열이 존재

# 3. 폐포

### 폐포

- 집합 $A \subseteq \mathbb{R}$이 주어질 때 $A$의 극한점 전체의 집합을 $L$이라 하면 $\overline{A} = A \cup L$

### 폐포 명제

- 임의의 $A \subseteq \mathbb{R}$에 대해 폐포 $\overline{A}$는 $A$를 포함하는 가장 작은 닫힌 집합

# 4. 여집합

### 여집합

- 집합 $A \subseteq \mathbb{R}$의 여집합 $A^C = \{x \in \mathbb{R} \mid x \notin A\}$

### 여집합 명제

- 집합 $O$가 열린 집합일 필요충분조건은 $O^C$가 닫힌 집합인 것
- 집합 $F$가 닫힌 집합일 필요충분조건은 $F^C$가 열린 집합인 것

### 닫힌 집합 명제

- 닫힌 집합의 유한 합집합은 닫힌 집합
- 닫힌 집합의 임의의 교집합은 닫힌 집합