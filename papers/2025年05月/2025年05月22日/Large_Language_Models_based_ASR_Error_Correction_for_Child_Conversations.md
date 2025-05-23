# 基于大型语言模型的儿童对话ASR错误修正

发布时间：2025年05月22日

`LLM应用` `语音处理` `儿童语音`

> Large Language Models based ASR Error Correction for Child Conversations

# 摘要

> 自动语音识别（ASR）近期取得了显著进展，但准确转录儿童语音仍具挑战性。大型语言模型（LLMs）在提升ASR转录质量方面展现出潜力，然而其在儿童对话场景中的应用尚未得到充分探索。本研究旨在探讨LLMs在纠正儿童对话语音ASR错误方面的潜力。通过在两个儿童对话语音数据集上进行实验，我们验证了LLMs的潜力与挑战。实验采用零样本和微调后的ASR输出，结果显示：LLMs在修正零样本及微调后的CTC基线ASR输出方面表现良好，但在结合上下文信息或使用微调后的自回归ASR（如Whisper）输出时，性能提升仍具挑战。

> Automatic Speech Recognition (ASR) has recently shown remarkable progress, but accurately transcribing children's speech remains a significant challenge. Recent developments in Large Language Models (LLMs) have shown promise in improving ASR transcriptions. However, their applications in child speech including conversational scenarios are underexplored. In this study, we explore the use of LLMs in correcting ASR errors for conversational child speech. We demonstrate the promises and challenges of LLMs through experiments on two children's conversational speech datasets with both zero-shot and fine-tuned ASR outputs. We find that while LLMs are helpful in correcting zero-shot ASR outputs and fine-tuned CTC-based ASR outputs, it remains challenging for LLMs to improve ASR performance when incorporating contextual information or when using fine-tuned autoregressive ASR (e.g., Whisper) outputs.

[Arxiv](https://arxiv.org/abs/2505.16212)