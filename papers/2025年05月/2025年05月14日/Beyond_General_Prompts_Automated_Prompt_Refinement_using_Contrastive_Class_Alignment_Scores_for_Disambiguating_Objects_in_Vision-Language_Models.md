# 超越通用提示：基于对比类对齐分数的自动提示优化，实现视觉-语言模型中的对象消歧

发布时间：2025年05月14日

`LLM应用` `计算机视觉`

> Beyond General Prompts: Automated Prompt Refinement using Contrastive Class Alignment Scores for Disambiguating Objects in Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）通过自然语言提示实现灵活的目标检测，但其性能受提示措辞影响较大。本文提出了一种基于“对比类对齐分数”（CCAS）的自动提示优化方法。该方法通过评估提示与目标类别的语义匹配度进行排序，同时抑制混淆类别的相似性。我们利用大型语言模型生成多样化的提示候选，并借助句子转换器计算的提示嵌入应用CCAS进行筛选。在具有挑战性的对象类别上的实验表明，自动选择高精度提示显著提升了目标检测的准确性，且无需额外的模型训练或标注数据。这一可扩展且模型无关的流水线为基于VLM的目标检测系统提供了一种替代手动提示工程的解决方案。

> Vision-language models (VLMs) offer flexible object detection through natural language prompts but suffer from performance variability depending on prompt phrasing. In this paper, we introduce a method for automated prompt refinement using a novel metric called the Contrastive Class Alignment Score (CCAS), which ranks prompts based on their semantic alignment with a target object class while penalizing similarity to confounding classes. Our method generates diverse prompt candidates via a large language model and filters them through CCAS, computed using prompt embeddings from a sentence transformer. We evaluate our approach on challenging object categories, demonstrating that our automatic selection of high-precision prompts improves object detection accuracy without the need for additional model training or labeled data. This scalable and model-agnostic pipeline offers a principled alternative to manual prompt engineering for VLM-based detection systems.

[Arxiv](https://arxiv.org/abs/2505.09139)