# 1. 연속

### 연속성

- 임의의 $\epsilon > 0$에 대해 $|x - c| < \delta$이면 $|f(x) - f(c)| < \epsilon$이 되게 하는 $\delta > 0$가 존재할 때 함수 $f : A \rarr \mathbb{R}$가 $c \in A$에서 연속
- $f$가 정의역 $A$의 모든 점에서 연속이면 $f$는 집합 $A$에서 연속

### 연속을 정의하는 동치 표현

함수 $f : A \rarr \mathbb{R}$와 점 $c \in A$에 대해 다음 조건 중 하나를 만족하는 것과 함수 $f$가 $c$에서 연속인 것은 동치

- 임의의 $\epsilon > 0$에 대해 $|x - c| < \delta$이면 $|f(x) - f(c)| < \epsilon$이 되게 하는 $\delta > 0$가 존재
- 임의의 $V_\epsilon(f(c))$에 대해 $x \in V_\delta(c)$이면 $f(x) \in V_\epsilon(f(c))$가 되게 하는 $V_\delta(c)$가 존재
- $(x_n) \rarr c$인 임의의 $(x_n)$에 대해 $f(x_n) \rarr f(c)$

$c$가 $A$의 극한점이면 위 조건과 다음 조건은 동치

- $\lim_{x \rarr c} f(x) = f(c)$

### 불연속성 판정법

- 함수 $f : A \rarr \mathbb{R}$와 $A$의 극한점 $c \in A$에 대해 $(x_n) \rarr c$이지만 $f(x_n)$은 $f(c)$로 수렴하지 않은 수열 $(x_n) \subseteq A$이 존재하면 $f$는 $c$에서 연속이 아님

### 연속성과 사칙연산

두 함수 $f : A \rarr \mathbb{R}$와 $g : A \rarr \mathbb{R}$가 점 $c \in A$에서 연속이라 가정하면 다음이 성립

- 임의의 $k \in \mathbb{R}$에 대해 $kf(x)$는 $c$에서 연속
- $f(x) + g(x)$는 $c$에서 연속
- $f(x)g(x)$는 $c$에서 연속
- 분모가 0이 아닐 때 $\frac{f(x)}{g(x)}$는 $c$에서 연속

### 연속함수의 합성

두 함수 $f : A \rarr \mathbb{R}$와 $g : B \rarr \mathbb{R}$에 대해 치역 $f(A) = \{f(x) \mid x \in A\}$가 정의역 $B$에 포함되어 합성함수 $g \cdot f(x) = g(f(x))$가 $A$에서 잘 정의된다고 가정

- $f$가 $c \in A$에서 연속이고 $g$가 $f(c) \in B$에서 연속이면 $g \cdot f$가 $c$에서 연속