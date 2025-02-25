# 探索自回归预测下一个词：In-Context Learning 源于泛化能力

发布时间：2025年02月24日

`LLM理论` `理论分析` `模型机制`

> Towards Auto-Regressive Next-Token Prediction: In-Context Learning Emerges from Generalization

# 摘要

> 大型语言模型（LLMs）展现出了显著超越传统方法的上下文学习（ICL）能力。然而，现有对ICL的理论分析主要存在两大局限：(a) 有限的独立同分布(i.i.d.)假设。大多数研究聚焦于监督函数学习任务，其中提示语的构造基于独立同分布的输入-标签对。这种i.i.d.假设与真实语言学习场景中的提示语标记相互依赖性存在显著差异。(b) 缺乏涌现机制解释。大部分文献从隐式优化角度解答了ICL在做什么，但对于ICL如何涌现以及预训练阶段对ICL的影响却鲜有阐释。在本文中，为扩展(a)的局限，我们采用更贴近语言模型实际训练的自回归下个词预测（AR-NTP）范式。具体而言，在AR-NTP框架下，我们强调提示语标记间的依赖关系，即基于前序序列预测后续每个标记。针对(b)的局限，我们系统地构建了预训练与ICL的理论框架，突出了序列和主题的分层结构，同时引入了双层期望机制。最终，我们为预训练LLMs推导出数据依赖、主题依赖和优化依赖的PAC-Bayesian泛化界限，研究发现ICL的涌现源于序列和主题的泛化能力。我们的理论通过数值线性动力系统、合成GINC和真实语言数据集的实验得到了验证。

> Large language models (LLMs) have demonstrated remarkable in-context learning (ICL) abilities. However, existing theoretical analysis of ICL primarily exhibits two limitations: (a) Limited i.i.d. Setting. Most studies focus on supervised function learning tasks where prompts are constructed with i.i.d. input-label pairs. This i.i.d. assumption diverges significantly from real language learning scenarios where prompt tokens are interdependent. (b) Lack of Emergence Explanation. Most literature answers what ICL does from an implicit optimization perspective but falls short in elucidating how ICL emerges and the impact of pre-training phase on ICL. In our paper, to extend (a), we adopt a more practical paradigm, auto-regressive next-token prediction (AR-NTP), which closely aligns with the actual training of language models. Specifically, within AR-NTP, we emphasize prompt token-dependency, which involves predicting each subsequent token based on the preceding sequence. To address (b), we formalize a systematic pre-training and ICL framework, highlighting the layer-wise structure of sequences and topics, alongside a two-level expectation. In conclusion, we present data-dependent, topic-dependent and optimization-dependent PAC-Bayesian generalization bounds for pre-trained LLMs, investigating that ICL emerges from the generalization of sequences and topics. Our theory is supported by experiments on numerical linear dynamic systems, synthetic GINC and real-world language datasets.

[Arxiv](https://arxiv.org/abs/2502.17024)