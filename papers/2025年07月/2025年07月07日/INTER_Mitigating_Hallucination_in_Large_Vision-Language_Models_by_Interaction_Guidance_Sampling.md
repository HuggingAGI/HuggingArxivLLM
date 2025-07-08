# # INTER：交互引导采样方法，有效缓解大型视觉-语言模型的幻觉问题

发布时间：2025年07月07日

`LLM应用

理由：这篇论文主要探讨了如何通过算法改进大型视觉-语言模型（LVLMs）的幻觉现象，属于模型的应用层面。` `视觉问答` `图像描述生成`

> INTER: Mitigating Hallucination in Large Vision-Language Models by Interaction Guidance Sampling

# 摘要

> 大型视觉-语言模型 (LVLMs) 中的幻觉现象为实际应用带来了严峻的挑战，因为 LVLMs 可能会生成看似合理但与视觉内容不一致的响应。这一问题在人类认知中极为罕见。我们主张，这种差异源于人类能够有效利用数据样本中的多模态交互信息。具体而言，人类通常会首先收集多模态信息，分析各模态之间的交互以理解内容，然后通过语言表达理解。基于这一观察，我们在流行的 LVLMs 上进行了大量实验，并获得了令人惊讶的见解：LVLMs 在多模态样本上表现出类似人类、尽管较不明显，的认知行为。在此基础上，我们进一步提出了 	extbf{INTER}: 	extbf{Inter}action Guidance Sampling，这是一种无需训练的新算法，可在不需额外数据的情况下缓解幻觉现象。具体来说，INTER 明确引导 LVLMs 在生成响应时有效重新应用其对多模态交互信息的理解，从而减少潜在的幻觉。在包括视觉问答 (VQA) 和图像描述生成任务在内的六个基准测试中，与最先进的解码策略相比，INTER 在五个 LVLMs 上实现了平均 3.4\% 的提升。代码将在论文被接受后发布。

> Hallucinations in large vision-language models (LVLMs) pose significant challenges for real-world applications, as LVLMs may generate responses that appear plausible yet remain inconsistent with the associated visual content. This issue rarely occurs in human cognition. We argue that this discrepancy arises from humans' ability to effectively leverage multimodal interaction information in data samples. Specifically, humans typically first gather multimodal information, analyze the interactions across modalities for understanding, and then express their understanding through language. Motivated by this observation, we conduct extensive experiments on popular LVLMs and obtained insights that surprisingly reveal human-like, though less pronounced, cognitive behavior of LVLMs on multimodal samples. Building on these findings, we further propose \textbf{INTER}: \textbf{Inter}action Guidance Sampling, a novel training-free algorithm that mitigate hallucinations without requiring additional data. Specifically, INTER explicitly guides LVLMs to effectively reapply their understanding of multimodal interaction information when generating responses, thereby reducing potential hallucinations. On six benchmarks including VQA and image captioning tasks, INTER achieves an average improvement of up to 3.4\% on five LVLMs compared to the state-of-the-art decoding strategy. The code will be released when the paper is accepted.

[Arxiv](https://arxiv.org/abs/2507.05056)