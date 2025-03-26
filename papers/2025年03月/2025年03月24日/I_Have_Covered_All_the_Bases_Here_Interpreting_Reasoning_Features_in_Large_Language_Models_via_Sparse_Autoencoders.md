# 我已涵盖所有关键点：借助稀疏自动编码器解读大型语言模型的推理特性

发布时间：2025年03月24日

`LLM理论` `推理系统`

> I Have Covered All the Bases Here: Interpreting Reasoning Features in Large Language Models via Sparse Autoencoders

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理领域取得了显著成功。近期进展催生了一类新的推理型 LLM；例如，开源的 DeepSeek-R1 通过整合深度思考和复杂推理，达到了最先进的性能水平。尽管这些模型展现出强大的能力，但其内部推理机制仍未被深入探索。

本研究中，我们采用稀疏自动编码器 (SAEs)，这是一种将神经网络潜在表示分解为可解释特征的方法，来识别驱动 DeepSeek-R1 系列模型推理的关键特征。首先，我们提出了一种从 SAE 表示中提取候选 ''推理特征'' 的方法。通过实证分析和可解释性方法，我们验证了这些特征与模型推理能力的直接关联。至关重要的是，我们展示了系统性地引导这些特征能够显著提升推理性能，从而为 LLM 中的推理机制提供了首个系统性解释。

代码可从 https://github.com/AIRI-Institute/SAE-Reasoning 获取。

> Large Language Models (LLMs) have achieved remarkable success in natural language processing. Recent advances have led to the developing of a new class of reasoning LLMs; for example, open-source DeepSeek-R1 has achieved state-of-the-art performance by integrating deep thinking and complex reasoning. Despite these impressive capabilities, the internal reasoning mechanisms of such models remain unexplored. In this work, we employ Sparse Autoencoders (SAEs), a method to learn a sparse decomposition of latent representations of a neural network into interpretable features, to identify features that drive reasoning in the DeepSeek-R1 series of models. First, we propose an approach to extract candidate ''reasoning features'' from SAE representations. We validate these features through empirical analysis and interpretability methods, demonstrating their direct correlation with the model's reasoning abilities. Crucially, we demonstrate that steering these features systematically enhances reasoning performance, offering the first mechanistic account of reasoning in LLMs. Code available at https://github.com/AIRI-Institute/SAE-Reasoning

[Arxiv](https://arxiv.org/abs/2503.18878)