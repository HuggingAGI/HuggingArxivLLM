# 探索离线强化学习在大型语言模型推理中的潜力：一项初步研究

发布时间：2025年05月04日

`LLM理论` `机器学习`

> Exploring the Potential of Offline RL for Reasoning in LLMs: A Preliminary Study

# 摘要

> 尽管大型语言模型（LLMs）在长上下文推理方面取得了显著进展，主要通过在线强化学习（RL）方法实现，但这些方法带来了巨大的计算成本和复杂性。相比之下，更简单且经济的离线RL方法仍未得到充分探索。为填补这一空白，我们研究了离线RL方法，特别是直接偏好优化（DPO）及其对长度不敏感的变体LD-DPO，在提升LLMs推理能力方面的有效性。在多个推理基准上的广泛实验表明，这些更简单的离线RL方法显著提升了模型性能，平均提升了3.3%，在具有挑战性的Arena-Hard基准上更是显著提升了10.1%。此外，我们分析了DPO对输出长度的敏感性，强调增加推理长度应与语义丰富性相匹配，因为不加选择地增加长度可能对模型性能产生不利影响。我们对数据处理和训练方法提供了全面描述，为开发更具成本效益的离线RL方法提供了实证依据和实用见解。

> Despite significant advances in long-context reasoning by large language models (LLMs), primarily through Online Reinforcement Learning (RL) methods, these approaches incur substantial computational costs and complexity. In contrast, simpler and more economical Offline RL methods remain underexplored. To address this gap, we investigate the effectiveness of Offline RL methods, specifically Direct Preference Optimization (DPO) and its length-desensitized variant LD-DPO, in enhancing the reasoning capabilities of LLMs. Extensive experiments across multiple reasoning benchmarks demonstrate that these simpler Offline RL methods substantially improve model performance, achieving an average enhancement of 3.3\%, with a particularly notable increase of 10.1\% on the challenging Arena-Hard benchmark. Furthermore, we analyze DPO's sensitivity to output length, emphasizing that increasing reasoning length should align with semantic richness, as indiscriminate lengthening may adversely affect model performance. We provide comprehensive descriptions of our data processing and training methodologies, offering empirical evidence and practical insights for developing more cost-effective Offline RL approaches.

[Arxiv](https://arxiv.org/abs/2505.02142)