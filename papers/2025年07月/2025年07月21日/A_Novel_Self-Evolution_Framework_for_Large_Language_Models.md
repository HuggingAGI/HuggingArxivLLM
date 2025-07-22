# 大型语言模型的新型自我进化框架

发布时间：2025年07月21日

`LLM理论

理由：这篇论文提出了一种新的框架（DPSE），专注于优化大型语言模型的能力，特别是在用户偏好适应和领域认知方面。它属于模型理论层面的改进，因此归类为LLM理论。` `人工智能`

> A Novel Self-Evolution Framework for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的能力受预训练限制，为此研究人员通过后训练优化模型。现有策略如记忆检索或偏好优化虽能改善用户对齐，却无法提升模型领域认知。针对这一问题，我们提出双阶段自进化 (DPSE) 框架，同时优化用户偏好适应和领域能力。DPSE 引入审查模块，提取多维信号并评估满意度，通过主题和偏好策略扩展数据。这些数据支持两阶段微调：监督式领域基础和频率感知偏好优化。实验表明，DPSE 在通用 NLP 和对话任务中优于现有方法。消融研究证实了各模块的贡献。我们的框架为 LLM 的持续进化提供了自主路径。

> The capabilities of Large Language Models (LLMs) are limited to some extent by pre-training, so some researchers optimize LLMs through post-training. Existing post-training strategies, such as memory-based retrieval or preference optimization, improve user alignment yet fail to enhance the model's domain cognition. To bridge this gap, we propose a novel Dual-Phase Self-Evolution (DPSE) framework that jointly optimizes user preference adaptation and domain-specific competence. DPSE introduces a Censor module to extract multi-dimensional interaction signals and estimate satisfaction scores, which guide structured data expansion via topic-aware and preference-driven strategies. These expanded datasets support a two-stage fine-tuning pipeline: supervised domain grounding followed by frequency-aware preference optimization. Experiments across general NLP benchmarks and long-term dialogue tasks demonstrate that DPSE consistently outperforms Supervised Fine-Tuning, Preference Optimization, and Memory-Augmented baselines. Ablation studies validate the contribution of each module. In this way, our framework provides an autonomous path toward continual self-evolution of LLMs.

[Arxiv](https://arxiv.org/abs/2507.15281)