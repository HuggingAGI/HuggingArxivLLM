# 高效隐私保护的软提示迁移方法在LLMs中的应用

发布时间：2025年06月19日

`LLM应用` `人工智能` `隐私保护`

> Efficient and Privacy-Preserving Soft Prompt Transfer for LLMs

# 摘要

> 提示工程已成为适应大型语言模型 (LLMs) 的主要范式。离散（文本）提示因其可解释性被广泛应用，而软（参数）提示在API中逐渐流行，因为它们能在最小化用户令牌使用的同时，从更多训练样本中编码信息，为特定任务输入留出更多上下文窗口空间。然而，软提示与其调优的 LLM 紧密耦合，限制了其在其他 LLM 上的泛化能力。这一限制在效率和隐私方面尤为突出：(1) 在每个 LLM 上调优提示会产生高昂的计算成本，尤其是随着 LLM 的规模持续扩大；(2) 当 LLM 由外部托管时，软提示调优通常需要与 LLM 提供商共享私有数据，例如 NVIDIA NeMo API。为了解决这些问题，我们提出了 POST（软提示迁移的隐私保护框架），一个能够在小型模型上进行私有软提示调优并将其迁移到大型 LLM 的框架。通过知识蒸馏直接从大型 LLM 中提取小型模型以提高提示的可迁移性，在本地调优软提示（可选配差分隐私保证），并使用一个小规模的公开数据集将其迁回大型 LLM。实验表明，POST 能够降低计算成本、保护隐私，并有效迁移具有高实用性的软提示。

> Prompting has become a dominant paradigm for adapting large language models (LLMs). While discrete (textual) prompts are widely used for their interpretability, soft (parameter) prompts have recently gained traction in APIs. This is because they can encode information from more training samples while minimizing the user's token usage, leaving more space in the context window for task-specific input. However, soft prompts are tightly coupled to the LLM they are tuned on, limiting their generalization to other LLMs. This constraint is particularly problematic for efficiency and privacy: (1) tuning prompts on each LLM incurs high computational costs, especially as LLMs continue to grow in size. Additionally, (2) when the LLM is hosted externally, soft prompt tuning often requires sharing private data with the LLM provider. For instance, this is the case with the NVIDIA NeMo API. To address these issues, we propose POST (Privacy Of Soft prompt Transfer), a framework that enables private tuning of soft prompts on a small model and subsequently transfers these prompts to a larger LLM. POST uses knowledge distillation to derive a small model directly from the large LLM to improve prompt transferability, tunes the soft prompt locally, optionally with differential privacy guarantees, and transfers it back to the larger LLM using a small public dataset. Our experiments show that POST reduces computational costs, preserves privacy, and effectively transfers high-utility soft prompts.

[Arxiv](https://arxiv.org/abs/2506.16196)