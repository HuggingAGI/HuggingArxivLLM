# 基于大型语言模型（LLMs）价值向量的免训练真实性检测

发布时间：2025年09月22日

`LLM理论` `基础理论`

> Training-free Truthfulness Detection via Value Vectors in LLMs

# 摘要

> 大型语言模型常产生事实性错误输出，推动了对其内容真实性的检测研究。现有方法多依赖训练探针分析内部激活，但存在扩展性与泛化能力不足的问题。近期无训练方法NoVo通过挖掘模型自身统计模式应对这一挑战，不过它仅聚焦注意力机制，却可能忽略了Transformer模型的核心组件——MLP模块，而该模块已知支持事实回忆。本文发现，MLP模块中的某些值向量存在与真实性相关的统计模式。基于此，我们提出无训练方法TruthV：这是一种简单可解释的方案，通过利用这些值向量实现内容真实性检测。在NoVo基准测试中，TruthV显著优于NoVo与对数似然基线，表明MLP模块虽在先前无训练研究中被忽视，却编码了丰富有效的真实性检测信号。这些发现为LLM中真实性的内部表示机制提供了新视角，也为可扩展、可解释的真实性检测研究指明了方向。

> Large language models often generate factually incorrect outputs, motivating efforts to detect the truthfulness of their content. Most existing approaches rely on training probes over internal activations, but these methods suffer from scalability and generalization issues. A recent training-free method, NoVo, addresses this challenge by exploiting statistical patterns from the model itself. However, it focuses exclusively on attention mechanisms, potentially overlooking the MLP module-a core component of Transformer models known to support factual recall. In this paper, we show that certain value vectors within MLP modules exhibit truthfulness-related statistical patterns. Building on this insight, we propose TruthV, a simple and interpretable training-free method that detects content truthfulness by leveraging these value vectors. On the NoVo benchmark, TruthV significantly outperforms both NoVo and log-likelihood baselines, demonstrating that MLP modules-despite being neglected in prior training-free efforts-encode rich and useful signals for truthfulness detection. These findings offer new insights into how truthfulness is internally represented in LLMs and motivate further research on scalable and interpretable truthfulness detection.

[Arxiv](https://arxiv.org/abs/2509.17932)