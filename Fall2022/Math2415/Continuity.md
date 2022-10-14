

#### Types of Continunity Graphs

What is continuity? Continuity is the unbroken and consistent existence or operation of something over a period of time. An example of this is a continuous function. 

An example of a continuous function is this:
![[Pasted image 20221012160505.png]]

There is a particular type of continuity known as a hole. This is an example of a hole:
![[Pasted image 20221012160558.png]]

This is an example of a jump continuity:
![[Pasted image 20221012160648.png]]

This is an example of a infinity continuity:
![[Pasted image 20221012160755.png]]

In a infinite continuity, the vertical asymptote is where there is a discontinuity. 

--- 


#### 3 Step Continuity Test
---
The first of the three steps is to show that f(a) is defined.

The second step step is to show that the limit x → a of f(x) exists
	You do this by proving that limit x → a- of f(x) is equal to limit x → a+ of f(x). Only under those coniditions will the limit exist

The third step is to show that limit x → a from either side of f(x) is equal to f(a)

Example:

Step 1:
$$
f(x) =

\left\{

\begin{array}{lr}

\sqrt{x+2}, & \text{if } x < 2\\

x^{2}-2, & \text{if } 2 \le x < 3\\

2x+5, & \text{if} \space x \ge 3



\end{array}

\right\} 

$$
$$
f(2) = (2)^{2}-2 = 2
$$
Step 2:

lim x → 2- of f(x) and since the limit is 2- that means we must use the if x < 2 statement which leads to this $$
lim \space x \rightarrow 2- = f(x) =\sqrt{2+2}=2 
$$
lim x → 2+ of f(x) and since the limit is 2+ that means we must use the if 2 < x < 3 statement which leads to this $$
lim \space x \rightarrow 2+ = f(x)=2^{2}-2 =2 
$$
The left and right side of the limit are the same so the limit does exist

Step 3: Since Limit x → 2 of f(x) = 2 and f(a) = 2 (f(a) = f(2) = 2^2 - 2 = 2) then step 3 is completed as f(x) = f(a). 

Example 2:
$$
f(x) =

\left\{

\begin{array}{lr}

\sqrt{x+2}, & \text{if } x < 2\\

x^{2}-2, & \text{if } 2 \le x < 3\\

2x+5, & \text{if} \space x \ge 3



\end{array}

\right\}
$$
Step 1: 
$$
f(3) = 2(3) + 5=11
$$
f(3) is defined as 11

Step 2:
$$
lim \space x \rightarrow 3- =f(x)=3^{2}-2 =7  
$$
$$
lim \space x \rightarrow 3+ = 2(3) + 5 = 11
$$
Both sides of the limit does not match so the limit x → 3 of f(x) does not exist. It is not continous at x = 3. Since the sides of the limit does not match and there is no rational equation this is known as a jump continuity. 

Example 3:
$$
\left\{

\begin{array}{lr}

2x+5, & \text{if } x < -1\\

x^{2}+2, & \text{if } x > -1\\

5, & \text{if} \space x=-1



\end{array}

\right\}
$$

Step 1:
$$
f(-1)= 5
$$
So f(a) is defined as 5

Step 2:
$$
lim \space x \rightarrow-1+ =f(x)=-1^{2}+2 =3
$$
$$
lim \space x \rightarrow -1- = f(x)=2(-1)+5 =3
$$
Since both sides of the limit match, this means the limit does exist

Step 3:
$$
lim x \rightarrow -1 =\space f(x)=3 
$$
$$
\space f(-1)= 5
$$
$$
 f(x) \neq f(a)
$$
Since step 3 failed it means it is discontinuous at -1 but the limit does exist.

Usually when step 2 fails, meaning the limits of both sides don’t match, it means that this is a jump continuity.

When step 3 fails, meaning f(x) does not equal f(a) this makes it a whole discontinuity.

--- 

