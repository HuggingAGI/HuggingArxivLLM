# # 利用注意力机制在Transformer中实现大规模记忆编辑：跨语言知识探索

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）中知识编辑方法的改进，特别是提出了MEMAT方法，该方法通过调整注意力机制来提升模型在多语言环境下的表现。论文的核心内容涉及LLM的内部机制和理论改进，因此应归类为LLM理论。` `多语言处理`

> Mass-Editing Memory with Attention in Transformers: A cross-lingual exploration of knowledge

# 摘要

> 近期研究聚焦于更新和修改大型语言模型中的事实知识，尤其关注特定的多层感知器块。本研究进一步探讨了现有知识编辑方法在多语言环境下的有效性，并深入分析了注意力机制的作用。基于这些发现，我们提出了MEMAT（Mass-Editing Memory with Attention in Transformers），该方法在所有评估指标上均显著提升，且仅需少量参数调整。MEMAT在幅度指标上实现了10%的显著提升，对未包含在训练数据中的语言同样有效，并展现出高度的可移植性。代码和数据已开源，详见https://github.com/dtamayo-nlp/MEMAT。

> Recent research has explored methods for updating and modifying factual knowledge in large language models, often focusing on specific multi-layer perceptron blocks. This study expands on this work by examining the effectiveness of existing knowledge editing methods across languages and delving into the role of attention mechanisms in this process. Drawing from the insights gained, we propose Mass-Editing Memory with Attention in Transformers (MEMAT), a method that achieves significant improvements in all metrics while requiring minimal parameter modifications. MEMAT delivers a remarkable 10% increase in magnitude metrics, benefits languages not included in the training data and also demonstrates a high degree of portability. Our code and data are at https://github.com/dtamayo-nlp/MEMAT.

[Arxiv](https://arxiv.org/abs/2502.02173)