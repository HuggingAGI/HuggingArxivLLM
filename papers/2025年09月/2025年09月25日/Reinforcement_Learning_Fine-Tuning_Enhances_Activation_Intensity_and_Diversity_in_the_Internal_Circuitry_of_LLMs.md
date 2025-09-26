# 强化学习微调提升LLMs内部电路的激活强度与多样性

发布时间：2025年09月25日

`强化学习` `基础理论`

> Reinforcement Learning Fine-Tuning Enhances Activation Intensity and Diversity in the Internal Circuitry of LLMs

# 摘要

> 大型语言模型（LLMs）通过大规模预训练积累了海量先验知识，而监督微调（SFT）或基于强化学习（RL）的后训练能进一步提升其性能。越来越多的研究证实，RL微调能让LLM的性能超越单纯SFT的效果。但RL微调究竟为何能提升不同内在特性LLM的性能，其深层机制尚未得到充分揭示。为此，本研究借鉴边缘归因修补（EAP）的先前成果，深入探究了LLM在RL微调前后的内部变化。通过对多个模型家族的分析，我们发现在线RL后训练存在两个稳健效应：（i）激活强度全面提升，意味着更多内部通路被激活且信号增强；（ii）激活模式多样性增加，具体表现为熵值更高、边缘分布更分散。这些变化意味着RL重塑了LLM的信息流，使其兼具更高的冗余性和灵活性——这或许正是其泛化能力出众的原因。值得注意的是，采用直接偏好优化（DPO）微调的模型则偏离了上述趋势：与PPO、GRPO训练的模型相比，其内部变化明显更弱或不一致。综上，我们的研究揭示了RL微调如何系统性地改变LLM的内部“电路”，并阐明了在线RL与基于偏好的方法在技术路径上的差异。相关代码已开源（https://anonymous.4open.science/r/llm_rl_probing_analysis-F673）。

> Large language models (LLMs) acquire extensive prior knowledge through large-scale pretraining and can be further enhanced via supervised fine-tuning (SFT) or reinforcement learning (RL)-based post-training. A growing body of evidence has shown that RL fine-tuning improves the capability of LLMs beyond what SFT alone achieves. However, the underlying mechanisms why RL fine-tuning is able to enhance the capability of various LLMs with distinct intrinsic characteristics remain underexplored. In this study, we draw inspiration from prior work on edge attribution patching (EAP) to investigate the internal differences of LLMs before and after RL fine-tuning. Our analysis across multiple model families shows two robust effects of online RL post-training: (i) an overall increase in activation intensity, indicating that more internal pathways are engaged and their signals become stronger, and (ii) greater diversity in activation patterns, reflected by higher entropy and less concentrated edge distributions. These changes suggest that RL reshapes information flow to be both more redundant and more flexible, which may explain its advantage in generalization. Notably, models fine-tuned with Direct Preference Optimization (DPO) deviate from these trends, exhibiting substantially weaker or inconsistent internal changes compared to PPO- and GRPO-based training. Together, our findings provide a unified view of how RL fine-tuning systematically alters the internal circuitry of LLMs and highlight the methodological distinctions between online RL and preference-based approaches. Our code is open source at https://anonymous.4open.science/r/llm_rl_probing_analysis-F673.

[Arxiv](https://arxiv.org/abs/2509.21044)