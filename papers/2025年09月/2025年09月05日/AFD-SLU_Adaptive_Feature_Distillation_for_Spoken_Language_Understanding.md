# AFD-SLU：面向口语理解的自适应特征蒸馏

发布时间：2025年09月05日

`LLM应用` `基础理论`

> AFD-SLU: Adaptive Feature Distillation for Spoken Language Understanding

# 摘要

> 口语语言理解（SLU）是对话系统的核心模块，让机器能够解读用户的语音输入。尽管SLU至关重要，但开发高效的SLU系统仍面临挑战：一方面标记训练数据稀缺，另一方面在实际应用中部署大型语言模型（LLMs）的计算成本高昂。为进一步缓解这些难题，我们提出自适应特征蒸馏框架，将基于通用文本嵌入（GTE）的教师模型中的丰富语义表示迁移至轻量级学生模型。该方法包含两个关键设计：一是配备残差投影神经网络（RPNN）的动态适配器，用于对齐异构特征空间；二是动态蒸馏系数（DDC），能根据意图和槽位预测性能的实时反馈自适应调整蒸馏强度。在中文档案类ProSLU基准数据集上的实验显示，AFD-SLU性能达到当前最优水平：意图准确率95.67%、槽位F1分数92.02%、总体准确率85.50%。

> Spoken Language Understanding (SLU) is a core component of conversational systems, enabling machines to interpret user utterances. Despite its importance, developing effective SLU systems remains challenging due to the scarcity of labeled training data and the computational burden of deploying Large Language Models (LLMs) in real-world applications. To further alleviate these issues, we propose an Adaptive Feature Distillation framework that transfers rich semantic representations from a General Text Embeddings (GTE)-based teacher model to a lightweight student model. Our method introduces a dynamic adapter equipped with a Residual Projection Neural Network (RPNN) to align heterogeneous feature spaces, and a Dynamic Distillation Coefficient (DDC) that adaptively modulates the distillation strength based on real-time feedback from intent and slot prediction performance. Experiments on the Chinese profile-based ProSLU benchmark demonstrate that AFD-SLU achieves state-of-the-art results, with 95.67% intent accuracy, 92.02% slot F1 score, and 85.50% overall accuracy.

[Arxiv](https://arxiv.org/abs/2509.04821)