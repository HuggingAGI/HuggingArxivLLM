# 基于多模态大型语言模型的语言引导推理：群体活动检测

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Language-Instructed Reasoning for Group Activity Detection via Multimodal Large Language Model

# 摘要

> 群体活动检测（GAD）旨在同时识别视频序列中的群体成员并对其集体活动进行分类。现有的深度学习方法通过开发专门架构（如Transformer网络）来建模个体角色动态及个体与群体间的语义依赖，但这些方法仅依赖视觉特征的隐式模式识别，在上下文推理和可解释性方面存在不足。为此，我们提出了LIR-GAD——一种基于多模态大型语言模型（MLLM）的群体活动检测语言引导推理新框架。该方法通过引入活动级<ACT>标记和多个集群专属<GROUP>标记，扩展了MLLM的原始词汇表。我们将视频帧与这两个特制标记及语言指令协同处理并整合到MLLM中，借助MLLM内置的预训练常识知识，使<ACT>标记有效捕捉集体活动语义信息，<GROUP>标记则学习不同群体的独特表征特征。此外，我们引入多标签分类损失以增强<ACT>标记的判别性语义表征学习能力，并设计多模态双对齐融合（MDAF）模块，将MLLM中与所设计标记对应的隐藏嵌入与视觉特征融合，大幅提升了群体活动检测性能。定量与定性实验均表明，我们提出的方法在群体活动检测任务中表现卓越。

> Group activity detection (GAD) aims to simultaneously identify group members and categorize their collective activities within video sequences. Existing deep learning-based methods develop specialized architectures (e.g., transformer networks) to model the dynamics of individual roles and semantic dependencies between individuals and groups. However, they rely solely on implicit pattern recognition from visual features and struggle with contextual reasoning and explainability. In this work, we propose LIR-GAD, a novel framework of language-instructed reasoning for GAD via Multimodal Large Language Model (MLLM). Our approach expand the original vocabulary of MLLM by introducing an activity-level <ACT> token and multiple cluster-specific <GROUP> tokens. We process video frames alongside two specially designed tokens and language instructions, which are then integrated into the MLLM. The pretrained commonsense knowledge embedded in the MLLM enables the <ACT> token and <GROUP> tokens to effectively capture the semantic information of collective activities and learn distinct representational features of different groups, respectively. Also, we introduce a multi-label classification loss to further enhance the <ACT> token's ability to learn discriminative semantic representations. Then, we design a Multimodal Dual-Alignment Fusion (MDAF) module that integrates MLLM's hidden embeddings corresponding to the designed tokens with visual features, significantly enhancing the performance of GAD. Both quantitative and qualitative experiments demonstrate the superior performance of our proposed method in GAD taks.

[Arxiv](https://arxiv.org/abs/2509.16054)