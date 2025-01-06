# ICPC: 上下文提示压缩与高效推理

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何通过提示压缩（Prompt Compression）来解决大型语言模型（LLMs）在处理长提示时面临的输入长度限制问题。论文提出的ICPC方法旨在优化提示压缩过程，减少计算资源和内存开销，并提升压缩速度和性能。这属于对LLM在实际应用中的优化和改进，因此归类为LLM应用。` `人工智能`

> ICPC: In-context Prompt Compression with Faster Inference

# 摘要

> 尽管大型语言模型（LLMs）近期取得了显著成功，但由于其输入长度的限制，处理长提示仍然面临挑战。为此，提示压缩通过去除冗余标记成为了一种有效的解决方案。然而，现有方法使用LLM时往往需要额外的计算资源，并带来内存开销。为了解决这一问题，我们提出了ICPC（In-context Prompt Compression），一种新颖且可扩展的提示压缩方法，能够自适应地缩短提示长度。ICPC的核心思想是利用编码器计算提示中每个单词的出现概率，并通过信息函数评估每个单词的信息量，从而在压缩过程中减少信息丢失并提升压缩速度。实验表明，ICPC能够高效压缩各类长文本，并在多种NLP任务中展现出卓越的性能和速度。

> Despite the recent success of Large Language Models (LLMs), it remains challenging to feed LLMs with long prompts due to the fixed size of LLM inputs. As a remedy, prompt compression becomes a promising solution by removing redundant tokens in the prompt. However, using LLM in the existing works requires additional computation resources and leads to memory overheads. To address it, we propose ICPC (In-context Prompt Compression), a novel and scalable prompt compression method that adaptively reduces the prompt length. The key idea of ICPC is to calculate the probability of each word appearing in the prompt using encoders and calculate information carried by each word through the information function, which effectively reduces the information loss during prompt compression and increases the speed of compression. Empirically, we demonstrate that ICPC can effectively compress long texts of different categories and thus achieve better performance and speed on different types of NLP tasks.

[Arxiv](https://arxiv.org/abs/2501.01625)