### Different ways of solving Limits:
---

#### Direct Substitution
---

lim x → 1; x^3 + 1 
1^3 + 1 = 2

lim x → 2; 5x^2+3x + 1 
5(2)^2 + 3(2) + 1 = 27

All polynomial limits can be evaluated by direct substiution 




#### Factorization
---

We saw an example of this method in evaluating:
lim x → 2

$$
\frac{x^2-1}{x-1}
$$         

In such forms, the limit is indeterminate due to a certain factor occuring in the expression (For example, in the limit above, (x – 1) occurs in both the numerator and denominator and makes the limit indeterminate, of the form $$0/0$$ ) . Factorization leads to cancellation of that common factor and reduction of the limit to a determinate form.

Example 1:
lim x → 1 
$$
\frac{x^3-1}{x-1}
= \frac{(x-1)(x^2+x+1)}{x-1}
= x^2+x+1
$$

the final product would be:
lim x → 1
$$
(x^2+x+1)= 3
$$
#### Rationalization
---
In this method, the rationalization of an indeterminate expression leads to determinate one. The following examples elaborate this method.

Example 1:
lim x → 9
$$
\frac{x-9}{\sqrt{x}-3}
$$
To rationalize a numerator or denominator you have to multiply using the conjugate. The conjugate is the same expression with a different value. When multiplying by the conjugate you must multiply the bottom and top. For example
$$
\frac{x-9}{\sqrt{x}-3} \times \frac{\sqrt{x}+3}{\sqrt{x}+3}=\frac{(x-9)(\sqrt{x}+3)}{x-9} = \frac{\sqrt{x}+3}{1}= \frac{\sqrt{9}+3}{1}=6
$$
An example of radicals in numerator and denominator
lim x → 2
$$
\frac{\sqrt{6-x}-2}{3-\sqrt{11-x}} \times \frac{\sqrt{6-x}+2}{\sqrt{6-x}+2}\times\frac{3+\sqrt{11-x}}{3+\sqrt{11-x}}= \frac{[(6-x)-4][(3+\sqrt{11-x})]}{[9-(11-x)][\sqrt{6-x}+2]}
$$
Simplify the equation now
$$
\frac{[(6-x)-4][(3+\sqrt{11-x})]}{[9-(11-x)][\sqrt{6-x}+2]} = \frac{(2-x)[3+\sqrt{11-x}]}{(-2+x)[\sqrt{6-x}+2]}
$$
Cancel out the (2-x) and (-2 + x) as if you multipy (-2 + x) you would get (2-x) which will cancel them out but leave -1 at the top
$$
\frac{(-1)(3+\sqrt{11-x})}{\sqrt{6-x}+2}
$$
Use direct substition lim x → 2
$$
\frac{3+\sqrt{11-2}}{\sqrt{6-x}+2}= \frac{3+\sqrt{9}}{\sqrt{4}+2}= \frac{(-1)(3+3)}{2+2}= \frac{-6}{4}=\frac{-3}{2}
$$
Please reference this video:
https://www.youtube.com/watch?v=ZgpSWq1Tyug


#### Reduction to Standard Forms
--- 

In this method, we try to reduce the given limit to one of the standard forms we studied earlier
lim x → 0

$$
(1+sinx)^{2cotx}=(1+sinx)^\frac{1}{sinx}=e^{2}
$$
cos x → 1 as x → 0