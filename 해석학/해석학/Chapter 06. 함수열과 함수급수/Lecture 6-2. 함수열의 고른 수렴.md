# 1. 점별수렴

### 점별수렴

- 각 $n \in \mathbb{N}$에 대해 $f_n$을 집합 $A \subseteq \mathbb{R}$에서 정의된 함수라고 할 때, 모든 $x \in A$에 대해 실수열 $f_n(x)$가 $f(x)$로 수렴할 때, 함수열 $(f_n)$이 $A$에서 함수 $f$로 점별수렴
    
    $f_n \rarr f, \lim f_n = f, \lim_{n \rarr \infty} f_n(x) = f(x)$
    

# 2. 극한 함수와 연속

### 연속함수는 연속함수로 점별수렴

- $|x - c| < \delta$이면 $|f(x) - f(c)| < \epsilon$ → 수렴 증명 실패

# 3. 고른 수렴

### 고른 수렴

- 집합 $A \subseteq \mathbb{R}$에서 정의된 함수 $(f_n)$으로 이루어진 함수열에서 모든 $\epsilon > 0$에 대해 $N \in \mathbb{N}$이 있어 $n \geq N$이고 $x \in A$이면 항상 $|f_n(x) - f(x)| < \epsilon$이 될 때, $(f_n)$이 $A$에서 극한 함수 $f$로 고르게 수렴

### 점별 수렴

- 집합 $A \subseteq \mathbb{R}$에서 정의된 함수 $(f_n)$으로 이루어진 함수열에서 모든 $\epsilon > 0$과 $x \in A$에 대해 $N \in \mathbb{N}$이 있어 $n \geq N$이면 $|f_n(x) - f(x)| < \epsilon$이 될 때, $(f_n)$이 $A$에서 극한 함수 $f$로 점별수렴

# 4. 코시 판정법

### 고른 수렴성에 대한 코시 판정법

- 집합 $A \subseteq \mathbb{R}$에서 정의된 함수 $(f_n)$으로 이루어진 함수열이 $A$에서 고르게 수렴하기 위한 필요충분조건은 모든 $\epsilon > 0$에 대해 어떤 $N \in \mathbb{N}$이 있어 $m, n \geq N$이고 $x \in A$이면 $|f_n(x) - f(x)| < \epsilon$인 것

# 5. 연속

### 연속함수와 고른 수렴

- $A \subseteq \mathbb{R}$에서 정의된 함수 $(f_n)$으로 이루어진 함수열이 $A$에서 함수 $f$로 고르게 수렴한다고 가정할 때 각 $f_n$이 $c \in A$에서 연속이면 $f$도 $c$에서 연속