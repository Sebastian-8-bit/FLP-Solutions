The exercises presented in this document are completed by CHEN, RONG-XIANG(陳融翔) from Taitung City, Taiwan.

All the figures in this document is redrawn using Mathcha or Inkscape.

***5.1***
**Two blocks of mass $m_{1}=1\: \text{kg}$, $m_{2}=2\:\text{kg}$ on a horizontal surface, connected by a string, are being pulled by another string which is attached to a mass $m_{3}=2\:\text{kg}$ hanging over a pulley, as shown in Fig. 5-1. Neglect friction and the masses of the pulley and strings.**
**![[Fig.5-1.svg#invert]]**
1. **Sketch free-body diagrams for all masses, showing the forces acting.**
2. **Find the acceleration $a$ of the masses.**
3. **Find the tension $T_{1}$ and $T_{2}$ in the strings.**

Ans:
1. The free-body diagrams for $m_{1}$, $m_{2}$ and $m_{3}$ are![[Fig.5-1sol 1.svg#invert]]
2. Assume that the acceleration is $a$, then by analyzing the free-body diagrams,$$\begin{align}
 &   &  & \begin{cases}
m_{3}g-T_{2} & =m_{3}a \\
T_{2}-T_{1} & =m_{2}a \\
T_{1} & =m_{1}a
\end{cases}  \\
 & \Rightarrow & m_{3}g  & =(m_{1}+m_{2}+m_{3})a \\
& \Rightarrow & a & =\frac{m_{3}}{m_{1}+m_{2}+m_{3}}g \\
& \Rightarrow &  & =\frac{2}{1+2+2}g \\
& \Rightarrow &  & =\frac{2}{5}g
\end{align}$$
3. From 2. $T_{1}=1\times \frac{2}{5}g=\frac{2}{5}g$ and $T_{2}=2\times \frac{2}{5}g+\frac{2}{5}g=\frac{6}{5}g$.

***5.2***
**A mass $m\:(\text{kg})$ hangs on a cord susupended from an elevator which is descending with an acceleration of $0.1g$. What is the tension $T$ in the cord in newtons?**

Ans:
By analyzing the free-body diagram, $mg-T=m(0.1g)$, which implies that $T=0.9mg \approx 8.829m \approx 8.8m\:\text{N}$.

***5.3***
**Two objects of mass $m=1\:\text{kg}$ each, connected by a taut string of length $L=2\:\text{kg}$, move in a circular orbit with constant speed $V=5ms^{-1}$ about their common center $C$ in a zero-$g$ environment, as shown in Fig. 5-2. What is the tension $T$ in the string in newtons?![[Fig.5-2.svg#invert]]**

Ans:
For a motion that is circular, in a small change in time, the distance that the moving object "falls" is $s=R\theta \times \theta / 2=\frac{R}{2}\left( \frac{V}{2\pi R}2\pi \right)^{2}=\frac{V^{2}}{2R}$. And $a=\frac{d^{2}s}{dt^{2}}=\frac{V^{2}}{R}$. Hence,![[moon_falling.svg#invert]]$$\begin{align}
T=ma=m \frac{V^{2}}{R}=1\times \frac{5^{2}}{2 / 2}=25\:\text{N}
\end{align}$$

***5.4***
**Referring to Fig. 5-3: What horizontal force $F$ must be constantly spplied to $M$ so that $M_{1}$ and $M_{2}$ do not move relative to $M$? Neglect friction.![[Fig.5-3.svg#invert]]**

Ans:
Since $M_{2}$ is relatively static to $M$, $M_{2}$ is static in the vertical direction. Let's say the tension of the string is $T$, then $M_{2}g=T$. In addition, $T=M_{1}a$ where $a$ is the acceleration of the $M_{1}$. Similarly, $M_{1}$ is relatively static to $M$, that is $$\begin{align}
F-M_{2}a-T=Ma
\end{align}$$which implies that$$\begin{align}
F & =Ma+M_{2}a+T \\
 & =(M+M_{2})\frac{M_{2}g}{M_{1}}+M_{2}g \\
 & =\frac{M_{2}}{M_{1}}(M+M_{1}+M_{2})g
\end{align}$$

***5.5***
**Referring to Fig. 5-4: what horizontal force $F$ must be constantly applied to $M=21\:\text{kg}$ so that $m_{1}=5\:\text{kg}$ does not move relative to $m_{2}=4\:\text{kg}$. Neglect friction.**
![[Fig.5-4.svg#invert]]
Ans:
Lets say the tension of the string is $T$ and the angle of the string on $m_{2}$ is $\theta$ with the horizontal. $m_{1}$ does not move relative to $m_{2}$ means that they have the same acceleration, and so do $M$. Assume that they accelerate in acceleration $a$, Then $$\begin{align}
  &   \begin{cases}
m_{2}g=T\sin \theta \\
m_{2}a=T\cos \theta
\end{cases}\\
   & m_{1}a =T   \\
 & Ma =F-T-T\cos \theta 
\end{align}$$Hence, $\cos \theta=m_{2} / m_{1}$ and $T=m_{2}g / \sqrt{ 1-(m_{2} / m_{1})^{2} }=m_{1}m_{2}g / \sqrt{ m_{1}^{2}-m_{2}^{2} }$. Thus,$$\begin{align}
 &  & \frac{m_{1}}{M} & =\frac{T}{F-T-Tm_{2} / m_{1}} \\
 & \Rightarrow & F & =\frac{M}{m_{1}}T\left( 1+\frac{m_{1}}{M} +\frac{m_{2}}{M}\right) \\
 & \Rightarrow &  & =\frac{Mm_{2}g(1+(m_{1}+m_{2}) / M)}{\sqrt{ m_{1}^{2}-m_{2}^{2} }} \\
 & \Rightarrow &  & =\frac{(Mm_{2}+(m_{1}+m_{2})m_{2})g}{\sqrt{ m_{1}^{2}-m_{2}^{2} }} \\
& \Rightarrow &  & =\frac{(21\times 4 \times +(5+4)\times 4)\times 9.81}{\sqrt{ 5^{2}-4^{2} }} \\
& \Rightarrow &  & =392.4\:\text{N} \\
& \Rightarrow & & \approx 392\:\text{N}
\end{align}$$

***5.6***
**In the system shown in Fig. 5-5, $M_{1}$ slides without friction on the inclined plane. $\theta=30^{\circ}$, $M_{1}=400\:\text{g}$, $M_{2}=200\:\text{g}$. Find the acceleration $a$ of $M_{2}$ and the tension $T$ in the cords**.
![[Fig.5-5.svg#invert]]
Ans:
Assume that the acceleration of $M_{2}$ is $a$, then $$\begin{align}
M_{2}g-T & =M_{2}a \\
\frac{T}{2}-M_{1}g\sin \theta & =M_{1} 2a
\end{align}$$Hence, $M_{2}g-2M_{1}g\sin \theta=M_{2}a+4M_{1}a$, that is, $$\begin{align}
a & =\frac{(M_{2}-2M_{1}\sin \theta)g}{M_{2}+4M_{1}} \\
 & =\frac{200-2\times 400 \times \frac{1}{2}}{200+4\times 400}g \\
 & =-\frac{1}{9}g
\end{align}$$Therefore, the acceleration of $M_{2}$ is $\frac{g}{9}$ upward. And $T=M_{2}\times \frac{10}{9}g=222.2g\:\text{g-wt}$.

***5.7***
**A simple crane is made of two parts, "$A$" with mass $M_{A}$, length $D$, height $H$, and distance $D / 2$ between wheels of radius $r$; and part "$B$", a uniform rod or boom of length $L$ and mass $M_{B}$. The crane is shown assembled in Fig. 5-6, with the pivot point $P$ at midpoint of top of $A$. The center of gravity of $A$ is midway between the wheels.**![[Fig.5-6 1.svg#invert]]
1. **With the rod or boom $B$ set at angle $\theta$ with the horizontal, what is the maximum mass $M_{max}$ that the crane can lift without tipping over?**
2. **If there is a mass $M'=(4 / 5)M_{max}$ at the end of the rope, what is the minimum time $t$ necessary to raise this load $M'$ a distance ($L\sin \theta$) from the ground? (The angle $\theta$ remains fixed, and the mass of the rope may be neglected.)**

Ans:
1. Assume that the normal force the ground acting on the left wheel is $W$, then the normal force action on the other wheel is $(M_{A}+M_{B}+M')g-W$ Where $W \in [0,\:M_{A}+M_{B}+M']$. Set a fulcrum at $P$. Since the system is balanced, the net torque in $P$'s point of view should equal zero. That is,$$
W \frac{D}{4}+M_{B}g \frac{L}{2}\cos \theta+M'gL\cos \theta=((M_{A}+M_{B}+M')g-W)\frac{D}{4}
$$And$$
\begin{align}
M'&=\frac{\left( M_{A}g \frac{D}{4}+M_{B}g\left(  \frac{D}{4}- \frac{L}{2}\cos \theta \right) -W \frac{D}{2} \right)}{g\left(  L\cos \theta- \frac{D}{4} \right)} \\
&=\frac{(M_{A}+M_{B})D-2M_{B}L\cos \theta}{4L\cos \theta-D}-\frac{W \frac{D}{w}}{g\left( L\cos \theta-\frac{D}{4} \right)}
\end{align}
$$We can see that $M'$ has its maximum when $W=0$. Therefore, $$M_{max}'=\frac{(M_{A}+M_{B})D-2M_{B}L\cos \theta}{4L\cos \theta-D}$$
2. $M'$ has its maximum mass $M'_{max}$ can be interpreted as the rope have its maximum tension $M'_{max}g$. For having the minimum time $t$, we want to raise the load with the maximum tension $M'_{max}g$. Thus the net force acting on $M'$ is $M'_{max}g-\frac{4}{5}M'_{max}g=\frac{1}{5}M'_{max}g$. By Newton's second law of dynamics, $\frac{1}{5}M'_{max}g=M'_{max}a$, which implies that the acceleration $a=\frac{g}{5}$. By kinematics, $L\sin \theta= \frac{1}{2}at^{2}$. So $t=\sqrt{ \frac{10L\sin \theta}{g} }$

***5.8***
**An early arrangement for measuring the acceleration of gravity, called At-wood's Machine, is shown in Fig.5-7. The pulley $P$ and cord $C$ have negligible mass and fiction. The system is balanced with equal masses $M$ on each side as shown (solid line), and then a small rider $m$ is added to one side. The combined masses accelerate through a certain distance $h$, the rider is caught on a ring and the two equal masses then move on with constant speed, $v$. find the value of $g$ that correspoonds to the measured values of $m$, $M$, $h$, and $v$.![[Fig.5-7.svg#invert]]

Ans:
After adding the rider $m$, the net force is $mg$ downward with respect to the left $M$. By Newton's second law of dynamics, acceleration is $a=\frac{m}{2M+m}g$. Using kinematics, we know that $v^{2}=0^{2}+2 \frac{m}{2M+m}gh$. That is, $g=\frac{(2M+m)v^{2}}{2mh}$.

***5.9***
**An elevator of mass $M_{2}$ has hanging from its ceiling a mass $M_{1}$, as shown in Fig. 5-8. The elevator is being accelerated upward by a constant force $F$. ($F$ is greater than ($M_{1}+M_{2}$)g.) The mass $M_{1}$ is initially a distance $s$ above the elevator floor.**
1. **Find the acceleration $a_{0}$ of the elevator.**
2. **What is the tension $T$ in the string connecting the mass $M_{1}$ to the elevator?**
3. **If the string suddenly breaks, what is the acceleration $a$ of the elevator immediately after, and what is the acceleration $a'$ of mass $M_{1}$?**
4. **How much time $t$ does it take for $M_{1}$ to hit the bottom of the elevator?**
![[Fig.5-8.svg#invert]]

Ans:
1. By Newton's second law of dynamics, $(M_{1}+M_{2})a_{0}=F-(M_{1}+M_{2})g$. That is, $a_{0}=\frac{F}{M_{1}+M_{2}}-g$.
2. The tension $T-M_{1}g=M_{1}a_{0}=\frac{M_{1}F}{M_{1}+M_{2}}-M_{1}g$. So $T=\frac{M_{1}F}{M_{1}+M_{2}}$.
3. By Newton's second law of dynamics, $a=\left( \frac{F}{M_{2}}-g \right)$. And $a'=-g$.
4. Set our view inside the elevator, then the net acceleration is $a'-a=-\frac{F}{M_{2}}$. Hence, applying formula from kinematics, we have $-s=\frac{1}{2}\left( - \frac{F}{M_{2}}t^{2} \right)$, which is $t=\sqrt{ \frac{2M_{2}s}{F} }$.

***5.10***
**Given the system shown in Fig. 5-9, consider all surfaces frictionless. If $m=150\:\text{g}$ is released when it is $d=1\:\text{m}$ above the base of $M=1650\:\text{g}$, how long after release, $\Delta t$, will $m$ strike the base of $M$?**
![[Fig.5-9.svg#invert]]
Ans:
Analyzing the free-body diagram of $m$. In the vertical direction of $m$, it has $$mg-T=ma$$In the horizontal direction, $F=m \frac{a}{2}$.

For $M$, $2T-F=M \frac{a}{2}$. Hence,$$\begin{align}
2(mg-ma)-m \frac{a}{2} & =M \frac{a}{2} \\
(M+5m)a & =4mg \\
 a& =\frac{4m}{M+5m}g \\
 & \approx \frac{4\times 150}{1650 + 5 \times 150}\times 9.81 \\
 & \approx 2.45
\end{align}$$Applying kinematics, we have$$\begin{align}
\frac{1}{2}a(\Delta t)^{2} & =d \\
\Delta t & =\sqrt{ \frac{2}{2.45} } \approx 0.9\:\text{s}
\end{align}$$

***5.11***
**None of the identical gondolas on the Martian canal Rimini is quite able to support the load of both Paolo and Francesca, two affectionate marsupials who refuse to go in separate boats. The enterprising gondolier, Giuseppe, collects their fare by rigging them up from the mast as shown in Fig. 5-10, using the massless ropes and massless, frictionless pulleys characteristic of Martian construction. Giuseppe ferries them across them before they hit either the mast of the deck. Assuming Paulo's mass is $90\: \mathrm{kg}$ and Francesca's is $60\:\mathrm{kg}$, how much load $W$ does Giuseppe save?**

***hint: *** **Remember that the tension in a massless cord that passes over a massless, frictionless pulley is the same on both sides of the pulley.**
![[Fig.5-10.svg#invert]]
Ans:
Assume that the tension in the cord is $T$. Analyzing the free-body diagram of Paolo and Francesca, we have$$\begin{align}
2T-90g&=90 \frac{a}{2} \\
T-60g &= 60(-a)
\end{align}$$Therefore, $a=\frac{2g}{11}$. And $T = \frac{540}{11}g$. The the weight of the system is $3T=\frac{1620}{11}g$. Thus,  Giuseppe had saved $90+60-\frac{1620}{11}\approx 2.7 \:\mathrm{kg-wt}$.

***5.12***
**A painter working from a "bosun's" chair is hung down the side of a tall building, as shown in Fig. 5-11. Wishing to move in a hurry, the  $180\:\mathrm{lb}$ painter pulls down on the fall rope so hard that he presses against the chair with a force of only $100\:\mathrm{lb}$. The chair itself weighs $30.0\:\mathrm{lb}$.**
1. **What is the acceleration $\mathbf{a}$ of the painter and the chair?**
2. **What is the total force $F$ supported by the pulley?**
![[Fig.5-11.svg#invert]]
Ans:
Assume that the painter pull the rope with a force $T$.
1. By analyzing the free-body diagram of the painter, we have$$180g-100g-T=180a$$For the chair, $$30g+100g-T=30a$$Combining the two equation, we have$$a=-\frac{g}{3}$$That is, $\mathbf{a}$ is equal to $\frac{g}{3}$ upward.
2. From the equation above, $T=140g$. The pulley supports $2T=280g$.

***5.13***
**A space traveler about to leave for the moon has a spring balance and a $1.0\:\mathrm{kg}$ mass $A$, which when hung on the balance on the Earth gives the reading of $9.8\: \mathrm{N}$. Arriving at the moon at a place where the acceleration of gravity is not known exactly but has a value of about one sixth the acceleration of gravity at the Earth's surface, he picks up a stone $B$ which gives a reading of $9.8\: \mathrm{N}$ when weighed on the spring balance. He then hangs $A$ and $B$ over a pulley as shown in Fig. 5-12 and observes that $B$ falls with an acceleration of $1.2\: \mathrm{ms}^{-2}$. What is the mass $m_{B}$ of the stone $B$?**
![[Fig.5-12.svg#invert]]
Ans:
Let the gravity on the moon be $g'$.
From the things the space traveler had done with the spring, we know that $1.0g = 9.8\:\mathrm{N}$ and $m_{B} g'=9.8\:\mathrm{N}$, which is, $m_{B}=\frac{g}{g'}\:\text{kg}$.

From Figure 5-12, by Newton's law of dynamics, we have$$m_{B}g'-m_{A}g'=1.2(m_{A}+m_{B})$$That is, $$\begin{align}
&&g' & =\frac{1.2\left( 1+\frac{g}{g'} \right)}{\frac{g}{g'}-1} \\
 &\Rightarrow& g-g'&=1.2+\frac{1.2g}{g'} \\
&\Rightarrow& 0 &=(g')^{2}-(g-1.2)g'+1.2g
\end{align}$$
And $$\begin{align}
g' & =\frac{g-1.2\pm \sqrt{ (g-1.2)^{2}-4.8g }}{2} \\
 & \approx 6.9\:\text{or}\: 1.7\:\text{ms}^{-2}
\end{align}$$Since $g'$ is about one sixth of $g$, $g'=1.7\:\text{ms}^{-2}$.
Therefore, $m_{B}=\frac{g}{g'}=\frac{9.8}{1.7}\approx 5.8\:\text{kg}$.

***5.14***
**Use numerical methods to solve the following exercises.**

**A mass suspended from a spring hangs motionless, and is then given an upward blow such that it moves initially at unit speed. If the mass and spring constant are such that the equation of motion is $\ddot{x} = -x$, find the maximum height $x_{\text{max}}$ attained by numerical integration of the equation of motion.**

Ans:
It is a two-dimensional phase space with initial states $$ \begin{align}
x(0)=0 \\
\dot{x}(0)=1
\end{align}$$
The motion of the system is given by$$\begin{align}
x_{i+1} & =x_{i}+\dot{x_{i}}\Delta t \\
\dot{x}_{i+1} & =\dot{x}_{i}-x_{i}\Delta t
\end{align}$$
Let $X_{i}=\begin{bmatrix}x_{i} \\ \dot{x}_{i}\end{bmatrix}$. Then $X_{0}=\begin{bmatrix}x_{0} \\ \dot{x}_{0}\end{bmatrix}=\begin{bmatrix}x(0) \\ \dot{x}(0)\end{bmatrix}=\begin{bmatrix}0 \\ 1\end{bmatrix}$ $$X_{i+1}=\begin{bmatrix}x_{i+1} \\ \dot{x}_{i+1}\end{bmatrix}=\begin{bmatrix}
1 & \Delta t \\
-\Delta t & 1
\end{bmatrix}\begin{bmatrix}
x_{i} \\
\dot{x_{i}}
\end{bmatrix}=\begin{bmatrix}
1 & \Delta t \\
-\Delta t & 1
\end{bmatrix}X_{i}$$It is easy to see that $$X_{n}=\begin{bmatrix}
1 & \Delta t \\
-\Delta t & 1
\end{bmatrix}^{n}X_{0}$$We diagonalize the matrix.
The characteristic polynomial of $\begin{bmatrix}1 & \Delta t \\-\Delta t & 1\end{bmatrix}$ is $$\det(\begin{bmatrix}1-\lambda & \Delta t \\ -\Delta t & 1-\lambda\end{bmatrix})=(1-\lambda)^{2}+(\Delta t)^{2}$$And$$\begin{align}
&&&(1-\lambda)^{2}+(\Delta t)^{2}=0 \\
&\Rightarrow&&\lambda^{2}-2\lambda+1+(\Delta t)^{2}=0 \\
&\Rightarrow& &\lambda=\frac{2\pm \sqrt{ 4-4-4(\Delta t)^{2} }}{2} \\
&\Rightarrow& &\lambda=1\pm(\Delta t)i
\end{align}$$If $\lambda=1-(\Delta t)i$, then $$\begin{align}
\mathrm{ker}(\begin{bmatrix}1 & \Delta t \\-\Delta t & 1\end{bmatrix}-\lambda I) & =\mathrm{ker}(\begin{bmatrix}1-(1-(\Delta t)i) & \Delta t \\ -\Delta t & 1-(1-(\Delta t)i)\end{bmatrix}) \\
 & =\mathrm{ker(\begin{bmatrix}(\Delta t)i & \Delta t \\ -\Delta t & (\Delta t)i\end{bmatrix})} \\
 & =\mathrm{ker(\begin{bmatrix}(\Delta t)i & \Delta t \\ 0 & 0\end{bmatrix})} \\
 & =\mathrm{span}(\begin{bmatrix}
i \\
1
\end{bmatrix})
\end{align}$$If $\lambda=1+(\Delta t)i$, then$$\begin{align}
\mathrm{ker}(\begin{bmatrix}1 & \Delta t \\-\Delta t & 1\end{bmatrix}-\lambda I) & =\mathrm{ker}(\begin{bmatrix}1-(1+(\Delta t)i) & \Delta t \\ -\Delta t & 1-(1+(\Delta t)i)\end{bmatrix}) \\
 & =\mathrm{ker(\begin{bmatrix}-(\Delta t)i & \Delta t \\ -\Delta t & -(\Delta t)i\end{bmatrix})} \\
 & =\mathrm{ker(\begin{bmatrix}-(\Delta t)i & \Delta t \\ 0 & 0\end{bmatrix})} \\
 & =\mathrm{span}(\begin{bmatrix}
-i \\
1
\end{bmatrix})
\end{align}$$
Let $P=\begin{bmatrix}i  & -i \\1 & 1\end{bmatrix}$, $P^{-1}=\begin{bmatrix}-\frac{i}{2} & \frac{1}{2} \\\frac{i}{2} & \frac{1}{2}\end{bmatrix}$.

Hence,$$
\begin{align} 
\begin{bmatrix}
1-(\Delta t)i & 0 \\
0 & 1+(\Delta t)i
\end{bmatrix}=P^{-1}\begin{bmatrix}1 & \Delta t \\-\Delta t & 1\end{bmatrix}P
\end{align}$$
And$$
\begin{align}
X_{n} & =\begin{bmatrix}
1 & \Delta t \\
-\Delta t & 1
\end{bmatrix}^{n}X_{i} \\
 & =\left( P\begin{bmatrix}
1-(\Delta t)i & 0 \\
0 & 1+(\Delta t)i
\end{bmatrix} P^{-1} \right)^{n}X_{0} \\
 & = P\begin{bmatrix}
1-(\Delta t)i & 0 \\
0 & 1+(\Delta t)i
\end{bmatrix}^{n} P^{-1} X_{0} \\
 & = P\begin{bmatrix}
(1-(\Delta t)i)^{n} & 0 \\
0 & (1+(\Delta t)i)^{n}
\end{bmatrix}P^{-1}X_{0}\\
 & =\begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
(1-(\Delta t)i)^{n} & 0 \\
0 & (1+(\Delta t)i)^{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0}
\end{align}$$
We want to calculate $X(t)$. Using the sum over $[t, 0]$ with partition $0=t_{0}<t_{1}<t_{2}<\dots<t_{n}=t$. We set $t_{i+1}-t_{i}=\Delta t$ for simplicity. Then $t_{n}=n\Delta t$ and $\Delta t=\frac{t_{n}}{n}$. Hence, $$\begin{align}
X_{n}(t_{n}) =\begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
\left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{n} & 0 \\
0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0}
\end{align}$$
We expect that $\lim \limits_{ n \to \infty }X_{n}(t_{n})=X(t)$. And$$\begin{align}
\lim \limits_{ n \to \infty } X_{n}(t_{n}) & =\lim \limits_{ n \to \infty } \begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
\left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{n} & 0 \\
0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0} \\
 & =\begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
\lim \limits_{ n \to \infty } \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{n} & 0 \\
0 & \lim \limits_{ n \to \infty } \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
e^{-it_{n}} & 0 \\
0 & e^{it_{n}}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0}
\end{align}$$Applying Euler's formula ($e^{it}=\cos t+i\sin t$), we have$$\begin{align}
 \lim \limits_{ n \to \infty } X_{n}(t_{n})& =\lim \limits_{ n \to \infty } \begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
\cos t_{n}-i\sin t_{n} & 0 \\
0 & \cos t_{n}+i\sin t_{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}X_{0} \\
& \left(X_{0}=\begin{bmatrix}0 \\ 1\end{bmatrix}\right) \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
i  & -i \\
1 & 1
\end{bmatrix}\begin{bmatrix}
\cos t_{n}-i\sin t_{n} & 0 \\
0 & \cos t_{n}+i\sin t_{n}
\end{bmatrix} \begin{bmatrix}
-\frac{i}{2} & \frac{1}{2} \\
\frac{i}{2} & \frac{1}{2}
\end{bmatrix}\begin{bmatrix}0 \\ 1\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
i\cos t_{n}+\sin t_{n} & -i\cos t_{n}+\sin t_{n} \\
\cos t_{n}-i\sin t_{n} & \cos t_{n}+i\sin t_{n}
\end{bmatrix}\begin{bmatrix}
\frac{1}{2} \\
\frac{1}{2}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
\sin t_{n} \\
\cos t_{n}
\end{bmatrix}
\end{align}$$
Finally, we have $$\begin{bmatrix}
x(t) \\
\dot{x}(t)
\end{bmatrix}=X(t)=\lim \limits_{ n \to \infty } X_{n}(t_{n})=\lim \limits_{ n \to \infty } \begin{bmatrix}
\sin t_{n} \\
\cos t_{n}
\end{bmatrix}=\begin{bmatrix}
\sin t \\
\cos t
\end{bmatrix}$$
Hence, the maximum height $x_{\text{max}}$ happens when $t=\frac{\pi(1+4k)}{2}$ where $k\in \mathbb{Z}$. Which is $x_{\text{max}}=1$.

***5.15***
**A particle of mass $m$ moves along a straight line. Its motion is resisted by a force proportional to its velocity, $F=-kv$. It starts with speed $v=v_{0}$ at $x=0$ and $t=0$.**
1. **Find $x$ as a function of $t$ by numerical integration.**
2. **Find the time $t_{\frac{1}{2}}$ required to lose half its speed, and the maximum distance $x_{\text{max}}$ attained.**

**Notes:**

1. **Adjust the scales of $x$ and $t$ so that the equation of motion has simple numerical coefficients.**
2. **Invent a scheme to attain good accuracy with a relatively coarse interval for $\Delta t$**
3. **Use dimensional analysis to deduce how $t_{\frac{1}{2}}$ and $x_{\text{max}}$ should depend upon $v_{0}$, $k$ and $m$, and solve for the actual motion only for a single convenient value of $v_{0}$, say $v_{0}=1.00$ (in the modified $x$ and $t$ units)**

Ans:
This is a second order ordinary differential equation $m \ddot{x}=-k \dot{x}$ with two-dimensional phase space.
We rescale $t$ and $x$ by substitute$$\tilde{t}=c_{1}t,\quad \tilde{x}=c_{2}x$$Then $$\frac{d^{2} \tilde{x}}{d \tilde{t}^{2}}=\frac{d}{dt}\left( \frac{d \tilde{x}}{dx}\frac{dx}{d t}\frac{d t}{d \tilde{t}} \right)\frac{dt}{d \tilde{t}}=\frac{c_{2}}{c_{1}^{2}}\left( \frac{d^{2}x}{dt^{2}} \right)=\frac{c_{2}}{c_{1}^{2}}\left( -k \frac{dx}{dt} \right)=\frac{c_{2}}{c_{1}^{2}}(-k) \frac{c_{1}}{c_{2}} \frac{d \tilde{x}}{d \tilde{t}}=-\frac{k}{c_{1}}\frac{d \tilde{x}}{d \tilde{t}}$$
Note that chain rule was used.
Let $c_{1}=k$, $c_{2}=1$. Then we have a rescaled differential equation.$$\ddot{\tilde{x}}=-\dot{\tilde{x}}$$
The initial states of this system is $$\tilde{X}_{0}=\begin{bmatrix}
\tilde{x}_{0} \\
\dot{\tilde{x}}_{0}
\end{bmatrix}=\begin{bmatrix}
\tilde{x}(0) \\
\dot{\tilde{x}}(0)
\end{bmatrix}=\begin{bmatrix}
0 \\
\tilde{v}_{0}
\end{bmatrix}$$
We apply the numerical method using numerical integration.
$$\tilde{X}_{i+1} = \begin{bmatrix}
\tilde{x}_{i+1} 
\dot{\tilde{x}}_{i+1}
\end{bmatrix}
=\begin{bmatrix}
\tilde{x}_{i} +\dot{\tilde{x}}_{i}\Delta t\\
\dot{\tilde{x}}_{i}-\dot{\tilde{x}}\Delta t 
\end{bmatrix}=\begin{bmatrix}
1 & \Delta t \\
0 & (1-\Delta t)
\end{bmatrix}\begin{bmatrix}
\tilde{x}_{i} \\
\dot{\tilde{x}}_{i}
\end{bmatrix}=\begin{bmatrix}
1 & \Delta t \\
0 & (1-\Delta t)
\end{bmatrix}\tilde{X}_{i}$$
It is easy to see that $$\tilde{X}_{n}=\begin{bmatrix}
1 & \Delta t \\
0 & (1-\Delta t)
\end{bmatrix}^{n}\tilde{X}_{0}$$Hence, it is reasonable for us to diagonalize $A:=\begin{bmatrix}1 & \Delta t \\0 & (1-\Delta t)\end{bmatrix}$.
The characteristic polynomial of $A$ is$$P_{A}(\lambda)=(1-\lambda)(1-\Delta t-\lambda)$$$P_{A}(\lambda)=0$ when $\lambda=1$ or $\lambda=1-\Delta t$.

When $\lambda=1$:
The eigenspace with respect to $\lambda$ is $E_{\lambda}=\mathrm{span}(\begin{bmatrix}1 \\ 0\end{bmatrix})$
When $\lambda=1-\Delta t$:
The eigenspace with respect to $\lambda$ is $E_{\lambda}=\mathrm{span}(\begin{bmatrix}1 \\ -1\end{bmatrix})$

Let $P=\begin{bmatrix}1 & 1 \\ 0 & -1\end{bmatrix}$. Then $P^{-1}=\begin{bmatrix}1 & 1 \\ 0 & -1\end{bmatrix}$. And $$P^{-1}AP=\begin{bmatrix}
1  & 0 \\
0 & 1-\Delta t
\end{bmatrix}$$Which is, $$A=P\begin{bmatrix}
1 & 0 \\
0 & 1-\Delta t
\end{bmatrix}P^{-1}$$
Consider the partition $0=t_{0}<t_{1}<t_{2}<\dots<t_{n}=t$ with $t_{i+1}-t_{i}=\Delta t,\: \forall i$ for simplicity. So $\Delta t=\frac{t_{n}}{n}$ We expect that $\tilde{X}(\tilde{t})=\lim \limits_{ n \to \infty }\tilde{X}_{n}(t_{n})$. That is$$\begin{align}
\lim \limits_{ n \to \infty } \tilde{X}_{n}(t_{n}) & =\lim \limits_{ n \to \infty } \begin{bmatrix}
1 & \Delta t \\
0 & 1-\Delta t
\end{bmatrix}^{n}\tilde{X}_{0} \\
 & =\lim \limits_{ n \to \infty } \left(P\begin{bmatrix}
1 & 0 \\
0 & 1-\Delta t
\end{bmatrix}P^{-1}\right)^{n}\begin{bmatrix}
\tilde{x}_{0} \\
\dot{\tilde{x}}_{0}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } P\begin{bmatrix}
1^{n} & 0 \\
0 & (1-\Delta t)^{n}
\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
\tilde{v}_{0}
\end{bmatrix} \\
 & =P\begin{bmatrix}
1 & 0 \\
0 & \lim \limits_{ n \to \infty } \left( 1-\frac{t_{n}}{n} \right)^{n}
\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
\tilde{v}_{0}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}1 & 1 \\ 0 & -1\end{bmatrix}\begin{bmatrix}
1 & 0 \\
0 & e^{-t_{n}}
\end{bmatrix}\begin{bmatrix}1 & 1 \\ 0 & -1\end{bmatrix}\begin{bmatrix}
0 \\
\tilde{v}_{0}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
1 & e^{-t_{n}} \\
0 & -e^{-t_{n}}
\end{bmatrix}\begin{bmatrix}
\tilde{v}_{0} \\
-\tilde{v}_{0}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
\tilde{v}_{0}-\tilde{v}_{0}e^{-t_{n}} \\
\tilde{v}_{0}e^{-t_{n}}
\end{bmatrix}
\end{align}$$Therefore,$$\tilde{X}(t)=\begin{bmatrix}
\tilde{x}(t) \\
\dot{\tilde{x}}(t)
\end{bmatrix}=\lim \limits_{ n \to \infty }\tilde{X}_{n}(t_{n})=\lim \limits_{ n \to \infty } \begin{bmatrix}
\tilde{v}_{0}-\tilde{v}_{0}e^{-t_{n}} \\
\tilde{v}_{0}e^{-t_{n}}
\end{bmatrix}= \begin{bmatrix}
\tilde{v}_{0}-\tilde{v}_{0}e^{-\tilde{t}} \\
\tilde{v}_{0}e^{-\tilde{t}}
\end{bmatrix}$$
1. For $x(t)$, we have $$\begin{align}
&&\tilde{x}(t) & =\tilde{v}_{0}-\tilde{v}_{0}e^{-\tilde{t}} \\
&\Rightarrow&c_{2}x(t) & =\frac{c_{2}}{c_{1}}v_{0}\left( 1-e^{-\tilde{t}/c_{1}} \right) \\
&\Rightarrow& x(t) & =\frac{v_{0}}{c_{1}}\left( 1-e^{-\tilde{t}/c_{1}} \right) \\
 &  &  & =\frac{v_{0}}{k}\left( 1-e^{-t/k} \right)
\end{align}$$
2. For $v(t)=\dot{x}(t)$, we have$$\begin{align}
 &  & \dot{\tilde{x}}(t) & =\tilde{v}_{0}e^{-\tilde{t}} \\
&\Rightarrow& \frac{c_{2}}{c_{1}}\dot{x}(t) & =\frac{c_{2}}{c_{1}}v_{0}e^{-\tilde{t}/c_{1}} \\
 & \Rightarrow & \dot{x}(t) & =v_{0}e^{-t/k}
\end{align}$$$\frac{v_{0}}{2}=v_{0}e^{-t/k}\Rightarrow t=k\ln 2$. Hence, it requires $t_{\frac{1}{2}}=k\ln 2$ to lose half its speed. From 1., it is easy to see that $x_{\text{max}}$ happens as $t\to \infty$, which is, $\lim \limits_{ t \to \infty } \frac{v_{0}}{k}(1-e^{-t/k})=\frac{v_{0}}{k}$.

We can use the half-way(middle point) of $x_{i}$ and $\dot{x}_{i}$, i.e., $\dot{x}_{i+1_{\text{mid}}}=\dot{x}_{i}-\dot{x}_{i} \frac{\Delta t}{2}$, $x_{i+1}=x_{i}+\dot{x}_{i+1_{\text{mid}}}\Delta t$, to attain a better accuracy.

For the units-modified value $\tilde{X}$ and $\tilde{t}$, we take $\tilde{v}_{0}=1.00$, then we have the equation of the motion is $$\begin{align}
\tilde{x}(t) & =1-e^{-t} \\
\dot{\tilde{x}}(t)  & =e^{-t}
\end{align}$$
***5.16***
**A certain charged particle moves in an electric and a magnetic filed according to the equations, $$\begin{align}
\frac{dv_{x}}{dt} & =-2v_{y}, \\
\frac{dv_{y}}{dt} & =1+2v_{x}.
\end{align}$$
At $t=0$ the particle starts at $x=0$, $y=0$ with velocity $v_{x}=1.00$, $v_{y}=0$. Determine the nature of the motion by numerical integration.**

Ans:
This is a second order ordinary differential equations system
$$\begin{align}
\ddot{x} & =-2\dot{y} \\
\ddot{y} & =1+2\dot{x}
\end{align}$$
with a four-dimensional phase space $(x, y,\dot{x},\dot{y})$. We rescale and substitute$$\tilde{t}=c_{1}t,\quad \tilde{x}=c_{2}x,\quad \tilde{y}=c_{3}y$$
So
$$\begin{align}
\frac{d^{2}\tilde{x}}{d\tilde{t}^{2}} & =\frac{d}{dt}\left( \frac{d\tilde{x}}{d x}\frac{dx}{dt}\frac{dt}{d \tilde{t}} \right)\frac{dt}{d \tilde{t}}=\frac{d \tilde{x}}{dx}\left( \frac{dt}{d \tilde{t}} \right)^{2}\left( -2\frac{d \tilde{y}}{d \tilde{t}} \frac{c_{1}}{c_{3}} \right)=-2 \frac{c_{2}}{c_{1}c_{3}} \frac{d \tilde{y}}{d \tilde{t}} \\
\frac{d^{2}\tilde{y}}{d \tilde{t}^{2}} & =\frac{d}{dt}\left( \frac{d \tilde{y}}{dy}\frac{dy}{dt}\frac{dt}{d \tilde{t}} \right)\frac{dt}{d\tilde{t}}=\frac{d \tilde{y}}{dy}\left( \frac{dt}{d \tilde{t}} \right)^{2}\left( 1+2\frac{d \tilde{x}}{d \tilde{t}} \frac{c_{1}}{c_{2}} \right)=\frac{c_{3}}{c_{1}^{2}}+2 \frac{c_{3}}{c_{1}c_{2}} \frac{d \tilde{x}}{d \tilde{t}}
\end{align}$$
Let $\frac{c_{2}}{c_{1}c_{3}}=\frac{1}{2}$, $\frac{c_{3}}{c_{1}c_{2}}=\frac{1}{2}$ and $\frac{c_{3}}{c_{1}^{2}}=1$. Then $c_{1}=2$, $c_{2}=4$ $c_{3}=4$.
The new differential equations system is$$\begin{align}
\ddot{\tilde{x}} & =-\dot{\tilde{y}} \\
\ddot{\tilde{y}} & =1+\dot{\tilde{x}}
\end{align}$$And $$\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}(0) \\
\dot{\tilde{y}}(0)
\end{bmatrix}=\begin{bmatrix}
0 \\
0 \\
2 \\
0
\end{bmatrix}$$
The numerical integration is given by
$$\begin{align}
\begin{bmatrix}
\tilde{x}_{i+1} \\
\tilde{y}_{i+1} \\
\dot{\tilde{x}}_{i+1} \\
\dot{\tilde{y}}_{i+1}
\end{bmatrix}=\begin{bmatrix}
\tilde{x}_{i} +\dot{\tilde{x}}_{i}\Delta t\\
\tilde{y}_{i} +\dot{\tilde{y}}_{i}\Delta t\\
\dot{\tilde{x}}_{i} -\dot{\tilde{y}}_{i}\Delta t\\
\dot{\tilde{y}}_{i}+(1+\dot{\tilde{x}}_{i})\Delta t
\end{bmatrix}=\begin{bmatrix}
1 & 0 & \Delta t & 0 \\
0 & 1 & 0 & \Delta t \\
0 & 0 & 1 & -\Delta t \\
0 & 0 & \Delta t & 1
\end{bmatrix}\begin{bmatrix}
\tilde{x}_{i} \\
\tilde{y}_{i} \\
\dot{\tilde{x}}_{i} \\
\dot{\tilde{y}}_{i}
\end{bmatrix}+\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix}
\end{align}$$
It is easy to see that $$\begin{align}
\begin{bmatrix}
\tilde{x}_{n} \\
\tilde{y}_{n} \\
\dot{\tilde{x}}_{n} \\
\dot{\tilde{y}}_{n}
\end{bmatrix}=\begin{bmatrix}
1 & 0 & \Delta t & 0 \\
0 & 1 & 0 & \Delta t \\
0 & 0 & 1 & -\Delta t \\
0 & 0 & \Delta t & 1
\end{bmatrix}^{n}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ 
\sum\limits_{k=0}^{n}  
\begin{bmatrix}
1 & 0 & \Delta t & 0 \\
0 & 1 & 0 & \Delta t \\
0 & 0 & 1 & -\Delta t \\
0 & 0 & \Delta t & 1
\end{bmatrix}^{k}
\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix}
\end{align}$$
Let $A:=\begin{bmatrix}1 & 0 & \Delta t & 0 \\0 & 1 & 0 & \Delta t \\0 & 0 & 1 & -\Delta t \\0 & 0 & \Delta t & 1\end{bmatrix}$. We diagonalize $A$. The characteristic polynomial of $A$ is given by $P_{A}(\lambda)=\det(A-\lambda I)=(1-\lambda)^{2}((1-\lambda)^{2}+\Delta t^{2})=(1-\lambda)^{2}(\lambda-(1\pm(\Delta t)i))$. $P_{A}(\lambda)=0$ when $\lambda=1\:\text{or}\:1-(\Delta t)i\:\text{or}\:1+(\Delta t)i$.

If $\lambda=1$, then
$$\begin{align}
\mathrm{ker}(A-I) & =\mathrm{ker}(\begin{bmatrix}0 & 0 & \Delta t & 0 \\0 & 0 & 0 & \Delta t \\0 & 0 & 0 & -\Delta t \\0 & 0 & \Delta t & 0\end{bmatrix}) \\
 & =\mathrm{span}(\begin{bmatrix}
1 \\
0 \\
0 \\
0
\end{bmatrix},\begin{bmatrix}
0 \\
1 \\
0 \\
0
\end{bmatrix})
\end{align}$$
If $\lambda=1-(\Delta t)i$, then
$$\begin{align}
\mathrm{ker}(A-(1-(\Delta t)i)I) & =\mathrm{ker}(\begin{bmatrix}(\Delta t)i & 0 & \Delta t & 0 \\0 & (\Delta t)i & 0 & \Delta t \\0 & 0 & (\Delta t)i & -\Delta t \\0 & 0 & \Delta t & (\Delta t)i\end{bmatrix}) \\
 & =\mathrm{ker}(\begin{bmatrix}i & 0 & 1 & 0 \\0 & i & 0 & 1 \\0 & 0 & i & -1 \\0 & 0 & 0 & 0\end{bmatrix}) \\
 & =\mathrm{span}(\begin{bmatrix}
1 \\
i \\
-i \\
1
\end{bmatrix})
\end{align}$$
If $\lambda=1+(\Delta t)i$, then
$$\begin{align}
\mathrm{ker}(A-(1+(\Delta t)i)I) & =\mathrm{ker}(\begin{bmatrix}-(\Delta t)i & 0 & \Delta t & 0 \\0 & -(\Delta t)i & 0 & \Delta t \\0 & 0 & -(\Delta t)i & -\Delta t \\0 & 0 & \Delta t & -(\Delta t)i\end{bmatrix}) \\
 & =\mathrm{ker}(\begin{bmatrix}-i & 0 & 1 & 0 \\0 & -i & 0 & 1 \\0 & 0 & i & 1 \\0 & 0 & 0 & 0\end{bmatrix}) \\
 & =\mathrm{span}(\begin{bmatrix}
1 \\
-i \\
i \\
1
\end{bmatrix})
\end{align}$$
Let $P=\begin{bmatrix}1 & 0 & 1 & 1 \\ 0 & 1 & i & -i \\ 0 & 0 & -i & i \\ 0 & 0 & 1 & 1\end{bmatrix}$, $P^{-1}=\begin{bmatrix}1&0&0&1 \\ 0&1&1&0 \\ 0&0& \frac{i}{2} & \frac{1}{2} \\ 0& 0 & -\frac{i}{2} & \frac{1}{2}\end{bmatrix}$.

Hence $P^{-1}AP=\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1-(\Delta t)i & 0 \\ 0 & 0 & 0 & 1+(\Delta t)i\end{bmatrix}$. 
And $A = P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1-(\Delta t)i & 0 \\ 0 & 0 & 0 & 1+(\Delta t)i\end{bmatrix}P^{-1}$

Now we calculate the numerical integration.
$$
\begin{align}
\lim \limits_{ n \to \infty } \begin{bmatrix}
\tilde{x}_{n} \\
\tilde{y}_{n} \\
\dot{\tilde{x}}_{n} \\
\dot{\tilde{y}}_{n}
\end{bmatrix} & =\lim \limits_{ n \to \infty } \left( \begin{bmatrix}
1 & 0 & \Delta t & 0 \\
0 & 1 & 0 & \Delta t \\
0 & 0 & 1 & -\Delta t \\
0 & 0 & \Delta t & 1
\end{bmatrix}^{n}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ 
\sum\limits_{k=0}^{n}  
\begin{bmatrix}
1 & 0 & \Delta t & 0 \\
0 & 1 & 0 & \Delta t \\
0 & 0 & 1 & -\Delta t \\
0 & 0 & \Delta t & 1
\end{bmatrix}^{k}
\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix} \right) \\
 & =\lim \limits_{ n \to \infty } \left(P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1-(\Delta t)i & 0 \\ 0 & 0 & 0 & 1+(\Delta t)i\end{bmatrix}P^{-1}\right)^{n}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ \\
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}\left(P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1-(\Delta t)i & 0 \\ 0 & 0 & 0 & 1+(\Delta t)i\end{bmatrix}P^{-1}\right)^{k}\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix} \\
 & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } (1-(\Delta t)i)^{n} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } (1+(\Delta t)i)^{n}\end{bmatrix}P^{-1}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ \\
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & (1-(\Delta t)i)^{k} & 0 \\ 0 & 0 & 0 & (1+(\Delta t)i)^{k}\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix}
\end{align}
$$
Consider the partition $0=t_{0}<t_{1}<t_{2}<\dots<t_{n}=t$. Let $t_{i+1}-t_{i}=\Delta t$ for simplicity. So $\Delta t=\frac{t_{n}}{t}$. We expect that $\lim \limits_{ n \to \infty } \begin{bmatrix}\tilde{x}_{n}(t_{n}) \\\tilde{y}_{n}(t_{n}) \\\dot{\tilde{x}}_{n}(t_{n}) \\\dot{\tilde{y}}_{n}(t_{n})\end{bmatrix}= \begin{bmatrix}\tilde{x}(t) \\\tilde{y}(t) \\\dot{\tilde{x}}(t) \\\dot{\tilde{y}}(t)\end{bmatrix}$
Hence, $$\begin{align}
\lim \limits_{ n \to \infty } \begin{bmatrix}
\tilde{x}_{n}(t_{n}) \\
\tilde{y}_{n}(t_{n}) \\
\dot{\tilde{x}}_{n}(t_{n}) \\
\dot{\tilde{y}}_{n}(t_{n})
\end{bmatrix}  & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } (1-(\Delta t)i)^{n} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } (1+(\Delta t)i)^{n}\end{bmatrix}P^{-1}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ \\
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & (1-(\Delta t)i)^{k} & 0 \\ 0 & 0 & 0 & (1+(\Delta t)i)^{k}\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
0 \\
0 \\
\Delta t
\end{bmatrix} \\
 & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{n} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{n}\end{bmatrix}P^{-1}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ \\
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} & 0 \\ 0 & 0 & 0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k}\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
0 \\
0 \\
\frac{t_{n}}{n}
\end{bmatrix} \\
 & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } e^{-it_{n}} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } e^{it_{n}}\end{bmatrix}P^{-1}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+ \\
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} & 0 \\ 0 & 0 & 0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k}\end{bmatrix}P^{-1}\begin{bmatrix}
0 \\
0 \\
0 \\
\frac{t_{n}}{n}
\end{bmatrix}
\end{align}$$
We first find $P^{-1}\begin{bmatrix}0 \\0 \\0 \\\frac{t_{n}}{n}\end{bmatrix}$.
$$\begin{align}
P^{-1}\begin{bmatrix}0 \\0 \\0 \\\frac{t_{n}}{n}\end{bmatrix} & =\begin{bmatrix}1&0&0&1 \\ 0&1&1&0 \\ 0&0& \frac{i}{2} & \frac{1}{2} \\ 0& 0 & -\frac{i}{2} & \frac{1}{2}\end{bmatrix}\begin{bmatrix}0 \\0 \\0 \\\frac{t_{n}}{n}\end{bmatrix} \\
 & =\begin{bmatrix}
\frac{t_{n}}{n} \\
0 \\
\frac{t_{n}}{2n} \\
\frac{t_{n}}{2n}
\end{bmatrix}
\end{align}$$
Next, $\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} & 0 \\ 0 & 0 & 0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k}\end{bmatrix}\begin{bmatrix}\frac{t_{n}}{n} \\0 \\\frac{t_{n}}{2n} \\\frac{t_{n}}{2n}\end{bmatrix}$.
$$\begin{align}
\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} & 0 \\ 0 & 0 & 0 & \left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k}\end{bmatrix}\begin{bmatrix}\frac{t_{n}}{n} \\0 \\\frac{t_{n}}{2n} \\\frac{t_{n}}{2n}\end{bmatrix}=\begin{bmatrix}
\frac{t_{n}}{n} \\
0 \\
\left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} \frac{t_{n}}{2n} \\
\left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k} \frac{t_{n}}{2n}
\end{bmatrix}
\end{align}$$
Thus, we have
$$\begin{align}
 & \lim \limits_{ n \to \infty } \sum\limits_{k=0}^{n}P\begin{bmatrix}
\frac{t_{n}}{n} \\
0 \\
\left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{k} \frac{t_{n}}{2n} \\
\left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{k} \frac{t_{n}}{2n}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } P\begin{bmatrix}
t_{n} \\
0 \\
\frac{1-\left( 1-\left( \frac{t_{n}}{n} \right)i \right)^{n+1}}{1-\left( 1-\left( \frac{t_{n}}{n} \right)i \right) } \frac{t_{n}}{2n} \\
\frac{1-\left( 1+\left( \frac{t_{n}}{n} \right)i \right)^{n+1}}{1-\left( 1+\left( \frac{t_{n}}{n} \right)i \right) } \frac{t_{n}}{2n}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } P\begin{bmatrix}
t_{n} \\
0 \\
\frac{1-e^{-it_{n}}}{2i} \\
\frac{1-e^{it_{n}}}{-2i}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}1 & 0 & 1 & 1 \\ 0 & 1 & i & -i \\ 0 & 0 & -i & i \\ 0 & 0 & 1 & 1\end{bmatrix}\begin{bmatrix}
t_{n} \\
0 \\
\frac{1-e^{-it_{n}}}{2i} \\
\frac{1-e^{it_{n}}}{-2i}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\frac{e^{it_{n}}-e^{-it_{n}}}{2i} \\
1-\frac{e^{it_{n}}+e^{-it_{n}}}{2} \\
-1 + \frac{e^{it_{n}}+e^{-it_{n}}}{2} \\
t_{n}+\frac{e^{it_{n}}-e^{-it_{n}}}{2i}
\end{bmatrix} \\
 & =\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix}
\end{align}$$
Back to $\lim \limits_{ n \to \infty } \begin{bmatrix}\tilde{x}_{n}(t_{n}) \\\tilde{y}_{n}(t_{n}) \\\dot{\tilde{x}}_{n}(t_{n}) \\\dot{\tilde{y}}_{n}(t_{n})\end{bmatrix}$.

We have $$\begin{align}
\lim \limits_{ n \to \infty } \begin{bmatrix}
\tilde{x}_{n}(t_{n}) \\
\tilde{y}_{n}(t_{n}) \\
\dot{\tilde{x}}_{n}(t_{n}) \\
\dot{\tilde{y}}_{n}(t_{n})
\end{bmatrix} & = 
P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } e^{-it_{n}} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } e^{it_{n}}\end{bmatrix}P^{-1}\begin{bmatrix}
\tilde{x}_{0} \\
\tilde{y}_{0} \\
\dot{\tilde{x}}_{0} \\
\dot{\tilde{y}}_{0}
\end{bmatrix}+\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } e^{-it_{n}} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } e^{it_{n}}\end{bmatrix}\begin{bmatrix}1&0&0&1 \\ 0&1&1&0 \\ 0&0& \frac{i}{2} & \frac{1}{2} \\ 0& 0 & -\frac{i}{2} & \frac{1}{2}\end{bmatrix}\begin{bmatrix}
0 \\
0 \\
2 \\
0
\end{bmatrix} \\
 & +\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =P\begin{bmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & \lim \limits_{ n \to \infty } e^{-it_{n}} & 0 \\ 0 & 0 & 0 & \lim \limits_{ n \to \infty } e^{it_{n}}\end{bmatrix}\begin{bmatrix}
0 \\
2 \\
i \\
-i
\end{bmatrix}+\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =P\begin{bmatrix}
0 \\
2 \\
\lim \limits_{ n \to \infty } ie^{-it_{n}} \\
\lim \limits_{ n \to \infty } -ie^{it_{n}}
\end{bmatrix}+\lim \limits_{ n \to \infty } \begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & = \begin{bmatrix}1 & 0 & 1 & 1 \\ 0 & 1 & i & -i \\ 0 & 0 & -i & i \\ 0 & 0 & 1 & 1\end{bmatrix}\begin{bmatrix}
0 \\
2 \\
\lim \limits_{ n \to \infty } ie^{-it_{n}} \\
\lim \limits_{ n \to \infty } -ie^{it_{n}}
\end{bmatrix}+\begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =\begin{bmatrix}
i(e^{-it_{n}}-e^{it_{n}}) \\
2-(e^{-it_{n}}+e^{it_{n}}) \\
e^{-it}+e^{it} \\
i(e^{-it_{n}}-e^{it_{n}})
\end{bmatrix}+\begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =\begin{bmatrix}
2\sin t_{n} \\
2-2\cos t_{n} \\
2\cos t_{n} \\
2\sin t_{n}
\end{bmatrix}+\begin{bmatrix}
t_{n}+\sin t_{n} \\
1-\cos t_{n} \\
-1+\cos t_{n} \\
t_{n}+\sin t_{n}
\end{bmatrix} \\
 & =\begin{bmatrix}
t_{n}+3\sin t_{n} \\
3-3\cos t_{n} \\
-1 + 3\cos t_{n} \\
t_{n}+3\sin t_{n}
\end{bmatrix}
\end{align}$$
Therefore, substitute $t$, $x$ and $y$ back to $\tilde{t}$, $\tilde{x}$ and $\tilde{y}$, we have.
$$\begin{bmatrix}
x(t) \\
y(t) \\
\dot{x}(t) \\
\dot{y}(t)
\end{bmatrix}=\begin{bmatrix}
\frac{1}{8}t+\frac{3}{4}\sin \frac{t}{2} \\
\frac{3}{4}-\frac{3}{4}\cos \frac{t}{2} \\
-\frac{1}{2}+\frac{3}{2}\cos \frac{t}{2} \\
\frac{1}{4}t+\frac{3}{2}\sin \frac{t}{2}
\end{bmatrix}$$

***5.17***
**A shell is fired with a muzzle velocity $v=1000\:\text{ft s}^{-1}$ at an angle of $45\degree$ with the horizontal. Its motion is resisted by a force proportional to the cube of its velocity ($F=-kv^{3}$). The coefficient $k$ is such that the resisting force is equal to twice the weight of the shell when $v=1000\:\text{ft s}^{-1}$. find the approximate maximum height attained $h_{\text{max}}$, and the horizontal range $R$ by numerical integration, and compare these with the values expected in the absence of resistance.**

Ans:
The motion of the shell can be described in a two-dimensional space, namely, in $x$ coordinate and $y$ coordinate. Moreover, the state of the system spans a four-dimensional phase space with initial state$$\begin{align}
x_{0}  & = x(0) =0\\
v_{x, 0}  & = v_{x}(0) =500\sqrt{ 2 }\: \text{ft s}^{-1}\\
y_{0}  & = y(0) =0\\
v_{y,0}  & = v_{y}(0)=500\sqrt{ 2 }\: \text{ft s}^{-1}
\end{align}$$Modeling the motion, we derive the difference equations$$\begin{align}
x_{i+1} & =x_{i}+v_{x, i}\Delta t \\
v_{x,i+1} & =v_{x,i}- \frac{k}{m}(\sqrt{ v_{x,i}^{2}+v_{y,i}^{2} })^{3} \times \frac{v_{x,i}}{\sqrt{ v_{x,i}^{2}+v_{y,i}^{2} }}\Delta t \\
 & =v_{x,i}-\frac{k}{m}(v_{x,i}^{2}+v_{y,i}^{2})v_{x,i}\Delta t \\
y_{i+1} & =y_{i}+v_{y,i}\Delta t \\
v_{y,i+1} & =v_{x,i}- \frac{k}{m}(v_{x,i}^{2}+v_{y,i}^{2})^{\frac{3}{2}} \times \frac{v_{y,i}}{\sqrt{ v_{x,i}^{2}+v_{y,i}^{2} }}\Delta t \\
 & =v_{y,i}-\left( \frac{k}{m}(v_{x,i}^{2}+v_{y,i}^{2})v_{y,i}+g \right)\Delta t
\end{align}$$
Since $k$ is such that the resisting force is equal to twice the weight of the shell when $v=1000\:\text{ft s}^{-1}$, we can calculate that $k\times 1000^{3}=2mg\Rightarrow k=2mg\times 10^{-9}$.

We can plot the figure using some modern technology. Below are the figures
![[Air.svg#invert]]
The maximum height is attained approximately $5.0\times 10^{3}\:\text{ft}$. And $R\approx 1.6\times 10^{4}\: \text{ft}$.
![[NoAir.svg#invert]]The maximum of the height is much higher than that with air resistance, which is about $7.8\times 10^{3}\:\text{ft}$. And also is the horizontal range $R$ which is almost twice the distance of that with air resistance, namely $3.1\times 10^{4}\:\text{ft}$.
The python code for plotting the figure of motion with air resistance is preserved below.
```Python
import numpy as np
import matplotlib.pyplot as plt

# Constants
g = 32.17 # Acceleration due to gravity in ft/s^2
# Mass of the object can be canceled out by k
k = 2 * g * 1e-9 # Resistance proportional constant

# Initial conditions
v0 = 1000 # Initial velocity in ft/s
theta = 45 # Launch angle in degrees
vx0 = v0 * np.cos(np.radians(theta)) # Initial horizontal velocity
vy0 = v0 * np.sin(np.radians(theta)) # Initial vertical velocity

# Time step and duration
dt = 0.0001 # Time step in seconds
t_max = 100 # Maximum simulation time in seconds

# Lists to store position and velocity
x, y = [0], [0]
vx, vy = [vx0], [vy0]
t = [0]

# Iterative simulation using difference equations
while y[-1] >= 0: # Stop simulation when projectile hits the ground

	# Compute the speed and resistive force
	v = np.sqrt(vx[-1]**2 + vy[-1]**2)
	
	# Update positions
	x_new = x[-1] + vx[-1] * dt
	y_new = y[-1] + vy[-1] * dt

	# Update velocities
	vx_new = vx[-1] + (-k * v**2 * vx[-1]) * dt
	vy_new = vy[-1] + (-k * v**2 * vy[-1] - g) * dt

	# Append new values
	x.append(x_new)
	y.append(y_new)
	vx.append(vx_new)
	vy.append(vy_new)
	t.append(t[-1] + dt)

# Convert to numpy arrays
x, y = np.array(x), np.array(y)

# Find maximum height and horizontal range
h_max = np.max(y)
R = x[-1]

# Plot trajectory
plt.figure(figsize=(10, 6))
plt.plot(x, y, label='Projectile Motion with Air Resistance')
plt.title('Projectile Motion with Resistive Force $F = -kv^3$')
plt.xlabel('Horizontal Distance (ft)')
plt.ylabel('Vertical Distance (ft)')
plt.axhline(0, color='gray', linestyle='--', linewidth=0.8)
plt.xlim(0, 32000)
plt.ylim(0, 8000)
plt.legend()
plt.grid()
plt.savefig("Air.svg")

# Print out the result
print(h_max, R)
```