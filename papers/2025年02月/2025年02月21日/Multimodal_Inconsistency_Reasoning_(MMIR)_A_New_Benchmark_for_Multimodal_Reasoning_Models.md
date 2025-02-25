# # 多模态不一致性推理 (MMIR)：一个多模态推理的全新基准测试

发布时间：2025年02月21日

`LLM应用` `多模态推理` `跨模态分析`

> Multimodal Inconsistency Reasoning (MMIR): A New Benchmark for Multimodal Reasoning Models

# 摘要

> 现有的多模态大型语言模型（MLLMs）主要在一致的视觉-文本输入上进行训练和测试，这使其在处理现实世界中布局丰富但内容不一致的场景时的能力仍有待验证。为此，我们提出了多模态不一致性推理（MMIR）基准测试，旨在评估MLLMs在检测和推理网页、演示文稿和海报等 artifacts 中语义不匹配方面的能力。MMIR 包含534个具有挑战性的样本，每个样本在五个需要大量推理的类别中注入了合成错误：事实矛盾、身份错误归属、上下文不匹配、数量差异以及时空不连贯。我们对六种最先进的MLLMs进行了评估，结果显示，具备专门多模态推理能力的模型（如 o1）显著优于其他模型，而开源模型在面对不一致性错误时则显得尤为脆弱。详细错误分析表明，模型在检测单一模态内的不一致性（尤其是在文本方面）表现出色，但在处理跨模态冲突和复杂布局时则显得力不从心。探查实验揭示，单模态提示方法（包括链式思维推理（CoT）和标记集方法（SoM））仅能带来微小的性能提升，这凸显了跨模态推理中的关键瓶颈。我们的研究结果强调了提升多模态推理能力的必要性，并为未来在多模态不一致性领域的研究指明了方向。

> Existing Multimodal Large Language Models (MLLMs) are predominantly trained and tested on consistent visual-textual inputs, leaving open the question of whether they can handle inconsistencies in real-world, layout-rich content. To bridge this gap, we propose the Multimodal Inconsistency Reasoning (MMIR) benchmark to assess MLLMs' ability to detect and reason about semantic mismatches in artifacts such as webpages, presentation slides, and posters. MMIR comprises 534 challenging samples, each containing synthetically injected errors across five reasoning-heavy categories: Factual Contradiction, Identity Misattribution, Contextual Mismatch, Quantitative Discrepancy, and Temporal/Spatial Incoherence. We evaluate six state-of-the-art MLLMs, showing that models with dedicated multimodal reasoning capabilities, such as o1, substantially outperform their counterparts while open-source models remain particularly vulnerable to inconsistency errors. Detailed error analyses further show that models excel in detecting inconsistencies confined to a single modality, particularly in text, but struggle with cross-modal conflicts and complex layouts. Probing experiments reveal that single-modality prompting, including Chain-of-Thought (CoT) and Set-of-Mark (SoM) methods, yields marginal gains, revealing a key bottleneck in cross-modal reasoning. Our findings highlight the need for advanced multimodal reasoning and point to future research on multimodal inconsistency.

[Arxiv](https://arxiv.org/abs/2502.16033)