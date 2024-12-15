The exercises presented in this document are completed by CHEN, RONG-XIANG(陳融翔) from Taitung City, Taiwan.

All the figures in this document is redrawn using Mathcha or Inkscape.

***4.1***
1. **A body travels in a straight line with a constant acceleration. At $t=0$, it is located at $x=x_{0}$ and has a velocity $v_{x}=v_{x0}$. Show that its position and velocity at time $t$ are$$
   \begin{align}
x(t) & =x_{0}+v_{x 0}t+\frac{1}{2}at^{2} \text{,}\\
v_{x}(t) & =v_{x 0}+at \text{.}
\end{align}$$**
2. **Eliminate $t$ from the preceding equations, and thus show that , at any time,$$v_{x}^{2}=v_{x0}^{2}+2a(x-x_{0}) \text{.}$$**
Ans:
Assume that the constant acceleration is $a$, then
$$\begin{align}
v_{x}(t) & =v_{x0}+\int_{0}^{t}a(\xi)d\xi =v_{x 0}+at
\end{align}$$
and
$$
\begin{align}
x(t) & =x_{0}+\int_{0}^{t}v_{x}(\xi)d\xi=x_{0}+v_{x 0}t+\frac{1}{2}at^{2}
\end{align}
$$
Here, $t=\frac{v_{x}(t)-v_{x 0}}{a}$. Hence
$$
x(t)-x_{0}=\frac{v_{x}(t)v_{x 0}-v_{x 0}^{2}}{a}+\frac{v_{x}^{2}(t)-2v_{x}(t)v_{x 0}+v_{x 0}^{2}}{2a}=\frac{v_{x}^{2}(t)-v_{x 0}^{2}}{2a}
$$
That is,
$$
v_{x}^{2}=v_{x 0}^{2}+2a(x-x_{0})
$$

***4.2***
**Generalize the preceding problem to the case of three dimensional motion with constant acceleration components $a_{x}$, $a_{y}$, $a_{z}$, along the three coordinate axis. Show that**
**$$\begin{align}
x(t) & =x_{0}+v_{x 0}t+\frac{1}{2}a_{x}t^{2}\text{,} \\
y(t) & =y_{0}+v_{y 0}t+\frac{1}{2}a_{y}t^{2}\text{,} \\
z(t) & =z_{0}+v_{z 0}t+\frac{1}{2}a_{z}t^{2}\text{,} \\
v_{x}(t) & =v_{x 0}+a_{x}t\text{,} \\
v_{y}(t) & =v_{y 0}+a_{y}t\text{,} \\
v_{z}(t) & =v_{z 0}+a_{z}t\text{.}
\end{align}$$** **$$v^{2}=v_{x}^{2}+v_{y}^{2}+v_{z}^{2}=v_{0}^{2}+2[a_{x}(x-x_{0})+a_{y}(y-y_{0})+a_{z}(z-z_{0})]\text{,}$$where$$v_{0}^{2}=v_{x0}^{2}+v_{y 0}^{2}+v_{z 0}^{2}\text{.}$$**
Ans:
It is easy to see that
$$
\begin{align}
v_{x}(t) & =v_{x 0}+\int_{0}^{t}a_{x}(\xi)d\xi \\
v_{y}(t) & =v_{y 0}+\int_{0}^{t}a_{y}(\xi)d\xi\\
v_{z}(t) & =v_{z 0}+\int_{0}^{t}a_{z}(\xi)d\xi
\end{align}
$$
and also
$$
\begin{align}
x(t) & =x_{0}+\int_{0}^{t}v_{x}(\xi)d\xi=x_{0}+v_{x 0}t+\frac{1}{2}a_{x}t^{2} \\
y(t) & =y_{0}+\int_{0}^{t}v_{y}(\xi)d\xi=y_{0}+v_{y 0}t+\frac{1}{2}a_{y}t^{2} \\
z(t) & =z_{0}+\int_{0}^{t}v_{z}(\xi)d\xi=z_{0}+v_{z 0}t+\frac{1}{2}a_{z}t^{2}
\end{align}
$$
Here, $t=\frac{v_{x}(t)-v_{x 0}}{a_{x}}=\frac{v_{y}(t)-v_{y 0}}{a_{y}}=\frac{v_{z}(t)-v_{z 0}}{a_{z}}$. Hence
$$
\begin{align}
x(t)-x_{0} & =\frac{v_{x}(t)v_{x 0}-v_{x 0}^{2}}{a_{x}}+\frac{v_{x}^{2}(t)-2v_{x}(t)v_{x 0}+v_{x 0}^{2}}{2a_{x}}=\frac{v_{x}^{2}(t)-v_{x 0}^{2}}{2a_{x}} \\
y(t)-y_{0} & =\frac{v_{y}(t)v_{y 0}-v_{y 0}^{2}}{a_{y}}+\frac{v_{y}^{2}(t)-2v_{y}(t)v_{y 0}+v_{y 0}^{2}}{2a_{y}}=\frac{v_{y}^{2}(t)-v_{y 0}^{2}}{2a_{y}} \\
z(t)-z_{0} & =\frac{v_{z}(t)v_{z 0}-v_{z 0}^{2}}{a_{z}}+\frac{v_{z}^{2}(t)-2v_{z}(t)v_{z 0}+v_{z 0}^{2}}{2a_{z}}=\frac{v_{z}^{2}(t)-v_{z 0}^{2}}{2a_{z}}
\end{align}
$$
That is,
$$
\begin{align}
v_{x}^{2} & =v_{x 0}^{2}+2a_{x}(x-x_{0}) \\
v_{y}^{2} & =v_{y 0}^{2}+2a_{y}(y-y_{0}) \\
v_{z}^{2} & =v_{z 0}^{2}+2a_{z}(z-z_{0}) \\
\hline
v^{2}&=v_{x}^{2}+v_{y}^{2}+v_{z}^{2}  \\
& =v_{x 0}^{2}+v_{y 0}^{2}+v_{z 0}^{2}+2[a_{x}(x-x_{0})+a_{y}(y-y_{0})+a_{z}(z-z_{0})] \\
 & =v_{0}^{2}+2[a_{x}(x-x_{0})+a_{y}(y-y_{0})+a_{z}(z-z_{0})]
\end{align}
$$

***4.3***
**An angle may be measured by the length of arc of a circle that the angle subtends, with the vertex of the angle at the center of the circle. If $s$ is the arc length and $R$ is the radius of the circle, as shown in Fig. 4-1, then the subtended angle $\theta$, in radians, is$$\theta=s/R\text{.}$$**![[Fig.4-1.svg#invert]]
1. **Show that, if $\theta \ll 1$ radian, $\sin \theta \approx \theta$, and $\cos \theta \approx 1$.
2. **With the above result, and the formulas for the sine and cosine of the sum of two angles, find the derivatives of $\sin x$ and $\cos x$, using the fundamental formula$$\frac{dy}{dx}=\lim_{ \Delta x \to 0 } \frac{y(x+\Delta x)-y(x)}{\Delta x}\text{.}$$**

Ans:
1. If we already know some calculus, when $\theta$ is near to $0$, using the first order linear approximation: $\sin \theta \approx \sin 0+\left.\frac{d\sin \theta}{d\theta}\theta \right|_{0}=\theta$. 
   
   For more general case, we use the Taylor's series of sine, which is$$
   \sin \theta=\frac{\theta}{1!}-\frac{\theta^{3}}{3!}+\frac{\theta^{5}}{5!}-\frac{\theta^{7}}{7!}+\dots \text{.}
   $$When $\theta$ is small, the higer exponential terms could be neglected. Therefore, $\sin \theta \approx \theta$.
   
   We can get the same results by geometry,![[sine.svg#invert]] From the figure above, $\sin \theta<\theta<\tan \theta$. Divide them by $\sin \theta$, we have $1< \frac{\theta}{\sin \theta}< \frac{1}{\cos \theta}\Rightarrow \cos \theta< \frac{\sin \theta}{\theta}<1\Rightarrow \lim \limits_{ \theta \to 0 }\cos \theta <\lim \limits_{ \theta \to 0 } \frac{\sin \theta}{\theta}<\lim \limits_{ \theta \to 0 }1$. That is $$1<\lim \limits_{ \theta \to 0 }\frac{\sin \theta}{\theta}<1$$By the squeeze theorem, $\lim \limits_{ \theta \to 0 }\frac{\sin \theta}{\theta}=1$, which implies that $\lim \limits_{ \theta \to 0 }\sin \theta=\lim \limits_{ \theta \to 0 }\theta$. Hence for small angle $\theta$, $\sin \theta \approx \theta$.


2. By the definition of derivative, $$\begin{align}
\frac{d}{dx}\sin x & =\lim \limits_{ \Delta x \to 0 } \frac{\sin(x+\Delta x)-\sin x}{\Delta x} \\
&=\lim \limits_{ \Delta x \to 0 } \frac{\sin x\cos \Delta x+\cos x\sin \Delta x-\sin x}{\Delta x} \\
 & =\lim \limits_{ \Delta x \to 0 } \frac{\sin x\times 1+\cos x\times \Delta x-\sin x}{\Delta x} \\
 & =\cos x
\end{align}$$Similarly, $$\begin{align}
\frac{d}{dx}\cos x & =\lim \limits_{ \Delta x \to 0 } \frac{\cos(x+\Delta x)-\cos x}{\Delta x} \\
 & =\lim \limits_{ \Delta x \to 0 } \frac{\cos x\cos \Delta x-\sin x\sin \Delta x-\cos x}{\Delta x} \\
 & =\lim \limits_{ \Delta x \to 0 } \frac{\cos x\times 1-\sin x\Delta x-\cos x}{\Delta x} \\
 & =-\sin x
\end{align}$$
***4.4***
**An object is moving counterclockwise in a circle of radius $R$ at constant speed $V$, as shown in Fig. 4-2. The center of the circle is at the origin of rectangular coordinates $(x,y)$, and at time $t=0$ the particle is at $(R,0)$. 
![[Fig.4-2 1.svg#invert]]Show that$$\begin{align}
x & =R\cos \omega t\text{,} \\y & =R\sin \omega t\text{,} \\v_{x} & =-V\sin \omega t\text{,} \\v_{y} & =V\cos \omega t\text{,} \\a_{x} & =-\frac{V^{2}}{R}\cos \omega t\text{,} \\a_{y} & =-\frac{V^{2}}{R}\sin \omega t\text{,} \\a & =\frac{V^{2}}{R}\text{,} \\ \\\ddot{x} & +\omega^{2}x=0 \\\ddot{y} & +\omega^{2}y=0\end{align}$$where $\omega=V/R=\text{angular frequency}$.**

Ans:
It is easy to see that
$$
\begin{align}
x & =R\cos \theta=R\cos \omega t \\
y & =R\sin \theta=R\sin \omega t
\end{align}
$$
Differentiate $x$ and $y$, we have
$$
\begin{align}
v_{x} & =-R\omega \sin \omega t=-V\sin \omega t \\
v_{y} & =R\omega \cos \omega t=V\cos \omega t
\end{align}
$$
Differentiate again gives
$$
\begin{align}
a_{x} & =-R\omega^{2}\cos \omega t =-\frac{V^{2}}{R}\cos \omega t\\
a_{y} & =-R\omega^{2}\sin \omega t=-\frac{V^{2}}{R}\sin \omega t
\end{align}
$$
The magnitude of the acceleration is $\sqrt{ a_{x}^{2}+a_{y}^{2} }$, which is 
$$
a=\frac{V^{2}}{R}(\sqrt{ \cos^{2}\omega t+\sin^{2}\omega t })=\frac{V^{2}}{R}
$$
Notice that
$$
\begin{align}
a_{x} & =-\frac{V^{2}}{R}\cos \omega t=-\omega^{2}x \\
a_{y} & =-\frac{V^{2}}{R}\sin \omega t=-\omega^{2}y
\end{align}
$$
Therefore,
$$
\begin{align}
\ddot{x}+\omega^{2}x & =0 \\

\ddot{y}+\omega^{2}y & =0
\end{align}
$$

***4.5***
**A Skyhook balloon with a scientific payload rises at a rate of $1000\: \text{feet}$ per minute. At an altitude of $30,000\: \text{feet}$ the balloon bursts and the payload free-falls. (Such disasters *do* occur!)**
1. **For what length of time $t$ was the payload off the ground?**
2. **What was the payload's speed $v$ at impact?**
**Neglect air-drag.**

Ans:
At the time the payload touches the ground the displacement of it is $-30,000\: \text{feet}$. Hence
$$
\begin{align}
-30,000=1000 / 60\:(\text{per second}) \Delta t-\frac{1}{2}\times 32\:(\text{acceleration})\times \Delta t^{2}
\end{align}
$$
That is,
$$
\begin{align}
16\Delta t^{2}-\frac{50}{3}\Delta t-30,000 & =0 \\
\Delta t^{2}-\frac{25}{24}\Delta t-1875 & =0
\end{align}
$$

Solve this quadratic equation, we have
$$
\begin{align}
\Delta t & =\frac{\frac{25}{24}\pm \sqrt{ \left( \frac{25}{24} \right)^{2}+4 \times \frac{25}{24}\times1875 }}{2} \\
 & =\frac{25}{48}\pm \frac{25}{48}\sqrt{ 6913 } \\
 & =\frac{25}{48}(1+\sqrt{ 6913 }) \\
&\approx 43.8
\end{align}
$$
It take $\frac{30,000}{1000}\times 60=1800$ seconds for the payload to reach altitude of $30,000\:\text{feet}$. Therefore, the total time the payload is off the ground is
$43.8+1800\approx1,843.8\: \text{second}$.

***4.6***
**Consider a train that can accelerate with an acceleration of $20\: \text{cm s}^{-2}$ and slow down with a deceleration of $100\: \text{cm s}^{-2}$. Find the minimum time $t$ for the train to travel between two stations $2\: \text{km}$ apart.**

Ans:
The distance the train travels is the area under the graph of velocity versus time. We want the time to be minimum. This appears when the train accelerates until some time $t_{m}$, then decelerates such that it would stop at the second station. Hence,
$$
\begin{align}
&&&\begin{cases}
20t_{m}-100(t-t_{m})=0 \\
\frac{1}{2}20t_{m}^{2}+20t_{m}\times (t-t_{m})-\frac{1}{2}100(t-t_{m})^{2}=2\times 1000\times 100 \\
t_{m}^{2}+2t_{m}t-2t_{m}^{2}-5t^{2}+10tt_{m}-5t_{m}^{2}=20000
\end{cases}
 \\ \\

&\Rightarrow&
&\begin{cases}
6t_{m}=5t \\
6t_{m}^{2}-12t_{m}t+5t^{2}+20000=0
\end{cases}
\end{align}
$$
That is,
$$
\begin{align}
 &  & 6\left( \frac{5}{6}t \right)^{2}-12t\left( \frac{5}{6}t \right)+5t^{2}+20000 & =0 \\
 & \Rightarrow & 25t^{2}-60t^{2}+30t^{2}+120000 & =0 \\ \\
 & \Rightarrow & t^{2} & =24000
\end{align}
$$
which implies that $t=\sqrt{ 24000 }\approx 154.9\approx 155\:\text{s}$.

***4.7***
**If you throw a small ball vertically upward in real air with drag, does it take longer to go up or come down?**

Ans:
It takes longer to fall down since if there are air drag, the speed of the ball when it falls down will be less than the speed it was throw up. And thus, it takes longer to fall down the same amount of distance it was thrown up.

***4.8***
**Consider a point on the surface of the earth at the equator:**
1. **What is its speed $v$ relative to the center of the earth?**
2. **What is its angular frequency $\omega$?**
3. **What is the ratio of its radial acceleration $a$ due to angular motion and its gravitational acceleration $g$?**

Ans:
The radius of the earth is $R=6,371\: \text{km}$.
1. The speed $v=\frac{2\pi R}{T}=\frac{2\pi \times 6,371\times 10^{3}}{1\times 24\times 60\times 60}\approx 463.3\: \text{m/s}$.
2. The angular frequency $\omega=\frac{2\pi}{1\times 24\times 60 \times 60}\approx 7.272\times 10^{-5} \: \text{Rad/s}$.
3. We can compute the small change in distance it falls down.![[moon_falling.svg#invert]]That is,$$\begin{align}
 &  & \frac{1}{2}a(\Delta t)^{2} & =v\Delta t\times \frac{\omega \Delta t}{2} \\
 & \Rightarrow & a & =463.3\times 7.272\times 10^{-5} \\
 &  &  & \approx 3.369\times 10^{-2} \: \text{m/s}^{2}
\end{align}$$Hence, $a / g=\frac{3.369\times 10^{-2}}{9.81}\approx 3.434\times 10^{-3}$.

***4.9***
**A Corporal rocket fired vertically was observed to have a constant upward acceleration of $2g$ during the burning of the rocket motor, which lasted for $50$ seconds. Neglecting air resistance and variation of $g$ with altitude,**
1. **Draw a $v$-$t$ diagram for the entire flight of rocket.**
2. **Calculate the maximum height attained $H_{max}$.**
3. **Calculate the total elapsed time $T$ from the firing of the rocket to its return to Earth.**

Ans:
1. The $v$-$t$ diagram looks like ![[Fig.4-9vt.svg#invert]]
2. The maximum height is the area below the graph of the $v$-$t$ diagram above before the velocity get back to zero, which is $$H_{max}=\frac{1}{2}\times 150\times 100g=7500\times \frac{9.81}{1609.34}\approx 45.7\approx 46\: \text{mi}$$
3. The distance the rocket rises equals the distance it falls. And the slope of the velocity is equal to the acceleration. In this case, the slope is $g$ when it free-falls. Hence$$\begin{align}
 &  & \frac{1}{2}(T-150)((T-150)g)&=46 \\
 & \Rightarrow & T=\sqrt{ \frac{92}{g} }+150&\approx 272.8\: \text{s} \\
 &  &  & \approx 2.7\times 10^{2}\: \text{s}
\end{align}$$

***4.10***
**In a lecture demonstration a small steel ball bounces on a steel plate. On each bounce the downward speed of the ball arriving at the plate is reduced by a factor e in the rebound, i.e., $v_{\text{upward}}=ev_{\text{downward}}$.**
**If the ball was initially dropped from a height of $50\: \text{cm}$ above the plate at time $t=0$, and if $30$ seconds later the silencing of a microphone sound indicated all bouncing had ceased, what was the value of e?**

Ans:
At the moment the ball is going to bounces the first time, it already takes $\sqrt{ \frac{2H}{g} }$ seconds to hit the ground and it has the velocity $v_{0}= g\sqrt{ \frac{2H}{g} }=\sqrt{ 2Hg }$. Let $v_{i}$ denote the velocity after the $i$th bounce. After the $i$th bounce, it would took $\frac{2v_{i}}{g}$ seconds to bounce again. The total time it takes after $n$ bounces is $T=\sqrt{ \frac{2H}{g} }+\sum\limits_{i=1}^{n} \frac{2v_{i}}{g}$. We also know that $v_{i}=ev_{i-1}\: \forall i>0 \in \mathbb{N}$. Hence, $T=\sqrt{ \frac{2H}{g} }+\sum\limits_{i=1}^{n}\frac{2v_{0}e^{i}}{g}$. When all bouncing is ceased, that mean $n\to \infty$. So $$\begin{align}
T_{cease} & =\sqrt{ \frac{2H}{g} }+\lim \limits_{ n \to \infty }\sum\limits_{i=1}^{n} \frac{2v_{0}e^{i}}{g} \\
 & =\sqrt{ \frac{2H}{g} }+\frac{2\sqrt{ 2Hg }}{g}\times \frac{1}{1-e} \\
 & =\left( 1+\frac{2}{1-e} \right)\sqrt{ \frac{2H}{g} } \\
\end{align}$$Therefore, $30=\left( 1+\frac{2}{1-e} \right)\sqrt{ \frac{2\times 0.5}{9.81} }$, which is $e\approx 0.98$.

***4.11***
**A projectile is fired over level terrain at an initial speed $v_{0}$, at an angle $\theta$ with the horizontal. (Neglect air resistance.)**
1. **Find the maximum height attained $H_{\text{max}}$ and the range $R$.**
2. **At what angle should the above projectile be fired in order to attain the maximum range?**

Ans:
1. The horizontal and vertical components of projectile's velocity initially are $v_{0}\cos \theta$ and $v_{0}\sin \theta$. When it is at the maximum height, the vertical velocity is equal to zero. Hence, by formula from problem [[4.1]],$$0^{2}=(v_{0}\sin \theta)^{2}-2gH_{\text{max}}$$Thus, $H_{max}=\frac{v_{0}^{2}\sin^{2}\theta}{2g}$. The time it took for the projectile to move from the ground to the maximum height is $\frac{v_{0}\sin \theta}{g}$. And the total time it travels is $2 \frac{v_{0}\sin \theta}{g}$. Therefore, the range is, $$\begin{align}
R & =v_{0}\cos \theta \times2\frac{v_{0}\sin \theta}{g} \\
 & =\frac{v_{0}^{2}\sin 2\theta}{g}
\end{align}$$
2. Since $R=\frac{v_{0}^{2}\sin 2\theta}{g}$, the range has its maximum when $\theta=\frac{\pi}{4}$.

***4.12***
**A champion archer hits a bullseye in a target mounted on a wall a distance $L$ away and situated at a height $h$ above his bow. Deduce the relation between the speed $V$ at which the arrow left his bow, the arrow's initiated angle $\theta$ with the horizontal, the height, and the distance to the target, whose solution the archer evidently knew.**

***Note:* The archer did not neglect air resistance, but you may have to.**

Ans:![[Fig.4-12archer.svg#invert]]As the figure shows, The total time the arrow flies is $t=L / V\cos \theta$. And by the formula from problem [[4.1]],$$\begin{align}
 &  & V\sin \theta \times t-\frac{1}{2}gt^{2} & =h \\
 & \Rightarrow & V\sin \theta \times \frac{L}{V\cos \theta} -\frac{1}{2}g\left( \frac{L}{V\cos \theta} \right)^{2} & =h \\
 & \Rightarrow & L\tan \theta-\frac{1}{2}g \frac{L^{2}}{V^{2}\cos^{2}\theta} & =h
\end{align}$$That is,$$V=\frac{L}{\cos \theta}\sqrt{ \frac{g}{2(L\tan \theta-h)} }$$

**A boy throws a ball upward at an angle of $70^{\circ}$ with the horizontal, and it passes neatly through an open window, $32$ feet above his shoulder, moving horizontally.**
1. **What speed $v$ did the ball have as it left his hand?**
2. **What was the radius of curvature of its path, $R$, as it passed over the windowsill?**

Ans:
![[ball_throw.svg#invert]]
1. Since the ball is moving horizontally when it passes the window, the vertical component of velocity is equal zero. Thus, the time it passes the window is $\frac{v\sin \theta}{g}$. By the formula from problem [[4.1]],$$\begin{align}
v\sin \theta \times t-\frac{1}{2}gt^{2} & =H \\
\frac{v^{2}\sin ^{2}\theta}{g}-\frac{1}{2}\frac{v^{2}\sin^{2}\theta}{g} & =H \\
\frac{1}{2}\frac{v^{2}\sin^{2}\theta }{g} & =H
\end{align}$$Thus, $v=\sqrt{ 2gH }\csc \theta=\sqrt{ 2\times 32.174\times 32.174 }\times \csc 70^{\circ}\approx 48\: \text{ft}$.
2. Let the hand of the boy's hand be the origin, $r(t)$ be the position vector of the ball. Then$$\begin{align}
r(t) & =\left[ v\cos \theta t,v\sin \theta t-\frac{1}{2}gt^{2} \right] \\
r'(t) & =[v\cos \theta,v\sin \theta-gt] \\
T(t) & =\frac{r'(t)}{|r'(t)|}=\frac{[v\cos \theta,v\sin \theta-gt]}{\sqrt{ v^{2}\cos^{2}\theta+v^{2}\sin^{2} \theta -2vgt\sin \theta+g^{2}t^{2}}} \\
 & =\frac{[v\cos \theta,v\sin \theta-gt]}{\sqrt{ v^{2}-2vgt\sin \theta+g^{2}t^{2} }} \\
T'(t) & =\frac{[0,-g]}{\sqrt{ v^{2}-2vgt\sin \theta+g^{2}t^{2} }}-[v\cos \theta,v\sin \theta-gt]\times \frac{-2vg\sin \theta+2g^{2}t}{2(v^{2}-2vgt\sin \theta+g^{2}t^{2})^{3/2}}
\end{align}$$At the window, $t=\frac{v\sin \theta}{g}$. Hence$$\begin{align}
T'\left( \frac{v\sin \theta}{g} \right) & =\frac{[0,-g]}{\sqrt{ v^{2}-2v^{2}\sin^{2}\theta+v^{2}\sin^{2}\theta }} \\
 & =\frac{[0,-g]}{v\cos \theta} \\
r'\left( \frac{v\sin \theta}{g} \right) & =[v\cos \theta,0]
\end{align}$$And the curvature is$$\begin{align}
\kappa & =\frac{\left|T'\left( \frac{v\sin \theta}{g} \right)\right|}{\left|r'\left( \frac{v\sin \theta}{g} \right)\right|} \\
 & =\frac{g / v\cos \theta}{v\cos \theta} \\
 &=\frac{g}{v^{2}\cos^{2}\theta}
\end{align}$$Therefore, $$\begin{align}
R & =\frac{1}{\kappa}=\frac{v^{2}\cos^{2} \theta}{g} \\
   & = \frac{2gH \csc^{2} \theta \cos^{2}\theta}{g}\\
& =2H\cot^{2}\theta \\
 & =2\times 32\times \cot^{2}70^{\circ} \\
 & \approx 8.5\: \text{ft}
\end{align}$$
***4.14***
**A small pebble is lodged in the tread of a tire of radius $R$. If this tire is rolling at speed $V$ without slipping on a horizontal road, and the pebble touches the road at time $t=0$, where coordinates $x$ (horizontal) and $y$ (vertical) are zero, find equations for the x and y components of**
1. **the position of the pebble,**
2. **its velocity $v$,**
3. **and its acceleration,**

**as functions of time.**

Ans:
![[cycloid.svg#invert]]
1. Let angular frequency of the ball be $\omega=\frac{V}{R}$. The position function of the pebble$$\begin{align}
[x,y] & =\left[ Vt-R\sin \left( \frac{V}{R}t \right),R-R\cos \left( \frac{V}{R}t \right)\right] \\
 & =\left[ Vt-R\sin\left( \frac{V}{R}t \right),R\left( 1-\cos\left( \frac{V}{R}t \right) \right) \right]
\end{align}$$
2. The velocity function is $$\begin{align}
\left[ \frac{dx}{dt}, \frac{dy}{dt} \right] & =\left[ V- \\
V\cos\left( \frac{V}{R}t \right),V\sin\left( \frac{V}{R}t \right) \right] \\
 & =\left[ V\left(1-\cos\left( \frac{V}{R}t \right)\right),V\sin\left( \frac{V}{R}t \right) \right]
\end{align}$$
3. The acceleration function is$$\begin{align}
\left[ \frac{d^{2}x}{d^{t^{2}}},\frac{d^{2}y}{dt^{2}} \right]=\left[ \frac{V^{2}}{R}\sin\left( \frac{V}{R}t \right), \frac{V^{2}}{R}\cos\left( \frac{V}{R}t \right) \right]
\end{align}$$

***4.15***
**The driver of a car is following a truck when he suddenly notices that a stone is caught between two of the rear tires of the truck. Being a safe driver (and a physicist too), he immediately increases his distance to the truck to $22.5$ meters, so as not to be hit by the stone in case it comes loose. At what speed $v$ was the truck traveling? (Assume the stone does not bounce after hitting the ground.)**

Ans:
After the stone fell, it would have the same velocity $v$ as the speed of the car. From the driver's perspective, it looked like the stone was projected. Assume that the stone was released at an angle $\theta$ with horizontal at the level of the road, then the time it falls is $\frac{2v\sin \theta}{g}$. And the range of the projection is $v\cos \theta \times \frac{2v\sin \theta}{g}=\frac{v\sin 2\theta}{g}$. For the sake of safety, the driver must have consider the worst case where the range was maximum, i.e., $\theta=\frac{\pi}{4}$. Therefore, $22.5\: m=\frac{v^{2}\sin \frac{\pi}{2}}{g}\Rightarrow v^{2}=22.5g\approx 14.8\:\text{m s}^{-1}$.


***4.16***
**A circus performer was devising a new act. He wanted to combine the Human Cannon Ball with a trapeze stunt. He had a cannon out of which he came with a muzzle velocity $V$. He wanted to get high enough so that he could grab the trapeze ($r=2\: \text{m}$) and then continue on up to the platform located at $h=20\: m$ above the floor, as shown in Fig. 4-3. (The trapeze should not go slack, i.e., his vertical velocity must be zero at both $r$ and $h$).**
![[Fig.4-3.svg#invert]]
1. **At what angle $\theta$ must the cannon be set?**
2. **How far down the tent from the platform, $x$, should he put the cannon?**
3. **What value of $V$ must he choose?**


Ans:
1. When the performer grabs the trapeze, he has velocity $V\cos \theta$ horizontal. By the conservation of energy, $$\frac{1}{2}m(V\cos \theta)^{2}=mgr\dots(1)$$Plus, $$0^{2}=(V\sin \theta)^{2}-2g(h-r)\dots(2)$$By$(1)(2)$, $$\begin{align}
 &  & \frac{(V\sin \theta)^{2}}{(V\cos \theta)^{2}} & =\frac{2g(h-r)}{2gr} \\
 & \Rightarrow & \tan \theta & =\sqrt{ \frac{h-r}{r} } \\
 &  &  & =\sqrt{ \frac{20-2}{2} }=3
\end{align}$$which implies that $\theta =\tan^{-1}3$.
2. The time it take for the performer to fly from the cannon to the trapeze is $\frac{V\sin \theta}{g}$. From $(1)$, $V^{2}=2gr\sec^{2}\theta$ Thus $$\begin{align}
x & =V\cos \theta \times \frac{V\sin \theta}{g}+r \\
 & =\frac{2gr\sec^{2}\theta \cos \theta \sin \theta}{g}+r \\
 & =r(2\tan \theta+1) \\
 & =2\times(2\times 3+1) \\
 & =14\: \text{m}
\end{align}$$
3. From 2., $V^{2} \frac{\cos \theta \sin \theta}{g}+r =x$. So $$\begin{align}
 V & =\sqrt{ (x-r)\frac{g}{\cos \theta \sin \theta} } \\
  & =\sqrt{ (14-2)\times \frac{9.81}{ \frac{1}{\sqrt{ 10 }}\times \frac{3}{\sqrt{ 10 }}} } \\
 & \approx 19.8\: \text{m/s}
\end{align}$$

***4.17***
**A mortar emplacement is set $27,000\: \text{ft}$ horizontally from the edge of a cliff that drops $350\: \text{ft}$ down from the level of the mortar, as shown in Fig. 4-4. It is desired to shell objects concealed on the ground behind the cliff. What is the smallest horizontal distance $d$ from the cliff face that shells can reach if fired at a muzzle speed of $1000\: \text{ft s}^{-1}$?**![[Fig.4-4.svg#invert]]
Ans:
The smallest distance appeared if the shell just pass through the edge of the cliff. Let the initial speed of the shell be $V$ angled $\theta$ with horizontal. Then $t'=\frac{27,000}{V\cos \theta}$ and $2V\sin \theta=gt'$, which implies that, $\sin 2\theta=\frac{27,000g}{V^{2}}=\frac{27,000\times g}{1000^{2}}=0.864$. $\theta \approx 30^{\circ}$ or $\theta \approx 60^{\circ}$. $d$ will be shorter if $\theta=60^{\circ}$. Hence, before the shell hits the ground after passing the edge, $V\sin \theta \times t+\frac{1}{2}gt^{2}=350 \Rightarrow 16t^{2}+500\sqrt{ 3 }t-350=0$. $t=\frac{-250\sqrt{ 3 }+\sqrt{ (250\sqrt{ 3 })^{2}+4\times 8\times 175 }}{2\times 8}\approx 0.4\: \text{s}$. Therefore, $$\begin{align}
d & =V\cos \theta \times t \\
 & =1000\times \frac{1}{2}\times 0.4 \\
 & \approx 200 \: \text{ft}
\end{align}$$
***4.18***
**A Caltech freshman, inexperienced with suburban traffic officers, has just received a ticket for speeding. Thereafter, when he comes upon one of the "Speedometer Test" sections on a level stretch of highway, he decides to check his speedometer reading. As he passes the ''$0$'' start of the marked section, he presses on his accelerator and for the entire period of the test he holds his car at constant acceleration. He notices that he passes the $0.10$ mile post $16\:\text{s}$ after**
**starting the test, and $8.0\:\text{s}$ later he passes the $0.20$ mile post.**
1. **What speed $v$ should his speedometer have read at the $0.20$ mile post?**
2. **What was his acceleration $a$?**

Ans:
The $x$-$t$ diagram of the car is ![[Fig.4-18car.svg#invert]]`Solution I`
We know that the car passes through point $(0,0)$, $(16,0.1)$ and $(24,0.1)$. We can use the Lagrange Interpolation Formula to find the Equation of $x$ versus $t$. The Lagrange polynomials associated with $0$, $16$ and $24$ are$$\begin{align}
f_{0} & =\frac{(t-16)(t-24)}{(0-16)(0-24)}=\frac{1}{384}(t-16)(t-24) \\
f_{1} & =\frac{(t-0)(t-24)}{(16-0)(16-24)}= -\frac{1}{128}t(t-24) \\
f_{2} & =\frac{(t-0)(t-16)}{(24-0)(24-16)}=\frac{1}{192}t(t-16)
\end{align}$$Therefore,$$\begin{align}
x(t) & =0\times \frac{1}{384}(t-16)(t-24)+0.1\times \left( -\frac{1}{128}t(t-24) \right)+0.2\times \frac{1}{192}t(t-16) \\
 & = -\frac{0.3}{384}t(t-24)+\frac{0.4}{384}t(t-16) \\
 & = \frac{1}{384}t(0.1t+0.8) \\
 & =\frac{t^{2}}{3840}+\frac{t}{480}
\end{align}$$
1. $v(t)=\frac{dx(t)}{dt}=\frac{t}{1920}+\frac{1}{480}$. At $t=24$, the car is at the $0.20$ mile post and $v(24)=\frac{24}{1920}+\frac{1}{480}\:\text{mi/s}=\left( \frac{24}{1920}+\frac{1}{480} \right)\times 60 \times 60=52.5\:\text{mi/h}$.
2. $a(t)=\frac{dv(t)}{dt}=\frac{1}{1920}\:\text{mi/s}^{2}= \frac{1}{1920}\times 5280=2.75\:\text{ft/s}^{2}$.

***4.19***
**On the long horizontal test track at Edwards AFB, both rocket and jet motors can be tested. On a certain day, a rocket motor, started from rest, accelerated constantly until its fuel was exhausted, after which it ran at constant speed. It was observed that this exhaustion of the rocket fuel took place as the rocket passed the midpoint of the measured test distance. Then a jet motor was started from rest down the track, with a constant acceleration for the entire distance. It was observed that both rocket and jet motors covered the test distance in exactly the same time. What was the ratio of the acceleration $a_{J}$ of the jet motor to that of the rocket motor, $a_{R}$?**

Ans:
The $v$-$t$ diagram looks like the following.
![[Fig.4-19RJ.svg#invert]]
The slope of the lines is the acceleration. The area under the line is the distance the traveled. Since the acceleration of the jet motor one stopped when at the midpoint of the distance, $\frac{1}{2}t_{m}\times a_{J}t_{m}=a_{J}t_{m}\times(t_{\text{end}}-t_{m})\Rightarrow t_{m}=\frac{2}{3}t_{\text{end}}$. In addition, $$\frac{1}{2}t_{\text{end}}\times a_{R}t_{\text{end}}=\frac{((t_{\text{end}}-t_{m})+t_{\text{end}})a_{R}t_{end}}{2}=2\times \frac{t_{\text{end}}}{3}\times a_{J} \frac{2}{3}t_{\text{end}}$$That is, $$\frac{a_{J}}{a_{R}}=\frac{9}{8}$$