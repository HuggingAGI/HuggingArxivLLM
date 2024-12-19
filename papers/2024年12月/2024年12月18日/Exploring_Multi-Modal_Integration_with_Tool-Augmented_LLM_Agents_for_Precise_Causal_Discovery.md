# 探索借助工具增强的 LLM 代理实现多模态集成，从而达成精确的因果发现

发布时间：2024年12月18日

`Agent` `智能健康` `药物发现`

> Exploring Multi-Modal Integration with Tool-Augmented LLM Agents for Precise Causal Discovery

# 摘要

> 因果推断是诸如智能健康、药物发现的人工智能和 AIOps 等领域决策的关键基础。传统的统计因果发现方法虽已成熟，却主要依赖观测数据，往往忽视因果关系中内在的语义线索。大型语言模型（LLMs）的出现开启了利用语义线索进行知识驱动因果发现的可行途径，然而用于因果发现的 LLMs 发展滞后于其他领域，尤其在多模态数据的探索上。为填补这一空缺，我们推出了 MATMCD，一个由工具增强型 LLMs 驱动的多智能体系统。MATMCD 有两个关键代理：一个是负责检索和处理模态增强数据的数据增强代理，一个是整合多模态数据进行知识驱动推理的因果约束代理。其内部工作机制的精心设计确保了代理之间的成功协作。我们对七个数据集的实证研究显示，多模态增强的因果发现潜力巨大。

> Causal inference is an imperative foundation for decision-making across domains, such as smart health, AI for drug discovery and AIOps. Traditional statistical causal discovery methods, while well-established, predominantly rely on observational data and often overlook the semantic cues inherent in cause-and-effect relationships. The advent of Large Language Models (LLMs) has ushered in an affordable way of leveraging the semantic cues for knowledge-driven causal discovery, but the development of LLMs for causal discovery lags behind other areas, particularly in the exploration of multi-modality data. To bridge the gap, we introduce MATMCD, a multi-agent system powered by tool-augmented LLMs. MATMCD has two key agents: a Data Augmentation agent that retrieves and processes modality-augmented data, and a Causal Constraint agent that integrates multi-modal data for knowledge-driven inference. Delicate design of the inner-workings ensures successful cooperation of the agents. Our empirical study across seven datasets suggests the significant potential of multi-modality enhanced causal discovery.

[Arxiv](https://arxiv.org/abs/2412.13667)