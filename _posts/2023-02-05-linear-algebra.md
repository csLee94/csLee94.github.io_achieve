---
title: 선형대수 독학하기[0]
author: csLee94
date: 2023-02-05 00:00:00 +0900
categories: [learning, data science]
tags: [linear algebra]
math: True
---

## Why should I Study linear alebra?
---
최근 추천 시스템에 대한 기획부터 구현까지 진행하며, 데이터 사이언티스트에게 **수리적 이해도**가 얼마나 중요한지 새삼 다시 깨닫게 되었습니다. 데이터 업을 대하는 저만의 가치관에서도 수학은 매우 중요한 부분을 차지하는 만큼, 이번 기회에 **선형 대수**에 대한 공부를 다시 해봐야겠다고 다짐했습니다.

> **What is Linear Alebra?**<br>
>선형대수학은 `행렬`과 `벡터`라는 수학 대상을 연구하는 학문으로, 행렬 & 선형변환 같은 내용들이 다양한 머신러닝 알고리즘의 수치계산 방식에 응용, 적용됩니다. 
{: .prompt-tip}

머신러닝을 가장 빠르게 떠올릴 수 있는 분야 중 하나가 **최적화**일텐데요, 선형대수학을 이용해 처리해냅니다. 만약 6개의 상품을 각각 $A$,$B$,$C$ 국가에 수출하는 상황을 가정한다면 아래와 같이 행렬로 표현할 수 있습니다.

$$
    \begin{pmatrix}
    3&2&1 \\
    2&2&2 \\
    1&2&3 \\
    \end{pmatrix}
    *
    \begin{pmatrix}
    100 \\
    120 \\
    80 \\
    \end{pmatrix}
$$

물론 위와 같이 간단한 행렬인 경우에는, 엑셀만으로도 최적의 값을 찾을 수 있겠지만 보다 복잡한 데이터를 깊이 있기 다루기엔 어려움이 있었습니다. 이때 백터를 이용해, 다양한 수학적 구조를 구성하고 수학적 기법들을 적용해서 보다 어렵고 복잡한 문제를 다룰 수 있게 됩니다.

<br>

## How to learn by myself?
---
세상이 많이 좋아져 수 많은 정보들을 무료로 접해볼 수 있게 됐지만, 그만큼 자료를 확인하고 검수하는데 어려움이 생겼습니다. 실제로 제로베이스인 상태로 어떤 것을 **독학**한다는 것은, 여전히 어려운 일입니다. 그래서 우선 간단한 자료조사를 통해 2가지 최우선 목표를 세웠습니다.

### 이상엽Math의 선형대수학 강의

{% include embed/youtube.html id='525w2Zqh13M' %}

우선은 학습에 길잡이를 위한 강의가 필요했고, 너무 지엽적이지 않은 기초적인 개념을 20시간 남짓되는 시간동안 유튜브에 무료 강의를 올려주셨다. OT를 들어봤을 때도 만족스러웠고 강의록까지도 공개되어있어 입문하는데 큰 도움이 될 것 같았습니다.

### 알고리즘 구현으로 배우는 선형대수 with 파이썬
행렬과 선형대수 관련 구글링을 통해 알게된 장철원님께서 지으신, `알고리즘 구현으로 배우는 선형대수 with 파이썬`이라는 책을 통해 위 강의에서 학습한 내용을 응용해보고자 합니다. 선형대수를 학습하는 가장 큰 이유가 **알고리즘을 더 잘 다루기 위함**이니, 이 책에서 제공하는 다양한 예제와 github repo가 큰 도움이 될 것  같습니다.

### 기타 

우선은 위 두 가지 항목들만을 목표로 하고 있지만, 이 밖에도 많은 분들이 추천해주신 강의입니다. 

{% include embed/youtube.html id='ZK3O402wf1c' %}

선형대수를 공부하고 계신 분들께는 이미 유명하신 Gilbert Strang 교수님의 강의입니다. 굉장히 많은 분들께서 반복적으로 추천해주셨지만, 강의 내용이 응용에 초점이 맞춰져 있다고해 저는 다음 기회로 미뤘습니다.


{% include embed/youtube.html id='lkx2BJcnyxk' %}

두 번째론 Axler 교수님의 강의입니다. linear algebra done right라는 유명한 개론서의 저자시며, 강의와 교재를 함께 학습할 수 있다는 장점이 있으나, 이 역시 다음 기회로 미뤘습니다.

<br>

## Wrap up 
---
목표 계획에 따라 학습하며, 학습 및 실무 적용했던 내용들을 후속 포스트로 업로드할 계획입니다. 이 포스트 시리즈가 마무리될 쯤에는, 선형대수에 대한 약간의 감이라도 잡힐 수 있다면 좋겠습니다.

<br>

## REFERENCE
> - [이상엽Math 강의 페이지](https://sites.google.com/mensakorea.org/math/%EC%B7%A8%EB%AF%B8%EB%A1%9C-%EC%88%98%ED%95%99%ED%95%98%EC%9E%90/%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98%ED%95%99)
> - [알고리즘 구현으로 배우는 선형대수 github repo](https://github.com/bjpublic/LinearAlgebra)