---
layout: test
title: K-Map Test 1
subject: computer_science
level: A2
time: 45min
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script type="text/javascript" id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

## Karnaugh Map - Test 1

#### 1) Obtain optimized SOP for the following truth tables using K-Map:

a) **3-variable truth table** 

| A | B | C | X |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 |
| 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

b) **4-variable truth table** 

| A | B | C | D | X |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 1 |
| 0 | 0 | 0 | 1 | 0 |
| 0 | 0 | 1 | 0 | 1 |
| 0 | 0 | 1 | 1 | 1 |
| 0 | 1 | 0 | 0 | 1 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 0 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 1 | 1 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 0 | 1 | 1 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 0 | 0 |
| 1 | 1 | 1 | 1 | 1 |

#### 2) Simplify the following boolean expressions using K-Map:

- $$ \ F(A, B, C) = \overline{A}BC + AB\overline{C} + A\overline{B}\overline{C} + \overline{A}\overline{B}C + ABC $$

- $$ \ F(A, B, C, D) = AB\overline{C}D + A\overline{B}CD + A\overline{B}\overline{C}D + ABC\overline{D} + \overline{A}B\overline{C}\overline{D} + \overline{A}BCD + AB\overline{C}\overline{D} $$

#### 3) The following logic circuits contain some redundancy. Use K-Map to get simplified SOP and draw the logic circuit of the simplified expression:

a) 
![logic_ckt_1](../img/logic_ckt_1.png)

b) 

![logic_ckt_2](../img/logic_ckt_2.png)

---