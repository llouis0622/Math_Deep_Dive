# 1. 수열

### 수열

- 정의역이 $\mathbb{N}$인 함수
- 실수의 나열

### 수열의 수렴

- 임의의 양수 $\epsilon$에 대해 $n \geq N$이면 $|a_n - a| < \epsilon$이 되게 하는 $N \in \mathbb{N}$이 존재할 때 수열 $(a_n)$이 실수 $a$로 수렴
    
    $\lim a_n = a, (a_n) \rarr a$
    
- 실수 $a \in \mathbb{R}$와 양수 $\epsilon > 0$에서 집합 $V_\epsilon(a)$를 $a$의 $\epsilon$-근방
    
    $V_\epsilon(a) = \{x \in \mathbb{R} \mid |x - a| < \epsilon\}$
    

### 위상으로 표현한 수열의 수렴

- 주어진 $a$의 임의의 $\epsilon$-근방 $V_\epsilon(a)$에 대해 수열의 어떤 지점이 있어서 그 이후 모든 항이 $V_\epsilon(a)$에 속할 때 수열 $(a_n)$이 실수 $a$로 수렴
- 모든 $\epsilon$-근방은 수열 $(a_n)$의 유한개를 제외한 모든 항을 포함

# 2. 전칭기호와 존재기호

### $(x_n) \rarr x$의 증명에 대한 템플릿

- 임의의 $\epsilon > 0$에 대해
- $N \in \mathbb{N}$을 선택. 엄밀한 증명을 쓰기 전에 시행착오를 반복하며 이러한 $N$ 찾기
- 이렇게 찾은 $N$이 조건을 만족함을 보임
- $n \geq N$이라 가정
- $N$을 제대로 선택했다면 부등식 $|x_n - x| < \epsilon$이 성립

### 극한값의 유일성

- 수열의 극한값은 존재한다면 유일

# 3. 발산

### 발산

- 수렴하지 않는 수열