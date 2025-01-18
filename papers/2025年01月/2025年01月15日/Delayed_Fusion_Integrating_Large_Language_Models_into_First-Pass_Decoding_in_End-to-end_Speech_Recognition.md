# 延迟融合：在端到端语音识别中，将大型语言模型融入第一遍解码

发布时间：2025年01月15日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于自动语音识别（ASR）系统中，并提出了一种新的“延迟融合”方法来提高解码效率和准确性。论文的核心是LLM在具体应用场景（ASR）中的优化和使用，因此属于LLM应用类别。` `语音识别`

> Delayed Fusion: Integrating Large Language Models into First-Pass Decoding in End-to-end Speech Recognition

# 摘要

> 本文介绍了一种结合大型语言模型（LLMs）的端到端自动语音识别（E2E-ASR）高效解码方法。尽管浅融合是常见的语言模型融入方式，但在LLMs应用中，我们面临两大挑战：（1）LLM推理计算成本高；（2）ASR模型与LLM可能存在词汇不匹配。为解决这一问题，通常需要重新训练ASR模型或LLM，这不仅耗时，有时甚至不可行。为此，我们提出了“延迟融合”方法，在解码过程中延迟应用LLM分数到ASR假设上，从而更便捷地使用预训练LLMs。该方法不仅减少了LLM评分的假设数量，还降低了LLM推理调用次数，并支持在解码过程中重新标记ASR假设，以应对ASR与LLM标记化方式不同的情况。通过LibriHeavy ASR语料库和OpenLLaMA 3B & 7B、Mistral 7B三个公开LLMs的实验，我们证明延迟融合在解码速度和准确性上均优于浅融合和N-best重评分。

> This paper presents an efficient decoding approach for end-to-end automatic speech recognition (E2E-ASR) with large language models (LLMs). Although shallow fusion is the most common approach to incorporate language models into E2E-ASR decoding, we face two practical problems with LLMs. (1) LLM inference is computationally costly. (2) There may be a vocabulary mismatch between the ASR model and the LLM. To resolve this mismatch, we need to retrain the ASR model and/or the LLM, which is at best time-consuming and in many cases not feasible. We propose "delayed fusion," which applies LLM scores to ASR hypotheses with a delay during decoding and enables easier use of pre-trained LLMs in ASR tasks. This method can reduce not only the number of hypotheses scored by the LLM but also the number of LLM inference calls. It also allows re-tokenizion of ASR hypotheses during decoding if ASR and LLM employ different tokenizations. We demonstrate that delayed fusion provides improved decoding speed and accuracy compared to shallow fusion and N-best rescoring using the LibriHeavy ASR corpus and three public LLMs, OpenLLaMA 3B & 7B and Mistral 7B.

[Arxiv](https://arxiv.org/abs/2501.09258)