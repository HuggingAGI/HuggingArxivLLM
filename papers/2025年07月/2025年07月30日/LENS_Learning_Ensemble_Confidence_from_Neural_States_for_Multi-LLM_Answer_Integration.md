# LENS：从神经状态学习集成置信度，实现多模型答案整合

发布时间：2025年07月30日

`LLM应用` `问答系统`

> LENS: Learning Ensemble Confidence from Neural States for Multi-LLM Answer Integration

# 摘要

> 大型语言模型（LLMs）在各类任务中表现优异，各有所长。如何有效融合多个LLMs的预测结果，是提升系统稳健性和性能的关键。然而，现有集成方法多依赖简单的投票或对数概率集成，忽视了不同模型在不同上下文中的信心和可靠性差异。我们提出了一种全新方法——LENS（Learning ENsemble confidence from Neural States），通过分析神经网络内部表示来学习模型信心。针对每个LLM，我们训练了一个轻量级的线性信心预测器，以层级隐藏状态和标准化概率为输入。这使得可以根据模型在不同上下文中的可靠性，对预测结果进行更细致的加权。LENS无需修改模型参数，几乎无需额外计算。实验结果表明，在多项选择题和布尔问答任务中，LENS相较于传统集成方法有着显著的优势。研究表明，内部表示为确定模型信心提供了有价值的信号，并且可以被有效利用于集成学习。

> Large Language Models (LLMs) have demonstrated impressive performance across various tasks, with different models excelling in distinct domains and specific abilities. Effectively combining the predictions of multiple LLMs is crucial for enhancing system robustness and performance. However, existing ensemble methods often rely on simple techniques like voting or logits ensembling, which overlook the varying confidence and reliability of models in different contexts. In this work, we propose LENS (Learning ENsemble confidence from Neural States), a novel approach that learns to estimate model confidence by analyzing internal representations. For each LLM, we train a lightweight linear confidence predictor that leverages layer-wise hidden states and normalized probabilities as inputs. This allows for more nuanced weighting of model predictions based on their context-dependent reliability. Our method does not require modifying the model parameters and requires negligible additional computation. Experimental results on multiple-choice and boolean question-answering tasks demonstrate that LENS outperforms traditional ensemble methods by a substantial margin. Our findings suggest that internal representations provide valuable signals for determining model confidence and can be effectively leveraged for ensemble learning.

[Arxiv](https://arxiv.org/abs/2507.23167)