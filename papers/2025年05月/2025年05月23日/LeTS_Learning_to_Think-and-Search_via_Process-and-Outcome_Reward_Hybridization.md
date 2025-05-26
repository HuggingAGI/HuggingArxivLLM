# LeTS：通过过程与结果奖励的混合学习，掌握思考与搜索技能

发布时间：2025年05月23日

`RAG` `生成式AI` `RAG框架`

> LeTS: Learning to Think-and-Search via Process-and-Outcome Reward Hybridization

# 摘要

> 大型语言模型 (LLMs) 在推理能力方面展现出令人瞩目的表现，尤其以 OpenAI-o1 和 DeepSeek-R1 等推理模型的出现为标志。近期研究集中于通过成果监督的强化学习 (RL) 方法将推理能力整合到检索增强生成 (RAG) 领域，但通常忽视了中间思考与搜索步骤的正确性。为解决这一问题，我们设计了一个过程级奖励模块，以缓解成果监督中对中间推理步骤的忽视，无需额外标注。基于此，我们提出了学习思考与搜索 (LeTS)，这是一种结合分步过程奖励与成果奖励的新型框架，将其融入当前 RAG 的 RL 方法中。大量实验表明，LeTS 在多种 RAG 基准测试中展现出良好的泛化能力和推理效率。此外，这些结果还揭示了过程与成果奖励结合在其他场景下通过 RL 提升 LLMs 推理能力的潜力。代码即将发布。

> Large language models (LLMs) have demonstrated impressive capabilities in reasoning with the emergence of reasoning models like OpenAI-o1 and DeepSeek-R1. Recent research focuses on integrating reasoning capabilities into the realm of retrieval-augmented generation (RAG) via outcome-supervised reinforcement learning (RL) approaches, while the correctness of intermediate think-and-search steps is usually neglected. To address this issue, we design a process-level reward module to mitigate the unawareness of intermediate reasoning steps in outcome-level supervision without additional annotation. Grounded on this, we propose Learning to Think-and-Search (LeTS), a novel framework that hybridizes stepwise process reward and outcome-based reward to current RL methods for RAG. Extensive experiments demonstrate the generalization and inference efficiency of LeTS across various RAG benchmarks. In addition, these results reveal the potential of process- and outcome-level reward hybridization in boosting LLMs' reasoning ability via RL under other scenarios. The code will be released soon.

[Arxiv](https://arxiv.org/abs/2505.17447)