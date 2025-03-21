# GraspCoT：结合物理特性推理，实现基于灵活语言指令的6自由度抓取

发布时间：2025年03月20日

`LLM应用` `机器人`

> GraspCoT: Integrating Physical Property Reasoning for 6-DoF Grasping under Flexible Language Instructions

# 摘要

> 灵活的指令引导6自由度抓取是机器人系统中一项重要且具挑战性的任务。现有方法利用大型语言模型（LLMs）的上下文理解能力，建立表达与目标之间的映射关系，使机器人能够理解用户指令中的意图。然而，尽管物体物理属性与抓取密切相关，但LLMs对物体物理属性的知识探索仍显不足。本研究提出GraspCoT框架，该框架结合了面向物理属性的链式思考（CoT）推理机制，并通过辅助问答（QA）任务进行引导。具体而言，我们设计了一组QA模板，支持包含目标解析、物理属性分析和抓取动作选择三个阶段的分层推理。此外，GraspCoT还提出了一种统一的多模态LLM架构，将三维场景的多视角观察编码为具有三维感知的视觉令牌，然后将这些视觉令牌与从CoT推理中得到的文本令牌在LLMs中联合嵌入，生成抓取姿态预测。此外，我们推出了IntentGrasp基准数据集，填补了现有公开数据集在多样且间接的语音指令下多物体抓取检测的空白。在IntentGrasp上的大量实验表明了我们方法的优越性，同时在现实世界机器人应用中的验证进一步证实了其实用性。代码和数据即将发布。

> Flexible instruction-guided 6-DoF grasping is a significant yet challenging task for real-world robotic systems. Existing methods utilize the contextual understanding capabilities of the large language models (LLMs) to establish mappings between expressions and targets, allowing robots to comprehend users' intentions in the instructions. However, the LLM's knowledge about objects' physical properties remains underexplored despite its tight relevance to grasping. In this work, we propose GraspCoT, a 6-DoF grasp detection framework that integrates a Chain-of-Thought (CoT) reasoning mechanism oriented to physical properties, guided by auxiliary question-answering (QA) tasks. Particularly, we design a set of QA templates to enable hierarchical reasoning that includes three stages: target parsing, physical property analysis, and grasp action selection. Moreover, GraspCoT presents a unified multimodal LLM architecture, which encodes multi-view observations of 3D scenes into 3D-aware visual tokens, and then jointly embeds these visual tokens with CoT-derived textual tokens within LLMs to generate grasp pose predictions. Furthermore, we present IntentGrasp, a large-scale benchmark that fills the gap in public datasets for multi-object grasp detection under diverse and indirect verbal commands. Extensive experiments on IntentGrasp demonstrate the superiority of our method, with additional validation in real-world robotic applications confirming its practicality. Codes and data will be released.

[Arxiv](https://arxiv.org/abs/2503.16013)