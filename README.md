# JavaStudy

假设有一个二分类问题，输出$$ y \in \{0, 1\} $$,而线性回归模型产生的预测值为$$ z = w^Tx + b $$,我们希望有一个理想的阶跃函数来帮我们实现z值到0/1值的转化。

$$ \begin{equation} \phi (z) = \begin{cases} 0 & \mbox{if z < 0}\\ 
0.5 & \mbox{if z = 0} \\
 1 & \mbox{if z > 0} \end{cases} \end{equation} $$
