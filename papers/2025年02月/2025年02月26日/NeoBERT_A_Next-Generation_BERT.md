# NeoBERT：新一代BERT模型

发布时间：2025年02月26日

`LLM理论`

> NeoBERT: A Next-Generation BERT

# 摘要

> 架构、预训练和微调领域的最新创新使得如LLaMA和DeepSeek等大型自回归语言模型具备了令人瞩目的上下文学习和推理能力。然而，尽管BERT和RoBERTa等编码器是许多下游NLP应用的基础，但它们并未取得同等水平的进展。为填补这一差距，我们推出了NeoBERT——新一代编码器，通过整合架构、现代数据和优化预训练方法的最新进展，重新定义了双向模型的能力。NeoBERT设计上注重无缝衔接：它可作为现有基础模型的即插即用替代品，采用优化的深度与宽度比例，并支持长达4,096个token的扩展上下文长度。尽管仅有2.5亿参数，NeoBERT在庞大的MTEB基准测试中达到了最先进水平，超越了BERT large、RoBERTa large、NomicBERT和ModernBERT，且在相同的微调条件下。此外，我们严格评估了每项改进对GLUE的影响，并为MTEB设计了一个统一的微调和评估框架。我们开放了所有代码、数据、检查点和训练脚本，以加速研究和实际应用。

> Recent innovations in architecture, pre-training, and fine-tuning have led to the remarkable in-context learning and reasoning abilities of large auto-regressive language models such as LLaMA and DeepSeek. In contrast, encoders like BERT and RoBERTa have not seen the same level of progress despite being foundational for many downstream NLP applications. To bridge this gap, we introduce NeoBERT, a next-generation encoder that redefines the capabilities of bidirectional models by integrating state-of-the-art advancements in architecture, modern data, and optimized pre-training methodologies. NeoBERT is designed for seamless adoption: it serves as a plug-and-play replacement for existing base models, relies on an optimal depth-to-width ratio, and leverages an extended context length of 4,096 tokens. Despite its compact 250M parameter footprint, it achieves state-of-the-art results on the massive MTEB benchmark, outperforming BERT large, RoBERTa large, NomicBERT, and ModernBERT under identical fine-tuning conditions. In addition, we rigorously evaluate the impact of each modification on GLUE and design a uniform fine-tuning and evaluation framework for MTEB. We release all code, data, checkpoints, and training scripts to accelerate research and real-world adoption.

[Arxiv](https://arxiv.org/abs/2502.19587)