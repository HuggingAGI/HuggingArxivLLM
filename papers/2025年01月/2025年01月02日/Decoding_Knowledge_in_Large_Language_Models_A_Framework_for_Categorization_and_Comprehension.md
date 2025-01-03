# 解码大型语言模型中的知识：一个用于分类与理解的框架

发布时间：2025年01月02日

`LLM理论` `语言模型` `知识评估`

> Decoding Knowledge in Large Language Models: A Framework for Categorization and Comprehension

# 摘要

> 理解大型语言模型（LLMs）怎样获取、留存和运用知识，至今仍是一项有待攻克的难题。本文引入了一个新颖的框架——K-(CSA)^2，它从正确性和置信度这两个维度对LLM知识予以分类。该框架界定了六种知识类别，涵盖从高度可信的正确知识到自信持有的错误认知，从而能够对模型的理解进行更细致的评估，而非局限于二元准确性。借助这一框架，我们展示了诸如思维链提示和基于人类反馈的强化学习等技术如何从根本上改变LLM中内部（预训练）和外部（依赖上下文）知识的结构。思维链尤其提升了基础模型的性能，在应用于对齐的LLM时还展现出协同优势。此外，我们的分层分析显示，LLM的较高层编码了更多高置信度知识，而低置信度知识则倾向于出现在中下层。

> Understanding how large language models (LLMs) acquire, retain, and apply knowledge remains an open challenge. This paper introduces a novel framework, K-(CSA)^2, which categorizes LLM knowledge along two dimensions: correctness and confidence. The framework defines six categories of knowledge, ranging from highly confident correctness to confidently held misconceptions, enabling a nuanced evaluation of model comprehension beyond binary accuracy. Using this framework, we demonstrate how techniques like chain-of-thought prompting and reinforcement learning with human feedback fundamentally alter the knowledge structures of internal (pre-trained) and external (context-dependent) knowledge in LLMs. CoT particularly enhances base model performance and shows synergistic benefits when applied to aligned LLMs. Moreover, our layer-wise analysis reveals that higher layers in LLMs encode more high-confidence knowledge, while low-confidence knowledge tends to emerge in middle-to-lower layers.

[Arxiv](https://arxiv.org/abs/2501.01332)