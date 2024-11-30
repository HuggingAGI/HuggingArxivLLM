# 本研究致力于将神经信号转化为可识别的语音，探索从大脑活动直接解读言语信息的可能性。

发布时间：2024年03月04日

`Agent`

> Decode Neural signal as Speech

# 摘要

> 随着大型语言模型的飞速发展，从大脑动态中解析语言已成为脑机接口研究的关键探索方向，其中，相比于需要通过手术植入电极的侵入式信号，非侵入式的神经信号（如EEG、MEG）因安全性高且适用广泛而备受瞩目。然而，在这一领域，有三个方面的研究仍显不足：首先，过往研究集中于EEG，却未曾充分利用拥有更好信号质量的MEG进行相关问题的解决；其次，大多数现有方法在生成解码阶段采用了实际应用中并不适宜的“教师强制”策略；再者，大部分研究基于非全自回归的“BART”模型，尽管它在其他序列任务上有不错的表现。本论文创新性地研究了在语音解码框架下利用MEG信号实现脑内思维到文本转换的问题，并首度提出了一种无需教师强制指导的基于交叉注意力机制的“whisper”模型，能够直接从MEG信号高效生成文本。在未预先训练及无教师强制指导下，该模型在\textit{GWilliams}和\textit{Schoffelen}两大数据集上取得了亮眼的BLEU-1分数——分别为60.30和52.89。此外，本文还系统梳理了语音解码结构在处理神经解码任务时的具体表现，深入探讨了预训练初始化、训练与验证集分割、数据增强技术以及规模效应等诸多关键因素。

> Decoding language from brain dynamics is an important open direction in the realm of brain-computer interface (BCI), especially considering the rapid growth of large language models. Compared to invasive-based signals which require electrode implantation surgery, non-invasive neural signals (e.g. EEG, MEG) have attracted increasing attention considering their safety and generality. However, the exploration is not adequate in three aspects: 1) previous methods mainly focus on EEG but none of the previous works address this problem on MEG with better signal quality; 2) prior works have predominantly used ``teacher-forcing" during generative decoding, which is impractical; 3) prior works are mostly ``BART-based" not fully auto-regressive, which performs better in other sequence tasks. In this paper, we explore the brain-to-text translation of MEG signals in a speech-decoding formation. Here we are the first to investigate a cross-attention-based ``whisper" model for generating text directly from MEG signals without teacher forcing. Our model achieves impressive BLEU-1 scores of 60.30 and 52.89 without pretraining \& teacher-forcing on two major datasets (\textit{GWilliams} and \textit{Schoffelen}). This paper conducts a comprehensive review to understand how speech decoding formation performs on the neural decoding tasks, including pretraining initialization, training \& evaluation set splitting, augmentation, and scaling law.

[Arxiv](https://arxiv.org/abs/2403.01748)