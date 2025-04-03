# 利用大型语言模型的全文本语音识别纠错链

发布时间：2025年04月02日

`LLM应用` `语音处理`

> Chain of Correction for Full-text Speech Recognition with Large Language Models

# 摘要

> 大语言模型（LLMs）在自动语音识别（ASR）中的全文本错误校正因其能够在长上下文中纠正错误并解决更广泛的错误类型（包括标点恢复和逆文本规范化）而备受关注。然而，仍存在许多挑战，包括与稳定性、可控性、完整性和流畅性相关的问题。为了解决这些挑战，本文提出了基于LLMs的全文本错误校正链式校正（Chain of Correction，CoC），它在常规的多轮对话格式下，利用预识别文本作为指导，分段落校正错误。CoC还利用预识别的全文本作为上下文，使模型能够更好地理解全局语义并全面掌握整个内容。通过使用开源的全文本错误校正数据集ChFT，我们对预训练的LLM进行了微调，以评估CoC框架的性能。实验结果表明，CoC能够有效校正全文本ASR输出中的错误，并显著优于基线和基准系统。我们进一步分析了如何设置校正阈值以平衡校正不足和过度重写，将CoC模型外推至极长的ASR输出，并研究了是否可以利用其他类型的信息来指导错误校正过程。

> Full-text error correction with Large Language Models (LLMs) for Automatic Speech Recognition (ASR) has gained increased attention due to its potential to correct errors across long contexts and address a broader spectrum of error types, including punctuation restoration and inverse text normalization. Nevertheless, many challenges persist, including issues related to stability, controllability, completeness, and fluency. To mitigate these challenges, this paper proposes the Chain of Correction (CoC) for full-text error correction with LLMs, which corrects errors segment by segment using pre-recognized text as guidance within a regular multi-turn chat format. The CoC also uses pre-recognized full text for context, allowing the model to better grasp global semantics and maintain a comprehensive overview of the entire content. Utilizing the open-sourced full-text error correction dataset ChFT, we fine-tune a pre-trained LLM to evaluate the performance of the CoC framework. Experimental results demonstrate that the CoC effectively corrects errors in full-text ASR outputs, significantly outperforming baseline and benchmark systems. We further analyze how to set the correction threshold to balance under-correction and over-rephrasing, extrapolate the CoC model on extremely long ASR outputs, and investigate whether other types of information can be employed to guide the error correction process.

[Arxiv](https://arxiv.org/abs/2504.01519)