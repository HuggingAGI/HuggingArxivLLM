# Empathy-R1：共情链与强化学习框架——面向长文本心理健康支持

发布时间：2025年09月18日

`LLM应用` `医疗健康`

> Empathy-R1: A Chain-of-Empathy and Reinforcement Learning Framework for Long-Form Mental Health Support

# 摘要

> 共情是提供有效心理健康支持的核心，尤其在应对长咨询文本（LCTs）时。但现有大型语言模型（LLMs）生成的回复虽语义流畅，却缺乏真正心理支持所需的结构化推理能力，在中文场景中这一问题尤为突出。为此，我们提出新型框架Empathy-R1，将共情链（CoE）推理过程与强化学习（RL）相融合，以提升LCTs的回复质量。借鉴认知行为疗法的思路，我们的CoE范式引导模型按顺序推理求助者的情绪、成因及意图，让模型的推理过程兼具透明性与可解释性。该框架依托全新的大规模中文数据集Empathy-QA和两阶段训练流程：首先通过监督微调植入CoE的推理结构，再通过专用奖励模型引导强化学习（RL），优化最终回复的治疗相关性与语境适配性。实验结果显示，Empathy-R1在关键自动指标上表现突出；更重要的是，人类评估验证了其优越性——不仅显著优于主流基线模型，在我们的新基准上Win@1率更达到44.30%。Empathy-R1通过生成可解释且语境细腻的回复，为开发负责任、真正有益的心理健康支持AI迈出了重要一步。

> Empathy is critical for effective mental health support, especially when addressing Long Counseling Texts (LCTs). However, existing Large Language Models (LLMs) often generate replies that are semantically fluent but lack the structured reasoning necessary for genuine psychological support, particularly in a Chinese context. To bridge this gap, we introduce Empathy-R1, a novel framework that integrates a Chain-of-Empathy (CoE) reasoning process with Reinforcement Learning (RL) to enhance response quality for LCTs. Inspired by cognitive-behavioral therapy, our CoE paradigm guides the model to sequentially reason about a help-seeker's emotions, causes, and intentions, making its thinking process both transparent and interpretable. Our framework is empowered by a new large-scale Chinese dataset, Empathy-QA, and a two-stage training process. First, Supervised Fine-Tuning instills the CoE's reasoning structure. Subsequently, RL, guided by a dedicated reward model, refines the therapeutic relevance and contextual appropriateness of the final responses. Experiments show that Empathy-R1 achieves strong performance on key automatic metrics. More importantly, human evaluations confirm its superiority, showing a clear preference over strong baselines and achieving a Win@1 rate of 44.30% on our new benchmark. By enabling interpretable and contextually nuanced responses, Empathy-R1 represents a significant advancement in developing responsible and genuinely beneficial AI for mental health support.

[Arxiv](https://arxiv.org/abs/2509.14851)