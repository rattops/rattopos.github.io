---
layout: post
title: "*-algebra"
tags:
  - star-algebra
  - hilbert
  - quantum
math: "true"
categories: Functional-Analysis
toc: "true"
---
## 정의

### ${ \ast }$-ring

ring ${ A }$가 **${ \ast }$-ring**이라는 것은 [involutive antiautomorphism](https://paraconsistent.github.io/category-theory/2024/02/09/antihomomorphism.html) ${ \ast:A \to A }$가 주어져 있다는 것이다.

### ${ \ast }$-algebra

commutative ring ${ R }$이 [involution](https://paraconsistent.github.io/category-theory/2024/02/09/antihomomorphism.html#involutive-automorphism) ${ ' }$를 가지고 있고, ${ A }$가 [associative algebra](https://paraconsistent.github.io/algebra/2024/03/08/associative-algebra.html) over ${ R }$이라고 하자. 이때 involutive ring antiautomorphism ${ \ast:A \to A }$가

$$ (\forall r \in R,\forall x \in A) \quad \left( rx \right)^{\ast} = r'x^{\ast} $$

을 만족하면 ${ A }$를 **${ \ast }$-algebra**라고 한다.

### ${ \ast }$-homomorphism

${ A }$와 ${ B }$ 모두 ${ \ast }$-algebra라고 하자.[^1] algebra homomorphism ${ f:A \to B }$가 다음 조건을 만족하면 **${ \ast }$-homomorphism**이라고 한다.

$$ (\ast\mbox{-compatibility}) \quad  \forall  a \in A, \ f(a^{\ast})=f(a)^{\ast} $$

## References

1. *\*-algebra*. In *Wikipedia*. Retrieved Febuary 9, 2024, from [https://en.wikipedia.org/wiki/\*-algebra](https://en.wikipedia.org/wiki/*-algebra)

---
[^1]: 엄밀히는 A의 \*와 B의 \*를 구분해야 될 것이다.