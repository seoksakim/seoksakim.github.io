---
title: "Edge Case: Nested and Mixed Lists"
categories:
  - 재정학
tags:
  - 조세
---

**초과부담 산식** 

조세가 징수되는 과정에서 징수액을 초과한 실제 부담을 **초과부담(EB: excess burden)**이라고 부른다. 때로는 자중손실(deadweight loss), 후생비용(welfare cost), 혹은 하버거의 삼각형(Harberger's Triangle)이라고 부르기도 한다.

품목당 $dt>0$원을 부과하는 물품세를 고려해보자. 재화의 가격이 $p$에서 $p\_{s}+dt$로 상승하는 한편 소비량은 $q$에서 $q+dQ$로 감소한다. 여기서, $p\_{s}$는 물품세 하에서의 생산자가격을 말하며, $dq<0$이다.

물품세의 초과부담은 삼각형의 넓이, 즉 $-\frac{1}{2} dt dq$와 같다. 이는 아래 도출과정에서 보듯이 다음처럼 표현할 수 있다. 

$$ EB = ~\frac{1}{2} \cdot \frac{1}{ \cfrac{1}{\epsilon\_{s}} + \cfrac{1}{\epsilon\_{d}} } \cdot \frac{q}{p} \cdot dt^{2}$$

위 식은 이준구&조명환(2016), 470쪽 주석 5와 다소 다르다. 품목당 생산자가격에 부과하는 우리와 달리 물품세를 소비자가격의 세율($t\\cdot P\_{d}$)로 정의한 데 따른 차이이다.

**산식의 도출**

수요함수와 공급함수를 각각 $Q\_{d}(p)$와 $q\_{s}(p)$로 표시하면, 수요와 공급의 가격탄력성을 다음과 같이 쓸 수 있다. 

$$ \\epsilon\_{d} = -\\frac{p q\_{d}'}{ Q\_{d} }, ~~~~~~~~\\epsilon\_{s} = \\frac{p q\_{s}'}{ q\_{s} }$$

$D(p\_{s}+t) = S(p\_{s})$와 $t=0$에서 $D'dp + D'dt = S'dp$이므로 

$$ dp = \\frac{D'}{S'-D'} dt = \\frac{-\\epsilon\_{d}~}{ \\epsilon\_{s}+ \\epsilon\_{d}} dt$$

이제 $S'(p) = \\cfrac{dq}{dp}$를 이용하면 $EB$는 다음처럼 표현가능하다. 

$$ \\begin{align} EB =& -\\frac{1}{2} dt dq = -\\frac{1}{2} dt \\cdot S'(p)dp \\\\ =& -\\frac{1}{2} \\cdot S'(p) \\cdot \\frac{-\\epsilon\_{d}~}{ \\epsilon\_{s}+ \\epsilon\_{d}} dt^{2} \\\\ =& ~\\frac{1}{2} \\cdot \\epsilon\_{s} \\frac{S}{p}\\cdot \\frac{\\epsilon\_{d}}{ \\epsilon\_{s}+ \\epsilon\_{d}} dt^{2} \\\\ =&~\\frac{1}{2} \\cdot \\frac{ \\epsilon\_{s} \\epsilon\_{d}}{ \\epsilon\_{s}+ \\epsilon\_{d}} \\cdot \\frac{q}{p} \\cdot dt^{2} \\\\ =&~\\frac{1}{2} \\cdot \\frac{ \\epsilon\_{s} \\epsilon\_{d}}{ \\epsilon\_{s}+ \\epsilon\_{d}} \\cdot (pq) \\cdot (\\frac{dt}{p})^{2} \\end{align} $$

따라서, 초과부담은 물품세의 제곱에 비례해 커진다. 유사하게, 수요와 공급의 탄력성이 커지면서 초과부담도 커지는 것을 쉽게 확인가능하다. 

**다음에는....**

초과부담을 처음으로 추정한 Harberger(1964)를 포함하여 2000년 이전의 연구에 대해 이야기해보겠다.
