# 用于基于 LLM 的隐喻检测的课程式数据增强

发布时间：2024年12月03日

`LLM应用` `隐喻检测`

> Curriculum-style Data Augmentation for LLM-based Metaphor Detection

# 摘要

> 近来，运用大型语言模型（LLMs）来检测隐喻已收获了不错的成果。不过，这些方法高度依赖闭源LLMs的能力，其推理成本和延迟都比较高。为此，我们提出了通过微调开源LLMs来检测隐喻的方法，仅需一个推理步骤就能有效降低推理成本和延迟。另外，隐喻检测存在严重的数据稀缺问题，这妨碍了LLMs的有效微调。针对此，我们引入了课程式数据增强（CDA）。具体而言，在微调前，我们评估训练数据，找出用于微调的正确预测实例，而错误预测的实例则作为数据增强的种子数据。这种方式能让模型迅速学习较简单的知识，并逐步掌握更复杂的知识，从而逐步提升性能。实验结果显示，我们的方法在所有基线中均达到了领先水平。此外，我们还提供了详细的消融研究来验证CDA的有效性。

> Recently, utilizing large language models (LLMs) for metaphor detection has achieved promising results. However, these methods heavily rely on the capabilities of closed-source LLMs, which come with relatively high inference costs and latency. To address this, we propose a method for metaphor detection by fine-tuning open-source LLMs, effectively reducing inference costs and latency with a single inference step. Furthermore, metaphor detection suffers from a severe data scarcity problem, which hinders effective fine-tuning of LLMs. To tackle this, we introduce Curriculum-style Data Augmentation (CDA). Specifically, before fine-tuning, we evaluate the training data to identify correctly predicted instances for fine-tuning, while incorrectly predicted instances are used as seed data for data augmentation. This approach enables the model to quickly learn simpler knowledge and progressively acquire more complex knowledge, thereby improving performance incrementally. Experimental results demonstrate that our method achieves state-of-the-art performance across all baselines. Additionally, we provide detailed ablation studies to validate the effectiveness of CDA.

[Arxiv](https://arxiv.org/abs/2412.02956)