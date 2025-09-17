# PAC：发音感知的基于上下文大型语言模型自动语音识别

发布时间：2025年09月16日

`LLM应用` `基础理论`

> PAC: Pronunciation-Aware Contextualized Large Language Model-based Automatic Speech Recognition

# 摘要

> 本文提出发音感知上下文（PAC）框架，旨在解决基于大型语言模型（LLM）的自动语音识别（ASR）系统中的两大核心挑战：高效发音建模与稳健同音词区分——这两者对于生僻词及长尾词识别至关重要。该方法采用两阶段学习模式：首先，引入发音引导的上下文学习机制，通过交错的字形-音素上下文建模策略并融入纯字形干扰项，引导模型借助音素线索实现精准识别；其次，提出带扰动标签采样的发音区分强化学习方法，进一步提升模型对上下文同音词的辨别能力。在英文Librispeech和中文AISHELL-1公开数据集上的实验显示，PAC框架表现卓越：（1）相比预训练的LLM-based ASR模型，词错误率（WER）相对降低30.2%和53.8%；（2）针对长尾词，相比强基线模型，偏向词错误率（biased WER）更是分别实现31.8%和60.5%的相对降幅。

> This paper presents a Pronunciation-Aware Contextualized (PAC) framework to address two key challenges in Large Language Model (LLM)-based Automatic Speech Recognition (ASR) systems: effective pronunciation modeling and robust homophone discrimination. Both are essential for raw or long-tail word recognition. The proposed approach adopts a two-stage learning paradigm. First, we introduce a pronunciation-guided context learning method. It employs an interleaved grapheme-phoneme context modeling strategy that incorporates grapheme-only distractors, encouraging the model to leverage phonemic cues for accurate recognition. Then, we propose a pronunciation-discriminative reinforcement learning method with perturbed label sampling to further enhance the modelś ability to distinguish contextualized homophones. Experimental results on the public English Librispeech and Mandarin AISHELL-1 datasets indicate that PAC: (1) reduces relative Word Error Rate (WER) by 30.2% and 53.8% compared to pre-trained LLM-based ASR models, and (2) achieves 31.8% and 60.5% relative reductions in biased WER for long-tail words compared to strong baselines, respectively.

[Arxiv](https://arxiv.org/abs/2509.12647)