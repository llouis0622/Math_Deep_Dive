# 1. 콤팩트성

### 콤팩트성

- $K$의 원소로 이루어진 임의의 수열에 대해 극한이 $K$의 원소인 부분수열이 존재할 때 집합 $K \subseteq \mathbb{R}$

### 유계집합

- 모든 $a \in A$에 대해 $|a| \leq M$인 $M > 0$이 존재할 때 집합 $A \subseteq \mathbb{R}$

### $\mathbb{R}$에서 콤팩트성의 특성

- 집합 $K \subseteq \mathbb{R}$가 콤팩트할 필요충분조건은 $K$가 닫힌 집합이면서 유계집합인 것

### 축소 콤팩트 집합 성질

- 다음과 같이 공집합이 아닌 콤팩트 집합으로 이루어진 축소집합열에서
    
    $K_1 \supseteq K_2 \supseteq K_3 \supseteq K_4 \supseteq \cdots$
    
- 교집합 $\bigcap_{n=1}^\infty K_n$$은 공집합이 아님

# 2. 열린 덮개

### 열린 덮개와 유한 부분덮개

집합 $A \subseteq \mathbb{R}$와 열린 집합의 모임 $\{O_\lambda \mid \lambda \in \Lambda\}$에 대해

- 열린 덮개 : $A \subseteq \bigcup_{\lambda \in \Lambda} O_\lambda$일 때, $\{O_\lambda \mid \lambda \in \Lambda\}$
- 유한 부분덮개 : 이 열린 덮개 중 유한개만의 합집합으로도 여전히 $A$가 완전히 포함될 수 있을 때, 이 유한개 집합의 모임

### 하이네-보렐 정리

$K$가 $\mathbb{R}$의 부분집합이라 하면 다음 명제는 모두 동치

- $K$는 콤팩트 집합
- $K$는 닫힌 집합이면서 유계집합
- $K$의 임의의 열린 덮개가 항상 유한 부분덮개를 가짐