# # **面向大型语言模型推理的多样性感知策略优化**

发布时间：2025年05月29日

`LLM理论` `人工智能`

> Diversity-Aware Policy Optimization for Large Language Model Reasoning

# 摘要

> 大型语言模型（LLMs）的推理能力在DeepSeek R1发布后得到了显著提升，这一突破激发了大量关于数据质量和强化学习（RL）算法的研究。尽管多样性在RL中至关重要，但其对LLM推理的影响尚未得到充分探索。为此，本研究系统地探讨了基于RL训练中多样性对LLM推理的影响，并提出了一种新型的多样性感知策略优化方法。通过对12个LLM的评估，我们发现高性能模型中解决方案多样性与Potential at k（衡量LLM推理潜力的新指标）之间存在显著的正相关关系。这一发现促使我们在RL训练中明确地促进多样性。具体来说，我们设计了一个基于token的多样性指标，并将其转化为实际目标，然后选择性地应用于正样本。将该方法集成到R1-zero训练框架中，我们在四个数学推理基准上实现了平均3.5%的性能提升，同时生成了更具多样性和鲁棒性的解决方案。

> The reasoning capabilities of large language models (LLMs) have advanced rapidly, particularly following the release of DeepSeek R1, which has inspired a surge of research into data quality and reinforcement learning (RL) algorithms. Despite the pivotal role diversity plays in RL, its influence on LLM reasoning remains largely underexplored. To bridge this gap, this work presents a systematic investigation into the impact of diversity in RL-based training for LLM reasoning, and proposes a novel diversity-aware policy optimization method. Across evaluations on 12 LLMs, we observe a strong positive correlation between the solution diversity and Potential at k (a novel metric quantifying an LLM's reasoning potential) in high-performing models. This finding motivates our method to explicitly promote diversity during RL training. Specifically, we design a token-level diversity and reformulate it into a practical objective, then we selectively apply it to positive samples. Integrated into the R1-zero training framework, our method achieves a 3.5 percent average improvement across four mathematical reasoning benchmarks, while generating more diverse and robust solutions.

[Arxiv](https://arxiv.org/abs/2505.23433)