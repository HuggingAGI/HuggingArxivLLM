# 基于大型语言模型的罕见词生成式错误修正研究：合成数据与语音上下文的结合

发布时间：2025年05月22日

`LLM应用` `语音识别`

> LLM-based Generative Error Correction for Rare Words with Synthetic Data and Phonetic Context

# 摘要

> 生成式错误校正（GER）与大型语言模型（LLMs）结合，成为提升自动语音识别（ASR）性能的有效后处理方法。然而，由于训练数据有限，该方法在处理罕见或领域特定词汇时效果欠佳。此外，现有基于LLMs的GER方法主要依赖文本信息，忽视语音提示，导致过度校正。为解决这些问题，我们提出了一种针对罕见词汇并结合语音信息的新型LLM-based GER方法。首先，我们生成包含罕见词汇的合成数据，用于微调GER模型；其次，将ASR的N-best假设与语音上下文相结合，以缓解过度校正。实验结果表明，我们的方法不仅提升了对罕见词汇的校正效果，还降低了英文和日文数据集上的WER和CER。

> Generative error correction (GER) with large language models (LLMs) has emerged as an effective post-processing approach to improve automatic speech recognition (ASR) performance. However, it often struggles with rare or domain-specific words due to limited training data. Furthermore, existing LLM-based GER approaches primarily rely on textual information, neglecting phonetic cues, which leads to over-correction. To address these issues, we propose a novel LLM-based GER approach that targets rare words and incorporates phonetic information. First, we generate synthetic data to contain rare words for fine-tuning the GER model. Second, we integrate ASR's N-best hypotheses along with phonetic context to mitigate over-correction. Experimental results show that our method not only improves the correction of rare words but also reduces the WER and CER across both English and Japanese datasets.

[Arxiv](https://arxiv.org/abs/2505.17410)