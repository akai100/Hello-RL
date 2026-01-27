Markob decision process:

+ Sets
  + State：the sets of states S
  + Action: the set of actions A(s) is associated for state $s \in S$
  + Reward
+ Probility distribution
  +  State transition probabilitu: at state s, takina action a, the transit to state s' is p(s'|s, a)
  +  Reward probability: at state s， taking action a, the probability to get reward r is p(r|s, a)
+ Policy: at state s, the probability to choose action a is $\pi(a|s)$
+ Markov propertyL memoryless propery:

$$p(s_{t+1}|a_{t+1},s_t,...,a_1,s_0)=p(s_{t+1}|a_{t+1},s_t)$$
