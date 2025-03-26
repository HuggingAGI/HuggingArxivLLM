# 安全的人类反馈强化学习（RLHF-V）：多模态大语言模型的安全强化学习方法

发布时间：2025年03月22日

`LLM应用` `人工智能` `人工智能安全`

> Safe RLHF-V: Safe Reinforcement Learning from Human Feedback in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）是通用人工智能助手开发的核心，但其安全风险日益凸显。如何确保MLLMs安全对齐，避免歧视、虚假信息或道德失范等不良行为？进一步而言，我们需要探索如何在确保安全约束的前提下，通过微调MLLMs来提升推理性能。从本质上讲，这可以被建模为一个最小化最大化的优化问题。

在本研究中，我们提出了Safe RLHF-V，这是首个多模态安全对齐框架。它在一个基于拉格朗日的约束优化框架内，使用独立的多模态奖励和成本模型，同时优化有用性和安全性。鉴于现有数据集中缺乏在多模态场景下区分有用性和安全性的能力，我们推出了BeaverTails-V——首个开源数据集，附带双偏好注释（针对有用性和安全性）以及多级安全标签（轻微、中度、严重）。此外，我们设计了一个多级护栏系统，用于主动防御不安全查询和对抗攻击。

通过在前驱模型上应用Beaver-Guard-V审核进行5轮过滤和重新生成，上游模型的整体安全性平均提升了40.9%。实验结果表明，使用Safe RLHF微调不同的MLLMs，可以有效提升模型的有用性，同时确保安全性得到显著改善。具体而言，Safe RLHF-V将模型安全性提升了34.2%，有用性提升了34.3%。所有数据集、模型和代码均可在https://github.com/SafeRLHF-V上找到，以支持MLLMs的安全开发并减少潜在的社会风险。

> Multimodal large language models (MLLMs) are critical for developing general-purpose AI assistants, yet they face growing safety risks. How can we ensure that MLLMs are safely aligned to prevent undesired behaviors such as discrimination, misinformation, or violations of ethical standards? In a further step, we need to explore how to fine-tune MLLMs to enhance reasoning performance while ensuring they satisfy safety constraints. Fundamentally, this can be formulated as a min-max optimization problem. In this study, we propose Safe RLHF-V, the first multimodal safety alignment framework that jointly optimizes helpfulness and safety using separate multimodal reward and cost models within a Lagrangian-based constrained optimization framework. Given that there is a lack of preference datasets that separate helpfulness and safety in multimodal scenarios, we introduce BeaverTails-V, the first open-source dataset with dual preference annotations for helpfulness and safety, along with multi-level safety labels (minor, moderate, severe). Additionally, we design a Multi-level Guardrail System to proactively defend against unsafe queries and adversarial attacks. By applying the Beaver-Guard-V moderation for 5 rounds of filtering and re-generation on the precursor model, the overall safety of the upstream model is significantly improved by an average of 40.9%. Experimental results demonstrate that fine-tuning different MLLMs with Safe RLHF can effectively enhance model helpfulness while ensuring improved safety. Specifically, Safe RLHF-V improves model safety by 34.2% and helpfulness by 34.3%. All of datasets, models, and code can be found at https://github.com/SafeRLHF-V to support the safety development of MLLMs and reduce potential societal risks.

[Arxiv](https://arxiv.org/abs/2503.17682)