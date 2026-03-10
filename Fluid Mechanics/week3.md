## Lesson1

关键词：Bernoulli’s equation,B.E，Pitot tube，stagnation pressure，Vena contracta，Coefficient of velocity（Cv）


检查实验所在小组
group 102
对比图表，了解自己需要在什么时候去参与实验
- [ ] 记得做moodle上面的测试

>10/24/2025 9：00-12：00
FLM1

>0/31/2025 15：00-18：00
ICH1

>11/7/2025 15：00-18：00
ICH2

>11/14/2025 15：00-18：00
PEF1、
周三上午9-10点中的课程，查找CEE PT，寻找自己以及对应老师，在日程表上看序号了解自己应该去哪一场。moodle上面找，已发送邮件。

有问题可以问LCF的代表（？）


boundary layer 边界层
turbulence湍流
laminar层流的

Bernoulli’s equation 伯努利方程（B.E）
压力能+动能+位能=常数
$$
\frac{p_1}{ρg}+\frac{v_1^2}{2g}+z+H_p=\frac{p_2}{ρg}+\frac{v_2^2}{2g}+z+H_L
$$
$H_p$是能量输入（泵的扬程）
$H_L$是能量损失（摩擦等）（水头的损失）

也可以写成
$$
\frac{1}{2}mv^2+mgz+PV=常数
$$

Pitot tube 皮托管：通过测量停滞压来推算流体速度的装置
>测量的是点速度，不是直接测体积流量

stagnation pressure 停滞压：流体在被等熵减速到零速度时所达到的压力

Vena contracta 缩流断面: 流体通过孔口或突然收缩后，射流横截面积达到最小、流速达到最大的位置
收缩系数
$C_c=\frac{A_c}{A_0}$
Ac是Vena contracta 的实际最小面积
A0是孔口的面积

Coefficient of velocity 黏度系数（Cv）：流体在出口处的实际平均速度与由伯努利方程预测的理想速度之比
$C_v=\frac{实际的速度}{理想速度}$
>实际速度更小

Coefficient of discharge 流量系数（Cd）：实际体积流量与由理想伯努利方程预测的理论流量之比
>实际流量更小

Obstruction flow meter 阻流式流量计
D:管道的内径（直径）
d:阻流处最窄处的直径
A:管道内部面积
$$
\frac{p_1}{ρg}+\frac{v_1^2}{2g}=\frac{p_2}{ρg}+\frac{v_2^2}{2g}
$$
和
$$
A_1V_1=A_2V_2
$$
可以推导出

$V_2^2=\frac{2(P_1-P_2)}{ρ(1-β^4)}$
($β=d/D$)

考虑到其他因素，用流量系数考虑这些影响
$
V_2^2=\frac{2(P_1-P_2)}{ρ(1-β^4)}*A_0^2C_d^2
$
($β=d/D$)


Velocity head = 当流体完全停止流动时所产生的液柱高度（动能）
Pressure head = 由压力产生的液柱的高度
Elevation head = 液体的液面高度（重力势能）

Energy grade line (EGL)：是一条表示流体所能获得的总扬程的曲线
hydraulic grade line (HGL) 显示的是若在管道中心位置取压时，液体会高出管道中心的高度

$$
EGL=HGL+\frac{V^2}{2g}
$$