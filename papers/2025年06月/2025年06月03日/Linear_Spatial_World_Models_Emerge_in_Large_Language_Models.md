# 大型语言模型中涌现线性空间世界模型

发布时间：2025年06月03日

`LLM理论` `机器人学` `计算机视觉`

> Linear Spatial World Models Emerge in Large Language Models

# 摘要

> 大型语言模型（LLMs）在多样任务中展现出的强大能力引发了一个重要问题：它们是否构建了内部世界模型？本研究聚焦于LLMs是否隐性地构建了线性空间世界模型，即对物理空间及物体配置的线性表征。我们提出了一套正式的框架来定义空间世界模型，并深入探究这种结构是否存在于模型的上下文嵌入中。通过构建合成物体位置数据集，我们训练探针模型来解码物体位置，并评估潜在空间的几何一致性。进一步，我们设计了因果干预实验，检验这些空间表征是否在模型的实际推理过程中被功能化使用。研究结果提供了有力的实证证据，表明LLMs确实编码了线性空间世界模型。

> Large language models (LLMs) have demonstrated emergent abilities across diverse tasks, raising the question of whether they acquire internal world models. In this work, we investigate whether LLMs implicitly encode linear spatial world models, which we define as linear representations of physical space and object configurations. We introduce a formal framework for spatial world models and assess whether such structure emerges in contextual embeddings. Using a synthetic dataset of object positions, we train probes to decode object positions and evaluate geometric consistency of the underlying space. We further conduct causal interventions to test whether these spatial representations are functionally used by the model. Our results provide empirical evidence that LLMs encode linear spatial world models.

[Arxiv](https://arxiv.org/abs/2506.02996)