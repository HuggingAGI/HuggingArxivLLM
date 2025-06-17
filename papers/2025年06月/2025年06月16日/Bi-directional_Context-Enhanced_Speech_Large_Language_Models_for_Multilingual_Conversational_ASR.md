# 双向上下文增强语音大型语言模型在多语言对话式ASR中的应用

发布时间：2025年06月16日

`LLM应用` `语音识别` `语音处理`

> Bi-directional Context-Enhanced Speech Large Language Models for Multilingual Conversational ASR

# 摘要

> 本文提出了一种将语言特定的双向上下文整合到语音大语言模型（SLLM）中的方法，旨在提升多语言连续对话式自动语音识别（ASR）的效果。我们在训练过程中引入了基于字符级别的上下文掩码策略，通过随机移除部分上下文来增强模型的鲁棒性，使其更贴近推理过程中可能出现的错误转录。在解码阶段，采用了两阶段流水线：首先进行孤立段落的初始解码，随后利用邻近假设进行上下文感知的重新解码。我们在涵盖11种语言的1500小时多语言对话语音与语言模型（MLC-SLM）语料库上进行了评估，与强基线相比，我们的方法实现了18%的相对提升，甚至超越了在6000小时数据上训练的MLC-SLM竞赛模型。这些结果凸显了在多语言连续对话式ASR中引入上下文信息的重要价值。

> This paper introduces the integration of language-specific bi-directional context into a speech large language model (SLLM) to improve multilingual continuous conversational automatic speech recognition (ASR). We propose a character-level contextual masking strategy during training, which randomly removes portions of the context to enhance robustness and better emulate the flawed transcriptions that may occur during inference. For decoding, a two-stage pipeline is utilized: initial isolated segment decoding followed by context-aware re-decoding using neighboring hypotheses. Evaluated on the 1500-hour Multilingual Conversational Speech and Language Model (MLC-SLM) corpus covering eleven languages, our method achieves an 18% relative improvement compared to a strong baseline, outperforming even the model trained on 6000 hours of data for the MLC-SLM competition. These results underscore the significant benefit of incorporating contextual information in multilingual continuous conversational ASR.

[Arxiv](https://arxiv.org/abs/2506.13396)