# PP-DocBee2：通过高效数据提升的多模态文档理解新基准

发布时间：2025年06月24日

`LLM应用` `多模态文档处理` `商业文档分析`

> PP-DocBee2: Improved Baselines with Efficient Data for Multimodal Document Understanding

# 摘要

> 本报告推出PP-DocBee2，作为PP-DocBee的升级版，专注于提升多模态文档理解能力。该模型基于先进多模态架构打造，通过三大核心技术突破前代局限：合成数据质量显著提升、视觉特征融合策略优化、推理方法全面升级。在中文商业文档的内部测试中，PP-DocBee2实现了11.4%的性能飞跃，推理速度较基础版本提升了73.0%。本次研究的核心创新在于提出了一种多模态文档任务的数据质量优化方案。我们利用大规模多模态预训练模型评估数据，通过创新的统计标准筛选异常值，确保了高质量的训练数据集。此外，基于对多模态模型中未充分挖掘的中间特征的深入研究，我们将ViT的表示能力进行分层处理，并引入新型特征融合策略，显著提升了复杂推理能力。项目源代码和预训练模型已开源，访问地址为\href{https://github.com/PaddlePaddle/PaddleMIX}{https://github.com/PaddlePaddle/PaddleMIX}。

> This report introduces PP-DocBee2, an advanced version of the PP-DocBee, designed to enhance multimodal document understanding. Built on a large multimodal model architecture, PP-DocBee2 addresses the limitations of its predecessor through key technological improvements, including enhanced synthetic data quality, improved visual feature fusion strategy, and optimized inference methodologies. These enhancements yield an $11.4\%$ performance boost on internal benchmarks for Chinese business documents, and reduce inference latency by $73.0\%$ to the vanilla version. A key innovation of our work is a data quality optimization strategy for multimodal document tasks. By employing a large-scale multimodal pre-trained model to evaluate data, we apply a novel statistical criterion to filter outliers, ensuring high-quality training data. Inspired by insights into underutilized intermediate features in multimodal models, we enhance the ViT representational capacity by decomposing it into layers and applying a novel feature fusion strategy to improve complex reasoning. The source code and pre-trained model are available at \href{https://github.com/PaddlePaddle/PaddleMIX}{https://github.com/PaddlePaddle/PaddleMIX}.

[Arxiv](https://arxiv.org/abs/2506.18023)