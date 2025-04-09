

构造无风险资产：

构造投资组合 $\Pi$ ：一单位衍生品空头和 $\delta$ 单位的标的资产多头，i．e．，
$$
\Pi_t=-f_t+\delta S_t
$$

选取 $\delta$ 使得该投资组合为无风险资产：

$$
\begin{aligned}
& d \Pi_t=-d f_t+\delta d S_t \\
& =-\left(\frac{\partial f}{\partial t}+\frac{\partial f}{\partial S} \mu S+\frac{1}{2} \frac{\partial^2 f}{\partial S^2} \sigma^2 S^2\right) d t-\frac{\partial f}{\partial S} \sigma S d W(t)+\delta(\mu S d t+\sigma S d W(t)) \\
& =\left(\delta \mu S-\left(\frac{\partial f}{\partial t}+\frac{\partial f}{\partial S} \mu S+\frac{1}{2} \frac{\partial^2 f}{\partial S^2} \sigma^2 S^2\right)\right) d t+\left(\delta-\frac{\partial f}{\partial S}\right) \sigma S d W(t)
\end{aligned}
$$


因为无风险资产随机项为 0 ，我们可推出

$$
\delta=\frac{\partial f}{\partial S} .
$$
无风险资产 $\Pi_t$ 应该满足

$$
d \Pi_t=r \Pi_t d t=r\left(-f_t+\delta S_t\right) d t
$$


比较＂实际＂价格：将 $\delta=\frac{\partial f}{\partial S}$ 代入（1）－（2），对比发现

$$
d \Pi_t=-\left(\frac{\partial f}{\partial t}+\frac{1}{2} \frac{\partial^2 f}{\partial S^2} \sigma^2 S^2\right) d t=r\left(-f_t+\frac{\partial f}{\partial S} S_t\right) d t
$$


合并同类项得，

$$
r f_t=\frac{\partial f}{\partial t}+r S \frac{\partial f}{\partial S}+\frac{1}{2} \frac{\partial^2 f}{\partial S^2} \sigma^2 S^2
$$