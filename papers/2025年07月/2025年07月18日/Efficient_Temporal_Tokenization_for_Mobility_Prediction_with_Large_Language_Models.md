# 高效的时间分词技术在大型语言模型中的移动性预测应用

发布时间：2025年07月18日

`LLM应用` `智能交通系统` `智慧城市`

> Efficient Temporal Tokenization for Mobility Prediction with Large Language Models

# 摘要

> 我们提出了一种名为 RHYTHM（基于分层时序标记化的轨迹推理框架）的框架，该框架巧妙地将大型语言模型（LLMs）应用于时空预测和轨迹推理。RHYTHM 创新性地将轨迹分割为日常片段，并通过分层注意力机制编码为离散标记，从而有效捕捉日常和每周的依赖关系，同时大幅缩短序列长度。Token 表示通过预计算的提示嵌入进行增强，这些嵌入由冻结的 LLM 提供，从而提升模型捕捉相互依赖的能力，而无需承担巨大的计算开销。通过冻结 LLM 主干，RHYTHM 实现了显著的计算效率提升。在三个真实数据集上的评估表明，与现有最优方法相比，RHYTHM 的准确率提高了 2.4%，周末场景提升了 5.0%，同时将训练时间减少了 24.6%。

> We introduce RHYTHM (Reasoning with Hierarchical Temporal Tokenization for Human Mobility), a framework that leverages large language models (LLMs) as spatio-temporal predictors and trajectory reasoners. RHYTHM partitions trajectories into daily segments encoded as discrete tokens with hierarchical attention, capturing both daily and weekly dependencies while substantially reducing the sequence length. Token representations are enriched with pre-computed prompt embeddings via a frozen LLM, enhancing the model's ability to capture interdependencies without extensive computational overhead. By freezing the LLM backbone, RHYTHM achieves significant computational efficiency. Evaluation on three real-world datasets demonstrates a 2.4% improvement in accuracy, 5.0% increase on weekends, and 24.6% reduction in training time compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2507.14017)