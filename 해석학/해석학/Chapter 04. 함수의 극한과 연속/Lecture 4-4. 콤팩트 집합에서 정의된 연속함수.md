# 1. 콤팩트 집합에서의 연속

### 콤팩트 집합의 보존

- 연속함수 $f : A \rarr \mathbb{R}$와 콤팩트 집합 $K \subseteq A$에 대해 $f(K)$도 콤팩트 집합

### 최대-최소 정리

- 함수 $f : K \rarr \mathbb{R}$가 콤팩트 집합 $K \subseteq \mathbb{R}$에서 연속이면 $f$는 최댓값과 최솟값을 가짐
- 모든 $x \in K$에 대해 $f(x_0) \leq f(x) \leq f(x_1)$인 $x_0, x_1 \in K$가 존재

# 2. 고른 연속

### 고른 연속

- 임의의 $\epsilon > 0$과 모든 $x, y \in A$에 대해 $|x - y| < \delta$일 때 항상 $|f(x) - f(y)| < \epsilon$이 되는 $\delta > 0$가 존재하면 함수 $f : A \rarr \mathbb{R}$를 $A$에서 고른 연속

### 고른 연속에 대한 수열 판정법

- 함수 $f : A \rarr \mathbb{R}$가 고른 연속이 아니기 위한 필요충분조건은 다음을 만족하는 어떤 $\epsilon_0 > 0$와 $A$의 두 수열 $(x_n)$과 $(y_n)$이 존재하는 것
    
    $|x_n - y_n| \rarr 0$이지만 $|f(x_n) - f(y_n)| \geq \epsilon_0$
    

### 콤팩트 집합에서 고른 연속

- 콤팩트 집합 $K$에서 연속인 함수는 $K$에서 고른 연속