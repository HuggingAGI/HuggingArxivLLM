# 触觉LLaMA：一种用于触觉描述的多模态感官语言模型

发布时间：2025年08月08日

`LLM应用

理由：这篇论文主要探讨了触觉信号如何通过大型语言模型（LLM）生成自然语言描述，并提出了一个名为HapticLLaMA的多模态感官语言模型。研究涉及将触觉信号转换为语言描述的具体方法和应用，属于大型语言模型在触觉感知和生成任务中的实际应用，因此归类为LLM应用。` `触觉感知` `虚拟现实`

> HapticLLaMA: A Multimodal Sensory Language Model for Haptic Captioning

# 摘要

> 触觉字幕生成是从触觉信号（如振动）生成自然语言描述的任务，应用于虚拟现实、无障碍和康复领域。尽管以往的多模态研究主要集中在视觉和音频上，但触觉信号作为触觉感知的研究仍相对较少。为了解决这一差距，我们正式定义了触觉字幕生成任务，并提出了HapticLLaMA，一个多模态感官语言模型，能够将振动信号解释为给定感官、情感或关联类别的描述。我们研究了两种类型的触觉分词器，即基于频率的分词器和基于EnCodec的分词器，它们将触觉信号转换为离散单元序列，从而实现与LLaMA模型的集成。HapticLLaMA的训练分为两个阶段：(1) 使用LLaMA架构和基于LoRA的自适应进行监督微调；(2) 通过基于人类反馈的强化学习（RLHF）进行微调。我们使用自动化的n-gram指标和人工评估来评估HapticLLaMA的字幕生成性能。HapticLLaMA在解释触觉振动信号方面表现出强大的能力，分别获得了59.98的METEOR分数和32.06的BLEU-4分数。此外，超过61%的生成字幕在7分制的人工评分中获得3.5分以上，其中RLHF使整体评分分布提高了10%，表明与人类触觉感知的更强对齐。这些发现突显了大型语言模型处理和适应感官数据的潜力。

> Haptic captioning is the task of generating natural language descriptions from haptic signals, such as vibrations, for use in virtual reality, accessibility, and rehabilitation applications. While previous multimodal research has focused primarily on vision and audio, haptic signals for the sense of touch remain underexplored. To address this gap, we formalize the haptic captioning task and propose HapticLLaMA, a multimodal sensory language model that interprets vibration signals into descriptions in a given sensory, emotional, or associative category. We investigate two types of haptic tokenizers, a frequency-based tokenizer and an EnCodec-based tokenizer, that convert haptic signals into sequences of discrete units, enabling their integration with the LLaMA model. HapticLLaMA is trained in two stages: (1) supervised fine-tuning using the LLaMA architecture with LoRA-based adaptation, and (2) fine-tuning via reinforcement learning from human feedback (RLHF). We assess HapticLLaMA's captioning performance using both automated n-gram metrics and human evaluation. HapticLLaMA demonstrates strong capability in interpreting haptic vibration signals, achieving a METEOR score of 59.98 and a BLEU-4 score of 32.06 respectively. Additionally, over 61% of the generated captions received human ratings above 3.5 on a 7-point scale, with RLHF yielding a 10% improvement in the overall rating distribution, indicating stronger alignment with human haptic perception. These findings highlight the potential of large language models to process and adapt to sensory data.

[Arxiv](https://arxiv.org/abs/2508.06475)