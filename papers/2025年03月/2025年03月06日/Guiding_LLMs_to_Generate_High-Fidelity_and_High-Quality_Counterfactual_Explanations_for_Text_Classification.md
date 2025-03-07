# # 指导大型语言模型生成高保真高质量的反事实解释用于文本分类
指导大型语言模型生成高保真、高质量的反事实解释，用于文本分类任务。

发布时间：2025年03月06日

`LLM应用` `机器学习` `反事实解释`

> Guiding LLMs to Generate High-Fidelity and High-Quality Counterfactual Explanations for Text Classification

# 摘要

> 深度学习中的可解释性需求推动了反事实解释的研究，这些解释能够识别出改变模型预测所需的最小实例修改。当前反事实（CF）生成方法需要特定任务的微调，并且生成文本质量较低。大型语言模型（LLMs）虽然在高质量文本生成方面表现出色，但在未经微调的情况下难以生成标签翻转的反事实（即能够改变预测结果的反事实）。我们提出了两种简单的基于分类器的指导方法，支持LLMs进行反事实生成，无需微调同时保留了LLMs的优势。尽管方法简单，但我们的方法在反事实生成方面超越了现有最先进的方法，并且在不同LLMs上均表现出有效性，突显了利用分类器信息指导LLMs生成反事实的优势。我们进一步展示了通过我们的生成CF进行数据增强可以提升分类器的鲁棒性。我们的分析揭示了LLMs生成反事实的一个关键问题：LLMs依赖于参数化的知识，而非忠实遵循分类器的判断。

> The need for interpretability in deep learning has driven interest in counterfactual explanations, which identify minimal changes to an instance that change a model's prediction. Current counterfactual (CF) generation methods require task-specific fine-tuning and produce low-quality text. Large Language Models (LLMs), though effective for high-quality text generation, struggle with label-flipping counterfactuals (i.e., counterfactuals that change the prediction) without fine-tuning. We introduce two simple classifier-guided approaches to support counterfactual generation by LLMs, eliminating the need for fine-tuning while preserving the strengths of LLMs. Despite their simplicity, our methods outperform state-of-the-art counterfactual generation methods and are effective across different LLMs, highlighting the benefits of guiding counterfactual generation by LLMs with classifier information. We further show that data augmentation by our generated CFs can improve a classifier's robustness. Our analysis reveals a critical issue in counterfactual generation by LLMs: LLMs rely on parametric knowledge rather than faithfully following the classifier.

[Arxiv](https://arxiv.org/abs/2503.04463)