# 音频大语言模型能够胜任描述性语音质量评估任务

发布时间：2025年01月27日

`Agent

理由：这篇论文主要讨论了多模态代理（特别是音频LLMs）如何感知和处理语音质量，并提出了一个基于自然语言的语音评估语料库以及一种与LLM蒸馏对齐的方法。研究的核心是提升代理在现实世界中的感知能力，特别是听觉和感官智能代理的发展。因此，这篇论文应归类为Agent。` `语音处理` `人工智能`

> Audio Large Language Models Can Be Descriptive Speech Quality Evaluators

# 摘要

> 理想的多模态代理应能感知输入模态的质量。近期，大型语言模型（LLMs）通过整合听觉系统，已能处理多种语音任务。然而，大多数音频LLMs仍无法感知其处理的语音质量。这一局限源于语音质量评估通常被排除在多任务训练之外，主要因缺乏合适的数据集。为此，我们推出了首个基于自然语言的语音评估语料库，该库由真实人类评分生成。除了提供整体平均意见得分（MOS）外，该语料库还支持多维度详细分析，并识别质量下降的原因。此外，它还能进行类似人类判断的语音样本A/B测试。基于此语料库，我们提出了与LLM蒸馏（ALLD）对齐的方法，指导音频LLM从原始语音中提取信息并生成有意义的响应。实验显示，ALLD在MOS预测中表现优异，均方误差为0.17，A/B测试准确率达98.6%。生成的任务响应在两个任务上的BLEU得分分别为25.8和30.2，超越了特定任务模型的能力。这一研究推动了音频LLMs对语音信号的全面感知，助力现实世界听觉和感官智能代理的发展。

> An ideal multimodal agent should be aware of the quality of its input modalities. Recent advances have enabled large language models (LLMs) to incorporate auditory systems for handling various speech-related tasks. However, most audio LLMs remain unaware of the quality of the speech they process. This limitation arises because speech quality evaluation is typically excluded from multi-task training due to the lack of suitable datasets. To address this, we introduce the first natural language-based speech evaluation corpus, generated from authentic human ratings. In addition to the overall Mean Opinion Score (MOS), this corpus offers detailed analysis across multiple dimensions and identifies causes of quality degradation. It also enables descriptive comparisons between two speech samples (A/B tests) with human-like judgment. Leveraging this corpus, we propose an alignment approach with LLM distillation (ALLD) to guide the audio LLM in extracting relevant information from raw speech and generating meaningful responses. Experimental results demonstrate that ALLD outperforms the previous state-of-the-art regression model in MOS prediction, with a mean square error of 0.17 and an A/B test accuracy of 98.6%. Additionally, the generated responses achieve BLEU scores of 25.8 and 30.2 on two tasks, surpassing the capabilities of task-specific models. This work advances the comprehensive perception of speech signals by audio LLMs, contributing to the development of real-world auditory and sensory intelligent agents.

[Arxiv](https://arxiv.org/abs/2501.17202)