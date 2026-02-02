# 1. 거리공간

### 거리와 거리공간

- 거리 : 집합 $X$의 모든 $x, y \in X$에 대해 다음을 만족하는 함수 $d : X \times X \rarr \mathbb{R}$
- $d(x, y) \geq 0$이며 $d(x, y) = 0$일 필요충분조건은 $x = y$
- $d(x, y) = d(y, x)$
- 모든 $z \in X$에 대해 $d(x, y) \leq d(x, z) + d(z, y)$
- 거리 공간 : 거리 $d$가 주어진 집합 $X$

### 이산 거리

- 집합 $X$가 주어졌을 때, 임의의 $x, y \in X$에 대해 다음과 같이 정의한 $\rho(x, y)$는 $X$에서의 거리
    
    $\rho(x, y) = \begin{cases} 1 & (x \neq y) \\ 0 & (x = y)\end{cases}$
    

# 2. 기본 정의

### 수렴

- 거리공간 $(X, d)$와 수열 $(x_n) \subseteq X$을 생각할 때, 임의의 $\epsilon > 0$에 대해 다음을 만족하는 $N \in \mathbb{N}$이 존재하면 수열 $(x_n) \subseteq X$은 $x \in X$로 수렴
    
    $n \geq N \Rightarrow d(x_n, x) < \epsilon$
    

### 코시 수열

- 거리공간 $(X, d)$와 수열 $(x_n) \subseteq X$을 생각할 때, 임의의 $\epsilon > 0$에 대해 다음을 만족하는 $N \in \mathbb{N}$이 존재하면 수열 $(x_n)$은 거리공간 $(X, d)$에서 코시 수열
    
    $m, n \geq N \Rightarrow d(x_m, x_n) < \epsilon$
    

### 완비거리공간

- 집합 $X$에 속하는 임의의 코시 수열이 항상 $X$의 어떤 원소로 수렴할 때의 거리공간 $(X, d)$

### 최소상계놈

- $||f||_\infty = d(f, 0) = \sup\{|f(x)| \mid x \in [0, 1]\}$

### 연속

- $(X, d_1)$과 $(Y, d_2)$를 거리공간이라고 할 때, 모든 $\epsilon > 0$에 대해 어떤 $\delta$가 존재하여 $d_1(x, y) < \delta$이면 $d_2(f(x), f(y)) < \epsilon$이 성립할 때, 함수 $f : X \rarr Y$를 $x \in X$에서 연속

# 3. 거리공간의 위상적 성질

### $\epsilon$-근방

- 양수 $\epsilon > 0$과 거리공간 $(X, d)$의 원소 $x$에 대해 집합 $V_\epsilon(x) = \{y \in X \mid d(x, y) < \epsilon\}$

### 개집합, 극한점, 폐집합

- 개집합 : 모든 $x \in O$에 대해 $V_\epsilon(x) \subseteq O$인 근방을 찾을 수 있을 때의 집합 $O \subseteq X$
- 극한점 : 모든 $V_\epsilon(x)$에 대해 $V_\epsilon(x)$와 $A$가 $x$ 이외의 다른 교집합을 가질 때의 점 $x$
- 폐집합 : 집합 $C$가 자기 자신의 극한점을 모두 포함하는 것

### 콤팩트

- 거리공간 $(X, d)$의 부분집합 $K$가 다음을 만족할 때 콤팩트함
    
    집합 $K$의 모든 수열이 수렴하는 부분수열을 가지고 그 극한값이 $K$에 속함
    

### 폐포와 내부

거리공간 $(X, d)$와 그 부분집합 $E$에 대해

- 폐포 : $\overline{E}$는 $E$와 $E$의 극한점들의 합집합
- 내부 : $E^o = \{x \in E \mid V_\epsilon(x) \subseteq E$인 $x$의 $\epsilon$-근방이 존재$\}$

### 조밀성

- 조밀 : $\overline{A} = X$일 때, 집합 $A \subseteq X$는 거리공간 $(X, d)$에서 조밀함
- 조밀한 곳이 없음 : $\overline{E}^o$이 공집합일 때, 거리공간 $(X, d)$의 부분집합 $E$

## 4. 베르 범주 정리

### 완비거리공간

- 완비거리공간 $(X, d)$와 $X$의 조밀한 열린 부분집합으로 이루어진 셀 수 없는 집합 $\{O_n\}$을 생각할 때, $\bigcap_{n=1}^\infty O_n$은 공집합이 아님

### 베르 범주 정리

- 완비거리공간은 조밀한 곳이 없는 집합의 셀 수 있는 합집합으로 나타낼 수 없음

### 제1 범주 집합

- $D = \{f \in C[0, 1] \mid$ 어떤 $x \in [0, 1]$에 대해 $f'(x)$이 존재$\}$