# 利用大型语言模型预测紧凑短语重写，助力ASR后编辑

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）在文本重写任务中的表现，并提出了新的编辑表示法来提高效率和准确性。虽然涉及到了模型的理论改进，但核心内容集中在如何应用LLMs来解决实际问题（如自动语音识别后编辑任务），因此更适合归类为“LLM应用”。` `语音识别`

> Predicting Compact Phrasal Rewrites with Large Language Models for ASR Post Editing

# 摘要

> 大型语言模型（LLMs）在文本风格转换和语法纠错等重写任务中表现卓越。尽管这些任务的输入与输出高度重叠，解码成本仍随输出长度增加而上升。Kaneko 和 Okazaki（2023）利用输入输出的重叠，提出了模型无关的编辑跨度表示法，压缩重写内容以节省计算资源，在四个重写任务中实现了近80%的输出长度缩减，且对准确性影响极小。本文受短语统计机器翻译启发，提出了替代的编辑短语表示法，并系统比较了其与跨度表示法的优劣。我们将LLM重写模型应用于自动语音识别（ASR）后编辑任务，发现仅目标短语编辑表示法在效率与准确性之间取得了最佳平衡。在LibriSpeech测试集上，该方法缩小了编辑跨度模型与完整重写模型之间50-60%的WER差距，同时仅损失了编辑跨度模型长度缩减率的10-20%。

> Large Language Models (LLMs) excel at rewriting tasks such as text style transfer and grammatical error correction. While there is considerable overlap between the inputs and outputs in these tasks, the decoding cost still increases with output length, regardless of the amount of overlap. By leveraging the overlap between the input and the output, Kaneko and Okazaki (2023) proposed model-agnostic edit span representations to compress the rewrites to save computation. They reported an output length reduction rate of nearly 80% with minimal accuracy impact in four rewriting tasks. In this paper, we propose alternative edit phrase representations inspired by phrase-based statistical machine translation. We systematically compare our phrasal representations with their span representations. We apply the LLM rewriting model to the task of Automatic Speech Recognition (ASR) post editing and show that our target-phrase-only edit representation has the best efficiency-accuracy trade-off. On the LibriSpeech test set, our method closes 50-60% of the WER gap between the edit span model and the full rewrite model while losing only 10-20% of the length reduction rate of the edit span model.

[Arxiv](https://arxiv.org/abs/2501.13831)