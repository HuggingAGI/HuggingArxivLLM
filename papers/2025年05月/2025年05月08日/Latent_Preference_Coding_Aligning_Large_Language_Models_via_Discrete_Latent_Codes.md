# 潜在偏好编码：通过离散潜在代码对齐大型语言模型的方法

发布时间：2025年05月08日

`LLM理论` `人工智能`

> Latent Preference Coding: Aligning Large Language Models via Discrete Latent Codes

# 摘要

> 大型语言模型（LLMs）虽然取得了巨大成功，但要使其生成内容与人类偏好保持一致仍是一个重大挑战。现有的偏好建模方法往往依赖于明确或隐含的奖励函数，却忽视了人类偏好复杂多面的本质，这些偏好可能在不同任务和人群中包含相互冲突的因素。为了解决这一问题，我们提出了潜在偏好编码（LPC），这是一种通过离散潜在代码建模整体偏好背后隐含因素及其组合的新颖框架。LPC能够无缝集成到各种离线对齐算法中，无需依赖预定义的奖励函数和手工设计的组合权重，即可从数据中自动推断潜在因素及其重要性。在多个基准上的广泛实验表明，LPC在使用三个基础模型（Mistral-7B、Llama3-8B 和 Llama3-8B-Instruct）时，始终改进了三种对齐算法（DPO、SimPO 和 IPO）的性能。此外，深入分析表明，学习到的潜在代码能够有效捕捉人类偏好分布的差异，并显著提高对数据噪声的对齐鲁棒性。通过为多样的偏好因素提供统一的表示，LPC为开发更强大和灵活的对齐技术铺平了道路，从而实现大型语言模型的负责任部署。

> Large language models (LLMs) have achieved remarkable success, yet aligning their generations with human preferences remains a critical challenge. Existing approaches to preference modeling often rely on an explicit or implicit reward function, overlooking the intricate and multifaceted nature of human preferences that may encompass conflicting factors across diverse tasks and populations. To address this limitation, we introduce Latent Preference Coding (LPC), a novel framework that models the implicit factors as well as their combinations behind holistic preferences using discrete latent codes. LPC seamlessly integrates with various offline alignment algorithms, automatically inferring the underlying factors and their importance from data without relying on pre-defined reward functions and hand-crafted combination weights. Extensive experiments on multiple benchmarks demonstrate that LPC consistently improves upon three alignment algorithms (DPO, SimPO, and IPO) using three base models (Mistral-7B, Llama3-8B, and Llama3-8B-Instruct). Furthermore, deeper analysis reveals that the learned latent codes effectively capture the differences in the distribution of human preferences and significantly enhance the robustness of alignment against noise in data. By providing a unified representation for the multifarious preference factors, LPC paves the way towards developing more robust and versatile alignment techniques for the responsible deployment of powerful LLMs.

[Arxiv](https://arxiv.org/abs/2505.04993)