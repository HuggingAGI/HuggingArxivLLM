# 衡量音频对正确性的影响：大型音频语言模型的音频贡献感知后训练

发布时间：2025年09月25日

`强化学习` `媒体与娱乐`

> Measuring Audio's Impact on Correctness: Audio-Contribution-Aware Post-Training of Large Audio Language Models

# 摘要

> 大型音频语言模型（LALMs）是多模态人工智能的重要前沿方向，可应对各类音频任务。近年来，LALMs的后训练因相比基础模型性能显著提升而备受关注。尽管单阶段后训练（如强化学习，RL）已展现出良好效果，但多阶段方法（如先监督微调SFT再RL）的表现仍不尽如人意。目前，如何在多个训练阶段分配数据以最大化LALM性能尚未得到充分研究，且此类研究缺乏大规模、高质量的数据集。为解决这些问题，我们首先构建了AudioMCQ——一个全面的音频多项选择题数据集，包含571k样本及两种思维链注释。其次，我们研究了LALMs中普遍存在的“零音频贡献”现象——模型仅依赖文本信息得出正确答案，完全不处理音频内容。为此，我们提出音频贡献过滤（Audio-Contribution Filtering）方法，将数据划分为弱音频贡献和强音频贡献两个子集。基于这些发现，我们提出了两种高效的后训练范式：弱到强（先在弱音频贡献数据上进行SFT，再在强音频贡献数据上进行RL）和混合到强（先在混合音频贡献数据上进行SFT，再在强音频贡献数据上进行RL）。借助AudioMCQ，我们在DCASE 2025音频问答挑战赛中斩获冠军。此外，结合我们的数据集与不同训练策略，我们在MMAU-test-mini、MMAU、MMAR和MMSU上分别达到78.2%、75.6%、67.1%和70.7%的准确率，刷新了这些基准测试的最先进性能。

> Large Audio Language Models (LALMs) represent an important frontier in multimodal AI, addressing diverse audio tasks. Recently, post-training of LALMs has received increasing attention due to significant performance improvements over foundation models. While single-stage post-training such as reinforcement learning (RL) has demonstrated promising results, multi-stage approaches such as supervised fine-tuning (SFT) followed by RL remain suboptimal. The allocation of data across multiple training stages to maximize LALM capabilities has not been fully explored, and large-scale, high-quality datasets for such research are also lacking. To address these problems, we firstly present AudioMCQ, a comprehensive audio multiple-choice question dataset comprising 571k samples with two kinds of chain-of-thought annotations. Secondly, we investigate the prevalent zero audio-contribution phenomenon in LALMs, where models derive correct answers solely from textual information without processing audio content. We propose Audio-Contribution Filtering to partition data into weak and strong audio-contribution subsets. Based on these insights, we develop two effective post-training paradigms: Weak-to-Strong (SFT on weak audio-contribution data followed by RL on strong audio-contribution data) and Mixed-to-Strong (SFT on mixed audio-contribution data followed by RL on strong audio-contribution data). We achieve first place in the DCASE 2025 Audio-Question-Answering challenge by using AudioMCQ. Additionally, leveraging our dataset with different training strategies, we achieve 78.2\% on MMAU-test-mini, 75.6\% on MMAU, 67.1\% on MMAR, and 70.7\% on MMSU, establishing new state-of-the-art performance across these benchmarks.

[Arxiv](https://arxiv.org/abs/2509.21060)