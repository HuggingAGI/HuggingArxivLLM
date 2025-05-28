# TAT-R1：基于强化学习与词对齐的术语感知翻译

发布时间：2025年05月27日

`LLM应用` `机器翻译`

> TAT-R1: Terminology-Aware Translation with Reinforcement Learning and Word Alignment

# 摘要

> 深度推理型大语言模型（LLMs）如DeepSeek-R1在数学和编码等领域取得了显著进展。受到启发，研究者开始采用强化学习（RL）提升模型推理能力并优化机器翻译（MT）质量。然而，MT中至关重要的术语翻译任务在深度推理型LLMs中尚未得到探索。本文提出	extbf{TAT-R1}，一个基于强化学习与词对齐的术语感知翻译模型。具体而言，我们首先通过词对齐模型提取关键词翻译对，然后基于提取的对齐关系设计了三种规则化的对齐奖励。借助这些奖励，强化学习训练的翻译模型能够更精准地关注源文本中关键信息，包括术语的准确翻译。实验结果表明，TAT-R1在术语翻译准确性和通用翻译任务上均取得了显著成效。与基线模型相比，我们的模型在术语翻译准确性上有明显提升，同时保持了通用翻译任务的可比性能。此外，我们对适用于机器翻译的DeepSeek-R1类训练范式进行了详细消融研究，揭示了几个关键发现。

> Recently, deep reasoning large language models(LLMs) like DeepSeek-R1 have made significant progress in tasks such as mathematics and coding. Inspired by this, several studies have employed reinforcement learning(RL) to enhance models' deep reasoning capabilities and improve machine translation(MT) quality. However, the terminology translation, an essential task in MT, remains unexplored in deep reasoning LLMs. In this paper, we propose \textbf{TAT-R1}, a terminology-aware translation model trained with reinforcement learning and word alignment. Specifically, we first extract the keyword translation pairs using a word alignment model. Then we carefully design three types of rule-based alignment rewards with the extracted alignment relationships. With those alignment rewards, the RL-trained translation model can learn to focus on the accurate translation of key information, including terminology in the source text. Experimental results show the effectiveness of TAT-R1. Our model significantly improves terminology translation accuracy compared to the baseline models while maintaining comparable performance on general translation tasks. In addition, we conduct detailed ablation studies of the DeepSeek-R1-like training paradigm for machine translation and reveal several key findings.

[Arxiv](https://arxiv.org/abs/2505.21172)