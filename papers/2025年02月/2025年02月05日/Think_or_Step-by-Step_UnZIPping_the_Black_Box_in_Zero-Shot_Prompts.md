# 思考还是逐步？揭秘零-shot提示中的黑箱

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了零-shot提示技术对大型语言模型（LLMs）性能的影响，并提出了一个新的指标（ZIP分数）来解释和评估提示词的重要性。研究内容涉及对LLM行为的理解和解释，属于对LLM内部机制和理论的研究，因此归类为“LLM理论”。` `人工智能`

> Think or Step-by-Step? UnZIPping the Black Box in Zero-Shot Prompts

# 摘要

> 零-shot 提示技术大幅提升了 LLMs 的性能，但其成功的原因尚不明确。例如，在提示“让我们一步一步地思考”中，“思考”和“一步一步”哪个更关键？现有的可解释性方法计算复杂且仅适用于开源模型。我们提出了 ZIP 分数（零-shot 扰动重要性分数），这是一种基于系统性输入词扰动的通用指标，适用于开源和闭源模型。通过对四个最新 LLMs、七个常用提示和多个任务的实验，我们发现了词重要性的有趣模式。例如，“一步一步”和“思考”的 ZIP 分数都很高，但哪个更具影响力取决于模型和任务。我们通过控制实验验证了该方法，并与人类判断进行了对比，发现专有模型在词重要性上更符合人类直觉。这些发现深化了我们对 LLM 行为的理解，有助于开发更有效的零-shot 提示和改进的模型分析。

> Zero-shot prompting techniques have significantly improved the performance of Large Language Models (LLMs). However, we lack a clear understanding of why zero-shot prompts are so effective. For example, in the prompt "Let's think step-by-step," is "think" or "step-by-step" more crucial to its success? Existing interpretability methods, such as gradient-based and attention-based approaches, are computationally intensive and restricted to open-source models. We introduce the ZIP score (Zero-shot Importance of Perturbation score), a versatile metric applicable to both open and closed-source models, based on systematic input word perturbations. Our experiments across four recent LLMs, seven widely-used prompts, and several tasks, reveal interesting patterns in word importance. For instance, while both 'step-by-step' and 'think' show high ZIP scores, which one is more influential depends on the model and task. We validate our method using controlled experiments and compare our results with human judgments, finding that proprietary models align more closely with human intuition regarding word significance. These findings enhance our understanding of LLM behavior and contribute to developing more effective zero-shot prompts and improved model analysis.

[Arxiv](https://arxiv.org/abs/2502.03418)