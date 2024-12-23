# 数据驱动的机制设计：共同获取偏好与信息

发布时间：2024年12月20日

`Agent` `数字广告` `机制设计`

> Data-Driven Mechanism Design: Jointly Eliciting Preferences and Information

# 摘要

> 我们探究当代理对自身偏好以及共同的与收益相关的状态均持有私有信息时的机制设计。我们发现，当代理具有多维类型时，即便在有利条件下，标准的消息驱动机制也难以实现社会高效的分配。为突破这一局限，我们提出了数据驱动机制，借助额外的分配后信息，将其建模为与收益相关状态的估计器。我们的数据驱动机制拓展了经典的维克里 - 克拉克 - 格罗夫斯类。我们证明，当状态完全披露或者效用在无偏估计器中呈线性时，它们在后验均衡中能达成精确实施。我们还表明，它们借助一致估计器能实现近似实施，且随着估计器的收敛而趋近于精确实施，并给出了收敛速率的界限。我们展示了其在数字广告拍卖和基于大型语言模型（LLM）的机制中的应用，在这些场景中，用户的参与自然地揭示了相关信息。

> We study mechanism design when agents hold private information about both their preferences and a common payoff-relevant state. We show that standard message-driven mechanisms cannot implement socially efficient allocations when agents have multidimensional types, even under favorable conditions. To overcome this limitation, we propose data-driven mechanisms that leverage additional post-allocation information, modeled as an estimator of the payoff-relevant state. Our data-driven mechanisms extend the classic Vickrey-Clarke-Groves class. We show that they achieve exact implementation in posterior equilibrium when the state is either fully revealed or the utility is linear in an unbiased estimator. We also show that they achieve approximate implementation with a consistent estimator, converging to exact implementation as the estimator converges, and present bounds on the convergence rate. We demonstrate applications to digital advertising auctions and large language model (LLM)-based mechanisms, where user engagement naturally reveals relevant information.

[Arxiv](https://arxiv.org/abs/2412.16132)