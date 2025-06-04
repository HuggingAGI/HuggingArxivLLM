# ORPP：通过自我优化的角色扮演提示，助力提升语言模型能力。

发布时间：2025年06月03日

`LLM应用` `人工智能`

> ORPP: Self-Optimizing Role-playing Prompts to Enhance Language Model Capabilities

# 摘要

> 高质量的提示对于大型语言模型（LLMs）在复杂任务中发挥出色性能至关重要。现有基于模型的提示优化策略虽然有效，但往往面临高昂计算成本或对模型优化能力的高要求，限制了它们的广泛应用。为了解决这一问题，我们提出了ORPP（优化的角色扮演提示框架），一个通过优化和生成角色扮演提示来提升模型性能的框架。ORPP的核心思想是将提示搜索空间限制在角色扮演场景中，通过精心设计的高质量角色扮演提示充分激活模型的内在能力。具体来说，ORPP首先对训练样本的一小部分进行迭代优化，生成高质量的角色扮演提示。然后，利用模型的少样本学习能力，将优化经验迁移，高效生成适用于剩余样本的合适提示。实验结果表明，ORPP不仅在性能上与现有主流提示优化方法相匹配，而且在大多数情况下表现更优。值得注意的是，ORPP展示了卓越的“即插即用”能力。在大多数情况下，它可以与其他提示方法结合使用，并进一步增强它们的效果。

> High-quality prompts are crucial for eliciting outstanding performance from large language models (LLMs) on complex tasks. Existing research has explored model-driven strategies for prompt optimization. However, these methods often suffer from high computational overhead or require strong optimization capabilities from the model itself, which limits their broad applicability.To address these challenges, we propose ORPP (Optimized Role-Playing Prompt),a framework that enhances model performance by optimizing and generating role-playing prompts. The core idea of ORPP is to confine the prompt search space to role-playing scenarios, thereby fully activating the model's intrinsic capabilities through carefully crafted, high-quality role-playing prompts. Specifically, ORPP first performs iterative optimization on a small subset of training samples to generate high-quality role-playing prompts. Then, leveraging the model's few-shot learning capability, it transfers the optimization experience to efficiently generate suitable prompts for the remaining samples.Our experimental results show that ORPP not only matches but in most cases surpasses existing mainstream prompt optimization methods in terms of performance. Notably, ORPP demonstrates superior "plug-and-play" capability. In most cases, it can be integrated with various other prompt methods and further enhance their effectiveness.

[Arxiv](https://arxiv.org/abs/2506.02480)