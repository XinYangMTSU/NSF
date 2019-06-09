Reinforcement Learning (RL) originates from animal learning in psychology and thus it can mimic human learning ability to
select actions that maximize long-term profit in their interactions with the environment. An RL agent conducts a trial and
error (TE) procedure to gain experiences and improve itself over time. [1]

However, RL has faced great challenges when dealing with high-dimensional problems known as the curse of dimensionality, which
exceeds the computatonal constraint of conventional computers. 

In 2015, Min et al. [2] made an important breakthrough by combining deep learning with RL which partiallly overcomes
the challenge of high-dimentionality. Since then, deep RL has become a promissing approach to solving complex real-world
problems.


As real-world problems have become increasingly complicated, there are many situations where a single deep RL agent is not
able to cope with. In such situations, multi-agent system (MAS) have attracted great attention becasuse they are able to solve
complex tasks through the cooperation of individual agents.

Challenges:


(1) Non-stationarity

Controlling multiple agents poses several additional challenges as compared to single agent setting such as the heterogeneity
of agents. In a multi-agent domain, an agent observes not only the outcomes of its own action but also the behavior of other
agents. Learning among the agents is complex because all agents potentially interact with each other and learn concurrently.
In this case, learning among the agents sometimes causes changes in the policy of an agent, and can affect the optimal policy
of other agents. The estimated potential rewards of an action would be inaccurate and therefore, good policies at a given
point in the multi-agent setting could not remain so in the future.


(2) Partial observability

In real-world applications, there are many circumstances where agents only have partial observability of the environment. In
other words, complete information of states pertaining to the environment is not known to the agents when they interact with
the environment. In such situations, the agents observe partial information about the environment, and need to make the best
decision during each time step. 

(3) DRL is vulnerable to overfitting and computationally expensive [3]. 

(4) Continuous action spaces

Most deep RL models can only be applied to discrete spaces [4]. Discretising the action space is a possible solution to adapt
deep RL methods to continuous domains. However, this creates many problems, notably is the curse of dimensionality: the
exponential increase of action numbers against the number of degrees of freedom.

(5) In the heterogeneous setting with many agents, the key challenge is how to provide the most optimal solution and maximize
the task completion success based on self- learning with effective coordinative and cooperative strategies among the agents.
This is more problematic in hostile environments where communications among agents are limited and in scenarios that involve
more heterogeneous agents as the credit assignment problem become increasingly difficult. A research direction to address
these difficulties is well worth an investigation.



Reference:

[1]Nguyen, Thanh Thi, Ngoc Duy Nguyen, and Saeid Nahavandi. "Deep Reinforcement Learning for Multi-Agent Systems: A Review of Challenges, Solutions and Applications." arXiv preprint arXiv:1812.11794 (2018).

[2]Mnih, Volodymyr, et al. "Human-level control through deep reinforcement learning." Nature 518.7540 (2015): 529.

[3]Lanctot, Marc, et al. "A unified game-theoretic approach to multiagent reinforcement learning." Advances in Neural
Information Processing Systems. 2017.

[4]Lillicrap, Timothy P., et al. "Continuous control with deep reinforcement learning." arXiv preprint arXiv:1509.02971 (2015).
