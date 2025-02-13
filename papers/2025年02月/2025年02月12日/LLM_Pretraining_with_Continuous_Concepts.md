# 基于连续概念的LLM预训练

发布时间：2025年02月12日

`LLM理论` `推理系统`

> LLM Pretraining with Continuous Concepts

# 摘要

> 词元预测一直是大型语言模型预训练的核心目标。模型通过优化词元级别的困惑度学习词元表示。我们提出了一种创新的预训练框架——连续概念混合（CoCoMix），它巧妙地结合了离散的词元预测与连续的概念学习。具体而言，CoCoMix 从预训练稀疏自编码器中学习连续概念，并通过与词元隐藏表示交替的方式将其融入模型的隐藏状态。在语言建模和下游推理任务的多个基准实验中，我们发现 CoCoMix 不仅更具样本效率，而且在性能上始终超越传统的词元预测、知识蒸馏和暂停词元插入方法。研究发现，将概念学习与交替机制结合在一个端到端框架中是性能提升的关键。此外，CoCoMix 通过直接检查和修改预测概念，显著提升了模型的可解释性和可控性，为引导模型的内部推理过程提供了一种透明且直观的方式。

> Next token prediction has been the standard training objective used in large language model pretraining. Representations are learned as a result of optimizing for token-level perplexity. We propose Continuous Concept Mixing (CoCoMix), a novel pretraining framework that combines discrete next token prediction with continuous concepts. Specifically, CoCoMix predicts continuous concepts learned from a pretrained sparse autoencoder and mixes them into the model's hidden state by interleaving with token hidden representations. Through experiments on multiple benchmarks, including language modeling and downstream reasoning tasks, we show that CoCoMix is more sample efficient and consistently outperforms standard next token prediction, knowledge distillation and inserting pause tokens. We find that combining both concept learning and interleaving in an end-to-end framework is critical to performance gains. Furthermore, CoCoMix enhances interpretability and steerability by allowing direct inspection and modification of the predicted concept, offering a transparent way to guide the model's internal reasoning process.

[Arxiv](https://arxiv.org/abs/2502.08524)