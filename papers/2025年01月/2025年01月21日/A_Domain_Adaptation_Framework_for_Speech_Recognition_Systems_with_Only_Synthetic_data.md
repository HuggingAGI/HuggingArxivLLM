# 仅用合成数据的语音识别系统领域适应框架

发布时间：2025年01月21日

`LLM应用

理由：该论文摘要描述了如何利用大型语言模型（LLMs）生成领域特定文本，并通过文本到语音技术将其转换为语音，进而用于预训练的ASR模型的领域适应。这涉及到LLM在实际应用中的使用，特别是通过生成合成数据来改进ASR模型的性能。因此，该论文应归类为“LLM应用”。` `语音识别` `领域适应`

> A Domain Adaptation Framework for Speech Recognition Systems with Only Synthetic data

# 摘要

> 我们提出了DAS（基于合成数据的领域适应），这是一种创新的领域适应框架，专为预训练的ASR模型设计，旨在无需真实数据的情况下高效适应多种语言定义的领域。DAS首先利用大型语言模型（LLMs）生成领域特定文本，再通过文本到语音技术将其转换为语音。这些合成数据用于通过低秩适配器（LoRAs）对Whisper进行微调，以适配音乐、天气和体育等目标领域。我们引入了一种新颖的一遍解码策略，在自回归文本生成过程中高效整合多个LoRA适配器的预测。实验结果表明，与原始模型相比，所有目标领域的单词错误率（WER）显著降低了10%到17%，而在域外设置中的性能损失极小（例如，Librispeech测试集上仅下降1%）。此外，DAS在推理时表现出色，使用三个LoRA适配器时，实时因子（RTF）仅增加9%。

> We introduce DAS (Domain Adaptation with Synthetic data), a novel domain adaptation framework for pre-trained ASR model, designed to efficiently adapt to various language-defined domains without requiring any real data. In particular, DAS first prompts large language models (LLMs) to generate domain-specific texts before converting these texts to speech via text-to-speech technology. The synthetic data is used to fine-tune Whisper with Low-Rank Adapters (LoRAs) for targeted domains such as music, weather, and sports. We introduce a novel one-pass decoding strategy that merges predictions from multiple LoRA adapters efficiently during the auto-regressive text generation process. Experimental results show significant improvements, reducing the Word Error Rate (WER) by 10% to 17% across all target domains compared to the original model, with minimal performance regression in out-of-domain settings (e.g., -1% on Librispeech test sets). We also demonstrate that DAS operates efficiently during inference, introducing an additional 9% increase in Real Time Factor (RTF) compared to the original model when inferring with three LoRA adapters.

[Arxiv](https://arxiv.org/abs/2501.12501)