# HapticCap：一个多模态数据集和任务，旨在深入理解用户对振动触觉信号的体验。

发布时间：2025年07月17日

`其他

理由：这篇论文主要探讨触觉信号与文本描述的匹配问题，涉及多模态数据集和跨模态检索任务，属于跨模态研究，并未直接涉及Agent、RAG、LLM应用或理论。` `触觉技术` `数据集`

> HapticCap: A Multimodal Dataset and Task for Understanding User Experience of Vibration Haptic Signals

# 摘要

> 触觉信号，从智能手机震动到虚拟现实触觉反馈，能有效传递信息并增强真实感，但设计能与用户产生有意义共鸣的信号颇具挑战。为解决这一难题，我们引入了一个多模态数据集和任务，旨在将用户描述与振动触觉信号匹配，并指出两大主要挑战：（1）缺乏大型带有文本描述的触觉振动数据集，因为收集触觉描述耗时耗力；（2）现有任务和模型难以用文字描述振动信号。为推动这一领域的发展，我们创建了HapticCap——首个完全由人工标注的触觉-字幕数据集，包含92,070对触觉-文本，用于用户描述震动的感官、情感和联想属性。基于HapticCap，我们提出了触觉字幕检索任务，并展示了从监督对比学习框架中获得的结果，该框架将文本表示与特定类别的震动结合在一起。总体而言，语言模型T5与音频模型AST的结合在触觉字幕检索任务中表现最佳，尤其在为每个描述类别单独训练时效果更佳。


> Haptic signals, from smartphone vibrations to virtual reality touch feedback, can effectively convey information and enhance realism, but designing signals that resonate meaningfully with users is challenging. To facilitate this, we introduce a multimodal dataset and task, of matching user descriptions to vibration haptic signals, and highlight two primary challenges: (1) lack of large haptic vibration datasets annotated with textual descriptions as collecting haptic descriptions is time-consuming, and (2) limited capability of existing tasks and models to describe vibration signals in text. To advance this area, we create HapticCap, the first fully human-annotated haptic-captioned dataset, containing 92,070 haptic-text pairs for user descriptions of sensory, emotional, and associative attributes of vibrations. Based on HapticCap, we propose the haptic-caption retrieval task and present the results of this task from a supervised contrastive learning framework that brings together text representations within specific categories and vibrations. Overall, the combination of language model T5 and audio model AST yields the best performance in the haptic-caption retrieval task, especially when separately trained for each description category.

[Arxiv](https://arxiv.org/abs/2507.13318)