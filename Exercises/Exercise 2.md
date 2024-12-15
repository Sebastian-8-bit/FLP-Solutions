The exercises presented in this document are completed by CHEN, RONG-XIANG(陳融翔) from Taitung City, Taiwan.

All the figures in this document is redrawn using Mathcha or Inkscape.

## 2.1
**Use the principle of virtual work to establish the formula for an unequal- arm balance, as shown in Fig. 2-1, $W_{1}l_{1}=W_{2}l_{2}$ . (Neglect the weight of the cross-beam.)**
![[templates/Fig.2-1.svg#invert]]
Ans:
Let's say, $W_{1}$ moves down $d$ unit, then $W_{2}$ will be lifted up $\frac{d}{l_{1}}l_{2}$. By the conservation of energy, $W_{1}d=W_{2}d \frac{l_{2}}{l_{1}}$, that is, $W_{1}l_{1}=W_{2}l_{2}$.

## 2.2
**Extend the formula obtained in Ex. 2.1 to include a number of weights hung at various distances from the pivot point,
$$\sum\limits_{i}^{}W_{i}l_{i}=0$$
(Distances on one side of the fulcrum are considered positive and on the other side, negative.)**

Ans:
When one of the $W_{i}$, say $W_{1}$ is moved down in a distance $d$, then $W_{i}$ moves down in distance $\frac{d}{l_{1}}l_{i}$ for all $W_{i}$ on the same side as $W_{1}$. Similarly, $W_{i}$ is lifted up in distance $\frac{d}{l_{1}}l_{2}$ for all $W_{i}$ on the opposite side of $W_{1}$. By the conservation of energy, $W_{1}d +\sum\limits_{i=2}^{k}W_{i} \frac{d}{l_{1}}l_{i}=\sum\limits_{k+1}^{n}W_{i} \frac{d}{l_{1}}(-l_{i})$ , and thus, $\sum\limits_{i}^{}W_{i}l_{i}=0$.

## 2.3
**A body is acted upon by $n$ forces and is in static equilibrium. Use the principle of virtual work to prove that:**
1. **If $n=1$, the magnitude of the force must be zero. (A trivial case.)**
2. **f $n=2$, the two forces must be equal in magnitude, opposite in direction, and collinear.**
3. **If $n=3$, the forces must be coplanar and their lines of action must pass through a single point.**
4. **For any $n$, the sum of the products of the magnitude of a force $F_{i}$ times the cosine of the angle $\Delta_{i}$ between the force and any fixed line, is zero:**
**$$\sum\limits_{i=1}^{n}F_{i}\cos\Delta_{i}=0$$**

Ans:
1. Assume that the object moves toward the same direction as $F_{1}$ in a non-zero distance $d$, then, by the conservation of energy, $F_{1}d=0$. This implies that $F_{1}=0$.
2. Assume that there are two forces $\vec{F}_{1}$ and $\vec{F}_{2}$. If the object moves $\vec{r}$, by the principle of virtual work, $\vec{F}_{1}\cdot \vec{r}+\vec{F}_{2}\cdot \vec{r}=0$. This equation could be developed to $\vec{F}_{1}\lvert \vec{r} \rvert^{2}+\vec{F}_{2}\lvert \vec{r} \rvert^{2}=0$, and hence, $\vec{F}_{1}=-\vec{F}_{2}$.
3. Suppose that there are three forces $\vec{F}_{1}$, $\vec{F}_{2}$ and $\vec{F}_{3}$ acting on the object. If the object moves $\vec{r}$, by the principle of virtual work, $\vec{F}_{1}\cdot \lvert \vec{r} \rvert^{2}+\vec{F}_{2}\cdot \lvert \vec{r} \rvert^{2}+\vec{F}_{3}\cdot \lvert \vec{r} \rvert^{2}=0$, that is $\vec{F}_{1}+\vec{F}_{2}+\vec{F}_{3}=0$. This implies that $\vec{F}_{1}$, $\vec{F}_{2}$ and $\vec{F}_{3}$ are collinear or form a triangle, and therefore, the forces are coplanar. By problem 2.12, the net torque about every arbitrary points would be the same. If their lines of action don't pass through a single point, without lost of generality, say, $F_{1}$ don't pass through the intersection of the acting lines of $F_{2}$ and $F_{3}$, then set the fulcrum to be at this intersection, the torque $\tau=\vec{F}_{1}\times\vec{r}_{1}\neq 0$ where $\vec{r}_{1}\neq \vec{0}$ is the vector pointing from the intersection of $F_{2}$ and $F_{3}$ to the acting point of $F_{1}$. This contradict the hypothesis that the body is in static equilibrium, and hence, their lines of action should pass through a single point.
4. Let the object move $\vec{r}$, by the principle of virtual work,$$\sum\limits_{i=1}^{n}\vec{F}_{i}\cdot \vec{r}=0$$That is, $$\sum\limits_{i=1}^{n}\lvert \vec{F}_{i} \rvert \lvert \vec{r} \rvert \cos \Delta_{i}=0$$ Hence, $$\sum\limits_{i=1}^{n}F_{i}\cos \Delta_{i}=0$$
## 2.4
**Problems involving static equilibrium in the absence of friction may be reduced, using the *Principle of Virtual Work*, to problems of mere geometry: Where does one point move when another moves a given small distance? In many cases this question is easily answered if the following properties of a triangle are used (referring to Figure below):**
![[templates/Fig.2-2.svg#invert]]
1. **1. If the sides $d_{1}$ and $d_{2}$ remain fixed in length, but the angle $\alpha$ changes by a small amount $\Delta \alpha$, the opposite side $L$ changes by an amount $$\Delta L=\frac{d_{1}d_{2}}{L}\sin \alpha \Delta \alpha$$**
2. **If the three sides $a$, $b$, $c$ of a right triangle change in length by small amounts $\Delta a$, $\Delta b$ and $\Delta c$, then $$a\Delta a+b\Delta b=c\Delta c \ \ \ \ \text{(where c is the hypotenuse).}$$
Prove these formulas.**

Ans:
![[templates/Fig.2-2solv.svg#invert]]
1. Consider the geometry, $$\begin{align}
&&\left(d_{1}\sin \alpha\right)^{2} + \left(d_{2}-d_{1}\cos \alpha\right)^{2}&=L^{2} \\
&\Rightarrow&d_{1}^{2}\sin ^{2}\alpha+d_{2}^{2}-2d_{2}d_{1}\cos \alpha+d_{1}^{2}\cos^{2}\alpha&=L^{2} \\
&\Rightarrow&d_{1}^{2}+d_{2}^{2}-2d_{2}d_{1}\cos \alpha&=L^{2}
\end{align}$$Differentiate both side of the equation, we get$$2L \frac{\mathrm{d}L}{\mathrm{d}\alpha}=2d_{2}d_{1}\sin \alpha$$and $$\mathrm{d}L=\frac{d_{1}d_{2}}{L}\sin \alpha \:\mathrm{d}\alpha$$Change $\mathrm{d}$ to $\Delta$, we consequently have$$\Delta L=\frac{d_{1}d_{2}}{L}\sin \alpha \Delta \alpha$$
2. If the right triangle have sides $a$, $b$ and hypotenuse $c$, By the Pythagorean Theorem, $c^{2}=a^{2}+b^{2}$. Differentiate both sides of the equation with respect to $a$, we have$$2c \frac{\mathrm{d}c}{\mathrm{d}a}=2a+2b \frac{\mathrm{d}b}{\mathrm{d}a}$$That is, $$c\:\mathrm{dc}=a\:\mathrm{d}a+b\:\mathrm{d}b$$$\mathrm{d}$ is the differential, which could be consider to be a small amount of change. Thus, we have $$c\:\Delta c=a\:\Delta a+b\:\Delta b$$

## 2.5
**A uniform plank $1.5 \:\text{m}$ long and weighing $3.00\: \text{kg}$ is pivoted at one end. The plank is held in equilibrium in a horizontal position by a weight and pulley arrangement, as shown in Figure. Find the weight $W$ needed to balance the plank. Neglect friction.**
![[templates/Fig.2-3.svg#invert]]
Ans:

For a uniform plank, its center of mass is at the middle of the plank. If the center of mass is moved down in a small distance $d$, the end of the plank is moved down $2d$, and $W$ is lifted up $\frac{2d}{\sqrt{ 2 }}$. By the principle of virtual work, $W\times \frac{2d}{\sqrt{ 2 }}-3.00 \times d = 0$, and $W=\frac{3}{\sqrt{ 2 }}\: \text{kg-wt}$.

## 2.6
**A ball of radius $3.0\: \text{cm}$ and weight $1.00\: \text{kg}$ rests on a plane tilted at an angle $\alpha$ with the horizontal and also touches a vertical wall, as shown in Figure. Both surfaces have negligible friction. Find the force with which the ball presses on the wall $F_{W}$ and on the plane $F_{P}$.**
![[templates/Fig.2-4.svg#invert]]
Ans:
Assume that the ball moves $\vec{r}=\langle s, s\tan \alpha \rangle$. By the principle of virtual work, $F_{W}s+F_{P}(\cos \alpha \times s\tan \alpha-\sin \alpha \times s)-1.00g\times s\tan \alpha=0$. And $F_{P}\cos \alpha=1.00g$. Hence,
$$
\begin{align}
F_{W}&= g\tan\alpha -g\tan \alpha+\tan \alpha=g\tan \alpha  \: \text{kg-wt}\\
F_{P}&=g\sec \alpha \: \text{kg-wt}
\end{align}

$$

## 2.7
**The jointed parallelogram frame $AA'BB'$ is pivoted (in a vertical plane) on the pivots $P$ and $P'$, as shown in Figure. There is negligible friction in the pins at $A$, $A'$, $B$, $B'$, $P$ and $P'$. The members $AA'CD$ and $B'BGH$ are rigid and identical in size. $AP=A'P'=\frac{1}{2}PB=\frac{1}{2}P'B'$. Because of the counterweight $w_{c}$, the frame is in balance without the loads $W_{1}$ and $W_{2}$ . If a $0.50\: \text{kg}$ weight $W_{1}$ is hung from $D$ , what weight $W_{2}$ , hung from $H$ , is needed to produce equilibrium?**
![[templates/Fig.2-5.svg#invert]]
Ans:
If $W_{1}$ moves down in distance $d$, $W_{2}$ is lifted up $\frac{d}{\overline{AP}}\overline{PB}=2d$. Thus, by the principle of virtual work, $W_{1}(-d)+W_{2}2d=0$, and $W_{2}=\frac{1}{2}W_{1}=0.25\: \text{kg-wt}$.

## 2.8
**The system shown in Figure is in static equilibrium. Use the principle of virtual work to find the weights $A$ and $B$. Neglect the weight of the strings and the friction in the pulleys.**
![[templates/Fig.2-6.svg#invert]]Ans:
`Solution I: using forces`
By analyzing the free-body diagram, $1g\cos 30^{\circ}=B\cos 45^{\circ}$. Hence, $B=\sqrt{ \frac{3}{2} }\: \text{kg-wt}$. And $A=1g\sin 30^{\circ}+B\sin 45^{\circ}=\frac{1}{2}(1+\sqrt{ 3 })\: \text{kg-wt}$.

`Solution II: using virtual work`
Let's say the tension of the lines connected to the $1 \: \text{kg}$ block and $B$ is $T_{1}$ and $T_{B}$, respectively. $T_{1}$ is equal to $1g$ and $T_{2}$ is equal to $B$. Assume that $A$ moves down in small distance $d$, the $1 \: \text{kg}$ block and $B$ move up $d_{1}$ and $d_{B}$, respectively. By principle of virtual work, 
$$
\begin{align} 
&&1gd_{1} -T_{1} d_{1}+Bd_{2}-T_{2}d_{2}+T_{1}\sin 30^{\circ}d+T_{2}\sin 45^{\circ}d-Ad&=0 \\

&\Rightarrow&(1gd_{1} -T_{1} d_{1}+Bd_{2}-T_{2}d_{2})+T_{1}\sin 30^{\circ}d+T_{2}\sin 45^{\circ}d-Ad &=0 \\
&\Rightarrow&T_{1}\sin 30^{\circ}d+T_{2}\sin 45^{\circ}d-Ad&=0 \\ 

&\Rightarrow&0+1g\times \frac{d}{2}+B\times \frac{d}{\sqrt{ 2 }}-Ad&=0
\end{align}
$$
Therefore, $A=\frac{1}{2}+\frac{\sqrt{ 3 }}{2}=\frac{1}{2}(1+\sqrt{ 3 })\: \text{kg-wt}$.

## 2.9
**A weight $W=50\: \text{lb}$ is suspended from the midpoint of a wire $ACB$ as shown in Figure. $AC=CB=5\: \text{ft}$. $AB=5\sqrt{ 2 }\: \text{ft}$. Find the tension $T_{1}$ and $T_{2}$ in the wire.**

![[templates/Fig.2-7.svg#invert]]
Ans:
By the principle of virtual work, $Wd=T_{1}\times \frac{d}{\sqrt{ 2 }}+T_{2}\times \frac{d}{\sqrt{ 2 }}$. In addition, $T_{1}=T_{2}$. Hence $T_{1}=T_{2}=\frac{W}{\sqrt{ 2 }}=\frac{50}{\sqrt{ 2 }} \: \text{lb}$.

## 2.10
**The truss shown in Figure is made of light aluminum struts pivoted at each end. At $C$ is a roller which rolls on a smooth plate. When a workman heats up member $AB$ with a welding torch, it is observed to increase in length by an amount $x$, and the load $W$ is thereby moved vertically an amount $y$.**
![[templates/Fig.2-8.svg#invert]]
1. **Is the motion of W upward or downward?**
2. **What is the force $F$ in the member $AB$ (including the sense, i.e., tension or compression)?**
Ans:
1. Downward.
2. By the principle of virtual work, $F\times x=W\times y$, that is, $F=\frac{y}{x}W$.

## 2.11
**What horizontal force $F$ (applied at the axle) is required to push a wheel of weight $W$ and radius $R$ over a block of height $h$, as shown in Figure?**
![[templates/Fig.2-9.svg#invert]]
Ans:
The magnitude of the horizontal force $F$ must at least be as strong as when the object is in static equilibrium with only force of gravity and the horizontal force $F$ acting on the wheel. 
![[templates/Fig.2-9sol.svg#invert]]
When the wheel moves in a small path $s$, $s_{x}=s\cos \phi$ and $s_{y}=s\sin \phi$. Hence by the principle of virtual work,
$$
\begin{align}
Fs_{x}-Ws_{y}&=0 \\
Fs\cos \phi-Ws\sin \phi&=0
\end{align}
$$
And therefore,
$$
\begin{align}
F&=W\tan \phi \\
&=\frac{\sqrt{ R^{2}-(R-h)^{2} }}{R-h}W \\
&=\frac{\sqrt{ 2Rh-h^{2} }}{R-h}W \\
&=\frac{\sqrt{ h(2R-h) }}{R-h}W
\end{align}
$$

## 2.12
**A horizontal turntable of diameter $D$ is mounted on bearings with negligible friction. Two horizontal forces in the plane of the turntable of equal magnitude $F$, parallel to each other but pointing in opposite directions, act on the rim of the turntable on opposite ends of the diameter, as shown in Figure.**
![[templates/Fig.2-10.svg#invert]]
1. **What force $F_{B}$ acts on the bearing?**
2. **What is the torque (= moment of the force couple) $\tau_{O}$ about a vertical axis through the center $O$?**
3. **What would be the moment $\tau_{P}$ about a vertical axis through an arbitrary point $P$ in the same plane?**
4. **Is the following statement correct or false? Explain. "*Any two forces acting on a body can be combined into a single resultant force that would have the same effect.*" In framing your answer, consider the case where the two forces are opposite in direction but not quite equal in magnitude.**

Ans:
1. No force except gravity acts on the bearing. So $F_{B}=0$.
2. The torque is $\tau_{O}=\frac{D}{2}F+\frac{D}{2}F=DF$.
3. Assume that $O$ is the origin $\left\langle  0, 0\right\rangle$ for a two dimensional plane, then the points where the two Force is acting on are at $\left\langle  \frac{D}{2},0 \right\rangle$ and $\left\langle  -\frac{D}{2},0 \right\rangle$, and the vector representation of the two forces are $\left\langle  0, -F\right\rangle$ and $\left\langle  0, F\right\rangle$. For an arbitrary point $P=(x, y)$, the torque is $$\begin{align}
\tau_{P}&=\left\langle  \frac{D}{2}-x,0-y \right\rangle \times \left\langle  0, -F \right\rangle +\left\langle  -\frac{D}{2}-x,0-y \right\rangle \times \left\langle  0, F \right\rangle &\\ &=\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\\frac{D}{2}-x & -y & 0 \\0 & -F & 0\end{vmatrix}+\begin{vmatrix}\hat{i} & \hat{j} & \hat{k} \\-\frac{D}{2}-x & -y & 0 \\0 & F & 0\end{vmatrix}\\&=\left( \frac{D}{2}-x \right)(-F)\hat{k} \:+\:\left( -\frac{D}{2}-x \right)F\hat{k} \\&=-DF\hat{k}\end{align}$$Therefore, the magnitude of $\tau_{P}$ is $DF$ as well.
4. No, as the figure shows above, if we combine the two forces into a single resultant force, that would produce a force that has the magnitude zero, which can not describe the torque despite the fact that we already know that there is torque $\tau=DF$

## 2.13
**A flat steel plate floating on mercury is acted upon by three forces at three corners of a square of side $0.100\: \text{m}$, as shown in Figure. Find a *single* fourth force $F$ which will hold the plate in equilibrium. Give the magnitude, direction, and point of application of $F$ along the line $AB$.**
![[templates/Fig.2-11.svg#invert]]
Ans:
Set $O$ to be the origin $\langle 0, 0\rangle$. Assume that the plate moves toward a direction in a distance $\vec{r}=\langle x,y \rangle$. Suppose that the forth force is $F= \langle F_{x}, F_{y}\rangle$. By the principle of virtual work,
$$
\left( 50-\frac{50}{\sqrt{ 2 }}+F_{x} \right)x+\left( 50-\frac{50}{\sqrt{ 2 }}+F_{y} \right)y=0
$$
If the plate moves only along the $x$-axis or $y$-axis, the two equations should hold as well.
Hence,
$$
\begin{align}
\left( 50-\frac{50}{\sqrt{ 2 }}+F_{x} \right)x&=0 \\
\left( 50-\frac{50}{\sqrt{ 2 }}+F_{y} \right)y&=0
\end{align}
$$
$F_{x}=50\left( \frac{1}{\sqrt{ 2 }}-1 \right)$ and $F_{y}=50\left( \frac{1}{\sqrt{ 2 }}-1 \right)$, and the magnitude of $F$ is
$$
\begin{align}
F&=\sqrt{ F_{x}^{2}+F_{y}^{2} } \\
&=\sqrt{ \left( 50\left( \frac{1}{\sqrt{ 2 }}-1 \right) \right)^{2}+ \left( 50\left( \frac{1}{\sqrt{ 2 }}-1 \right) \right)^{2}} \\
&=\sqrt{ 2 }\times \lvert 50\left( \frac{1}{\sqrt{ 2 }}-1 \right) \rvert  \\
&\approx 20.7\: \text{N}
\end{align}
$$
And the direction is as same as $\langle -1,-1\rangle$.
`Point of application solution I: using torques`
Set $P$ to be the fulcrum. and $F$ is acting at $\langle x_{F},y_{F} \rangle$. The torque should be zero, that is,
$$
\begin{align}
\tau&=\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
0 & -\overline{OP} & 0 \\
-\frac{50}{\sqrt{ 2 }} & -\frac{50}{\sqrt{ 2 }} & 0
\end{vmatrix}+\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
x_{F} & y_{F}-\overline{OP} & 0 \\
F_{x} & F_{y} & 0
\end{vmatrix} \\

&=-\frac{50}{\sqrt{ 2 }}\overline{OP}\hat{k}+x_{F}F_{y}\hat{k}-F_{x}(y_{F}-\overline{OP})\hat{k}=0
\end{align}
$$
Plug in the values of $F_{x}$ and $F_{y}$ into the equation above, we have
$$
\begin{align}
&&-\frac{50}{\sqrt{ 2 }}\overline{OP}\hat{k}+x_{F}50\left( \frac{1}{\sqrt{ 2 }}-1 \right)\hat{k}-50\left( \frac{1}{\sqrt{ 2 }}-1 \right)(y_{F}-\overline{OP})\hat{k}&=0 \\

&\Rightarrow &-\frac{50}{\sqrt{ 2 }}\overline{OP}+\frac{50}{\sqrt{ 2 }}x_{F}-50x_{F}-\frac{50}{\sqrt{ 2 }}y_{F}+\frac{50}{\sqrt{ 2 }}\overline{O{P}}+50y_{F}-50\overline{OP}&=0 \\

&\Rightarrow&50\left( \frac{1}{\sqrt{ 2 }}-1 \right)x_{F}-50\left( \frac{1}{\sqrt{ 2 }}-1 \right)y_{F}-50\overline{OP}&=0
\end{align}
$$
Since we are looking at $F$ that is applied along $\overline{AB}$, $y_{F}=0$. So 
$$
50\left( \frac{1}{\sqrt{ 2 }}-1 \right)x_{F}-50\overline{OP}=0
$$
and
$$

$$

$$
\begin{align}
x_{F}&=\frac{\overline{OP}}{\left( \frac{1}{\sqrt{ 2 }}-1 \right)} \\

&=\frac{0.100}{\left( \frac{1}{\sqrt{ 2 }}-1 \right)} \\

&\approx-0.341\: \text{m}
\end{align}
$$
Therefore, the force $F$ is applied $0.34\: \text{m}$ left of the point $O$.

`Point of application solution II: using virtual work`
Set $O$ to be the fulcrum, if the plate rotates in a small angle $\phi$, then, by the principle of virtual work,
$$

\begin{align}
&&\overline{OP}\sqrt{ 2 }\phi \cos 45^{\circ}\times 50\: \text{N} + \frac{F_{x}-\frac{x_{F}}{y_{F}}F_{y}}{\left( \sqrt{ 1^{2}+\frac{x_{F}^{2}}{y_{F}^{2}} } \right)^{2}}\sqrt{ \langle 1,\frac{{-x_{F}}}{y_{F}}\rangle }\times \sqrt{ x_{F}^{2}+y_{F}^{2} }\phi&=0 \\

&\Rightarrow& \overline{OP}\sqrt{ 2 }\phi\cos 45^{\circ}\times 50\: \text{N} +(F_{x}y_{F}-F_{y}x_{F})\phi&=0 \\

&\Rightarrow& 50\left( \frac{1}{\sqrt{ 2 }}-1 \right)x_{F}-50\left( \frac{1}{\sqrt{ 2 }}-1 \right)y_{F}-50\overline{OP}&=0
\end{align}
$$

Since we are looking at $F$ that is applied along $\overline{AB}$, $y_{F}=0$. So 
$$
50\left( \frac{1}{\sqrt{ 2 }}-1 \right)x_{F}-50 \overline{OP}=0
$$
and
$$

$$

$$
\begin{align}
x_{F}&=\frac{\overline{OP}}{\left( \frac{1}{\sqrt{ 2 }}-1 \right)} \\

&=\frac{0.100}{\left( \frac{1}{\sqrt{ 2 }}-1 \right)} \\

&\approx-0.341\: \text{m}
\end{align}
$$
Therefore, the force $F$ is applied $0.34\: \text{m}$ left of the point $O$.

## 2.14
**In the absence of friction, at what speed $v$ will the weights $W_{1}$ and $W_{2}$ in Figure be moving when they have traveled a distance $D$, starting from rest? ($W_{1}>W_{2}$).**
![[templates/Fig.2-12.svg#invert]]
Ans:
By the conservation of energy, the change of energy is equal to zero. Hence,
$$
W_{1}(-D)\sin \theta + W_{2}D\sin \theta+\frac{W_{1}v^{2}}{2g}+\frac{W_{2}v^{2}}{2g}=0
$$
and
$$
\begin{align}
&&v^{2}&=2\frac{(W_{1}-W_{2})D\sin \theta}{W_{2}+W_{1}}g \\
&\Rightarrow&v&=\sqrt{ 2gD\frac{(W_{1}-W_{2})}{W_{1}+W_{2}} \sin \theta}
\end{align}
$$
## 2.15 
**In Figure, the weights are equal, and there is negligible friction. If the system is released from rest, at what speed $v$ will the weights be moving when they have traveled a distance $D$?**
![[templates/Fig.2-13.svg#invert]]
Ans:
By the conservation of energy,
$$
WD\sin \theta-WD\sin \phi+\frac{2Wv^{2}}{2g}=0
$$
Therefore,
$$
\begin{align}
v^{2}&=\frac{D(\sin \phi-\sin \theta)}{1 / g} \\
v&=\sqrt{ Dg(\sin \phi-\sin \theta) }
\end{align}
$$

## 2.16 
**A mass $M_{1}$ slides on a $45^{\circ}$ inclined plane of height $H$ as shown in Figure. It is connected by a flexible cord of negligible mass over a small pulley (neglect its mass) to an equal mass $M_{2}$ hanging vertically as shown. The length of the cord is such that the masses can be held at rest both at height $\frac{H}{2}$. The dimensions of the masses and the pulley are negligible compared to $H$. At time $t=0$ the two masses are released.**
![[templates/Fig.2-14.svg#invert]]
1. **For $t>0$ calculate the vertical acceleration $a$ of $M_{2}$.**
2. **Which mass will move down?**
3. **At what time $t_{1}$ will the mass identified in part 2. strike the ground**
4. **If the mass identified in part 2. stops when it hits the ground, but the other mass keeps moving, will it strike the pulley?**

Ans:
1. The cord has a tension force which acted both on $M_{1}$ and $M_{2}$.  $M_{1}$ and $M_{2}$ have the same magnitude of acceleration. We can simply draw the free body diagram and calculate$$\begin{align}&\left\{\begin{split}-M_{1}g\cos 45^{\circ}+T&=M_{1}a  \\-M_{2}g+T&=-M_{2}a\end{split}\right. \\ &\left\{\begin{split}-Mg\cos 45^{\circ}+T&=Ma  \\-Mg+T&=-Ma\end{split}\right. \\ \\\Rightarrow& \:Mg(1-\cos 45^{\circ})=2Ma \\ \Rightarrow&\:a=\frac{1}{2}\left( 1-\frac{1}{\sqrt{ 2 }} \right)g\end{align}$$
2. $M_{2}$ will move down.
3. We know that $v=\int a\:\mathrm{d}t=at+C$. Plug in $t=0$ we have $C$ is the initial velocity for $v$. So $v=v_{0}+at$. Similarly, $s=\int v\:\mathrm{dt}=\int v_{0}+at\:\mathrm{d}t=v_{0}t+\frac{1}{2}at^{2}+D$. Plug in $t=0$, we have $D$ equals the initial position. So $s=s_{0}+v_{0}t+\frac{1}{2}at^{2}$. Hence,$$\begin{align}
&&-\frac{H}{2}&=0+0t_{1}-\frac{1}{2}at_{1}^{2} \\
&\Rightarrow& t_{1}&=\sqrt{ \frac{H}{a} }
\end{align}$$
4. By the formula above, when $M_{2}$ strikes, it has the speed $v=0+at_{1}=\sqrt{ aH }$, and so does $M_{1}$. By the conservation of energy, the total energy of $M_{1}$ remains constant. And it could move up until all the kinetic energy of $M_{1}$ changes into the gravitational potential energy, that is, $$
\frac{1}{2}M_{1}v^{2}=M_{1}gh
$$So we get$$\begin{align}
h&=\frac{aH}{2g} \\
&=\frac{\frac{1}{2}\left( 1-\frac{1}{\sqrt{ 2 }} \right)}{g}\times \frac{H}{2} \\
\end{align}$$$M_{1}$ will move up to$$\begin{align}
&&\frac{H}{2}\sin 45^{\circ}+\frac{\frac{1}{2}\left( 1-\frac{1}{\sqrt{ 2 }} \right)}{g} \frac{H}{2} \\
&=&\left(\frac{1}{\sqrt{ 2 }}+\frac{1-\frac{1}{\sqrt{ 2 }}}{2g}\right)\frac{H}{2}
 \\
&\approx& 0.72\times\frac{H}{2}< \frac{H}{2}
\end{align}$$Therefore, $M_{1}$ will not strike the pully.

## 2.17
**A derrick is made of a uniform boom of length $L$ and weight $w$, pivoted at its lower end, as shown in Figure. It is supported at an angle $\theta$ with the vertical by a horizontal cable attached at a point a distance $x$ from the pivot, and a weight $W$ is slung from its upper end. Find the tension $T$ in the horizontal cable.**
![[templates/Fig.2-15.svg#invert]]
Ans:
When $\theta$ changes in a small angle $\Delta\theta$, the change in distance of the cable is $\Delta S=\frac{x\times x\cos \theta}{x\sin \theta}\sin \theta \Delta \theta$ (See problem 2.4.1). The center of mass of the derrick moves $\frac{2}{L}\Delta \theta \sin \theta$ in the vertical direction and $W$ moves $L\Delta \theta \sin \theta$. Hence, by the principle of virtual work,
$$
\begin{align}
&&&-T \times\frac{x\times x\cos \theta}{x\sin \theta}\sin \theta \Delta \theta+w\times \frac{L}{2}\Delta \theta \sin \theta+W\times L\Delta \theta \sin \theta=0 \\ 
&\Rightarrow& &T=\frac{L\left( \frac{w}{2}+W \right)}{x}\tan \theta=\frac{L}{x}\left( \frac{w}{2}+W \right)\tan \theta
\end{align}
$$

## 2.18 
**A uniform ladder $10\: \text{ft}$ long with rollers at the top end leans against a smooth vertical wall, as shown in Figure. The ladder weighs $30\: \text{lb}$. A weight $W=60\: \text{lb}$ is hung from a rung $2.5\: \text{ft}$ from the top end. Find**
![[templates/Fig.2-16.svg#invert]]
1. **the force $F_{R}$ with which the rollers push on the wall.**
2. **the horizontal and vertical forces $F_{h}$ and $F_{v}$ with which the ladder pushes on the ground.**

Ans:
1. We set the bottom end of the ladder be the pivot. If the ladder rotates in a small angle $\Delta\phi$, then the rollers move $10\Delta \phi \times \frac{8}{10}$ horizontally, $W$ and the center of mass of the ladder move $7.5\Delta \phi \times \frac{6}{10}$ and $5\Delta \phi \times \frac{6}{10}$,vertically, respectively. By the principle of virtual work, $$F_{R}\times 10\Delta \phi \times \frac{8}{10}-W\times 7.5\Delta \phi \times \frac{6}{10}-w\times 5\Delta \phi \times \frac{6}{10}=0$$where $w$ is the weight of the ladder. Plug in the values of each variable, we have $F_{R}=45\: \text{lb-wt}$.
2. Since the system is static equilibrium, it is easy to see that $F_{h}=F_{R}=45\: \text{lb-wt}$ and $F_{v}=W+w=90\: \text{lb-wt}$.

## 2.19 
**A plank of weight $W$ and length $\sqrt{ 3 }R$ lies in a smooth circular trough of radius $R$, as shown in Figure. At one end of the plank is a weight $\frac{W}{2}$. Calculate the angle $\theta$ which the plank lies when it is in equilibrium.**
![[templates/Fig.2-17.svg#invert]]
Ans:
Analyzing the figure, we have 
![[templates/Fig.2-17sol.svg#invert]]
If the plank rotates along the smooth surface so that the one end walks in distance $s$, the angle of $120^{\circ}$ changes in $\frac{s}{R}$, and the center of mass of the plank walks in distance $\frac{R}{2}\times \frac{s}{R}=\frac{s}{2}$. The center of mass of the plank and the one end move $\frac{s}{2}\times \sin \theta$ and $s\times \cos(30^{\circ}+\theta)$ vertically, respectively. Therefore, by the principle of virtual work,
$$
\begin{align}
&&\frac{W}{2} \times s\cos(30^{\circ} +\theta)-W\times \frac{s}{2}\sin \theta&=0 \\
&\Rightarrow& \cos 30^{\circ}\cos \theta-\sin 30^{\circ}\sin \theta-\sin \theta&=0 \\
&\Rightarrow& \frac{\sqrt{ 3 }}{2}\cos \theta-\left( \frac{1}{2}+1 \right)\sin \theta&=0 \\
&\Rightarrow& \tan \theta=\frac{\frac{\sqrt{ 3 }}{2}}{\frac{1}{2}+1} &=\frac{1}{\sqrt{ 3 }} \\
&\Rightarrow& \theta&=30^{\circ}
\end{align}
$$


## 2.20
**A uniform bar of length $l$ and weight $W$ is supported at its ends by two inclined planes as shown in Figure. From the principle of virtual work find the angle $\alpha$ at which the bar is in equilibrium. (Neglect friction.)**
![[templates/Fig.2-18.svg#invert]]
Ans:
Let the forces that the two inclined planes give the bar be $F_{R}$ and $F_{L}$ correspond to the left plane and right plane. If the bar slides up along the left inclined plane in a small distance $s$, by the principle of virtual work,
$$
\begin{align}
&&-Ws\sin 60^{\circ}+F_{R}s&=0 \\
&\Rightarrow& F_{R}&=\frac{\sqrt{ 3 }}{2}W
\end{align}
$$
Similarly, $F_{L}=\frac{1}{2}W$.
If $\alpha$ changes in a small angle $\Delta \alpha$, the bottom end of the bar walks along the circle with center at the top of bar and radius $l$ in distance $l\Delta \alpha$, and the center of mass of the bar walks along the circle with the same center but radius $\frac{l}{2}$ in distance $\frac{l}{2}\Delta \alpha$. 
![[templates/Fig.2-18sol.svg#invert]]
By the principle of virtual work,
$$
\begin{align}
&&-W \frac{l}{2}\Delta \alpha\cos(60^{\circ}-\alpha)+F_{R}\cos 30^{\circ}l\Delta \alpha \cos(60^{\circ}-\alpha)& \\
&&-F_{R}\sin 30^{\circ}l\Delta \alpha \sin(60^{\circ}-\alpha)&=0 \\
 \\
&\Rightarrow& - \frac{1}{2}+\frac{3}{4}-\frac{\sqrt{ 3 }}{4}\tan(60^{\circ}-\alpha)&=0
\end{align}
$$
Therefore, $\tan (60^{\circ}-\alpha)=\frac{1}{\sqrt{ 3 }}$. This implies that $\alpha=30^{\circ}$.

## 2.21
**A small solid sphere of radius $4.5\: \text{cm}$ and weight $W$, is to be suspended by a string from the ends of a smooth hemispherical bowl of radius $49\: \text{cm}$, as shown in Figure. It is found that if the string is any shorter than $40\: \text{cm}$, it breaks. Use the principle of virtual work to find the breaking strength $F$ of the string.**
![[templates/Fig.2-19.svg#invert]]
Ans:
It is easy to see that the triangle drawn below is an isosceles triangle.
Let $r$ and $R$ be the radii of the solid sphere and of the bowl, respectively, $l$ be the length of the string when $l=40\: \text{cm}$, $N$ be the force that the bowl gives to the ball. And let $\phi$ be the angle in the following figure. We can calculate $\cos \phi=\frac{R^{2}+(R-r)^{2}-(l+r)^{2}}{2R(R-r)}$. 
![[templates/Fig.2-19sol.svg#invert]]
`solution I: force`
$N$ could be compute via analyzing the free-body diagram.
$$
\begin{align}
N\cos \phi&=F\cos \phi \\
N\sin \phi+F\sin \phi&=W
\end{align}
$$
So $N=F$ and $F=W \frac{\csc \phi}{2}\approx 0.6W$

`solution II: virtual work`
Assume that the ball moves along the bowl in a small distance $\Delta s$, then the ball will move upward in distance $\Delta s\cos \phi$.
The component of $F$ along the path that the ball moves is $F\cos(2\phi-90^{\circ})=F\sin 2\phi$.
By the principle of virtual work,
$$
\begin{align}
&&F(\sin 2\phi) \Delta s-W\Delta s\cos \phi&=0 \\
&\Rightarrow& -F(2\sin \phi \cos\phi) \Delta s+-W\cos \phi \Delta s&=0
\end{align}
$$
We have
$$
\begin{align} \\
F&=\frac{\cos \phi}{2\sin \phi \cos \phi}W \\
&=\frac{\csc \phi}{2}W
 \\
&\approx 0.6 W
\end{align}
$$

## 2.22
**An ornament for a courtyard at a World's Fair is to be made up of four identical, frictionless metal spheres, each weighing $2\sqrt{ 6 }\: \text{ton-wt}$. The spheres are to be arranged as shown in Figure, with three resting on a horizontal surface and touching each other; the fourth is to rest freely on the other three. The bottom three are kept from separating by spot welds at the points of contact with each other. Allowing for a factor of safety of $3$, how much tension $T$ must the spot welds withstand?**
![[templates/Fig.2-20.svg#invert]]
Ans:
Assume that the top ball moves down in a small distance $\Delta s$, the ball will move apart from each other in a distance $\Delta s\tan \theta \cos 30^{\circ}$ where $\cos \theta=\frac{1}{3}$(regular tetrahedron).
![[templates/Fig.2-20sol.svg#invert]]
Hence, by the principle of virtual work,
$$
\begin{align}
&&W\Delta s-3T\Delta s\tan \theta \cos 30^{\circ}&=0 \\
&\Rightarrow&W-3\times 3\text{}T\times 2\sqrt{ 2 }\times \frac{\sqrt{ 3 }}{2}&=0 \\
&\Rightarrow&W-3\sqrt{ 6 }T=0
\end{align}
$$
and $T=\frac{W}{3\sqrt{ 6 }}=\frac{2\sqrt{ 6 }}{3\sqrt{ 6 }}=\frac{2}{3}\: \text{ton-wt}$.
Allowing a factor of three, the welds withstand $2\: \text{ton-wt}$.

## 2.23
**A rigid wire frame is formed in a right triangle, and set in a vertical plane as shown in Figure. Two beads of masses $m_{1}=100\: \text{g}$, $m_{2}=300\: \text{g}$ slide without friction on the wires, and are connected by a cord. When the system is in static equilibrium, what is the tension $T$ in the cord, and what angle $\alpha$ does it make with the first wire?**
![[templates/Fig.2-21.svg#invert]]
Ans:
Set the length of the triangle with the angle $\alpha$ to be $a$, $b$, and $c$, where $a$ is the adjacent for $\alpha$, $b$ the opposite and $c$ the hypotenuse. By problem 2.4.2, $c\Delta c=a\Delta a+b\Delta b$. Assume that $m_{1}$ along the slide down in a small distance $\Delta a$, and that the length of the wire is a constant($\Delta b=-\frac{a}{b}\Delta a$). Applying virtual work, we have
$$
\begin{align}
&&m_{1}g\Delta a\sin 30^{\circ}-m_{2}g\Delta b\sin 60^{\circ}-T\cos \alpha \Delta a+T\sin \alpha \Delta b&=0 \\
&\Rightarrow& m_{1}g \frac{1}{2}-m_{2}g \left( -\frac{a}{b} \right) \frac{\sqrt{ 3 }}{2}-T\left( \cos \alpha-\sin \alpha\left( -\frac{a}{b} \right) \right)&=0 \\
&\Rightarrow& \frac{1}{2} m_{1}g + \frac{\sqrt{ 3 }}{2}m_{2}g\cot \alpha-T(\cos \alpha+\cos \alpha)&=0 \\
&\Rightarrow& \frac{1}{2}m_{1}g+\frac{\sqrt{ 3 }}{2}m_{2}g\cot \alpha-2T\cos \alpha&=0\dots(1)
\end{align}
$$
If $m_{2}$ slides up in a small distance $\Delta b$. By the principle of virtual work,
$$
T\sin \alpha \Delta b=m_{2}g\Delta b\sin 60^{\circ}
$$
So $T\sin \alpha=\frac{\sqrt{ 3 }}{2}m_{2}g \dots(2)$.
By $(1)$ and $(2)$, 
$$
\begin{align}
&& &\left\{
\begin{split}
4T\cos \alpha&=m_{1}g+ \sqrt{ 3 }m_{2}g\cot \alpha \\
T\sin \alpha&=\frac{\sqrt{ 3 }}{2}m_{2}g
\end{split}
\right. \\
&\Rightarrow&
&4\cot \alpha= \frac{2}{\sqrt{ 3 }} \frac{m_{1}}{m_{2}}+2\cot \alpha \\
&\Rightarrow& &\cot \alpha=\frac{\frac{2}{\sqrt{ 3 }} \frac{m_{1}}{m_{2}}}2=\frac{1}{\sqrt{ 3 }}\frac{m_{1}}{m_{2}}
\end{align}
$$
So we have $\cot \alpha=\frac{1}{3\sqrt{ 3 }}$, and $\alpha \approx 79.1^{\circ}$.
Plug in the value of $\alpha$ in $(2)$, we have $T=\sqrt{ 1+\cot^{2} \alpha } \frac{\sqrt{ 3 }}{2}m_{2}g\approx 265\: \text{g-wt}$.

## 2.24
**Find the tension $T$ needed to hold the cart shown in Figure in equilibrium, if there is no friction.**
1. **Using the principle of virtual work.**
2. **Using force components.**
![[templates/Fig.2-22.svg#invert]]

Ans:
1. Let $N$ denote the force that the cart gives to $W$. Assume that $W$ moves along the circle with circle at the end of the cord which holds $W$ and radius equals the length of the cord in a small distance $\Delta s$.![[templates/Fig.2-22sol.svg#invert]]Then $W$ will move up $\Delta s\cos \phi$.  Here $\phi=30^{\circ}$. By the principle of virtual work, $$-W\Delta s\cos \phi+N\Delta s=0$$
   So $N=W\cos \phi$. 
   If the cart move forward in a small distance $\Delta x$, then, by the principle of virtual,$$T\Delta x-N\sin 30^{\circ}\Delta s=0$$
   Therefore, $T=W\cos 30^{\circ}\sin 30^{\circ}=\frac{\sqrt{ 3 }}{4}W$.

2. By analyzing the free-body diagram, ![[templates/Fig.2-22sol1.svg#invert]]
   $W\cos 30^{\circ}\sin 30^{\circ}=T$. And therefore, $T=\frac{\sqrt{ 3 }}{4}W$.
## 2.25
**A bobbin of mass $M=3\: \text{kg}$ consists of a central cylinder of radius $r=5\: \text{cm}$ and two end plates of radius $R=6\: \text{cm}$. It is placed on a slotted incline on which it will roll but not slip, and a mass $m=4.5\: \text{kg}$ is suspended from a cord wound around the bobbin, as shown in Figure. It is observed that the system is in static equilibrium. What is the angle of tilt of tilt $\theta$ the incline?**
![[templates/Fig.2-23.svg#invert]]
Ans:
Assume that the string that holds $m$ is lengthened in a small distance $\Delta s$ vertically, then the bobbin will rotate in an angle $\frac{\Delta s}{r}$. And the bobbin will move along the incline in distance $-R\frac{\Delta s}{r}$. So $m$ will move in distance $\Delta s - R \frac{\Delta s}{r}\sin \theta$ and $M$ will move $-R \frac{\Delta s}{r}\sin \theta$. By the principle of virtual work,
$$
\begin{align}
&&mg\left( \Delta s-R \frac{\Delta s}{r}\sin \theta \right)+Mg\left( -R \frac{\Delta s}{r}\sin \theta \right)&=0 \\
&\Rightarrow& mr-(m+M)R\sin \theta&=0
\end{align}
$$
Hence, $\sin \theta=\frac{mr}{R(m+M)}= \frac{4.5\times 5}{6\times (4.5+3)}=0.5$, and $\theta=30^{\circ}$

## 2.26
**A loop of flexible chain, of total weight $W$, rests on a smooth right circular cone of base radius $r$ and height $h$, as shown in Figure. The chain rests in a horizontal circle on the cone, whose axis is vertical. Find the tension $T$ in the chain. Neglect friction.**
![[templates/Fig.2-24.svg#invert]]
Ans:
Assume that the chain moves down in a small distance $\Delta x$, then the chain would be stretched $2\pi \Delta x\tan \theta$ where $\tan \theta=\frac{r}{h}$. By the principle of virtual work,
$$
\begin{align}
&&W\Delta x-T 2\pi \Delta x\tan \theta&=0 \\
&\Rightarrow&W-2\pi  \frac{r}{h}T=0
\end{align}
$$
Therefore, $T=\frac{1}{2\pi}\frac{h}{r}W$.

## 2.27
**A cart on an inclined plane is balanced by the weight $w$ as shown in Figure. All parts have negligible friction. Find the weight $W$ of the cart.**
![[templates/Fig.2-25.svg#invert]]
Ans:
When $W$ moves along the inclined plane in a distance $\Delta s$, *string 1* will change in $2\Delta s$. *string 2* will change in twice *string 1*.
![[templates/Fig.2-25sol.svg#invert]]
By the principle of virtual work,

$$
W\Delta s\sin \theta-w 4\Delta s=0
$$
Therefore, $W=4\csc \theta w$.

## 2.28
**A bridge truss is constructed as shown in Figure. All joints may be considered frictionless pivots and all members rigid, weightless, and of equal length. Find the reaction forces $F_{1}$ and $F_{2}$ and the force $F_{DF}$ in the member $DF$.**
![[templates/Fig.2-26.svg#invert]]
Ans:
Set $E$ to be a fulcrum. Since $\sum\limits_{}^{}\vec{\tau}=0$, $2F_{1}=F_{2}$. In addition, $F_{1}+F_{2}=W$. Hence, $F_{1}=\frac{1}{3}W$ and $F_{2}=\frac{2}{3}W$.
![[templates/Fig.2-26sol.svg#invert]]
Assume that $\overline{DF}$ is stretched in a distance $\Delta s$, by problem 2.4.1, $\Delta s=\frac{l^{2}}{l}\sin \theta \Delta \theta=l\sin \theta \Delta \theta$ where $l$ is the length of the triangles. $\phi=360^{\circ}-2\times 60^{\circ}-\theta=240^{\circ}-\theta$, and $\Delta \phi=-\Delta \theta$. Here, $\theta=60^{\circ}$. If $W$ is lifted up $\Delta y$, then
$$
\frac{1}{2}2l\times l\sin \phi=\frac{1}{2}3l\times y
$$
(Left hand side of the equation is the formula for finding the area of a triangle using sine, and right hand side is the area formula for a triangle).
So
$$
l^{2}\cos \phi \Delta \phi=\frac{3}{2}l\Delta y
$$
Thus, $\Delta y=\frac{2}{3}l\cos \phi \Delta \phi$

By the principle of virtual work,
$$
\begin{align}
&&-F_{DF}\Delta s+W\Delta y&=0 \\
&\Rightarrow&-F_{DF}\Delta s+W\times \frac{2}{3}l\cos \phi \Delta \phi&=0 \\
&\Rightarrow&-F_{DF}\Delta s-\frac{2}{3}Wl\cos(240^{\circ}-\theta)\Delta \theta&=0 \\
&\Rightarrow&-F_{DF}\Delta s-\frac{2}{3}Wl\cos(240^{\circ}-\theta)\times \frac{1}{l}\csc \theta \Delta s&=0 \\
&\Rightarrow&-F_{DF}-\frac{2}{3}W\cos 180^{\circ}\csc 60 ^{\circ}&=0
\end{align}
$$
Consequently, we have
$$
\begin{align}
F_{DF}=\frac{2}{3}W\times 1 \times \frac{2}{\sqrt{ 3 }} \\
=\frac{4}{3\sqrt{ 3 }}W
\end{align}
$$

## 2.29
**In the truss shown in Figure, all diagonal struts are of length $5$ units and all horizontal ones are of length $6$ units. All joints are freely hinged, and the weight of the truss is negligible.**
![[templates/Fig.2-27.svg#invert]]
1. **Which of the members could be replaced with flexible cables, for the load position shown?**
2. **Find the forces in struts $BD$ and $DE$.**

Ans:
1. I don't know.
2. Similar as problem 2.28. $\Delta BD=\frac{5\times 5}{6}\sin \theta \Delta \theta$ where $\sin \frac{\theta}{2}=\frac{3}{5}$. So $\Delta BD=\frac{25}{6}\times2\times \frac{3}{5} \times \frac{4}{5}\Delta \theta=4\Delta \theta$. $\Delta y_{C}=-\frac{2}{3}\times 6\cos(2\pi-2\angle ACB-\theta)\Delta \theta$ (from problem 2.30).$$\begin{align}
\Delta y_{C}&=-4\cos(2\angle ACB+\theta)\Delta \theta \\
&=-4\cos(\pi)\Delta \theta \\
&=\Delta BD
		\end{align}$$And$\Delta y_{E}=\frac{1}{2}\Delta y_{C}$. Hence, by the principle of virtual work,$$-F_{BD}\Delta BD+W \frac{1}{2}\Delta BD=0$$This implies that $F_{BD}=\frac{1}{2}W$. For $F_{DE}$, by the problem 2.4.1, $$\Delta DE=\frac{6\times 5}{5}\times \frac{4}{5}\Delta (\angle DFE)=\frac{24}{5}\Delta(\angle DFE)$$![[templates/Fig.2-27sol 1.svg#invert]]If we want $\overline{DF}$ remain horizontal, then $\triangle FEG$ need to be rotated in an angle $-\Delta(\angle DFE)$ with point $G$ fixed. Similarly, $\triangle BDC$ is rotated $-\Delta(\angle DFE)$ with point $C$ fixed. Therefore, $A$ will be lifted up in distance $18(-\Delta(\angle DFE))+6\Delta(-\Delta(\angle DFE))$.![[templates/Fig.2-27sol3.svg#invert]]But $A$ should be on the ground. So we move the whole truss down $18(-\Delta(\angle DFE))+6\Delta(-\Delta(\angle DFE))$. From $W$'s perspective, $W$ is lifted up $6(-\Delta(\angle DFE))$ and dropped down $\frac{1}{3}(18(-\Delta(\angle DFE))+6(-\Delta(\angle DFE)))$. Thus, $$\begin{align}
\Delta y_{W}&=\frac{1}{3}(18\Delta(\angle DFE)+6\Delta(\angle DFE)) -6\Delta(\angle DFE)\\
&=2\Delta(\angle DFE)=\frac{5}{12}\Delta DE
\end{align}$$Hence, by the principle of virtual work $$\begin{align}
&&-F_{DE}\Delta DE+W\Delta y_{W}&=0 \\
&\Rightarrow&-F_{DE}\Delta DE+W\frac{5}{12}\Delta DE&=0 \\
\end{align}$$This implies that $F_{DE}=\frac{5}{12}W$.

## 2.30
**In the system shown in Figure, a pendulum bob of weight $w$ is initially held in the vertical position by a thread $A$. When this thread is burned, releasing the pendulum, it swings to the left and barely reaches the ceiling at its maximum swing. Find the weight $W$. (Neglect friction, the radius of the pulley, and the finite sizes of the weights.)**
![[templates/Fig.2-28.svg#invert]]
Ans:
When $w$ is swung to the ceiling, $W$ would move down $5-(4-3)=4 \: \text{unit}$. By the conservation of energy,
$$
-3w+4W=0
$$
and $W=\frac{3}{4}w$.

## 2.31
**Two equal masses $m$ are attached to a third mass $2m$ by equal lengths of fine thread and the thread is passed over two small pulleys with negligible friction situated $100\: \text{cm}$ apart, as shown in Figure. The mass $2m$ is initially held level with the pulleys midway between them, and is then released from rest. When it has descended a distance of $50\: \text{cm}$ it strikes a table top. What is it's speed $v$ when it reaches the table top?**![[templates/Fig.2-29.svg#invert]]
Ans:
$L^{2}+x^{2}=y^{2}\Rightarrow 2x\Delta x=2y\Delta y\Rightarrow x\Delta x=y\Delta$ where $\Delta x$ and $\Delta y$ are the change in distance of $2m$ and $m$, respectively. So $50v_{2m}=50\sqrt{ 2 }v_{m}$, and$v_{m}=\frac{1}{\sqrt{ 2 }}v_{2m}$.
By the conservation of energy,
$$
\begin{align}
&&2mg\times 50-2\times mg\times(50\sqrt{ 2 }-50)&=\frac{1}{2}2mv^{2}+2\times \frac{1}{2}m\left( \frac{1}{\sqrt{ 2 } } v\right)^{2} \\
&\Rightarrow& (100-100\sqrt{ 2 }+100)g&= \frac{3}{2}v^{2}
\end{align}
$$
Therefore, $v=\sqrt{\frac{2}{3}(200-100\sqrt{ 2 } )g}\approx 196\: \text{cm s}^{-1}$.

## 2.32
**A tank of cross-sectional area $A$ contains a liquid having density $\rho$. The liquid squirts freely from a small hole of area $a$ distance $H$ below the free surface of the liquid, as shown in Figure. If the liquid has no internal friction (viscosity), with what speed v does it emerge?**
![[templates/Fig.2-30.svg#invert]]
Ans:
The volume of the liquid that is above the level of the hole is equal to the volume with bottom area equals $a$ and its height $s=\frac{HA}{a}$. So $\Delta s=\frac{A}{a}\Delta H$.
By the conservation of energy,
$$
\begin{align}
AH\rho g\Delta H&=\frac{1}{2}a\Delta s \rho v^{2} \\
AH\rho g\Delta H&=\frac{1}{2}A\Delta H\rho v^{2}
\end{align}
$$
Therefore, $v=\sqrt{ 2gH }$.

## 2.33
**Smooth, identical logs are piled in a stake truck. The truck is forced off the highway and comes to rest on an even keel lengthwise but with the bed at an angle $\theta$ with the horizontal, as shown in Figure. As the truck is unloaded, the removal of the log shown dotted leaves the remaining three in a condition where they are just ready to slide, that is, if $\theta$ were any smaller, the logs would fall down. Find $\theta$.**
![[templates/Fig.2-31.svg#invert]]
Ans:
Let $W$ and $R$ be the weight and radius of each log, and let $N_{l}$ and $N_{u}$ be the normal forces the lower ball and the upper give to the top ball.

By the principle of virtual work, if the top log moves perpendicular to $N_{l}$ in a small distance $\Delta s$,
![[templates/Fig.2-31sol1.svg#invert]]
then by the principle of virtual work,
$$
\begin{align}
&&W\Delta s \sin(30^{\circ}-\theta)-N_{u}\Delta s\cos 30^{\circ}&=0 \\
&\Rightarrow& W \left(\frac{1}{2}\cos \theta-\frac{\sqrt{ 3 }}{2}\sin \theta\right)-N_{u}\frac{\sqrt{ 3 }}{2}=0
\end{align}
$$
That is, $N_{u}=\left( \frac{1}{\sqrt{ 3 }}\cos \theta-\sin \theta \right)W$.
If the right bottom log moves along the incline in a small distance $\Delta s$, by the principle of virtual work, 
$$
\begin{align}
&&-W\Delta s\sin \theta+N_{u}\sin 30^{\circ}\Delta s&=0 \\
&\Rightarrow&-\sin \theta+\frac{1}{2\sqrt{ 3 }}\cos \theta-\frac{1}{2}\sin \theta&=0
\end{align}
$$
Consequently, $\frac{3}{2}\sin \theta=\frac{1}{2\sqrt{ 3 }}\cos \theta$ and $\tan \theta=\frac{1}{3\sqrt{ 3 }}$, which implies that $\theta \approx 10.9^{\circ}$.

## 2.34
**A spool of weight $w$ and radii $r$ and $R$ is wound with cord, and suspended from a fixed support by two cords wound on the smaller radius; a weight $W$ is then suspended from two cords wound on the larger radius, as shown in Figure. W is chosen so that the spool is just balanced. Find $W$.**
![[templates/Fig.2-32.svg#invert]]

Ans:
Assume that the spool rotates in a small angle $\Delta \theta$, then the spool will move $-r\Delta \theta$ vertically, and the cord will move $R\Delta \theta-r\Delta \theta$ vertically. By the principle of virtual work,
$$
\begin{align}
&&w(-r\Delta \theta)+W(R\Delta \theta-r\Delta \theta)&=0
\end{align}
$$
Which implies that $W=\frac{r}{R-r}w$.

## 2.35
**A suspension bridge is to span a deep gorge $54\: \text{m}$ wide. The roadway will consist of a steel truss supported by six pairs of vertical cables spaced $9.0\: \text{m}$ apart, as shown in Figure. Each cable is to carry an equal share of the $4.80\times 10^{4}\: \text{kg}$ weight. The two pairs of cables nearest the center are to be $2.00\: \text{m}$ long. Find the proper lengths for the remaining vertical cables $A$ and $B$ and the maximum tension $T_{max}$ in the two longitudinal cables, if the latter are to be at a $45^{\circ}$ angle with the horizontal at their ends.**
![[templates/Fig.2-33.svg#invert]]
Ans:
Let $w$ be the weight each of the six cable carries. Analyzing the free-body diagram, we have 
$$
\begin{align}
T_{1}=T_{2}\cos \theta=T_{3}\cos \phi =T_{4}\cos 45^{\circ}&\dots (1) \\
w=T_{2}\sin \theta=T_{3}\sin \phi-T_{2}\sin \theta=T_{4}\sin 45 ^{\circ}-T_{3}\sin \phi&\dots (2)
\end{align}
$$
![[templates/Fig.2-33sol.svg#invert]]
From $(2)$, 
$$
\begin{align}
w&=T_{2}\sin \theta \\
w&=T_{3}\sin \phi-T_{2}\sin \theta \\
w&=T_{4}\sin 45 ^{\circ}-T_{3}\sin \phi\\
\hline 
3w&=T_{4}\sin 45^{\circ}
\end{align}
$$
Now we have
$$
\begin{align}
T_{1}&=T_{4}\cos 45^{\circ} \\
T_{1}&=T_{2}\cos \theta \\
w&=T_{2}\sin \theta \\
3w&=T_{4}\sin 45^{\circ}
\end{align}
$$
So
$$
\begin{align}
&&T_{2}\cos \theta&=T_{4}\cos 45^{\circ} \\
&\Rightarrow&w\csc \theta \cos \theta&=3w\csc 45^{\circ}\cos 45^{\circ} \\
&\Rightarrow&\cot \theta&=3\cot 45^{\circ}
\end{align}
$$
Thus, $\tan \theta=\frac{1}{3}$ and  the length of the vertical cable $A$ is $2.00 + 9.0\tan \theta=5.0\: \text{m}$.

Similarly, 
$$
\begin{align}
T_{1}&=T_{3}\cos \phi \\
T_{1}&=T_{4}\cos 45^{\circ} \\
w&=T_{4}\sin 45^{\circ}-T_{3}\sin \phi \\
3w&=T_{4}\sin 45^{\circ}
\end{align}
$$
So
$$
\begin{align}
&&T_{4}\cos 45 ^{\circ}&=T_{3}\cos \phi \\
&\Rightarrow& 3w\csc 45^{\circ}\cos 45^{\circ}&=2w\csc \phi \cos \phi \\
&\Rightarrow& \frac{3}{2}\cot 45^{\circ}=\cot \phi
\end{align}
$$
Thus, $\tan \phi=\frac{2}{3}$ and the length of the vertical cable $B$ is $2.00+9.0\tan \theta+9.0\tan \phi=11 \: \text{m}$

$w=\frac{4.8\times 10^{4}}{6}=8\times 10^{3}\: \text{kg-wt}$. $T_{4}$ is the maximum tension, which is $T_{4}=3w\csc 45^{\circ}\approx 34 \times 10^{3}\: \text{kg-wt}$.

## 2.36
**The insulating support structure of a Tandem Van de Graaff may be represented, as shown in Figure: two blocks of about uniform density, length $L$ , height $h$ and weight $W$ , supported from vertical bulkheads by pivot joints ($A$ and $B$) and forced apart by a screw jack ($F$) at the center. Since the material of the blocks cannot support tension, the jack must be adjusted to give zero force on the upper pivot.**
![[templates/Fig.2-34.svg#invert]]
1. **What force $F$ is required?**
2. **What is the total force (magnitude and direction) *$F_{a}$* on one of the lower pivots $A$**

Ans:
1. `solution I: using virtual work`
   ![[templates/Fig.2-34sol.svg#invert]]
   If the left one block rotates around $A$ in an angle $\Delta \theta$, then by the center of mass of the block moves $\sqrt{ \left( \frac{h}{2} \right)^{2}+\left( \frac{L}{2} \right)^{2} }\Delta \theta \frac{\frac{L}{2}}{\sqrt{ \left( \frac{h}{2} \right)^{2}+\left( \frac{L}{2} \right)^{2} }}=\frac{L}{2}\Delta \theta$ downward and $\sqrt{ \left( \frac{h}{2} \right)^{2}+\left( \frac{L}{2} \right)^{2} }\Delta \theta \frac{\frac{h}{2}}{\sqrt{ \left( \frac{h}{2} \right)^{2}+\left( \frac{L}{2} \right)^{2} }}=\frac{h}{2}\Delta \theta$ toward right hand side. By the principle of virtual work $$W\frac{L}{2}\Delta \theta-F \frac{h}{2}\Delta \theta=0$$
   Which implies that $F=\frac{L}{h}W$
   `solution II: using force`
   Since the system is in static equilibrium, the net torque is equal to zero. Hence, if we set $A$ to be a fulcrum, $$\frac{h}{2}F=\frac{L}{2}W$$Which implies that  $F=\frac{L}{h}W$.
2. The block acted upon by $3$ forces and is in static equilibrium, by problem 2.3.3, the lines of action of the forces must pass through a single point, which in this case is the center of mass of the block. Thus, $F_{A}$ points toward the center of the mass of the block, which is $\arctan\left( \frac{h}{L} \right)$ with horizontal. The horizontal component of $F_{A}$ must equal $F$ and the vertical component of $F_{A}$ must equal $W$ to remain equilibrium. Therefore, $F_{A}\frac{\frac{h}{2}}{\sqrt{ \left( \frac{h}{2} \right)^{2}+\left( \frac{L}{2} \right)^{2} }}=W$ and $F_{A}=\sqrt{ 1+\left( \frac{L}{h} \right)^{2} }W$.