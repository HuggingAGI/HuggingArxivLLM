# 从压缩到扩展：深入探究上下文学习的分层机制

发布时间：2025年05月22日

`LLM理论` `机器学习`

> From Compression to Expansion: A Layerwise Analysis of In-Context Learning

# 摘要

> 上下文学习（ICL）使大型语言模型（LLMs）无需更新模型参数即可通过学习演示序列适应新任务。尽管ICL在实际应用中表现出色，但其内在的表征机制尚未被充分理解。本研究通过对ICL的表征进行统计几何分析，揭示了一个引人注目的现象——*层压缩-扩展*：早期层逐步生成紧凑且具有判别性的表征，编码来自输入演示的任务信息；后期层则扩展这些表征，整合查询并生成预测。这一现象在各种任务和当代LLM架构中均表现一致。研究发现，这一现象对ICL性能具有重要影响——随着模型规模和演示数量的增加而提升——并且在存在噪声示例时也表现出更强的鲁棒性。我们提出了一种偏差-方差分解，并通过理论分析揭示了注意力机制如何通过减少方差和偏差来提升性能，尤其在演示数量增加时。本研究不仅揭示了ICL中引人注目的层间动态，还展示了结构化表征在LLMs中的形成过程，表明对内部表征的分析能够促进对模型行为的更深入理解。
    

> In-context learning (ICL) enables large language models (LLMs) to adapt to new tasks without weight updates by learning from demonstration sequences. While ICL shows strong empirical performance, its internal representational mechanisms are not yet well understood. In this work, we conduct a statistical geometric analysis of ICL representations to investigate how task-specific information is captured across layers. Our analysis reveals an intriguing phenomenon, which we term *Layerwise Compression-Expansion*: early layers progressively produce compact and discriminative representations that encode task information from the input demonstrations, while later layers expand these representations to incorporate the query and generate the prediction. This phenomenon is observed consistently across diverse tasks and a range of contemporary LLM architectures. We demonstrate that it has important implications for ICL performance -- improving with model size and the number of demonstrations -- and for robustness in the presence of noisy examples. To further understand the effect of the compact task representation, we propose a bias-variance decomposition and provide a theoretical analysis showing how attention mechanisms contribute to reducing both variance and bias, thereby enhancing performance as the number of demonstrations increases. Our findings reveal an intriguing layerwise dynamic in ICL, highlight how structured representations emerge within LLMs, and showcase that analyzing internal representations can facilitate a deeper understanding of model behavior.

[Arxiv](https://arxiv.org/abs/2505.17322)