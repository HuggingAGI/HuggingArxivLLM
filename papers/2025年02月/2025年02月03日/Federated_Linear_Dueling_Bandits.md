# 联邦线性对决赌博机

发布时间：2025年02月03日

`Agent

理由：这篇论文主要讨论了多个代理在推荐系统和大型语言模型等领域的协作问题，特别是通过联邦学习的方式提升性能。论文的核心内容涉及多个代理的协作和优化，这与“Agent”分类密切相关。虽然论文也提到了大型语言模型，但其重点在于代理的协作和优化，而不是直接讨论LLM的应用或理论。因此，将其分类为“Agent”更为合适。` `推荐系统` `联邦学习`

> Federated Linear Dueling Bandits

# 摘要

> # 摘要
上下文线性对决赌博机（Contextual linear dueling bandits）因其在推荐系统和大型语言模型等领域的广泛应用而备受关注。经典的对决赌博机算法通常只适用于单个代理，但在实际应用中，多个代理往往希望通过协作提升性能，却不愿共享数据。这促使我们借鉴联邦学习的思路，即多个代理通过梯度下降（GD）协作训练神经网络，而无需共享原始数据。此前的研究已开发出依赖赌博机参数闭式更新的联邦线性赌博机算法，但在线性对决赌博机中，线性函数参数缺乏闭式表达式，需通过最小化损失函数进行估计，导致这些方法不再适用。为此，我们创新性地结合在线梯度下降（用于估计线性函数参数）和联邦学习，首次提出了联邦线性对决赌博机算法。通过严格的理论分析，我们证明了该算法的累积遗憾具有次线性上界，并通过实验验证了其有效性和协作的实际优势。

> Contextual linear dueling bandits have recently garnered significant attention due to their widespread applications in important domains such as recommender systems and large language models. Classical dueling bandit algorithms are typically only applicable to a single agent. However, many applications of dueling bandits involve multiple agents who wish to collaborate for improved performance yet are unwilling to share their data. This motivates us to draw inspirations from federated learning, which involves multiple agents aiming to collaboratively train their neural networks via gradient descent (GD) without sharing their raw data. Previous works have developed federated linear bandit algorithms which rely on closed-form updates of the bandit parameters (e.g., the linear function parameter) to achieve collaboration. However, in linear dueling bandits, the linear function parameter lacks a closed-form expression and its estimation requires minimizing a loss function. This renders these previous methods inapplicable. In this work, we overcome this challenge through an innovative and principled combination of online gradient descent (for minimizing the loss function to estimate the linear function parameters) and federated learning, hence introducing the first federated linear dueling bandit algorithms. Through rigorous theoretical analysis, we prove that our algorithms enjoy a sub-linear upper bound on its cumulative regret. We also use empirical experiments to demonstrate the effectiveness of our algorithms and the practical benefit of collaboration.

[Arxiv](https://arxiv.org/abs/2502.01085)