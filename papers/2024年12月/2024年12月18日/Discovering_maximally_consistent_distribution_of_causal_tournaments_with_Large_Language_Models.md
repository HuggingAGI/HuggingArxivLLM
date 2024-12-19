# 利用大型语言模型探寻因果竞赛的最大一致分布

发布时间：2024年12月18日

`LLM应用` `流行病学` `公共卫生`

> Discovering maximally consistent distribution of causal tournaments with Large Language Models

# 摘要

> 因果发现对于理解复杂系统意义重大，然而传统方法通常依赖于强烈且未经证实的假设，致使这一过程充满挑战。大型语言模型（LLMs）为从基于文本的元数据中获取因果洞察提供了颇具前景的替代途径，整合了领域专业知识。但 LLMs 容易出现不可靠和幻觉的情况，所以需要有应对其局限性的策略。其中一种策略是利用一致性度量来评估可靠性。另外，大多数文本元数据无法清晰区分直接因果关系和间接因果关系，进一步让因果图的推断变得复杂。因此，关注因果顺序而非因果图成为更实用且稳健的方法。我们提出了一种新的方法来推导无环竞赛（代表可能的因果顺序）的分布，以实现一致性得分的最大化。我们的方法首先计算变量之间的成对一致性得分，从而得到一个汇总这些得分的循环竞赛。基于此结构，我们找出与原始竞赛兼容的最优无环竞赛，优先考虑在所有配置中能使一致性最大化的竞赛。我们在经典且成熟的基准以及来自流行病学和公共卫生的真实世界数据集中测试了我们的方法。我们的结果表明，我们的方法在以最小误差恢复因果顺序分布方面成效显著。

> Causal discovery is essential for understanding complex systems, yet traditional methods often depend on strong, untestable assumptions, making the process challenging. Large Language Models (LLMs) present a promising alternative for extracting causal insights from text-based metadata, which consolidates domain expertise. However, LLMs are prone to unreliability and hallucinations, necessitating strategies that account for their limitations. One such strategy involves leveraging a consistency measure to evaluate reliability. Additionally, most text metadata does not clearly distinguish direct causal relationships from indirect ones, further complicating the inference of causal graphs. As a result, focusing on causal orderings, rather than causal graphs, emerges as a more practical and robust approach. We propose a novel method to derive a distribution of acyclic tournaments (representing plausible causal orders) that maximizes a consistency score. Our approach begins by computing pairwise consistency scores between variables, yielding a cyclic tournament that aggregates these scores. From this structure, we identify optimal acyclic tournaments compatible with the original tournament, prioritizing those that maximize consistency across all configurations. We tested our method on both classical and well-established bechmarks, as well as real-world datasets from epidemiology and public health. Our results demonstrate the effectiveness of our approach in recovering distributions causal orders with minimal error.

[Arxiv](https://arxiv.org/abs/2412.14019)