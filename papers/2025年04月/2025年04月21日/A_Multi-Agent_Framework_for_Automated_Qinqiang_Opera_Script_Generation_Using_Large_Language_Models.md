# # 基于大型语言模型的多智能体秦腔剧本自动生成框架

发布时间：2025年04月21日

`Agent

这篇论文讨论了多智能体框架的设计与应用，重点在于多个智能体如何协作完成复杂的任务。虽然提到了大型语言模型等技术，但核心在于智能体的分工与协作，属于多智能体系统的研究。` `人工智能`

> A Multi-Agent Framework for Automated Qinqiang Opera Script Generation Using Large Language Models

# 摘要

> 本文提出了一种全新的多智能体框架，通过整合大型语言模型、视觉生成和文本转语音合成技术，实现从创作到呈现的全流程自动化秦腔制作。三个专业智能体分工协作，依次完成创作、呈现与演绎：智能体1借助大型语言模型生成连贯且富有文化内涵的剧本；智能体2运用视觉生成模型呈现符合情境的舞台场景；智能体3则通过文本转语音技术生成同步且富有情感表现力的 vocal 表演。以《窦娥冤》为例，该系统在剧本忠实度、视觉连贯性和语音准确性方面分别获得3.8、3.5和3.8的专家评分，整体评分达到3.6，较单智能体基线提升了0.3分。通过消融实验发现，移除智能体2或智能体3会导致评分分别下降0.4和0.5分，充分证明了模块化协作的价值。这项研究展示了AI驱动的流水线如何简化并扩大传统表演艺术的保护工作，并为未来在跨模态对齐、情感细腻度提升以及支持更多戏曲种类方面指明了方向。

> This paper introduces a novel multi-Agent framework that automates the end to end production of Qinqiang opera by integrating Large Language Models , visual generation, and Text to Speech synthesis. Three specialized agents collaborate in sequence: Agent1 uses an LLM to craft coherent, culturally grounded scripts;Agent2 employs visual generation models to render contextually accurate stage scenes; and Agent3 leverages TTS to produce synchronized, emotionally expressive vocal performances. In a case study on Dou E Yuan, the system achieved expert ratings of 3.8 for script fidelity, 3.5 for visual coherence, and 3.8 for speech accuracy-culminating in an overall score of 3.6, a 0.3 point improvement over a Single Agent baseline. Ablation experiments demonstrate that removing Agent2 or Agent3 leads to drops of 0.4 and 0.5 points, respectively, underscoring the value of modular collaboration. This work showcases how AI driven pipelines can streamline and scale the preservation of traditional performing arts, and points toward future enhancements in cross modal alignment, richer emotional nuance, and support for additional opera genres.

[Arxiv](https://arxiv.org/abs/2504.15552)