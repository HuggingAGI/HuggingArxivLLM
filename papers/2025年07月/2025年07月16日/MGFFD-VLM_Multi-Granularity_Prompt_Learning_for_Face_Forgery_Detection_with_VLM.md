# # **多粒度提示学习用于人脸伪造检测的多粒度提示学习模型（MGFFD-VLM）**

发布时间：2025年07月16日

`LLM应用` `深度伪造` `视觉问答`

> MGFFD-VLM: Multi-Granularity Prompt Learning for Face Forgery Detection with VLM

# 摘要

> 近期研究通过视觉大语言模型（VLMs）不仅回答“这张脸是伪造的吗？”，还深入分析“为什么这张脸是伪造的？”。研究者引入了伪造位置、类型等属性，构建了深度伪造VQA数据集并训练VLMs，不仅实现了高精度，还提供了人类可理解的解释性描述。然而，现有方法仍存在局限：未能充分利用伪造脸上异常的人脸质量属性，且缺乏有效的伪造感知VLM训练策略。

本文将VQA数据集扩展为DD-VQA+，拥有更丰富的属性和多样化样本。我们还提出全新伪造检测框架MGFFD-VLM，整合基于属性驱动的混合LoRA策略，增强VLM能力。框架采用多粒度提示学习和伪造感知训练策略，将分类与伪造分割结果转化为提示，不仅提升分类性能，更增强可解释性。此外，我们设计了多种伪造相关辅助损失函数，进一步提升检测性能。实验结果表明，我们的方法在文本伪造判断与分析方面均超越现有方法，实现更优准确率。

> Recent studies have utilized visual large language models (VLMs) to answer not only "Is this face a forgery?" but also "Why is the face a forgery?" These studies introduced forgery-related attributes, such as forgery location and type, to construct deepfake VQA datasets and train VLMs, achieving high accuracy while providing human-understandable explanatory text descriptions. However, these methods still have limitations. For example, they do not fully leverage face quality-related attributes, which are often abnormal in forged faces, and they lack effective training strategies for forgery-aware VLMs. In this paper, we extend the VQA dataset to create DD-VQA+, which features a richer set of attributes and a more diverse range of samples. Furthermore, we introduce a novel forgery detection framework, MGFFD-VLM, which integrates an Attribute-Driven Hybrid LoRA Strategy to enhance the capabilities of Visual Large Language Models (VLMs). Additionally, our framework incorporates Multi-Granularity Prompt Learning and a Forgery-Aware Training Strategy. By transforming classification and forgery segmentation results into prompts, our method not only improves forgery classification but also enhances interpretability. To further boost detection performance, we design multiple forgery-related auxiliary losses. Experimental results demonstrate that our approach surpasses existing methods in both text-based forgery judgment and analysis, achieving superior accuracy.

[Arxiv](https://arxiv.org/abs/2507.12232)