# 在大型语言模型中构建因果世界模型以实现零样本物理推理

发布时间：2025年07月26日

`LLM应用` `因果推理` `机器人`

> Inducing Causal World Models in LLMs for Zero-Shot Physical Reasoning

# 摘要

> 尽管大型语言模型（LLMs）在语言能力上表现卓越，但它们从根本上缺乏对物理动态的直观理解，这限制了它们在需要因果推理的真实场景中的应用效果。本文中，我们提出了因果世界模型归纳（CWMI），这是一种全新的框架，旨在将明确的因果物理模型嵌入到LLM中。我们的方法整合了专门设计的因果物理模块（CPM），并引入了名为因果干预损失的新训练目标，以鼓励模型从多模态数据中学习因果关系。通过训练模型预测假设性干预的结果，而非仅仅捕捉统计相关性，CWMI能够构建出对物理法则的坚实内部表征。实验结果表明，在包括PIQA基准测试和我们新提出的PhysiCa-Bench数据集在内的零样本物理推理任务中，CWMI显著超越了当前最先进的LLMs。这些结果表明，归纳因果世界模型是迈向更加可靠和通用的人工智能系统的关键一步。

> Large Language Models (LLMs), despite their advanced linguistic capabilities, fundamentally lack an intuitive understanding of physical dynamics, which limits their effectiveness in real-world scenarios that require causal reasoning. In this paper, we introduce Causal World Model Induction (CWMI), a novel framework designed to embed an explicit model of causal physics within an LLM. Our approach incorporates a dedicated Causal Physics Module (CPM) and a new training objective called Causal Intervention Loss, encouraging the model to learn cause-and-effect relationships from multimodal data. By training the model to predict the outcomes of hypothetical interventions instead of merely capturing statistical correlations, CWMI develops a robust internal representation of physical laws. Experimental results show that CWMI significantly outperforms state-of-the-art LLMs on zero-shot physical reasoning tasks, including the PIQA benchmark and our newly proposed PhysiCa-Bench dataset. These findings demonstrate that inducing a causal world model is a critical step toward more reliable and generalizable AI systems.

[Arxiv](https://arxiv.org/abs/2507.19855)