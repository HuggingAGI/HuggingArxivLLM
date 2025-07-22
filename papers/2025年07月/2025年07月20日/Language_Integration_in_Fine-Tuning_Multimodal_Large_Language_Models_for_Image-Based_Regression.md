# 多模态大语言模型在基于图像回归任务中的语言整合微调研究

发布时间：2025年07月20日

`LLM应用` `图像处理` `多模态`

> Language Integration in Fine-Tuning Multimodal Large Language Models for Image-Based Regression

# 摘要

> 多模态大型语言模型（MLLMs）在图像回归任务中展现出潜力，但现有方法存在关键局限。当前技术通过预设输出词汇表和通用提示（如“你会如何评价这张图像？”）对模型进行微调，试图模拟人类评分行为。然而，我们的分析表明，这些方法并未超越仅基于图像的训练效果。使用预设词汇和通用提示的模型表现与仅基于图像的模型持平，未能充分利用文本输入的语义价值。

我们提出了一种基于Transformer的分类回归方法（RvTC），采用灵活的分箱方法替代传统的词汇受限分类。与通过复杂分布建模解决离散化误差的方法不同，RvTC通过简单的增加分箱数量，消除了人工设计词汇的需要。仅使用图像输入，该方法在四个图像评估数据集中实现了最先进性能。

更重要的是，我们发现数据特定的提示能够显著提升模型表现。与通用任务描述不同，包含特定图像语义信息的提示使MLLMs能够更好地利用跨模态理解能力。在AVA数据集上，将挑战标题添加到提示中，将模型的相关性从0.83提升至0.90，达到了新的最先进水平。

通过AVA和AGIQA-3k数据集的实证研究，我们证明MLLMs能够从语义提示信息中获益，而不仅仅是依赖统计偏差。这凸显了在多模态回归任务中融入有意义文本上下文的重要性。

> Multimodal Large Language Models (MLLMs) show promise for image-based regression tasks, but current approaches face key limitations. Recent methods fine-tune MLLMs using preset output vocabularies and generic task-level prompts (e.g., "How would you rate this image?"), assuming this mimics human rating behavior. Our analysis reveals these approaches provide no benefit over image-only training. Models using preset vocabularies and generic prompts perform equivalently to image-only models, failing to leverage semantic understanding from textual input. We propose Regression via Transformer-Based Classification (RvTC), which replaces vocabulary-constrained classification with a flexible bin-based approach. Unlike approaches that address discretization errors through complex distributional modeling, RvTC eliminates manual vocabulary crafting through straightforward bin increase, achieving state-of-the-art performance on four image assessment datasets using only images. More importantly, we demonstrate that data-specific prompts dramatically improve performance. Unlike generic task descriptions, prompts containing semantic information about specific images enable MLLMs to leverage cross-modal understanding. On the AVA dataset, adding challenge titles to prompts improves correlations from 0.83 to 0.90, a new state-of-the-art. We demonstrate through empirical evidence from the AVA and AGIQA-3k datasets that MLLMs benefit from semantic prompt information surpassing mere statistical biases. This underscores the importance of incorporating meaningful textual context in multimodal regression tasks.

[Arxiv](https://arxiv.org/abs/2507.14997)