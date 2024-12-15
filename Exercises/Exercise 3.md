The exercises presented in this document are completed by CHEN, RONG-XIANG(陳融翔) from Taitung City, Taiwan.

All the figures in this document is redrawn using Mathcha or Inkscape.

***3.1***
**Some properties of the ellipse. The size and shape of an ellipse are determined by specifying the values of any two of the following quantities (as shown in Fig. 3-1):**
![[Fig.3-1.svg#invert]]
- **$a$: the semi-major axis**
- **$b$: the semi-minor axis**
- **$c$: the distance from the center to one focus**
- **$e$: the eccentricity**
- **$r_{p}$ the perihelion (or perigee) distance (the closest distance from the focus to the ellipse)**
- **$r_{a}$ the aphelion (or apogee) distance (the farthest distance from a focus to the ellipse)**
**The relationships of these various quantities are$$
\begin{align}a^{2}&=b^{2}+c^{2}, \\
e&=c / a \quad \text{(definition of }e\text{ )}, \\
r_{p}&=a-c=a(1-e), \\
r_{a}&=a+c=a(1+e).
\end{align}$$Show that the area of an ellipse is given by $A=\pi ab$.**

Ans:
The definition of an ellipse:
`The sum of a distance from any point on the curve to the foci is a constant.`
Let's say the focus is $(-c,0)$ and $(c,0)$, $2a$ is the sum of the distance. By the definition of ellipses, if $(x,y)$ is an arbitrary point on the ellipse, 
$$
\begin{align}
\sqrt{ (x-(-c))^{2}+(y-0)^{2} }+\sqrt{ (x-c)^{2}+(y-0)^{2} }&=2a \\
\sqrt{ (x+c)^{2}+y^{2} }+\sqrt{ (x-c)^{2}+y^{2} }&=2a  \\

\left(\sqrt{ (x+c)^{2}+y^{2} }+\sqrt{ (x-c)^{2}+y^{2} }\right)^{2}&=4a^{2} \\

 ((x+c)^{2}+y^{2})+((x-c)^{2}+y^{2})+2\sqrt{ ((x+c)^{2}+y^{2})((x-c)^{2}+y^{2}) }&=4a^{2}
\end{align}
$$
Expanding all squares, we have
$$
\begin{align}
x^{2}+2xc+y^{2}+x^{2}-2xc+c^{2}+y^{2}-4a^{2}&=-2\sqrt{ (x^{2}+y^{2}+c^{2}-2xc)(x^{2}+y^{2}+c^{2}+2xc) } \\

2x^{2}+2y^{2}+2c^{2}-4a^{2}&=-2\sqrt{ (x^{2}+y^{2}+c^{2})^{2}-(2xc)^{2} } \\

x^{2}+y^{2}+c^{2}-2a^{2}&=-\sqrt{ (x^{2}+y^{2}+c^{2})^{2}-(2xc)^{2} } \\

\cancel{(x^{2}+y^{2}+c^{2})^{2}}-2(x^{2}+y^{2}+c^{2})(2a^{2})+4a^{4}&=\cancel{(x^{2}+y^{2}+c^{2})^{2}}-(2xc)^{2} \\

-a^{2}(x^{2}+y^{2}+c^{2})+a^{4}&=-x^{2}c^{2}
\end{align}
$$
From the properties of the ellipse, $a^{2}=b^{2}+c^{2}$.
$$
\begin{align}
a^{2}(x^{2}+y^{2}+a^{2}-b^{2})-a^{4}&=x^{2}(a^{2}-b^{2}) \\

a^{2}x^{2}+a^{2}y^{2}+a^{2}(a^{2}-b^{2})-a^{4}-x^{2}(a^{2}-b^{2})&=0 \\

a^{2}(x^{2}-a^{2})-(x^{2}-a^{2})(a^{2}-b^{2})+ay^{2}&=0 \\

b^{2}(x^{2}-a^{2})+ay^{2}&=0 \\

b^{2}x^{2}+a^{2}y^{2}&=a^{2}b^{2} \\

\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}&=1
\end{align}
$$
Therefore, the equation for ellipse is $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$.
This function could also be written as
$$
y(x)=\begin{cases}
b\sqrt{ 1-\frac{x^{2}}{a^{2}} } \\
-b\sqrt{ 1-\frac{x^{2}}{a^{2}} }
\end{cases}
$$
Which is symmetric about the $x$-axis. So the area is
$$
A=2\int _{-a}^{a}b\sqrt{ 1-\frac{x^{2}}{a^{2}} } \mathrm{d}x
$$
We use trigonometric substitution. Let $x=a\sin \theta$, $\mathrm{d}x=a\cos \theta \mathrm{d}\theta$.
$$
\begin{align}
A&=2\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}ab\sqrt{ 1-\sin ^{2}\theta }\cos \theta \mathrm{d}\theta \\
 
&=2ab\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\cos^{2}\theta \mathrm{d}\theta \\

&=2ab\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}} \frac{1+\cos 2\theta}{2}\mathrm{d}\theta \\

&=2ab\left[ \frac{1}{2}\theta+\frac{1}{4}\sin 2\theta \right]_{-\frac{\pi}{2}}^{\frac{\pi}{2}} \\

&=ab\pi
\end{align}
$$
Hence, the area is $ab\pi$.

***3.2***
**The distance of the moon from the center of the earth varies from $363,300\: \text{km}$ at perigee to $405,500\: \text{km}$ at apogee, and its period is $27.322$ days. A certain artificial earth satellite is orbiting so that its perigee height from the surface of the Earth is $225\: \text{km}$, and its apogee height is $710\: \text{km}$. The mean diameter of the Earth is $12,756\: km$. What is the sidereal period $T$ of this satellite?**

Ans:
By the Kepler's third law, $T \propto a^{3/2}$. In addition, the semi-major axis is equal to the average value of the perigee and apogee, which is $a=\frac{r_{p}+r_{a}}{2}$. Hence
$$
\begin{align}
\frac{T}{27.322}&=\left( \frac{\frac{1}{2}\left( \frac{12,756}{2}+225+\frac{127,56}{2}+710 \right)}{\frac{1}{2}(363,300+405,500)} \right)^{3/2} \\
T&=27.322\left( \frac{\frac{1}{2}\left( \frac{12,756}{2}+225+\frac{127,56}{2}+710 \right)}{\frac{1}{2}(363,300+405,500)} \right)^{3/2} \\
&\approx 0.0649\: \text{days}=1.56\: \text{h} \approx 1.6\: \text{h}
\end{align}
$$

***3.3***
**The eccentricity of the earth's orbit is $0.0167$. Find the ratio $v_{max}/v_{min}$ of its maximum speed in its orbit to its minimum speed.**

By the Kepler's second law states that the area that the radius vector from the sun to the planet sweeps out in equal intervals of time is equal, that is, the speed is proportional to the speed:
$$
\frac{t}{A}=C \quad \Rightarrow \quad t \propto A
$$
Let $s(t)$ be the path the earth run through in $t$, and let $r$ be the distance from the sun to the earth. Then 
$$
\lim_{ t \to 0 } \frac{s(t)}{t}=\frac{\mathrm{d}s}{\mathrm{d}t}=v
$$
We know that
$$
r\theta=s \quad \Rightarrow \quad r\mathrm{d}\theta=\mathrm{d}s
$$
When $t\to 0 \Leftrightarrow \Delta s \to 0 \Leftrightarrow \Delta \theta \to 0 \Leftrightarrow A\to 0$.
So when $\Delta \theta\to 0$
$$
\begin{align}
A&=\frac{1}{2}r^{2}\sin \theta \\
\mathrm{d}A&=0+\frac{1}{2}r^{2}\Delta \theta \quad \text{(first order linear approximation at } \theta \to \text{0)}\\
&=\frac{1}{2}r^{2}\mathrm{d}\theta
\end{align}
$$
Hence,
$$
\begin{align}
\frac{v_{max}}{v_{min}}&=\frac{\frac{\mathrm{d}s_{max}}{\mathrm{dt}}}{\frac{\mathrm{d}s_{min}}{\mathrm{d}t}} \\
&=\frac{r_{max}\mathrm{d}\theta_{max}}{r_{min}\mathrm{d}\theta_{min}} \\
&=\frac{r_{max} \frac{2}{r_{max}^{2}}\mathrm{d}A_{max}}{r_{min} \frac{2}{r^{2}_{min}}\mathrm{d}A_{min}}
\end{align}
$$
Since the time that is passed is equal for the denominator and the numerator, by the Kepler's second law, $\mathrm{d}A_{max}=\mathrm{d}A_{min}$.
$$
\frac{v_{max}}{v_{min}}=\frac{r_{min}}{r_{max}}
$$
Because it is the ratio of the maximum speed and minimum speed of the planet, $r_{min}$ should be as large as possible and $r_{max}$ should be as small as possible. This implies that $r_{min}$ is the apogee $r_{a}$ and $r_{max}$ is the perigee $r_{p}$. Consequently
$$
\begin{align}
\frac{v_{max}}{v_{min}}&=\frac{r_{a}}{r_{p}} \\
&=\frac{a(1+e)}{a(1-e)} \\
&=\frac{1+0.0167}{1-0.0167} \\
&\approx 1.033
\end{align}
$$

***3.4***
**The radii of the earth and the moon are $6378\: \text{km}$ and $1738\: \text{km}$, respectively, and their masses are in the ratio $81.3$ to $1.000$. Calculate the acceleration of gravity $g_{☾}$ at the surface of the moon. ($g_{♁}=9.81\: \text{m s}^{-2}$.)**

Ans:
From Newton's law of gravity, we have
$$
F=\frac{Gmm'}{r^{2}}
$$
And $F=m'a=\frac{Gmm'}{r^{2}}$, which implies that $a=\frac{Gm}{r^{2}}$.
Hence,
$$
\begin{align}
&&\frac{g_{☾}}{g_{♁}}&=\frac{{Gm_{☾} / r_{☾}^{2}}}{Gm_{♁} / r_{♁}^{2}} \\
&\Rightarrow& g_{☾}&=g_{♁} \frac{m_{☾}r_{♁}^{2}}{m_{♁}r_{☾}^{2}} \\
&\Rightarrow& g_{☾}&=9.81\times \frac{1}{81.3}\times \frac{6378^{2}}{1738^{2}} \\
&&&\approx 1.62\: \text{m s}^{-2}
\end{align}
$$

***3.5***
**In 1986, Halley's comet is expected to return on its seventh trip around the sun since the days in 1456 when people were so frightened that they offered prayers in the churches "to be saved from the Devil, the Turk, and the comet." In its most recent perihelion on April 19, 1910, it was observed to pass near the sun at a distance $0.60\: \text{AU}$.**
1. **How far $r_{a}$ does it go from the sun at the outer extreme of its orbit?**
2. **What is the ratio $v_{max} / v_{min}$ of its maximum orbital speed to its minimum speed?**

Ans:
1. Since it is the seventh times for Halley's comet to trip around the sun since 1456, we could estimate the time Halley's comet travel for one round: $\frac{1910-1456}{6}\approx 75.67$ years.
   By the Kepler's third law, the squares of the periods of any two planets are proportional to the cubes of the semi-major axes of their respective orbits. So
   $$
   \begin{align}
&&\frac{T_{H}}{T_{♁}}&=\left( \frac{\frac{1}{2}(r_{p}+r_{a})}{1} \right)^{3/2} \\
&\Rightarrow& \frac{75.67}{1}&=\left( \frac{1}{2}(0.60+r_{a}) \right)^{3/2}
\end{align}
   $$
   That is, 
   $$
   \begin{align}
r_{a}&=75.67^{\frac{2}{3}}\times2-0.60 \\
&\approx 35.2\: \text{AU}
\end{align}
   $$
2. By problem 3.3, $v_{max} / v_{min}=r_{a} / r_{p}=35.2 / 0.6\approx 59$.

***3.6***
**A satellite in a circular orbit near the earth's surface has a typical period of about $100$ minutes. What should be the radius $r$ of its orbit (in Earth radii, $r_{♁}$) for a period of $24$ hours?**

Ans:
By the Kepler's third law, $T \propto a^{3/2}$. So
$$
\begin{align}
&&\left( \frac{r}{r_{♁}} \right)^{3/2}&=\frac{24\times 60}{100} \\ \\

&\Rightarrow& r&=r_{♁}\left( \frac{24\times 60}{100} \right)^{2/3} \\ \\

&&&\approx 5.9r_{♁}
\end{align}
$$

***3.7***
**Consider two earth satellites of equal orbital radius, one of them in a polar orbit, the other in an orbit in the equatorial plane. Which satellite needed the larger booster rocket and why?**

Ans:
![[orbits.svg#invert]]
The polar orbit one would need a larger booster rocket since all the kinetic energy it needs to rotate round around the earth must be derived all from the booster, however, the kinetic energy for the other satellite that orbits the equatorial plane could be obtained partly from the earth spinning.

***3.8***
**A true "Syncom" satellite rotates synchronously with the earth. It always remains in a fixed position with respect to a point $P$ on the earth's surface.**
1. **Consider the straight line connecting the center of the earth with the satellite. If $P$ lies on the intersection of this line with the earth's surface, can $P$ have any geographic latitude $\lambda$ or what restrictions do exist? Explain.**
2. **What is the distance $r_{s}$ from the earth's center to a Syncom satellite of mass $m$? Express $r_{s}$ in unites of the earth-moon distance $r_{♁☾}$
Note: Consider the earth a uniform sphere. You may use $T_{☾}=27$ days for the moon's period.**

Ans:
![[orbits_latitude.svg#invert]]
1. Since the Syncom satellite remains in a fixed point, it must rotates in the same plane which the earth spins, otherwise, the latitude would change and the satellite would move toward north or south. In addition, the satellite rotates around the center of the earth, thus, the satellite must rotate on the same plane as the plane of the latitude $\lambda=0^{\circ}$. So $P$ is at latitude $\lambda=0^{\circ}$.
2. By the Kepler's third law, $T\propto a^{3/2}$.
   $$
   \begin{align}
&&\frac{1}{T_{☾}}&=\left( \frac{r_{s}}{r_{♁☾}} \right)^{3/2} \\
&\Rightarrow& \frac{r_{♁☾}}{(T_{☾})^{2/3}}&=r_{s} \\
&\Rightarrow& r_{s}&=\frac{r_{♁☾}}{9}
\end{align}
   $$

***3.9***
1. **Comparing data describing the earth's orbital motion about the sun with data for the moon's orbital motion about the earth, determine the mass of the sun $m_{☼}$ relative to the mass of the earth $m_{♁}$**
2. **Io, a moon of Jupiter, has an orbital period of revolution of $1.769$ days and an orbital radius of $421,800\: \text{km}$. Determine the mass of Jupiter $m_{♃}$ in terms of the mass of the earth.**

Ans:
1. From the data [here](https://nssdc.gsfc.nasa.gov/planetary/factsheet/index.html), we can get the apogee, perigee and orbital period of the earth and the moon about the sun and the earth, respectively.
   $$
   \begin{matrix}
& \text{Earth} & \text{Moon} \\
\text{Aphelion}(10^{6}\: \text{km}) & 152.1 & 0.406 \\
\text{Perihelion}(10^{6}\: \text{km}) & 147.1 & 0.363 \\
\text{Semi-major axis}(10^{6}\: \text{km}) & 149.598 & 0.3844 \\
\text{orbital period}(\text{days}) & 365.2 & 27.3
\end{matrix}
   $$
   Assume that the earth and the moon rotates in a circle. The speed of the earth is $v_{♁}=\frac{2\pi r_{♁}}{T_{♁}}$, and the speed of the moon is $v_{☾}=\frac{2\pi r_{☾}}{T_{☾}}$.  ![[moon_falling.svg#invert]]
   Consider the planets moves in a small amount of time. Then the angle would change in $\theta=\frac{\Delta t}{T}2\pi$. And the planets will 'fall down' $s=r\theta \times \sin \frac{\theta}{2}=2\pi r \frac{\Delta t}{T}\sin \left( \frac{\Delta t}{T}\pi \right)$. When $\Delta t$ tends to $0$, $\lim \limits_{ \Delta t \to 0 }s=2\pi r \frac{\Delta t}{T}\times \frac{\Delta t}{T}\pi=2\pi^{2}r\left( \frac{\Delta t}{T} \right)^{2}$ For a static object, the change in distance is proportional to its acceleration, $s\propto a=\frac{GM}{r^{2}}$. So $M \propto sr^{2}$. Hence
   $$
   \begin{align}
\frac{M_{☼}}{M_{♁}}&=\frac{ 2\pi^{2}r_{♁}\left( \frac{\Delta t}{T_{♁}} \right)^{2} r_{♁}^{2}}{2\pi^{2}r_{☾} \left( \frac{\Delta t}{T_{☾}} \right)^{2} r_{☾}^{2}} \\
&=\frac{r_{♁}^{3}T_{☾}^{2}}{r_{☾}^{3}T_{♁}^{2}} \\
&=\frac{(149.597)^{3}(27.3)^{2}}{(0.3844)^{3}(365.2)^{2}} \\
&\approx 329,368\approx 3.3\times 10^{5}
\end{align}
   $$
2. Similarly, We compute how much distance Jupiter will 'fall down' in a small distance:
   $$
   s=2\pi^{2} r_{♃} \left( \frac{\Delta t}{T_{♃}} \right)^{2}
   $$
   and
   $$
   \begin{align}
&&\frac{M_{♃}}{M_{♁}}&=\frac{r_{♃☾}^{3}T_{☾}^{2}}{r_{☾}^{3}T_{♃☾}^{2}} \\
&\Rightarrow& M_{♃}&=\frac{r_{♃☾}^{3}T_{☾}^{2}}{r_{☾}^{3}T_{♃☾}^{2}}M_{♁} \\
&&&=\frac{0.4218^{3}\times 27.3^{2}}{0.3844^{3}\times 1.769^{2}}M_{♁} \\
&&&\approx 314.6M_{♁}
\end{align}
   $$

***3.10***
**Two stars, $a$ and $b$, move around one another under the influence of their mutual gravitational attraction. If the semi major axis of their relative orbit is observed to be $R$, measured in astronomical units ($\text{AU}$) and their period of revolution is $T$ years, find an expression for the sum of the mass, $m_{a}+m_{b}$, in terms of the mass $m_{☼}$ of the sun.**

Ans:
Notation:
$$
\begin{matrix*}[l]
a & \text{star}\:a \\
b & \text{star}\:b \\
R & \text{relative semi-major axis} \\
T & \text{period of revolution} \\
m_{a} & \text{mass of star } a \\
m_{b} & \text{mass of star } b \\
m_{☼} & \text{mass of the sun} \\
\vec{a}_{a}(t) & \text{acceleration function of star }a \\
\vec{a}_{b}(t) & \text{acceleration function of star }b \\
\vec{v}_{a}(t) & \text{velocity function of star } a \\
\vec{v}_{b}(t) & \text{velocity function of star } b \\
\vec{x}_{a}(t) & \text{position function of star } a \\
\vec{x}_{b}(t) & \text{position function of star } b \\
\Delta\vec{v}_{a}(t) & \text{change in velocity function of star } a \\
\Delta\vec{v}_{b}(t) & \text{change in velocity function of star } b \\
\Delta\vec{x}_{a}(t) & \text{change in position function of star } a \\
\Delta\vec{x}_{b}(t) & \text{change in position function of star } b \\
e_{a} & \text{eccentricity of the motion of star }a \\
e_{b} & \text{eccentricity of the motion of star }b \\
e & \text{relative eccentricity of the motion of star }b \\
r_{a,a} & \text{aphelion distance of the motion of star }a \\
r_{a,b} & \text{aphelion distance of the motion of star }b \\
r_{a} & \text{aphelion distance of the relative motion of star }b \\
r_{p,a} & \text{perihelion distance of the motion of star }a \\
r_{p,b} & \text{perihelion distance of the motion of star }b \\
r_{p} & \text{perihelion distance of the relative motion of star }b \\
a_{a} & \text{semi-major axis of }a \\
a_{b} & \text{semi-major axis of }b \\
b_{a} & \text{semi-minor axis of }a \\
b_{b} & \text{semi-minor axis of }b \\
a & \text{semi-major axis} \\
b & \text{semi-minor axis} \\
\Delta t & \text{infinitesimal change in time} \\
\Delta x & \text{infinitesimal change in position along velocity} \\
\Delta \theta & \text{infinitesimal change in angle about the rotating star} \\
r & \text{distance between two star} \\
G & \text{gravity constant}
\end{matrix*}
$$
We know that the forces acting on the two stars are identical but in opposite direction, that is, $m_{a}\vec{a}_{a}(t)=-m_{b}\vec{a}_{b}(t)$. Integrate with respect to $t$ on both sides of the equation, we have
$$
m_{a}[\Delta\vec{v}_{a}(t)+\vec{v}_{a}(0)]=-m_{b}[\Delta\vec{v}_{b}(t)+\vec{v}_{b}(0)]
$$
Integrate again by time gives
$$
m_{a}[\Delta\vec{x}_{a}(t)+\vec{v}_{a}(0)t+\vec{x}_{a}(0)]=-m_{b}[\Delta\vec{x}_{b}(t)+\vec{v}_{b}(0)t+\vec{x}_{b}(0)]
$$
If we put our view on the center of mass, then $m_{a}\vec{x}_{a}(t)=-m_{b}\vec{x}_{b}(t),\:\forall t$. Furthermore, the net momentum should be zero, thus, $m_{a}\vec{v}_{a}(t)=-m_{b}\vec{v}_{b}(t),\:\forall t$. This results in
$$
m_{a}\Delta\vec{x}_{a}(t)=-m_{b}\Delta\vec{x}_{b}(t)
$$
Which means that the two stars have the same motion shape, but scaled by their masses. Therefore they have the same eccentricity, $e_{a}=e_{b}$.

Simulation [here](https://ccnmtl.github.io/astro-simulations/eclipsing-binary-simulator/) or [here](https://www.astro.ucla.edu/undergrad/astro3/orbits.html).
![[binary_star.svg#invert]]
Consider the figure above, $2a_{a}-r_{p}+2a_{b}=r_{a}$, so $2R=r_{a}+r_{p}=2a_{a}+2a_{b}\Rightarrow R=a_{a}+a_{b}$. Furthermore, $r_{a,a}+r_{a,b}=r_{a}$ and $r_{p,a}+r_{p,b}=r_{p}$, which implies that $r_{a,a}+r_{a,b}+r_{p,a}+r_{p,b}=2R=2a_{a}+2a_{b}$. 
As for the eccentricity of the relative ellipse,
$$
\begin{align}
e&= c / a=\frac{r_{a}-R}{R}=\frac{r_{a}-\frac{r_{a}}{2}-\frac{r_{p}}{2}}{\frac{r_{a}}{2}+\frac{r_{p}}{2}}=\frac{r_{a}-r_{p}}{r_{a}+r_{p}} \\ \\

&=\frac{r_{a,a}+r_{a,b}-r_{p,a}-r_{p,b}}{r_{a,a}+r_{a,b}+r_{p,a}+r_{p,b}} \\ \\

&=\frac{r_{a,a}-r_{p,a}+r_{a,b}-r_{p,b}}{r_{a,a}+r_{p,a}+r_{a,b}+r_{p,b}} \\ \\

&=\frac{a_{a}[(1+e_{a})-(1-e_{a})]+a_{b}[(1+e_{b})-(1-e_{b})]}{a_{a}[(1+e_{a})+(1-e_{a})]+a_{b}[(1+e_{b})+(1-e_{b})]} \\ \\

&=\frac{2e_{a}(a_{a}+a_{b})}{2(a_{a}+a_{b})}=\frac{2e_{b}(a_{a}+a_{b})}{2(a_{a}+a_{b})} \\ \\

&=e_{a}=e_{b}
\end{align}
$$
Therefore, they share the same eccentricity.

As the figure shows below, $R_{c}=\frac{b^{2}}{a}$ is the radius of curvature for the motion shape at its aphelion. $r_{a}\Delta \theta=R_{c}\Delta \phi=v\Delta t$
![[Falls.svg#invert]]
We consider star $a$ at its aphelion, by the Kepler's second law,
$$
\begin{align}
&&\frac{a_{a}b_{a}\pi}{T}\Delta t&=\frac{1}{2}r_{a,a}\Delta x=\frac{1}{2}r_{a,a}v\Delta t \\
& \Rightarrow& \frac{2a_{a}b_{a}\pi}{T}&=r_{a,a}v
\end{align}
$$
So 
$$
\begin{align}
\Delta s&=\Delta x \times \frac{\Delta \phi}{2} \equiv r_{a,a}\Delta \theta \times \frac{\Delta \phi}{2} \\
&= \frac{1}{2}v\Delta t\times \frac{v}{R_{c,a}}\Delta t \\
 & =\frac{1}{2} \frac{v^{2}}{R_{c,a}}(\Delta t)^{2} \\
 & =\frac{1}{2}\frac{\left( \frac{2a_{a}b_{a}\pi}{r_{a,a}T} \right)^{2}}{R_{c,a}}(\Delta t)^{2} \\
 & =\frac{2a_{a}^{3}\pi^{2}}{r_{a,a}^{2}T^{2}}(\Delta t)^{2}
\end{align}
$$
where $\Delta s$ is the distance the star 'falls' when the star is at the farthest distance from the other star.

By the Newton's law of gravitation,
For star at aphelion,
$$
\begin{align}
\frac{2a_{a}^{3}\pi^{2}}{r_{a,a}^{2}T^{2}}(\Delta t)^{2}&=\frac{1}{2}\frac{Gm_{b}}{r_{a}^{2}}(\Delta t)^{2} \\
\frac{4\pi^{2}r_{a}^{2}a_{a}^{3}}{r_{a,a}^{2}T^{2}} & =Gm_{b}
\end{align}
$$
Hence,
$$
\begin{align}
Gm_{b}&=\frac{4\pi^{2}r_{a}^{2}a_{a}^{3}}{r_{a,a}^{2}T^{2}} \\
 & =\frac{4\pi^{2}}{T^{2}} \frac{(R(1+e))^{2}a_{a}^{3}}{(a_{a}(1+e))^{2}} \\
 & =\frac{4\pi^{2}}{T^{2}}Ra_{a}\dots(1)
\end{align}
$$
Similarly, for star $b$,
$$
Gm_{a}=\frac{4\pi^{2}}{T^{2}}Ra_{b}\dots(2)
$$
As for the sun
$$
\begin{align}
&& \frac{1}{2}\frac{Gm_{☼}}{1\: \text{AU}}(\Delta t)^{2}&= \frac{2}{(1\: \text{AU})^{3}}\times\left( \frac{1\times1\pi}{1\: \text{year}}\Delta t \right)^{2} \\
&\Rightarrow& Gm_{☼}&=4\pi^{2}
\end{align}
$$
Therefore,
$$
\begin{align}
&&\frac{m_{☼}}{m_{b}+m_{a}}&=\frac{4\pi^{2}}{\frac{4\pi^{2}}{T^{2}}R^{2}(a_{a}+a_{b})} \\
&&&=\frac{T^{2}}{R^{3}} \\
&\Rightarrow& m_{a}+m_{b}&=\frac{R^{3}}{T^{2}}m_{☼}
\end{align}
$$

***3.11***
**If the attractive gravitational force between a very large central sphere $M$ and a satellite $m$ in orbit about it were actually $\mathbf{F}=-GMm \mathbf{R} /R^{(3+a)}$, (where $\mathbf{R}$ is the radial vector between them) how would Kepler's second and third law be modified? (In discussing the third law, assume a circular orbit.)**

Ans:
For the satellite, it will falls down $s=\frac{1}{2}\frac{GM}{R^{(2+a)}}(\Delta t)^{2}=R\frac{\theta^{2}}{2}$.
![[moon_falling.svg#invert]]
Which is,
$$
\begin{align}
(\Delta t)^{2}\propto R^{(3+a)}\theta^{2}\propto R^{(a-1)}A^{2}
\end{align}
$$
$R$ is a constant, hence $\Delta t\propto A$. The second law would not change.

As for the third law,
$$
(\Delta t)^{2}\propto R^{(3+a)}\theta^{2}\propto R^{(3+a)}\left( \frac{\Delta t}{T}2\pi \right)^{2}
$$
Therefore, $T^{2}\propto R^{(3+a)}$ would be the corrected third law.

***3.12***
**In making laboratory measurements of $g$, how precise does one have to be to detect diurnal variations $\Delta g$ due to the moon's gravitation? For simplicity, assume that your laboratory is so located that the moon passes through zenith and nadir. Also, neglect earth-tide effects.**

Ans:
![[moon_earth.svg#invert]]
From the figure above,
$g=\frac{Gm_{♁}}{R^{2}}$ and $\Delta g= \frac{Gm_{☾}}{(r_{♁☾}+R)^{2}}-\left( -\frac{Gm_{☾}}{(r_{♁☾}-R)^{2}} \right)$. Hence
$$
\begin{align}
\frac{\Delta g}{g}&=\frac{\frac{Gm_{☾}}{(r_{♁☾}+R)^{2}}-\left( -\frac{Gm_{☾}}{(r_{♁☾}-R)^{2}} \right)}{\frac{Gm_{♁}}{R^{2}}} \\
&=\frac{\frac{7.347\times 10^{22}}{((384,400+6371)\times 10^{3})^{2}}+\frac{7.347\times 10^{22}}{((384,400-6371)\times 10^{3})^{2}}}{\frac{5.972\times 10^{24}}{6371^{2}}} \\
&\approx 6.76\times 10^{-6}\approx 7\times 10^{-6}
\end{align}
$$

***3.13***
**An eclipsing binary star system is one whose orbital plane nearly contains the line of sight, so that one star eclipses the other periodically. The relative orbital velocity of the two components can be measured from the Doppler shift of their spectral lines. If $T$ is the observed period in days, and $V$ is the orbital velocity in $\text{km s}^{-1}$, what is the total mass $M$ of the binary system in solar masses?**

***Note*: The mean distance from the earth to the sun is $1.50\times 10^{8}\: \text{km}$.**

Ans:
There are two eclipse for one period. So the period of the binary star system is $2T$ days. We know that $\frac{2\pi R\: (\text{km})}{V\times 60 \times 60\times 24 \: (\text{km d}^{-1})}=T\: (\text{d})$, and $R=60\times 60 \times 24 \times \frac{TV}{2\pi}$
By problem 3.10, $M=\frac{R^{3}}{T^{2}}m_{☼}$ where it uses unit $\text{AU}$ and $\text{year}$. For unit that is in $\text{km}$ and $\text{d}$,
$$
\begin{align}
M&=\frac{\left( \frac{R}{1.50\times 10^{8}} \right)^{3}}{\left(  \frac{T}{365} \right)^{2}}m_{☼} \\
&=\frac{\left( \frac{60\times 60\times 24 TV / 2\pi}{1.5\times 10^{8}} \right)^{3}}{\left(  \frac{T}{365} \right)^{2}}m_{☼} \\
&\approx 1.02\times 10^{-7}\:\mathrm{km}^{-3}\:\mathrm{d}^{-1}\mathrm{s}^{3}\:TV^{3}m_{☼}
\end{align}
$$

***3.14***
**A comet rounds the sun at a perihelion distance of $r_{p}=1.00\times 10^{6}\: \mathrm{km}$. At this point its velocity is $v=500.0\: \text{km s}^{-1}$.**
1. **What is the radius of curvature $R_{c}$ of the orbit at perihelion (in $\mathrm{km}$)?**
2. **For an ellipse with semi-major axis $a$ and semi-major axis $b$, the radius of curvature at perihelion is $R_{c}=\frac{b^{2}}{a}$. If you know $R_{c}$ and $r_{p}$ you should be able to write a relation involving $a$ and only these quantities. Do so, and find $a$.**
3. **If you were able to solve for $a$ from the above information, you should be able to calculate the period $T_{c}$ of the comet. Do so.**

Ans:
1. Assume that the motion equation of the comet is $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$. In polar coordinate, we have $x=a\cos \theta$ and $y=b\sin \theta$. Now, let $r(\theta)=[x,y]=[a\cos \theta,b\sin \theta]$, and $T(\theta)=\frac{r'(\theta)}{\lvert r'\theta \rvert}=\frac{[-a\sin \theta,b\cos \theta]}{\sqrt{ a^{2}\sin^{2} \theta+b^{2}\cos^{2}\theta }}$. Then $r'(\theta)=[-a\sin \theta,b\cos \theta]$ and $T'(\theta)=\frac{[-a\cos \theta,-b\sin \theta]}{\sqrt{ a^{2}\sin ^{2}\theta+b^{2}\cos^{2}\theta }}-\frac{(a^{2}-b^{2})\cos \theta \sin \theta}{(a^{2}\sin^{2}\theta+b^{2}\cos^{2}\theta)^{3/2}}[-a\sin \theta,b\cos \theta]$. The curvature at $\theta=0$ (which is at the aphelion or perihelion) could be calculated as$$
   \begin{align}
\kappa(\theta=0)&=\frac{\left|T'(0)\right|}{\left|r'(0)\right|} \\
&=\frac{\left| \frac{[-a\cos 0,-b\sin 0]}{\sqrt{ a^{2}\sin ^{2}0+b^{2}\cos^{2}0 }}-\frac{(a^{2}-b^{2})\cos 0 \sin 0}{(a^{2}\sin^{2}0+b^{2}\cos^{2}0)^{3/2}}[-a\sin 0,b\cos 0] \right|}{\left|[-a\sin 0, b\cos 0]\right|} \\
&=\frac{\left| \frac{1}{b}[-a,0] \right|}{\left| [0,b] \right|}=\frac{a}{b^{2}}
\end{align}$$
   The curvature of a circle is $\kappa_{\text{circle}}=\frac{1}{\text{radius}}$. Hence, the radius of curvature is defined to be $\frac{1}{\kappa}$. Therefore, the radius of curvature at its perihelion is $R_{c}=\frac{b^{2}}{a}= \frac{a^{2}-c^{2}}{a}=\frac{r_{p}r_{a}}{(r_{p}+r_{a}) / 2}$.
   
   By Kepler's second law,$$
   \begin{align}
&&\frac{\Delta t}{\frac{1}{2}r_{p}v\Delta t}&=\frac{T}{ab\pi} \\
&\Rightarrow&\frac{1}{\frac{1}{4}r_{p}^{2}v^{2}}&=\frac{T^{2}}{a^{2}r_{p}r_{a}\pi^{2}} \\
&\Rightarrow& \frac{4}{r_{p}v^{2}}&=\frac{T^{2}}{\left( \frac{r_{a}+r_{p}}{2} \right)^{2}r_{a}\pi^{2}}
\end{align}
   $$From problem [[3.13]], we have the mean distance from  the earth to the sun is $1.50\times 10^{8}\: \text{km}$. By Kepler's third law, $T^{2}\propto R^{3}$ where $R$ is the semi-major axis. Hence,$$
   \begin{align}
&&\frac{T_{♁}^{2}}{T^{2}}&=\frac{(1\times 365\times 24\times 60 \times 60 \:(\text{second}))^{2}}{4\left( \frac{r_{a}+r_{p}}{2} \right)^{2}r_{a}\pi^{2} / r_{p}v^{2}}=\frac{(1.50 \times 10^{8})^{3}}{\left( \frac{r_{a}+r_{p}}{2} \right)^{3}}
\end{align}
   $$and$$
   \begin{align}
&&3.68\times 10^{-11}&\approx \frac{r_{a}\pi^{2}}{r_{p}v^{2}(r_{a}+r_{p})} \\
&\Rightarrow& \frac{r_{p}r_{p}}{(r_{a}+r_{p}) /2}&\approx 3.68\times 10^{-11}r_{p}^{2} \frac{v^{2}}{\pi^{2}}\times2
\end{align}
   $$Therefore, $$
   \begin{align}
R_{c}&= \frac{b^{2}}{a}= \frac{a^{2}-c^{2}}{a}=\frac{r_{p}r_{a}}{(r_{p}+r_{a}) / 2} \\
&=3.68\times 10^{-11}r_{p}^{2} \frac{v^{2}}{\pi^{2}}\times 2 \\
&=3.68\times 10^{-11}(1.00\times 10^{6})^{2} \frac{(500.0)^{2}}{\pi^{2}}\times 2 \\
&\approx 1.87\times 10^{6}\: \text{km}
\end{align}$$
2. From 1., $R_{c}=\frac{b^{2}}{a}= \frac{a^{2}-c^{2}}{a}=\frac{r_{p}r_{a}}{(r_{p}+r_{a}) / 2}=\frac{r_{p}(2a-r_{p})}{a}$. Hence$$\begin{align}
a&=\frac{r_{p}^{2}}{2r_{p}-R_{c}} \\
&=\frac{(1.00\times 10^{6})^{2}}{2\times 1.00 \times 10^{6}-1.87\times 10^{6}} \\
&\approx 7.692\times 10^{6}\: \text{km}
\end{align}$$If we take $R_{c}=1.88\times 10^{6}$, we have $a\approx 8.33\times 10^{6}\: \text{km}$

3. From 1., $$\begin{align}
&&\frac{\Delta t}{\frac{1}{2}r_{p}v\Delta t}&=\frac{T}{ab\pi}
\end{align}$$and from 2.$$R_{c}=\frac{r_{p}(2a-r_{p})}{a}$$Hence,
 $$
\begin{align}
T&=\frac{2ab\pi}{r_{p}v} \\
&=\frac{2\pi a\sqrt{ r_{p}(2a-r_{p}) }}{r_{p}v} \\
&=\frac{2\pi a\sqrt{ aR_{c} }}{r_{p}v} \\
&=\frac{2\pi a^{3/2}\sqrt{ R_{c} }}{r_{p}v} \\
&=\frac{2\pi (8.33\times 10^{6})^{\frac{3}{2}}\times \sqrt{ 1.88\times 10^{6} }}{1.00\times 10^{6}\times 500.0} \\
&\approx 4.142\times 10^{5}\: \text{s} \\
&\approx 4.8 \: \text{d}
\end{align}$$
***3.15***
**Using the idea that two mutually gravitating bodies each "fall" toward the other, and thus move about some fixed common point (their center of mass), show that their period in an orbit in which they remain a given fixed distance apart depends only upon the sum of their masses $M+m$ and not at all upon the ratio of their masses. This is also true for elliptical orbits. Assuming that the semi-major axes of the ellipses in which the bodies move are $R$ and $r$, find the period $T$ of their orbit.**

Ans:
By problem [[3.10]], for a binary star system, $m_{a}\Delta \vec{x}_{a}(t)=-m_{b}\Delta \vec{x}_{b}(t)$, which mean the two stars have the same but reflected and scaled motion shape. That is, they have the same period $T$. Also by problem [[3.10]], $Gm_{a}=\frac{4\pi^{2}}{T^{2}}R^{2}a_{b}$ and $Gm_{b}=\frac{4\pi^{2}}{T^{2}}R^{2}a_{a}$ where $m_{a}=M$, $m_{b}=m$ and $R\:(\text{relative semi-major axis})=R\:(\text{semi-major axis of one star})+r$. Hence, $GM+Gm=4\pi^{2} \frac{(R+r)^{3}}{T^{2}}$. And
$$
T^{2}=4\pi^{2}\frac{(R+r)^{3}}{G(M+m)}
$$
which has only to do with $M+m$ and $R+r$, and not the ratio of the two stars' masses.

***3.16***
**How can one find the mass of the moon?**

Ans:
By Kepler's law on planetary motion,
1. Each planet moves around the sun in an ellipse, with the sun at one focus.
   
2. The radius vector from the sun to the planet sweeps out equal areas in equal intervals of time.
   
3. The squares of the periods of any two planets are proportional to the cubes of the semi-major axes of their respective orbits: $T\propto a^{3/2}$.
and Newton's law of gravitation,
$$
F=\frac{Gmm'}{r^{2}}
$$
*We view the earth and the moon as a binary planet system.*

By problem [[3.10]], the sum of the masses of a binary star system is $m_{a}+m_{b}=\frac{R^{3}}{T^{2}}m_{☼}$ where $R$ is the relative semi-major axis in units $AU$ which is $R=\frac{r_{a}+r_{p}}{2}$, $r_{a}$ and $r_{p}$ are the relative aphelion distance and perihelion distance, and $T$ is the period of revolution of the system in units $year$. This is also true for planet.

We can observe the motion of the moon and get its perihelion distance $r_{p}$, aphelion distance $r_{a}$, period $T$. Hence,
$$m_{☾}+m_{♁}= \frac{\left( \frac{r_{p}+r_{a}}{2} \right)^{3}}{T^{2}}m_{☼}$$
And $m_{☾}=\frac{(r_{p}+r_{a})^{3}}{8T^{2}}m_{☼}-m_{♁}$.

***3.17***
**The trigonometric parallax of Sirius (i.e., the angle subtended at Sirius by the radius of the Earth's orbit) is $0.378\: \text{degrees arc}$. Using this and the data contained in Fig. 3-2, deduce as best you can the mass $M$ of the Sirius system in terms of that of the sun, and**
1. **assuming that the orbital plane is perpendicular to the line of sight, and**
2. **allowing for the actual tilt of the orbit.**
**Is you value in part 2 above an upper or lower limit (or either)?**
![[Fig.3-2.svg#invert]]
Ans:
From the figure above, we know that half the period of revolution is about $1896.9-1874=22.9$ years. Hence the period of revolution is about $T=45.8$ years.
![[degree_arc.svg#invert]]
The trigonometric parallax is $p= 0.378\: \text{degrees arc}$. (*Here it seems that $p$ is unusually large, I guess it should be $0.378\: \text{arcseconds}$ instead of $\text{degrees arc}$.*) Let $r$ be the distance from the sun to Sirius, then $rp=1\Rightarrow r=\frac{1}{p}=\frac{1}{\frac{0.378}{ 60\times 60} \times \frac{\pi}{180}}\approx 5.45\times 10^{5}\: \text{AU}$. By using a rule, the trigonometric parallax of the major axis of this ellipse is about $\frac{6.3}{5.3}\times12''\approx 14.2\: \text{arcsecond}=\frac{14.2}{60\times 60}\times \frac{\pi}{180}\approx 6.91\times 10^{-5} \: \text{Rad arc}$. And the semi-major axis is $a\approx \frac{1}{2}\times5.45\times 10^{5}\times 6.91\times 10^{-5}\approx 18.8\: \text{AU}$.

From problem [[3.14]], the radius of curvature of at the perihelion and the aphelion is $R_{c}=\frac{b^{2}}{a}$. As the figure shows below,
![[Falls.svg#invert]]
$R_{c}\Delta \phi=v_{a}\Delta t=r_{a}\Delta \theta$ and $\frac{1}{2}r_{a}v_{a}\Delta t=\frac{1}{2}r_{a}^{2}\Delta \theta$, $\frac{1}{2}R_{c}v_{a}\Delta t=\frac{1}{2}R_{c}^{2}\Delta \phi$.
By the Kepler's second law, when the planet is at its apogee,
$$
\begin{align}
&&\frac{ab\pi}{T}\Delta t &=\frac{1}{2}r_{a}v_{a}\Delta t\\
&\Rightarrow& \frac{ab\pi}{T}&=\frac{1}{2}r_{a}v_{a}
\end{align}
$$
Thus, 
$$
\begin{align}
s&=v_{a}\Delta t \frac{\Delta \phi}{2} \\
 & =\frac{1}{2}\frac{v_{a}^{2}(\Delta t)^{2}}{R_{c}} \\
 & =\frac{1}{2} \frac{\left( \frac{2ab\pi}{r_{a}T} \right)^{2}(\Delta t)^{2}}{\frac{b^{2}}{a}} \\
 & =\frac{2a^{3}\pi^{2}}{r_{a}^{2}T^{2}}(\Delta t^{2})
\end{align}
$$
Combining this with the Newton's law of gravitation, we have
$$
\frac{1}{2}\frac{Gm_{Sirius}}{r_{a}^{2}}(\Delta t)^{2}=\frac{2a^{3}\pi^{2}}{r_{a}^{2}T^{2}}(\Delta t^{2})
$$
Which implies that
$$
Gm_{Sirius}=\frac{4\pi^{2}a^{3}}{T^{2}}
$$
We know that $Gm_{☼}=4\pi^{2}$. Therefore,
$$
\begin{align}
&&\frac{Gm_{Sirius}}{Gm_{☼}}&=\frac{\frac{4\pi^{2}a^{3}}{T^{2}}}{4\pi^{2}}=\frac{a^{3}}{T^{2}} \\
&\Rightarrow&m_{Sirius}&= \frac{a^{3}}{T^{2}}m_{☼} \\
&&&=\frac{(18.8)^{3}}{(45.6)^{2}}m_{☼} \\
&&&\approx 3.16m_{☼}
\end{align}
$$

If the orbit tilts, $a$  will increase. This mean that the mass of Sirius is greater than it is when the orbital plane is perpendicular to the line of sight. Hence, its an lower bound.