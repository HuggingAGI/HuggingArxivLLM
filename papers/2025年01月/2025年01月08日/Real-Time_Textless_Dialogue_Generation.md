# 实时无文本对话生成

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进语音对话系统，特别是通过提出一种实时、无文本的语音对话生成模型（RTTL-DG）来提升语音对话的自然度和响应速度。虽然论文涉及了语音处理和多模态交互，但其核心仍然是基于LLMs的应用，旨在通过直接处理流式语音对话来生成更自然的响应。因此，这篇论文应归类为LLM应用。` `语音交互` `对话系统`

> Real-Time Textless Dialogue Generation

# 摘要

> # 摘要
大型语言模型（LLMs）的最新进展推动了文本对话系统的显著进步，使其能够生成高质量、准确且连贯的响应，覆盖广泛主题和任务。然而，语音对话系统在自然度方面仍显不足，常表现为响应迟缓、回复过于保守或通用，缺乏自然的节奏和流畅的轮换。这一短板主要源于对传统级联设计的过度依赖，该设计采用分离的、顺序的组件，并以文本作为中间表示。本文提出了一种实时、无文本的语音对话生成模型（RTTL-DG），旨在突破这些限制。我们的系统通过直接处理流式语音对话，实现了流畅的轮换和极低延迟的响应生成。此外，模型还整合了反馈信号、过滤器、笑声等副语言信号，这些在级联系统中通常缺失，从而打造更自然、更人性化的交互体验。实现代码和生成样本已开源：https://github.com/mailong25/rts2s-dg

> Recent advancements in large language models (LLMs) have led to significant progress in text-based dialogue systems. These systems can now generate high-quality responses that are accurate and coherent across a wide range of topics and tasks. However, spoken dialogue systems still lag behind in terms of naturalness. They tend to produce robotic interactions, with issues such as slow response times, overly generic or cautious replies, and a lack of natural rhythm and fluid turn-taking. This shortcoming is largely due to the over-reliance on the traditional cascaded design, which involve separate, sequential components, as well as the use of text as an intermediate representation. This paper propose a real-time, textless spoken dialogue generation model (RTTL-DG) that aims to overcome these challenges. Our system enables fluid turn-taking and generates responses with minimal delay by processing streaming spoken conversation directly. Additionally, our model incorporates backchannels, filters, laughter, and other paralinguistic signals, which are often absent in cascaded dialogue systems, to create more natural and human-like interactions. The implementations and generated samples are available in our repository: https://github.com/mailong25/rts2s-dg

[Arxiv](https://arxiv.org/abs/2501.04877)