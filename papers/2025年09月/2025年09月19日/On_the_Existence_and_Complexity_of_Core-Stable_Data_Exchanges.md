# 论核稳定数据交换的存在性与复杂性

发布时间：2025年09月19日

`Agent` `基础理论`

> On the Existence and Complexity of Core-Stable Data Exchanges

# 摘要

> 数据驱动技术的迅猛发展与各类数据共享范式的兴起，凸显了高效稳定的数据交换协议的必要性。在这类数据交换中，代理需谨慎权衡获取有价值数据的收益与共享自身数据的成本。确保交换的稳定性是防止代理（或代理群体）脱离并自行开展本地（可能更有利的）交换的关键。为此，我们研究了一个代理参与数据交换的模型：每个代理从其他代理处获取数据可获得收益，共享自身数据则需付出成本，净效用为收益与成本之差。我们将合作博弈论中的经典核心稳定性概念引入数据交换场景，定义核心稳定的数据交换为：不存在任何代理子集有动机脱离当前交换而进行其他交换。我们证明，当代理的收益函数为凹函数、成本函数为凸函数时，核心稳定的数据交换一定存在——这一设定在PAC学习、随机发现模型等领域十分常见。同时，若放宽上述任一条件，核心稳定的数据交换便可能不复存在。随后，我们证明寻找核心稳定交换是PPAD难问题，即便潜在阻碍联盟的规模被限制为常数；据我们所知，这是数据经济学领域首个关于核心类保证的PPAD难结果。最后，我们证明数据交换可建模为平衡n人博弈，并基于斯卡夫定理\cite{Scarf1967core}推导出旋转算法。实证结果表明，该算法在实际应用中表现优异。

> The rapid growth of data-driven technologies and the emergence of various data-sharing paradigms have underscored the need for efficient and stable data exchange protocols. In any such exchange, agents must carefully balance the benefit of acquiring valuable data against the cost of sharing their own. Ensuring stability in these exchanges is essential to prevent agents -- or groups of agents -- from departing and conducting local (and potentially more favorable) exchanges among themselves. To address this, we study a model where agents participate in a data exchange. Each agent has an associated payoff for the data acquired from other agents and a cost incurred during sharing its own data. The net utility of an agent is payoff minus the cost. We adapt the classical notion of core-stability from cooperative game theory to data exchange. A data exchange is core-stable if no subset of agents has any incentive to deviate to a different exchange. We show that a core-stable data exchange is guaranteed to exist when agents have concave payoff functions and convex cost functions -- a setting typical in domains like PAC learning and random discovery models. We show that relaxing either of the foregoing conditions may result in the nonexistence of core-stable data exchanges. Then, we prove that finding a core-stable exchange is PPAD-hard, even when the potential blocking coalitions are restricted to constant size. To the best of our knowledge, this provides the first known PPAD-hardness result for core-like guarantees in data economics. Finally, we show that data exchange can be modelled as a balanced $n$-person game. This immediately gives a pivoting algorithm via Scarf's theorem \cite{Scarf1967core}. We show that the pivoting algorithm works well in practice through our empirical results.

[Arxiv](https://arxiv.org/abs/2509.16450)