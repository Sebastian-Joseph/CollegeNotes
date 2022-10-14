
## What is a derivative?
--- 
In Organic Chemistry Tutor terms a derivative is a function that gives you the slope at some x value.

The derivative of a constant is always 0

Examples:
$$
\frac{d}{dx}(5)=0
$$
$$
\frac{d}{dx}(-7) = 0
$$
Another example is f(x)=8. With this equation it means y = 8 and the slope is 0.  Since the slope is 0 the derivative would also be 0. Hence why the derivative of a constant is always 0.

If you see d/dx it means you are about to differentiate something with respect to x. d/dx(f(x)) = f’(x) ← this is f prime of x

---

## The Power Rule
--- 

This is the equation for the power rule in derivatives
$$
\frac{d}{dx}(x^{n}) = n \times x^{n-1}
$$
Let’s do 2
$$
\frac{d}{dx}(x^{2}) = 2 \times x^{2-1}= 2x^{1}= 2x
$$
Let’s do 3 
$$
\frac{d}{dx}(x^{3}) = 3 \times x^{3-1}= 3x^2
$$Let’s do 4
$$
\frac{d}{dx}(x^{4})= 4 \times x^{4-1}= 4x^{3}
$$
Let’s do 5 
$$
\frac{d}{dx}(x^{5})= 5 \times x^{5-1}= 5x^{4}
$$

---

## The Constant Multiple Rule
---
This is the constant multiple rule in derivatives
$$
\frac{d}{dx}[c \times f(x)]=c \times \frac{d}{dx}[f(x)]
$$
Examples:
$$
\frac{d}{dx}[4x^{7}]=\frac{d}{dx}[4*x^{7}]=4* \frac{d}{dx}[x^{7}]=4 \times (7 \times x^{6})=28x^{6}
$$
$$
\frac{d}{dx}[8x^{4}]= 8 \times \frac{d}{dx}[x^{4}]=8\times (4 \times x^{3})=32x^3
$$
$$
\frac{d}{dx}[5x^{6}]=5\times \frac{d}{dx}[x^{6}]= 5 \times(6 \times x^{5})=30x^{5}
$$

---

## Definition of Derivatives 
---
$$
f(x)=x^{2}= \space f'(x)=2x
$$
Is there any way to prove this other than the power rule? 
Yes this is what is called the definition of the derivative.
$$
f'(x)=lim \space h \rightarrow 0: \frac{f(x+h)-f(x)}{h}
$$
What exactly is f(x + h)? We know that f(x) is x^2 in this situation. 
In this situation you would replace x in x^2 with x+h so 
$$
f(x)=x^{2}=f(x+h)=(x+h)^{2}
$$
So again we are trying to prove f(x) = x^2 equates to 2x without the power rule and using the equation above.
$$
f'(x)=lim \space h \rightarrow 0: \frac{(x+h)^{2}-x^{2}}{h}
$$
The next step is to foil the expression (x+h)^2.
$$
f'(x)=lim \space h \rightarrow 0: \frac{(x+h)(x+h)-x^{2}}{h}
$$
In a Calculus Exam you would actually have to rewrite the expression so you can get full credit points.
$$
f'(x)=lim \space h \rightarrow 0: \frac{x^{2}+xh+xh+h^2-x^{2}}{h}
$$
$$
f'(x)=lim \space h \rightarrow 0: \frac{2xh+h^2}{h}
$$
Next you factor out the GCF (Greatest Common Factor) which is h
$$
f'(x)=lim \space h \rightarrow 0: \frac{h(2x+h)}{h}
$$
Then you cancel out the h
$$
f'(x)=lim \space h \rightarrow 0: 2x+h
$$
This is now when you plug in h → 0 leading to your final answer of 2x
$$
f'(x)= lim \space h \rightarrow 0: 2x+0=2x
$$
This is how 
$$
\frac{d}{dx}(x^{2)}=2x
$$

---

## Finding the slope at the tangent line 
---
Example:
$$
f(x)=x^{2} \space at \space x=1
$$
In order to find the slope at the tagent line which 1 we would need to evalute the prime function when x=1
$$
f(x)=x^{2}\space \frac{d}{dx}(x^{2})=2x
$$
f’(x)=2x is the prime function
$$
f'(x)=2x \rightarrow f'(1)=2(1)=2
$$
So the slope of the tangent line should be 2
$$
m_{tan}=2
$$
##### Difference between Tangent and Secant Line
---
The tangent line only touches the curve at one point while the secant line touches the curve at two points.

To find the slope of the secant line you must use this equation:

$$
m_{sec}= \frac{Y_2-Y_1}{X_2-X_1}
$$
Example: f(x) at x = 1
$$
x_{1}=0.9 \space and \space x_{2}=1.1 
$$
$$
y=f(x)=x^{2}\space so \space y_2=f(1.1)=1.1^{2} \space and \space y_{1}=f(0.9)=0.9^2
$$
$$
m_{sec}= \frac{Y_{2}-Y_{1}}{x_{2}-x_{2}}= \frac{1.1^{2}-0.9^{2}}{1.1-0.9}=\frac{1.21-0.81}{0.2}=2
$$
Example 2: f(x^3) at x = 2
$$
\frac{d}{dx}(x^{3})=3x^{2}\space so \space f'(x)=3x^{2}
$$
$$
f'(2)=3(2)^{2=12}\space so \space m_{tan}=12
$$
$$
x_{1}=1.9 \space x_{2} = 2
$$
$$
m_{sec}= \frac{Y_{2}-Y_{1}}{X_{2}-X_{1}}= \frac{2.1^{3}-1.9^{3}}{2.1-1.9}= \frac{9.261-6.859}{2.1-1.9}=\frac{2.402}{0.2}=12.01
$$

Finding the derivative of a polynomial function
$$
f(x)=x^{3}+7x^{2}-8x+6
$$
First you must differentiate each nomial separately 
$$
f'(x^3)=3x^{2}
$$
$$
\frac{d}{dx}(7x^{2})=7 \times \frac{d}{dx}(x^{2})=7(2x)=14x
$$
$$
\frac{d}{dx}(-8x^{1})=-8(1 \times x^{0})=-8
$$
$$
\frac{d}{dx}(6)=0
$$
So the final prime function will be 
$$
f'(x)=3x^2+14x-8
$$

Example 3:
$$
f(x)=4x^{5}+3x^{4}+9x-7 
$$
$$
\frac{d}{dx}(4x^5)=20x^4
$$
$$
\frac{d}{dx}(3x^4)=12x^{3}
$$
$$
\frac{d}{dx}(9x)=9
$$
$$
\frac{d}{dx}(-7)=0
$$
$$
f'(x)=20x^{4}+12x^{3}+9
$$

Example 4: Find at x = 2
$$
f(x)=2x^{5}+5x^{3}+3x^{2}+4
$$
$$
f'(x)=10x^{4}+15x^{2}+6x+0 
$$
Since it is at 2 we just plug in 2 into the prime function
$$
f'(2)=10(2)^{4}+15(2)^{2}+6(2)=160+60+12=232 \space so \space m_{tan}=232
$$
Example 5: 
$$
f(x)=\frac{1}{x}
$$
In situations like these we must rewrite the function
$$
f(x)=x^{-1}=f'(x)=-1x^{-2}= \frac{-1}{x^{2}}
$$
Example 6: 
$$
f(x)=\frac{1}{x^{2}}
$$
$$
f(x)=x^{-2}=f'(x)=-2x^{-3}=\frac{-2}{x^{3}}
$$
Example 7:
$$
f(x)=\frac{8}{x^{4}} 
$$
$$
f(x)=8x^{-4}=f'(x)=-32x^{-5}= \frac{-32}{x^{-5}}
$$
Example 8:
$$
f(x)= \sqrt{x}
$$
$$
f(x)=x^{\frac{1}{2}}=f'(x)=\frac{1 \times x^\frac{-1}{2}}{2}
$$
$$
f'(x)=\frac{1}{2  \sqrt{x}}
$$
Example 9:
$$
f(x)= \sqrt[3]{x^5}
$$
$$
f'(x)=x^\frac{5}{3}=\frac{5x^{{\frac{2}{3}}}}{3}={\frac{5 \sqrt[3]{x^2}}{3}}
$$

---

#### Derivatives of Trigonometric Functions
---
Derivatives of Trig Function you **NEED** to know
$$
\frac{d}{dx}[sin \space x]=cos \space x
$$
$$
\frac{d}{dx}[cos \space x]=-sin \space x
$$
$$
\frac{d}{dx}[sec \space x]=sec \space x \space tan \space x
$$
$$
\frac{d}{dx}[csc \space x]= -csc \space x \space cot \space x
$$
$$
\frac{d}{dx}[tan \space x]=sec^{2} \space x
$$
$$
\frac{d}{dx}[cot \space x]=-csc^{x} \space x
$$


---


#### Product Rule
----
$$
[f \times g]' =f'(x) \times g(x) + f(x) \times g'(x)
$$
Example:
$$
\frac{d}{dx}[x^{2}\times sin \space x]
$$
$$
f(x)=x^{2}\space so \space f'(x)=2x
$$
$$
g(x)=sin \space x = g'(x)= cos \space x
$$
$$
[2x \times sin \space x]+ [x^{2}\times cos \space x]
$$

Example 2:
$$
\frac{d}{dx}[(3x^{4}+7)(x^{3}-5x)]
$$
$$
f(x)=3x^4+7=f'(x)=12x^3
$$
$$
g(x)=x^3-5x=g'(x)=3x^2-5
$$
$$
[12x^{3}\times x^{3}-5x]+[3x^{4}+7 \times 3x^{2}-5]
$$

---

#### Quotient Rule
---
$$
\frac{d}{dx}[\frac{f}{g}]=\frac{gf'(x)-fg'(x)}{g^2}
$$
$$
\frac{d}{dx}[\frac{5x+6}{3x-7}]
$$
$$
f'(x)=5
$$
$$
g'(x)=3
$$
$$
\frac{(3x-7)(5)-(5x+6)(3)}{(3x-7)^2}
$$
$$
\frac{15x-35-15x-18}{(3x-7)(3x-7)}=\frac{-53}{(3x-7)^2}=\frac{-53}{9x^{2}+21x+21x+49}=\frac{-53}{9x^2+42x+49}
$$

---
