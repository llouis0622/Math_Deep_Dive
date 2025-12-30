# 1. 함수의 극한

### $\epsilon-\delta$ 논법

- 함수 $f : A \rarr \mathbb{R}$와 정의역 $A$의 극한점 $c$에 대해 모든 $\epsilon > 0$에 대해 $0 < |x - c| < \delta$이면 항상 $|f(x) - L| < \epsilon$이 되게 하는 $\delta > 0$이 존재할 때 $\lim_{x \rarr c} f(x) = L$

### 위상으로 표현한 함수의 극한

- 점 $c$가 $f : A \rarr \mathbb{R}$의 정의역의 극한점이라 하고 $L$의 모든 $\epsilon$-근방 $V_\epsilon(L)$에 대해 $c$와 다른 $x \in V_\delta(c)$이면 항상 $f(x) \in V_\epsilon(L)$이 되게 하는 $c$의 $\delta$-근방 $V_\delta(c)$가 존재할 때 $\lim_{x \rarr c} f(x) = L$

# 2. 함수의 극한에 대한 수열 판정법

### 함수의 극한에 대한 수열 판정법

함수 $f : A \rarr \mathbb{R}$와 $A$의 극한점 $c$가 주어졌을 때 다음 두 명제는 동치

- $\lim_{x \rarr c} f(x) = L$
- $x_n \neq c$이면서 $(x_n) \rarr c$인 모든 수열 $(x_n) \subseteq A$에 대해 $f(x_n) \rarr L$

### 함수의 극한과 사칙연산

$f$와 $g$가 정의역 $A \subseteq \mathbb{R}$에서 정의된 함수라고 하고 $A$의 어떤 극한점 $c$에 대해 $\lim_{x \rarr c} f(x) = L$이고 $\lim_{x \rarr c} g(x) = M$이라 하면 다음이 성립

- 모든 $k \in \mathbb{R}$에 대해 $\lim_{x \rarr c} kf(x) = kL$
- $\lim_{x \rarr c} [f(x) + g(x)] = L + M$
- $\lim_{x \rarr c} [f(x)g(x)] = LM$
- $\lim_{x \rarr c} [\frac{f(x)}{g(x)}] = \frac{L}{M}$

### 함수의 극한에 대한 발산 판정법

$A$에서 정의된 함수 $f$와 $A$의 극한점 $c$를 생각할 때, $A$에 포함되는 두 수열 $(x_n)$과 $(y_n)$이 있어 $x_n \neq c, y_n \neq c$이고 다음을 만족한다고 하자

$\lim x_n = \lim y_n = c$이지만 $\lim f(x_n) \neq \lim f(y_n)$

- 극한값 $\lim_{x \rarr c} f(x)$는 존재하지 않음