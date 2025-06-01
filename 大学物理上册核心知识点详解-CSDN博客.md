## 大学物理（上）知识点总结

```
期末，总结一下大学物理知识点
对于大学物理（以下简称大物）的知识点总结，采取以公式为主线的方式进行
```

#### 文章目录

- [大学物理（上）知识点总结](#_0)
- - [一、质点动力学](#_5)
    - [二、刚体的定轴转动](#_39)
    - [三、机械振动基础](#_72)
    - [四、机械波](#_121)
    - [五、波动光学](#_186)
    - [六、热力学](#_306)
    - [七、气体动理论](#_393)
    - [参考资料](#_445)

### 一、质点动力学

速度：  
v ⃗ = d r ⃗ d t \vec v = \frac{d\vec r}{dt} v =dtdr ​  
加速度：  
a ⃗ = d 2 r ⃗ d t 2 = d v ⃗ d t \vec a = \frac{d^2\vec r}{dt^2} = \frac{d\vec v}{dt} a =dt2d2r ​=dtdv ​  
圆周运动：  
a ⃗ = a ⃗ n + a ⃗ τ = v ⃗ 2 R ⋅ n ⃗ + d v ⃗ d t \vec a = \vec a_n + \vec a_\tau = \frac{\vec v^2}{R} \cdot \vec n + \frac{d\vec v}{dt} a =a n​+a τ​=Rv 2​⋅n +dtdv ​  
β = d ω ⃗ d t = d 2 θ d t 2 \beta = \frac{d\vec\omega}{dt} = \frac{d^2\theta}{dt^2} β=dtdω ​=dt2d2θ​  
a ⃗ = a ⃗ n + a ⃗ τ = r ⋅ β ⃗ + r ⋅ w ⃗ 2 \vec a = \vec a_n + \vec a_\tau = r \cdot \vec \beta + r \cdot \vec w^2 a =a n​+a τ​=r⋅β ​+r⋅w 2  
功：  
保守力做功仅与相对位置有关，存在保守立场，蕴含的能量称为势能，即保守力做功 = 势能的增量的负值，而势能只存在相对意义，即必须选取零势能面（点）  
非保守力做功与相对移动有关  
A = ∫ a b F ⃗ d r ⃗ A = \int_a^b\vec Fd\vec r A=∫ab​F dr  
势能：  
E p = ∫ M 参 F ⃗ d r E_p = \int_M^参 \vec F dr Ep​=∫M参​F dr  
引力势能为 ∫ r ∞ − G m M r 2 d r = − G M m r \int_r^\infty -G\frac{mM}{r^2}dr = -G\frac{Mm}{r} ∫r∞​−Gr2mM​dr=−GrMm​  
功率：  
P ‾ = Δ A Δ t \overline P = \frac{\Delta A }{\Delta t} P=ΔtΔA​  
P = d A d t = F ⃗ r ⃗ d t = F ⃗ ⋅ v = F ⃗ v c o s θ P = \frac{dA}{dt} = \frac{\vec F \vec r}{dt} = \vec F \cdot v = \vec F v cos\theta P=dtdA​=dtF r ​=F ⋅v=F vcosθ  
动能定理：（空间积累）  
合外力做功 = 物体始末的动能变化量  
A = 1 2 m v 2 2 − 1 2 m v 1 2 A = \frac{1}{2}mv_2^2 - \frac{1}{2}mv_1^2 A=21​mv22​−21​mv12​  
功能原理：  
A 外 A_外 A外​  
A 内 = A 非 + A 保 A_内 = A_非 + A_保 A内​=A非​+A保​  
机械能守恒为 ∑ A 外 + A 非 = 0 \sum_{A_外} + A_非 = 0 ∑A外​​+A非​=0**时刻**满足  
动量定理：（时间积累）  
条件： ∑ F ⃗ 外 = 0 \sum{\vec F_外} = 0 ∑F 外​=0 or 内力>>外力  
I ⃗ = ∫ t 1 t 2 F ⃗ d t = ∫ t 1 t 2 d m v ⃗ = m v 1 − m v 2 \vec I = \int_{t1}^{t2}\vec F dt = \int_{t1}^{t2}dm\vec v = mv_1 - mv_2 I =∫t1t2​F dt=∫t1t2​dmv =mv1​−mv2​  
碰撞（对心）：  
完全非弹性碰撞：机械能损失最大  
弹性碰撞：动能增量为零  
非弹性碰撞：动能增量不为零（一般不讨论）  
质心：意会

### 二、刚体的定轴转动

力矩：  
M ⃗ 0 = r ⃗ × F ⃗ \vec M_0 = \vec r \times \vec F M 0​=r ×F  
定轴转动定理：  
M = J β M = J\beta M=Jβ  
转动惯量：  
J = ∑ Δ m i r i 2 J = \sum \Delta m_i r_i^2 J=∑Δmi​ri2​  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/21e037ac198913b31bbdc13c8d65d2d4.png)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/ce7d204dfd736c976c8d31916440bd6a.png)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/e64a87bb8694a9167cf4642d0337983f.png)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/4e013c1a45b2601892f57ab1f0488fdf.png)  
平行轴定理：  
J z = J c + m d 2 J_z = J_c + md^2 Jz​=Jc​+md2  
定轴转动刚体动能：  
E k = 1 2 J ω 2 E_k = \frac{1}{2}J\omega^2 Ek​=21​Jω2  
注：平动动能依然为： E k = 1 2 m v 2 E_k = \frac{1}{2}mv^2 Ek​=21​mv2  
力矩的功：  
A = ∫ θ 1 θ 2 M d θ A = \int_{\theta_1}^{\theta_2}Md\theta A=∫θ1​θ2​​Mdθ  
定轴转动的动能定理：  
A = ∫ ω 1 ω 2 d ( 1 2 J ω 2 ) = 1 2 J ω 2 2 − 1 2 J ω 1 2 A = \int_{\omega_1}^{\omega_2}d(\frac{1}{2}J\omega^2) = \frac{1}{2}J\omega_2^2 - \frac{1}{2}J\omega_1^2 A=∫ω1​ω2​​d(21​Jω2)=21​Jω22​−21​Jω12​  
角动量：  
L ⃗ 0 = r ⃗ × m v ⃗ \vec L_0 = \vec r \times m\vec v L 0​=r ×mv  
角动量定理：  
M ⃗ 0 = d L ⃗ 0 d t \vec M_0 = \frac{d\vec L_0}{dt} M 0​=dtdL 0​​  
角动量守恒定理：（有心力）  
若 M 0 = 0 M_0 = 0 M0​=0则 L ⃗ = 常 矢 量 \vec L = 常矢量 L =常矢量  
定轴转动的角动量：  
L ⃗ z = J z ω \vec L_z = J_z \omega L z​=Jz​ω  
定轴转动的角动量定理：  
若J为恒量 M ⃗ z = J z d w d t = J z β \vec M_z = J_z\frac{dw}{dt} = J_z \beta M z​=Jz​dtdw​=Jz​β  
定轴转动的角动量守恒定理：（有心力）  
若 M z = 0 M_z = 0 Mz​=0则 L ⃗ z = J z ω = 常 矢 量 \vec L_z = J_z\omega = 常矢量 L z​=Jz​ω=常矢量  
进动：选学

### 三、机械振动基础

简谐振动：  
x ( t ) = A c o s ( ω t + ϕ ) x(t) = Acos(\omega t + \phi) x(t)=Acos(ωt+ϕ)其中， ω = 2 π T \omega = \frac{2\pi}{T} ω=T2π​  
**旋转矢量法**  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/cb2e0548fd18e0fde7c6b2ef9e0607a6.png)  
单摆：  
ω = g l \omega = \sqrt{\frac{g}{l}} ω=lg​ ​  
T = 2 π l g T = 2\pi\sqrt{\frac{l}{g}} T=2πgl​ ​  
复摆：  
ω = m g h J （ M = J β ） \omega = \sqrt{\frac{mgh}{J}} （M = J\beta） ω=Jmgh​ ​（M=Jβ）  
简谐振动的能量：  
动能：  
E k = 1 2 m v 2 = 1 2 m ω 2 A 2 s i n 2 ( ω t + ϕ ) E_k = \frac{1}{2}mv^2 = \frac{1}{2}m\omega^2A^2sin^2(\omega t + \phi) Ek​=21​mv2=21​mω2A2sin2(ωt+ϕ)  
若 ω = k m \omega = \sqrt{\frac{k}{m}} ω=mk​ ​则$E_k = 1 2 k A 2 s i n 2 ( ω t + ϕ ) \frac{1}{2}kA^2sin^2(\omega t + \phi) 21​kA2sin2(ωt+ϕ)  
平均动能：  
E ‾ k = 1 T ∫ t t + T E k d t = 1 4 k A 2 \overline E_k =\frac{1}{T}\int_t^{t+T}E_kdt = \frac{1}{4}kA^2 Ek​=T1​∫tt+T​Ek​dt=41​kA2  
势能：  
E p = 1 2 k x 2 = 1 2 k A 2 c o s 2 ( ω t + ϕ ) E_p = \frac{1}{2}kx^2 =\frac{1}{2}kA^2cos^2(\omega t +\phi) Ep​=21​kx2=21​kA2cos2(ωt+ϕ)  
机械能：  
E = E k + E p = 1 2 k A 2 E = E_k + E_p = \frac{1}{2}kA^2 E=Ek​+Ep​=21​kA2  
两个同频率振动的相位关系：  
超前 or 落后  
同相 or 反相  
**谐振动的合成：**  
1、同方向同频率谐振动的合成：  
x 1 = A 1 c o s ( ω t + ϕ 1 ) x_1 = A_1cos(\omega t + \phi_1) x1​=A1​cos(ωt+ϕ1​)  
x 2 = A 2 c o s ( ω t + ϕ 2 ) x_2 = A_2cos(\omega t + \phi_2) x2​=A2​cos(ωt+ϕ2​)  
x = x 1 + x 2 = ⋯ = A c o s ( ω t + ϕ ) x = x_1 + x_2 = \dots=Acos(\omega t +\phi) x=x1​+x2​=⋯=Acos(ωt+ϕ)  
（用旋转矢量的方法思考问题）  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/cb07c904fb05bc7f18d0e35ff2c5358d.png)  
2、同方向不同频率谐振动合成：  
x 1 = A 1 c o s ω 1 t x_1 = A_1cos\omega_1 t x1​=A1​cosω1​t  
x 2 = A 2 c o s ω 2 t x_2 = A_2cos\omega_2 t x2​=A2​cosω2​t  
x = x 1 + x 2 = A 1 c o s ω 1 t + A 2 c o s ω 2 t = 2 A c o s ( ω 2 − ω 1 2 t ) ⋅ 2 A c o s ( ω 2 + ω 1 2 t ) x = x_1 + x_2 =A_1cos\omega_1 t + A_2cos\omega_2 t = 2Acos(\frac{\omega_2-\omega_1}{2}t)\cdot2Acos(\frac{\omega_2+\omega_1}{2}t) x=x1​+x2​=A1​cosω1​t+A2​cosω2​t=2Acos(2ω2​−ω1​​t)⋅2Acos(2ω2​+ω1​​t)  
和振动不再是简谐振动 A = A 1 2 + A 2 2 + 2 A 1 A 2 c o s [ ( ω 2 − ω 1 ) t ] A= \sqrt{A_1^2+A_2^2+2A_1A_2cos[(\omega_2-\omega_1)t]} A=A12​+A22​+2A1​A2​cos[(ω2​−ω1​)t] ​

当 ω 1 ≈ ω 2 \omega_1 \approx \omega_2 ω1​≈ω2​时可以近似看作振幅缓慢变化的简谐振动，这就是“拍”，拍频指单位时间内合振动振幅强弱变化的次数，即 v = ∣ ω 2 − ω 1 2 π ∣ = ∣ v 2 − v 1 ∣ v = |\frac{\omega_2-\omega_1}{2\pi}| = |v_2 - v_1| v=∣2πω2​−ω1​​∣=∣v2​−v1​∣  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/6ae6981d1a9f337bcaa86a3bae166d27.png)  
3、两个同频率相互垂直谐振动的合成  
x = A 1 c o s ( ω t + ϕ 1 ) x = A_1cos(\omega t+\phi_1) x=A1​cos(ωt+ϕ1​)  
y = A 2 c o s ( ω t + ϕ 2 ) y = A_2cos(\omega t+\phi_2) y=A2​cos(ωt+ϕ2​)  
s i n 2 ( ϕ 2 − ϕ 1 ) sin^2(\phi_2 - \phi_1) sin2(ϕ2​−ϕ1​)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/18d9990fb041c990a0ebd7b3964f5b30.png)  
（李萨如图）  
阻尼振动：  
线形恢复力+阻尼力  
受迫振动：  
弹性力+阻尼力+周期性策动力  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/3d44f1c7a80e9449af4710394523939b.png)

### 四、机械波

机械波的几个概念：  
横波：质点振动方向垂直波传播的方向  
纵波：质点振动方向平行于波传播方向  
波面：在波传播过程中，振动相位相同的点联结成的面  
波线：沿波传播方向的直线  
波前：在某一时刻，波传播到最前面的波面  
在各向同性均匀媒质中，波线与波面相互垂直  
波长：同一波线上相差为 2 π 2\pi 2π的相邻两点间的距离  
周期：波前进一个周期的距离为一个波长  
频率：周期的倒数  
波速：振动状态在媒质中传播的速度 u = λ T = v λ u = \frac{\lambda}{T} = v\lambda u=Tλ​=vλ  
其中，波速由媒质决定，频率与媒质无关，是波的特质  
波动方程：  
o 点 振 动 方 程 ： y 0 = A c o s ( ω t + ϕ 0 ) o点振动方程：y_0 = Acos(\omega t+ \phi_0) o点振动方程：y0​=Acos(ωt+ϕ0​)  
经过 Δ t = x u \Delta t = \frac{x}{u} Δt=ux​传播到p点，则p点落后于o点，振动方程为： y = A c o s [ ω ( t − x u ) + ϕ 0 ] y = Acos[\omega(t-\frac{x}{u})+\phi_0] y=Acos[ω(t−ux​)+ϕ0​]  
波函数的其他形式：  
y = A c o s [ 2 π ( v t − x λ ) + ϕ 0 ] y = Acos[2\pi(vt-\frac{x}{\lambda})+\phi_0] y=Acos[2π(vt−λx​)+ϕ0​]  
y = A c o s [ 2 π ( t T − x λ ) + ϕ 0 ] y = Acos[2\pi(\frac{t}{T}-\frac{x}{\lambda})+\phi_0] y=Acos[2π(Tt​−λx​)+ϕ0​]  
y = A c o s [ 2 π λ ( u t − x ) + ϕ 0 ] y = Acos[\frac{2\pi}{\lambda}(ut-x)+\phi_0] y=Acos[λ2π​(ut−x)+ϕ0​]  
小技巧：x,t异号正向传播，x,t同号逆向传播  
平面简谐波的波动微分方程：意会  
波的能量：  
动能： ω k = 1 2 Δ m v 2 = 1 2 μ Δ x ω 2 A 2 s i n 2 ( ω [ t − x u ) + ϕ 0 ] （ μ 为 线 密 度 ） \omega _k = \frac{1}{2}\Delta mv^2 = \frac{1}{2}\mu\Delta x\omega^2A^2sin^2(\omega[t-\frac{x}{u})+\phi_0]（\mu为线密度） ωk​=21​Δmv2=21​μΔxω2A2sin2(ω[t−ux​)+ϕ0​]（μ为线密度）  
势能： ω p = 1 2 μ Δ x A 2 ω 2 s i n 2 [ ω ( t − x u ) + ϕ 0 ] \omega_p = \frac{1}{2}\mu\Delta xA^2\omega^2sin^2[\omega(t-\frac{x}{u})+\phi_0] ωp​=21​μΔxA2ω2sin2[ω(t−ux​)+ϕ0​]  
我们会发现势能等于动能，即机械能不守恒  
总能量：  
ω = 2 ω = μ Δ x A 2 ω 2 s i n 2 [ ω ( t − x u ) + ϕ 0 ] \omega = 2\omega = \mu\Delta xA^2\omega^2sin^2[\omega(t-\frac{x}{u})+\phi_0] ω=2ω=μΔxA2ω2sin2[ω(t−ux​)+ϕ0​]  
能量密度：（单位体积中波的能量）  
设质元横截面为S，体密度为 ρ \rho ρ，则单位线元中的机械能为： ω = W S Δ x = ρ A 2 ω 2 s i n 2 [ ω ( t − x u ) + ϕ 0 ] \omega = \frac{W}{S\Delta x} = \rho A^2\omega^2 sin^2[\omega(t-\frac{x}{u})+\phi_0] ω=SΔxW​=ρA2ω2sin2[ω(t−ux​)+ϕ0​]  
一个周期内的平均能量密度：  
ω ‾ = 1 T ∫ 0 T ω d t = 1 2 ρ A 2 ω 2 \overline \omega = \frac{1}{T}\int_0^T\omega dt = \frac{1}{2}\rho A^2\omega^2 ω=T1​∫0T​ωdt=21​ρA2ω2  
一个周期内通过S的能量：  
Δ w = w ‾ u T S \Delta w = \overline w uTS Δw=wuTS  
能流密度：（波的强度）  
I = Δ w T S = w ‾ u = 1 2 ρ A 2 w 2 u I = \frac{\Delta w}{TS} = \overline wu = \frac{1}{2}\rho A^2w^2u I=TSΔw​=wu=21​ρA2w2u  
**波的强度与振幅的平方成正比**  
球面波的振幅：  
A = A 0 r A =\frac{A_0}{r} A=rA0​​  
则球面波的振幅随r增大而减小  
惠更斯原理：理解  
波的干涉：  
相干条件为频率相同，振动方向相同，相位差恒定  
A 2 = A 1 2 + A 2 2 + 2 A 1 A 2 c o s Δ ϕ A^2 = A_1^2+A^2_2+2A_1A_2cos\Delta\phi A2=A12​+A22​+2A1​A2​cosΔϕ  
Δ ϕ = ϕ 1 − ϕ 2 − 2 π r 2 − r 1 λ \Delta\phi = \phi_1 - \phi_2 - 2\pi\frac{r_2-r_1}{\lambda} Δϕ=ϕ1​−ϕ2​−2πλr2​−r1​​  
I = I 1 + I 2 + I 1 I 2 c o s Δ ϕ I = I_1+ I_2+\sqrt{I_1I_2}cos\Delta\phi I=I1​+I2​+I1​I2​ ​cosΔϕ  
强度分布显然可见  
干涉相长的条纹为 Δ ϕ = ± 2 k π \Delta \phi = \pm2k\pi Δϕ=±2kπ则 δ = r 2 − r 1 = k λ \delta = r_2 - r_1 = k\lambda δ=r2​−r1​=kλ  
干涉相消的条纹为 Δ ϕ = ± ( 2 k + 1 ) π \Delta \phi = \pm(2k+1)\pi Δϕ=±(2k+1)π则 δ = r 2 − r 1 = ( k + 1 2 ) λ \delta = r_2 - r_1 = (k+\frac{1}{2})\lambda δ=r2​−r1​=(k+21​)λ  
驻波：  
两列等振幅，传播方向相反的相干波叠加形成驻波  
波腹和波节  
半波损失：  
当波由波疏介质射入波密介质，再返回波疏介质时会产生半波损失，若反射时无能量损失，则形成驻波  
对于驻波，其能量在波节和波腹来回振动，势能和动能相互转化  
多普勒效应：  
v s v_s vs​为波原始频率， v v v为波新的相对频率  
1、波源静止，观察者运动  
v = u + v 0 u v s = ( 1 + v 0 u ) v s v =\frac{u+v_0}{\frac{u}{v_s}} = (1+\frac{v_0}{u})v_s v=vs​u​u+v0​​=(1+uv0​​)vs​  
2、观察者静止，波源运动  
v = u u − v s v s v =\frac{u}{u-v_s} v_s v=u−vs​u​vs​  
3、波源和观察者同时运动  
v = u + v 0 λ − v s T = ( u + v 0 u − v s ) v s v =\frac{u+v_0}{\lambda -v_sT} = (\frac{u+v_0}{u-v_s})v_s v=λ−vs​Tu+v0​​=(u−vs​u+v0​​)vs​  
注意：波源的运动与观察者运动不等价

### 五、波动光学

光源：  
1）热辐射；2）电致发光；3）光致发光；4）化学发光  
以上属于自发辐射，初相不相关  
一下属于受激辐射，具有统一性  
5）同步辐射光源；6）激光光源  
光的干涉：  
相长干涉： I m a x = I 1 + I 2 + 2 I 1 I 2 I_{max} = I_1 + I_2 + 2\sqrt{I_1I_2} Imax​=I1​+I2​+2I1​I2​ ​  
相消干涉： I m i n = I 1 + I 2 − 2 I 1 I 2 I_{min} = I_1 + I_2 - 2\sqrt{I_1I_2} Imin​=I1​+I2​−2I1​I2​ ​  
如果 ϕ ! = ϕ 2 \phi_! = \phi_2 ϕ!​=ϕ2​  
相长干涉： δ = r 2 − r 1 = ± k λ \delta = r2-r1 = \pm k\lambda δ=r2−r1=±kλ  
相消干涉： δ = r 2 − r 1 = ± ( 2 k + 1 ) λ 2 \delta = r2-r1 = \pm (2k+1)\frac{\lambda}{2} δ=r2−r1=±(2k+1)2λ​  
其中，k为干涉级  
杨氏双缝干涉：（分波阵面法）  
只有把同一个波列分割成两个波列，让这两个波列在空间相遇，才能获得相干波  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/c22ab3f38572b7a16928812b6ec03863.png)  
明纹： Δ ϕ = ± 2 k π , δ = ± k λ , x k = ± k D λ d \Delta\phi = \pm 2k\pi,\delta = \pm k\lambda,x_k = \pm k\frac{D\lambda}{d} Δϕ=±2kπ,δ=±kλ,xk​=±kdDλ​  
暗纹： Δ ϕ = ± ( 2 k + 1 ) π , δ = ± ( k + 1 2 ) λ , x k = ± ( k + 1 2 ) D λ d \Delta\phi = \pm (2k+1)\pi,\delta = \pm (k+\frac{1}{2})\lambda,x_k = \pm (k+\frac{1}{2})\frac{D\lambda}{d} Δϕ=±(2k+1)π,δ=±(k+21​)λ,xk​=±(k+21​)dDλ​  
获得单色光的方法：  
1）棱镜散射法；2）滤光片；3）单色光源；4）激光  
洛埃镜：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/cc68c46b479dd0ccc8ca7862b7ea267e.png)  
存在半波损失  
δ = r 2 − r 1 + λ 2 \delta = r_2 - r_1 + \frac{\lambda}{2} δ=r2​−r1​+2λ​  
明纹： δ = ± k λ \delta = \pm k\lambda δ=±kλ  
暗纹： δ = ± ( k + 1 2 ) λ \delta = \pm (k+\frac{1}{2})\lambda δ=±(k+21​)λ  
薄膜干涉：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/525321c9f3084644c32b48524e773a86.png)  
光程差为 δ = n 2 ( A B + B C ) − n 1 D C = ⋯ = 2 d n 2 2 − n 1 2 s i n 2 i \delta =n_2(AB+BC)-n_1DC=\dots=2d\sqrt{n_2^2-n1^2sin^2i} δ=n2​(AB+BC)−n1​DC=⋯=2dn22​−n12sin2i ​  
若 n 2 n_2 n2​最大或最小，则需要考虑半波损失，否则，不需要  
明纹： δ = ± k λ \delta = \pm k\lambda δ=±kλ  
暗纹： δ = ± ( k + 1 2 ) λ \delta = \pm (k+\frac{1}{2})\lambda δ=±(k+21​)λ  
若从薄膜下方看，反射光干涉加强时，透射光干涉相消；反射光干涉相消时，透射光干涉加强  
几种等厚干涉：  
1、劈尖干涉：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/a9131c1b72dfd139c14faa33c877ec22.png)  
δ = 2 d + λ 2 \delta = 2d+\frac{\lambda}{2} δ=2d+2λ​  
相邻条纹之间的距离 a s i n θ = λ 2 asin\theta = \frac{\lambda}{2} asinθ=2λ​  
明纹： δ = ± k λ , d = 2 k − 1 4 λ \delta = \pm k\lambda,d = \frac{2k-1}{4}\lambda δ=±kλ,d=42k−1​λ  
暗纹： δ = ± ( k + 1 2 ) λ , d = 1 2 k λ \delta = \pm (k+\frac{1}{2})\lambda,d = \frac{1}{2}k\lambda δ=±(k+21​)λ,d=21​kλ  
检测工件表面的不平整  
牛顿环：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/35bb1c8a46c5abfe2a4dfd1ec04acb56.png)  
δ = 2 d + λ 2 \delta = 2d + \frac{\lambda}{2} δ=2d+2λ​  
明纹： δ = ± k λ , d = 2 k − 1 4 λ \delta = \pm k\lambda,d = \frac{2k-1}{4}\lambda δ=±kλ,d=42k−1​λ  
暗纹： δ = ± ( k + 1 2 ) λ , d = 1 2 k λ \delta = \pm (k+\frac{1}{2})\lambda,d = \frac{1}{2}k\lambda δ=±(k+21​)λ,d=21​kλ  
3、增透膜  
原理为使反射光相消，则透射光加强（能量守恒）  
增反膜同理  
麦克尔逊干涉仪：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/4a65c5f9384e77ac6599897cca919396.png)  
明纹： δ = ± k λ \delta = \pm k\lambda δ=±kλ  
暗纹： δ = ± ( k + 1 2 ) λ \delta = \pm (k+\frac{1}{2})\lambda δ=±(k+21​)λ  
条纹特点：  
当M1水平、M2竖直时为等倾条纹（圆环）  
当M1和M2有小夹角时，会出现等厚条纹  
M1移动 λ \lambda λ，光程差改变 2 λ 2\lambda 2λ，视场中有两个条纹移动  
惠更斯—菲涅尔原理：  
光的衍射现象：  
当光遇到障碍物时，能够改变方向并绕过障碍物的边缘前进  
惠更斯菲涅尔原理：  
同一波前的各点发出的都是相干次波  
各次波在空间某点的相干叠加，就决定了该波的强度  
**单缝的夫琅禾费衍射：**  
菲涅尔半波带法：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/0ff921329b24bbfa5e032e668c9159f6.png)  
半波带数 N = b s i n θ λ 2 N = \frac{bsin\theta}{\frac{\lambda}{2}} N=2λ​bsinθ​  
暗纹条件： N = ± 2 k , b s i n θ = ± k λ N = \pm 2k , bsin\theta = \pm k\lambda N=±2k,bsinθ=±kλ  
明纹条件： N = ± ( 2 k + 1 ) , b s i n θ = ± ( k + 1 2 ) λ N = \pm (2k+1) , bsin\theta = \pm (k+\frac{1}{2})\lambda N=±(2k+1),bsinθ=±(k+21​)λ  
明纹强度来自于一个半波带的贡献  
中央明纹： b s i n θ = 0 bsin\theta = 0 bsinθ=0  
条纹在屏上的位置为（f为透镜的焦距） x = f t a n θ ≈ f s i n θ x = ftan\theta \approx fsin\theta x=ftanθ≈fsinθ  
则，暗纹坐标： x = ± k f λ a x =\pm k\frac{f\lambda}{a} x=±kafλ​  
明纹坐标： x = ± ( 2 k + 1 ) f λ 2 a x =\pm (2k+1)\frac{f\lambda}{2a} x=±(2k+1)2afλ​  
中央明纹宽度： 2 f λ a \frac{2f\lambda}{a} a2fλ​  
k级明纹宽度： f λ a \frac{f\lambda}{a} afλ​  
注：  
θ 增 加 ， 半 波 带 面 积 减 小 ， 明 纹 强 度 减 弱 \theta增加，半波带面积减小，明纹强度减弱 θ增加，半波带面积减小，明纹强度减弱  
狭缝上下移动条纹不动  
透镜上下移动，条纹跟着移动  
瑞利判据：  
对于两个等光强的非相干点，如果一个像斑中心恰好落在另一个像斑边缘，则认为这两个像恰好可辨  
衍射光栅：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/5858a69382aaa1e37294d2e453b186f2.png)  
光栅常数d = a + b  
狭缝数目N  
主极大级数：  
d s i n ϕ = ± k λ ( k = 0 , 1 , 2 …   ) dsin\phi = \pm k\lambda(k = 0,1,2\dots) dsinϕ=±kλ(k=0,1,2…)其中 ∣ s i n ϕ ∣ ≤ 1 , k < d λ |sin\phi|\leq1,k<\frac{d}{\lambda} ∣sinϕ∣≤1,k<λd​  
暗纹条件：  
非主极大就是暗纹  
若N为狭缝数目，则两主极大之间有N-1个极小，N-2个次级大  
随着N增大，主极大更为尖锐  
主极大强度正比于 N 2 N^2 N2  
缺级：  
主极大明纹位置与单缝衍射暗纹位置重合  
主极大明纹： d s i n ϕ = ± k λ dsin\phi = \pm k \lambda dsinϕ=±kλ  
单缝衍射暗纹： a s i n ϕ = ± k ′ λ asin\phi = \pm k'\lambda asinϕ=±k′λ  
则， k = d a k ′ k = \frac{d}{a}k' k=ad​k′(k为整数即可)  
主极大条纹的坐标：  
x = ± k f f λ d x = \pm kf\frac{f\lambda}{d} x=±kfdfλ​  
间距 Δ x = f λ d \Delta x = \frac{f\lambda}{d} Δx=dfλ​  
斜入射光栅方程：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/20add95386306b78dde699e01d4b808d.png)  
光程差： δ = d ( s i n θ + s i n ϕ ) \delta = d(sin\theta+sin\phi) δ=d(sinθ+sinϕ)  
剩余与正射无异  
偏振光的表示：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/dde975bbdd3574198dd92b6e5320a96d.png)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/1afca7baf842445c7941a7a8e81dd041.png)  
自然光转化为偏振光： I = 1 2 I 0 I = \frac{1}{2}I_0 I=21​I0​  
马吕斯定律：  
线偏振光通过一个偏振片后，透射光强 I I I与入射光强 I 0 I_0 I0​之间满足： I = I 0 c o s 2 α ( α 为 入 射 光 与 偏 振 化 方 向 的 夹 角 ) I = I_0cos^2\alpha(\alpha为入射光与偏振化方向的夹角) I=I0​cos2α(α为入射光与偏振化方向的夹角)  
布儒斯特定律：  
自然光反射后，垂直振动对于平行振动  
自然光折射后，平行振动多于垂直振动  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/0aeff80dd6ba082eace33f372f2c72b0.png)  
晶体的双折射现象：  
遵循折射定律的叫做o光，反之叫做e光  
一般情况下，认为o光和e光的振动相互垂直  
o光与e光传播速度不同，o光波面为球面，e光波面为椭球面，沿光轴方向，o光和e光速度相同，垂直光轴方向，o光和e光速度相差最大  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/4bbb4f161239d757491d9cc1c650affb.png)

### 六、热力学

符号规定：  
V : 体 积 V:体积 V:体积  
P : 压 强 P:压强 P:压强  
T : 温 度 T:温度 T:温度  
ν : 摩 尔 数 \nu:摩尔数 ν:摩尔数  
R : 普 适 气 体 常 数 = 8.31 ( J ⋅ m o l − 1 ⋅ K − 1 ) R:普适气体常数 = 8.31(J\cdot mol^{-1}\cdot K^{-1}) R:普适气体常数=8.31(J⋅mol−1⋅K−1)  
A : 功 A:功 A:功  
Q : 热 量 Q:热量 Q:热量  
E : 内 能 E:内能 E:内能  
γ : 热 容 比 C p C v \gamma:热容比\frac{C_p}{C_v} γ:热容比Cv​Cp​​

平衡态：在没有外界影响的情况下，系统各部分的宏观性质在长时间内不发生变化的状态  
准静态过程：热力学过程中，系统从某一状态开始经历一系列的中间状态达到另一状态的过程，如果过程进行的无限缓慢，则在这个过程中系统经历的每一个中间态都可以看作平衡态  
理想气体状态方程：  
P V = ν R T PV = \nu RT PV=νRT  
热力学第一定律：  
系统从外界吸收的热量Q，一部分使其内能增加 Δ E ， 另 一 部 分 用 以 对 外 界 做 功 \Delta E，另一部分用以对外界做功 ΔE，另一部分用以对外界做功  
即 Q = E 2 − E 1 + A Q = E_2-E_1+A Q=E2​−E1​+A  
功和热量的计算：  
A = ∫ V 1 V 2 p d V A = \int_{V_1}^{V_2}pdV A=∫V1​V2​​pdV  
注：气体向真空自由膨胀时，不做功  
两个常用热容：  
定容摩尔热容： C v = ( d Q d T ) v C_v = (\frac{dQ}{dT})_v Cv​=(dTdQ​)v​  
定压摩尔热容： C p = ( d Q d T ) p C_p = (\frac{dQ}{dT})_p Cp​=(dTdQ​)p​  
C p = C v + R C_p = C_v + R Cp​=Cv​+R  
Q = ν ∫ T 1 T 2 C x d T Q = \nu\int_{T_1}^{T_2}C_xdT Q=ν∫T1​T2​​Cx​dT  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/26ea525dd294ba51e86aed671407d94d.png)  
热力学第一定律对理想气体在典型准静态过程中的应用：  
1、等体过程：  
A = 0 A = 0 A=0  
Q = ν C v ( T 2 − T 1 ) Q = \nu C_v(T_2 - T_1) Q=νCv​(T2​−T1​)  
Δ E = Q \Delta E = Q ΔE=Q  
2、等压过程：  
A = p ( V 2 − V 1 ) = ν R ( T 2 − T 1 ) A = p(V_2 - V_1) = \nu R (T_2 - T_1) A=p(V2​−V1​)=νR(T2​−T1​)  
Q = ν C p ( T 2 − T 1 ) Q = \nu C_p(T_2 - T_1) Q=νCp​(T2​−T1​)  
Δ E = ν C v ( T 2 − T 1 ) \Delta E = \nu C_v(T_2 - T_1) ΔE=νCv​(T2​−T1​)  
3、等温过程：  
A = ∫ V 1 V 2 p d V = ∫ V 1 V 2 ν R T V d V = ν R T l n V 2 V 1 = ν R T l n p 1 p 2 A = \int_{V_1}^{V_2}pdV = \int _{V_1}^{V_2}\frac{\nu RT}{V}dV = \nu RT ln\frac{V_2}{V_1} = \nu RT ln\frac{p_1}{p_2} A=∫V1​V2​​pdV=∫V1​V2​​VνRT​dV=νRTlnV1​V2​​=νRTlnp2​p1​​  
Q = A Q = A Q=A  
Δ E = 0 \Delta E = 0 ΔE=0

绝热过程  
p V γ = C 1 pV^\gamma = C_1 pVγ=C1​  
T V γ = C 2 TV^\gamma = C_2 TVγ=C2​  
p γ − 1 T − γ = C 3 p^{\gamma -1}T^{-\gamma} = C_3 pγ−1T−γ=C3​  
A = ∫ V 1 V 2 p d V = ∫ V 1 V 2 p 1 V 1 γ d V V γ = 1 γ − 1 ( p 1 V 1 − p 2 V 2 ) 因 为 [ p 1 V 1 γ = p 2 V 2 γ = p V γ ] A = \int_{V_1}^{V_2}pdV = \int_{V_1}^{V_2}p_1V_1^\gamma\frac{dV}{V^\gamma} = \frac{1}{\gamma - 1}(p_1V_1 - p_2V_2)因为[p1V_1^\gamma = p_2V_2^\gamma = pV^\gamma] A=∫V1​V2​​pdV=∫V1​V2​​p1​V1γ​VγdV​=γ−11​(p1​V1​−p2​V2​)因为[p1V1γ​=p2​V2γ​=pVγ]  
Q = 0 Q = 0 Q=0  
Δ E = − A \Delta E = -A ΔE=−A  
如何判断等温线和绝热线  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/32ced12d2c6dd40f9784163b220f575c.png)  
由于 γ > 1 \gamma >1 γ>1所以绝热线比等温线要陡  
绝热自由膨胀：  
Δ E = 0 A = 0 Q = 0 \Delta E = 0 A = 0 Q = 0 ΔE=0A=0Q=0  
该过程不是准静态过程，所以热力学许多方程均不适用  
循环过程：  
Δ E = 0 \Delta E = 0 ΔE=0  
1、正循环（热机循环）（顺时针）  
Q = A > 0 Q = A > 0 Q=A>0  
系统从高温热源吸收热量 Q 1 Q_1 Q1​一部分转化为做功A，另一部分以热量形式是放到低温热源去  
热机效率： η = A Q 1 = Q 1 − Q 2 Q 1 = 1 − Q 2 Q 1 \eta = \frac{A}{Q_1} = \frac{Q_1-Q_2}{Q_1} = 1 - \frac{Q_2}{Q_1} η=Q1​A​=Q1​Q1​−Q2​​=1−Q1​Q2​​  
2、逆循环（制冷循环）（逆时针）  
系统做功A，使其从低温热源吸收 Q 2 Q_2 Q2​的热量，连同A的能量以热量形式 Q 1 Q_1 Q1​释放到高温热源去  
制冷系数： ω = Q 2 A = Q 2 Q 1 − Q 2 \omega = \frac{Q_2}{A} = \frac{Q_2}{Q_1-Q_2} ω=AQ2​​=Q1​−Q2​Q2​​  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/366ab75550d735afd76dfbaa2d274aa7.png)  
卡诺循环：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/bffc5f239de504a8deb97eb73a3b4063.png)  
DC、AB为绝热过程  
AD、BC为等温过程  
T 1 V 2 γ − 1 = T 2 V 3 γ − 1 T_1V_2^{\gamma -1} = T_2V_3^{\gamma-1} T1​V2γ−1​=T2​V3γ−1​  
T 1 V 1 γ − 1 = T 2 V 4 γ − 1 T_1V_1^{\gamma -1} = T_2V_4^{\gamma-1} T1​V1γ−1​=T2​V4γ−1​  
则， V 2 V 1 = V 3 V 4 \frac{V_2}{V_1} = \frac{V_3}{V_4} V1​V2​​=V4​V3​​  
Q 1 = ν R T 1 l n V 2 V 1 Q_1 = \nu RT_1ln{\frac{V_2}{V_1}} Q1​=νRT1​lnV1​V2​​  
Q 2 = ν R T 2 l n V 3 V 4 Q_2 = \nu RT_2ln{\frac{V_3}{V_4}} Q2​=νRT2​lnV4​V3​​  
故，若做正循环，热机效率为 η = A Q 1 = 1 − T 2 T 1 \eta = \frac{A}{Q_1} = 1-\frac{T_2}{T_1} η=Q1​A​=1−T1​T2​​  
若做逆循环，制冷效率为 η = Q 2 A = 1 − T 2 T 1 − T 2 \eta = \frac{Q_2}{A} = 1-\frac{T_2}{T_1-T_2} η=AQ2​​=1−T1​−T2​T2​​

热力学第二定律  
1、开尔文表述：不可能从单一热源吸热，使之完全转化为功，而不引起其它变化  
2、克劳修斯表述：不可能将热量从低温物体传向高温物体而不引起其他变化  
这两种表述是等价的  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/675674a0f62ab93415a6425384936fc9.png)  
可逆与不可逆过程：  
可逆过程：若系统经历了一个过程，而过程的每一步都可以沿相反方向进行，同时不引起外界的任何变化  
不可逆过程：如对某一过程，用任何方法都不能使系统和外界恢复到原来的状态  
热力学第二定律的本质就解释了自然界的一切自发过程都是单方向进行的不可逆过程  
可逆卡诺热机的效率是最高的

### 七、气体动理论

符号规定：  
V : 体 积 V:体积 V:体积  
p : 压 强 p:压强 p:压强  
T : 温 度 T:温度 T:温度  
μ : 分 子 质 量 \mu:分子质量 μ:分子质量  
R : 普 适 气 体 常 数 = 8.31 ( J ⋅ m o l − 1 ⋅ K − 1 ) R:普适气体常数 = 8.31(J\cdot mol^{-1}\cdot K^{-1}) R:普适气体常数=8.31(J⋅mol−1⋅K−1)  
N : 分 子 总 数 N:分子总数 N:分子总数  
n : 分 子 密 度 n:分子密度 n:分子密度  
K : 波 尔 兹 曼 常 数 1.38 × 1 0 − 23 J / K K:波尔兹曼常数 1.38 \times10^{-23}J/K K:波尔兹曼常数1.38×10−23J/K其中 K = R N 0 K = \frac{R}{N_0} K=N0​R​  
N 0 : 阿 伏 伽 德 罗 常 数 6.02 × 1 0 23 N_0:阿伏伽德罗常数6.02 \times 10^{23} N0​:阿伏伽德罗常数6.02×1023  
M : 摩 尔 质 量 M:摩尔质量 M:摩尔质量  
Ω : 各 部 分 微 观 状 态 数 之 积 \Omega:各部分微观状态数之积 Ω:各部分微观状态数之积  
S : 熵 S:熵 S:熵  
标 准 状 态 : 0 摄 氏 度 , 101 k p a 标准状态:0摄氏度,101kpa 标准状态:0摄氏度,101kpa  
0 摄 氏 度 = 273.15 开 尔 文 0 摄氏度 = 273.15 开尔文 0摄氏度=273.15开尔文

平衡状态时，气体分子沿各个方向的运动概率相等，则 v ‾ x 2 = v ‾ y 2 = v ‾ z 2 = 1 3 v ‾ 2 \overline v_x^2 = \overline v_y^2 =\overline v_z^2 = \frac{1}{3}\overline v^2 vx2​=vy2​=vz2​=31​v2  
理想气体的微观模型：  
1、忽略分子大小  
2、除碰撞一瞬间外，分子间作用力忽略不计，分子做自由运动  
3、分子与分子之间，分子与容器之间的碰撞为完全弹性碰撞  
p = n μ v ‾ x 2 = n μ ( 1 3 v ‾ 2 ) = 2 3 n ( 1 2 μ v ‾ 2 ) = 2 3 n ε ‾ p = n\mu \overline v_x^2 = n\mu(\frac{1}{3}\overline v^2) = \frac{2}{3}n(\frac{1}{2}\mu \overline v^2) = \frac{2}{3}n\overline\varepsilon p=nμvx2​=nμ(31​v2)=32​n(21​μv2)=32​nε  
分子平均动能为： ε ‾ = 1 2 μ v ‾ 2 \overline\varepsilon = \frac{1}{2}\mu\overline v^2 ε=21​μv2  
麦克斯韦速率分布规律：  
f ( v ) d v = d N N f(v)dv = \frac{dN}{N} f(v)dv=NdN​曲线下面积表示该区间的分子数比率  
分子速率的三种统计平均值：  
1、平均速率： v ‾ = ∫ 0 ∞ v f ( v ) d v = 8 K T μ π = 8 R T M π \overline v = \int_0^\infty vf(v)dv = \sqrt{\frac{8KT}{\mu\pi}} = \sqrt{\frac{8RT}{M\pi}} v=∫0∞​vf(v)dv=μπ8KT​ ​=Mπ8RT​ ​  
2、方均根速率： v ‾ 2 = 1 N ∫ 0 ∞ v 2 d v = ∫ 0 ∞ v 2 f ( v ) d v = 3 K T μ \overline v^2 = \frac{1}{N}\int_0^\infty v^2dv = \int_0^\infty v^2f(v)dv = \frac{3KT}{\mu} v2=N1​∫0∞​v2dv=∫0∞​v2f(v)dv=μ3KT​  
v ‾ 2 = 3 K T μ = 3 R T M \sqrt{\overline v^2} = \sqrt{\frac{3KT}{\mu}} = \sqrt{\frac{3RT}{M}} v2 ​=μ3KT​ ​=M3RT​ ​  
3、最概燃速率： v p = 2 K T μ = 2 R T M v_p = \sqrt{\frac{2KT}{\mu}} = \sqrt\frac{2RT}{M} vp​=μ2KT​ ​=M2RT​ ​  
![在这里插入图片描述](https://i-blog.csdnimg.cn/blog_migrate/b5840e3fbe6943560deffc098d91613e.png)  
温度的微观本质：  
理想气体的平均平动动能： ε ‾ = 1 2 μ v ‾ 2 = 3 2 K T \overline\varepsilon = \frac{1}{2}\mu \overline v^2 =\frac{3}{2}KT ε=21​μv2=23​KT  
温度是分子热运动剧烈程度的度量，反映了分子无规则热运动的剧烈程度  
由 p = 2 3 n ε ‾ p = \frac{2}{3}n\overline\varepsilon p=32​nε 和 ε ‾ = 3 2 K T \overline\varepsilon = \frac{3}{2}KT ε=23​KT得 p = n K T p = nKT p=nKT  
能量按自由度均分原理：  
单原子分子：3个平动自由度  
双原子分子：5个平动自由度  
多原子分子：6个平动自由度  
温度为T的平衡状态下，在分子的每个自由度上的平均的分配有 K T 2 \frac{KT}{2} 2KT​的能量  
理想气体的内能：  
E = i 2 R T E = \frac{i}{2}RT E=2i​RT  
分子平均碰撞频率：  
Z ‾ = 2 n π d 2 8 R T M π \overline Z = \sqrt{2}n\pi d^2\frac{8RT}{M\pi} Z=2 ​nπd2Mπ8RT​  
分子的平均自由程：  
λ ‾ = ν ‾ Z ‾ = 1 2 π d 2 n = K T 2 n d 2 p \overline \lambda = \frac{\overline \nu}{\overline Z} = \frac{1}{\sqrt{2}\pi d^2 n} = \frac{KT}{\sqrt{2}nd^2p} λ=Zν​=2 ​πd2n1​=2 ​nd2pKT​  
熵：  
S = K l n Ω S = Kln\Omega S=KlnΩ  
可逆过程： Δ S = 0 \Delta S = 0 ΔS=0  
熵增原理： Δ S ≥ 0 \Delta S \geq 0 ΔS≥0

### 参考资料

[1] https://wenku.baidu.com/view/093e9d3cc850ad02df804110.html 百度文库 louyc288 2018.6.26  
[2]https://zhuanlan.zhihu.com/p/40823585 知乎 linmue-谭祥军 2018-07-29​  
[3]https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1591022055237&di=8d82854691e80dcb696f0f7bf9a6cbb3&imgtype=0&src=http%3A%2F%2Fh.hiphotos.baidu.com%2Fzhidao%2Fwh%253D450%252C600%2Fsign%3D424491a3af51f3dec3e7b160a1dedc29%2F6a600c338744ebf8c51e3d56d9f9d72a6059a768.jpg  
[4]http://www.51wendang.com/pic/58299afefe74d56f505d26b1/8-810-jpg_6-1080-0-0-1080.jpg  
[5]https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1591071656568&di=3a30414ce35726e500703572d455f309&imgtype=0&src=http%3A%2F%2Fe.hiphotos.baidu.com%2Fbaike%2Fs%253D290%2Fsign%3D1a7dd6d87cd98d1072d40b38113eb807%2Fb2de9c82d158ccbf5821f51e19d8bc3eb1354170.jpg  
[6]https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3124615832,3581950698&fm=26&gp=0.jpg  
[7]https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1591073223292&di=989dd08bbc18aeb64419511ca31c6924&imgtype=0&src=http%3A%2F%2Fgss0.baidu.com%2F9fo3dSag_xI4khGko9WTAnF6hhy%2Fzhidao%2Fpic%2Fitem%2F18d8bc3eb13533fa681f635fa8d3fd1f41345b12.jpg  
[8]https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1135769897,1428545594&fm=26&gp=0.jpg  
[9]https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=2942328315,1350693005&fm=26&gp=0.jpg