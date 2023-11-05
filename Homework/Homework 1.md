---
tags:
  - 🌱
date: 23--Sep--2023
---
# Homework 1

Assumption for all questions:

- Fixed power budget  
- Total power is proportional to square of frequency
- Performance is proportional to frequency
- 90% program can be perfectly parallelised, 10% of the program remains sequential

## Part 1
Let P be the power, $f_1$ be the frequency for single core, $f_2$ be the frequency for dual core. Performance of this program on a single core is $f_1 =$ 1 solution/s

$$
\begin{flalign*}
P=cf_{1}^{2}&&\\
\frac{P}{2}=cf_{2}^{2}\\
\frac{cf_{2}^{2}}{2}= cf_{2}^{2}\\
\frac{f_{1}^{2}}{ \sqrt{2}} = f_{2}^{2}\\
\text{For 90\% parallel, and 10\% sequential, }
&= 0.9(2\times f_{2}) + 0.1(f_{1})\\
&= 0.9(2 \times \frac{f_{1}^{2}}{\sqrt{2}})+ 0.1(f_{1}^{2})\\
&= 0.9(\sqrt{2} \times {f_{1}^{2}})+ 0.1(f_{1}^{2})\\
&= f_{1}^{2}(0.9\sqrt{2} + 0.1)\\
&= (0.9\sqrt{2} + 0.1)
\end{flalign*}
$$

## Part 2
$$
\begin{flalign*}\\
P=cf_{1}^{2}\\
\frac{P}{4}=cf_{2}^{2}\\
\frac{cf_{2}^{2}}{4}= cf_{2}^{2}\\
\frac{f_{1}^{2}}{ \sqrt{4}} = f_{2}^{2}\\
\text{For a quad core then, }
&= 0.9(2\times f_{2}) + 0.1(f_{1})\\
&= 0.9(2 \times \frac{f_{1}^{2}}{\sqrt{4}})+ 0.1(f_{1}^{2})\\
&= 0.9({f_{1}^{2}})+ 0.1(f_{1}^{2})\\
&= f_{1}^{2}(0.9 + 0.1)\\
&= f_{1}^{2}\\
&= 1
\end{flalign*}
$$
