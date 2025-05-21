# AdAEM：一种自适应且自动化的LLMs价值差异可扩展测量方法

发布时间：2025年05月18日

`LLM理论` `人工智能` `语言模型评估`

> AdAEM: An Adaptively and Automated Extensible Measurement of LLMs' Value Difference

# 摘要

> 评估大型语言模型（LLMs）的价值差异，能够全面比较它们的对齐程度、文化适应性及偏见。然而，现有的价值评估数据集面临信息性挑战：由于测试问题通常过时、受污染或过于通用，它们只能捕捉不同LLMs间共有的价值取向，导致结果饱和且缺乏信息量。为解决这一问题，我们引入AdAEM，一个新颖且可自我扩展的评估框架，用于揭示LLMs的倾向。与之前静态的基准测试不同，AdAEM能够自动且自适应地生成和扩展测试问题。这是通过以一种上下文优化的方式，探测跨文化和跨时期开发的多样化LLMs的内部价值边界来实现的。优化过程理论上最大化了一个信息论目标，以提取最新或具有文化争议的话题，从而提供关于模型价值差异的更具辨别力和信息量的见解。如此一来，AdAEM能够与LLMs的发展共同演进，持续追踪它们的价值动态。通过AdAEM，我们基于Schwartz价值理论生成了12,310个问题，进行了广泛的分析以证明我们方法的有效性和有效性，并对16个LLMs的价值进行了基准测试，为更好的价值研究奠定了基础。

> Assessing Large Language Models (LLMs)' underlying value differences enables comprehensive comparison of their misalignment, cultural adaptability, and biases. Nevertheless, current value measurement datasets face the informativeness challenge: with often outdated, contaminated, or generic test questions, they can only capture the shared value orientations among different LLMs, leading to saturated and thus uninformative results. To address this problem, we introduce AdAEM, a novel, self-extensible assessment framework for revealing LLMs' inclinations. Distinct from previous static benchmarks, AdAEM can automatically and adaptively generate and extend its test questions. This is achieved by probing the internal value boundaries of a diverse set of LLMs developed across cultures and time periods in an in-context optimization manner. The optimization process theoretically maximizes an information-theoretic objective to extract the latest or culturally controversial topics, providing more distinguishable and informative insights about models' value differences. In this way, AdAEM is able to co-evolve with the development of LLMs, consistently tracking their value dynamics. Using AdAEM, we generate 12,310 questions grounded in Schwartz Value Theory, conduct an extensive analysis to manifest our method's validity and effectiveness, and benchmark the values of 16 LLMs, laying the groundwork for better value research.

[Arxiv](https://arxiv.org/abs/2505.13531)