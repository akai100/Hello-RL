定义：

$$q_{\pi}(s, a) = E[G_t|S_t = s, A_t = a]$$

从当前的状态 s 出发，采取动作 a 之后得到的 收益平均值

$$ E[G_t|S_t=s]=\sum_a{E[G_t|S_t=s, A_t=a]\pi(a|s)}$$

得到：

$$v_\pi(s)=\sum_a{\pi(a|s)q_\pi(s,a)}$$
