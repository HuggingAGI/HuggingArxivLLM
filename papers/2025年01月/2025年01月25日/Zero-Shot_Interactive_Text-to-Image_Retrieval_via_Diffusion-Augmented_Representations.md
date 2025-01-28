# 基于扩散增强表示的零-shot 交互式文本到图像检索

发布时间：2025年01月25日

`LLM应用

理由：该论文主要讨论了如何利用大型语言模型（LLM）和扩散模型（DM）来改进交互式文本到图像检索（I-TIR）系统。论文提出的方法DAR通过结合LLM引导的查询优化和基于DM的视觉合成，生成上下文丰富的中间表示，从而提升检索性能。虽然涉及多模态模型（MLLMs），但核心创新点在于如何利用LLM和DM来优化检索系统，因此应归类为LLM应用。` `电子商务`

> Zero-Shot Interactive Text-to-Image Retrieval via Diffusion-Augmented Representations

# 摘要

> # 交互式文本到图像检索（I-TIR）
交互式文本到图像检索（I-TIR）已成为电子商务和教育等领域中的革命性用户交互工具。然而，现有方法主要依赖微调的多模态大型语言模型（MLLMs），存在两大瓶颈：（1）微调带来高昂的计算成本和长期维护负担；（2）微调限制了MLLMs的预训练知识分布，削弱了其对新场景的适应能力。这些问题在现实世界的I-TIR系统中尤为突出，因为查询和图像库的复杂性和多样性不断演变，常常偏离静态训练分布。为此，我们提出了扩散增强检索（DAR），这是一个完全绕过MLLM微调的创新框架。DAR通过结合大型语言模型（LLM）引导的查询优化和基于扩散模型（DM）的视觉合成，生成上下文丰富的中间表示。这种双模态方法能够更全面地捕捉用户意图，实现文本查询与视觉图像的精准匹配。在四个基准测试中的评估表明，DAR具有双重优势：（1）在无需任务特定训练的情况下，与最先进的微调I-TIR模型在简单查询上表现相当；（2）在多轮对话复杂性下，Hits@10（前10准确率）比微调基线高出7.61%，展现了其对复杂、分布偏移交互的强大适应能力。通过摒弃微调依赖并利用生成增强表示，DAR为高效、自适应和可扩展的跨模态检索系统开辟了新路径。

> Interactive Text-to-Image Retrieval (I-TIR) has emerged as a transformative user-interactive tool for applications in domains such as e-commerce and education. Yet, current methodologies predominantly depend on finetuned Multimodal Large Language Models (MLLMs), which face two critical limitations: (1) Finetuning imposes prohibitive computational overhead and long-term maintenance costs. (2) Finetuning narrows the pretrained knowledge distribution of MLLMs, reducing their adaptability to novel scenarios. These issues are exacerbated by the inherently dynamic nature of real-world I-TIR systems, where queries and image databases evolve in complexity and diversity, often deviating from static training distributions. To overcome these constraints, we propose Diffusion Augmented Retrieval (DAR), a paradigm-shifting framework that bypasses MLLM finetuning entirely. DAR synergizes Large Language Model (LLM)-guided query refinement with Diffusion Model (DM)-based visual synthesis to create contextually enriched intermediate representations. This dual-modality approach deciphers nuanced user intent more holistically, enabling precise alignment between textual queries and visually relevant images. Rigorous evaluations across four benchmarks reveal DAR's dual strengths: (1) Matches state-of-the-art finetuned I-TIR models on straightforward queries without task-specific training. (2) Scalable Generalization: Surpasses finetuned baselines by 7.61% in Hits@10 (top-10 accuracy) under multi-turn conversational complexity, demonstrating robustness to intricate, distributionally shifted interactions. By eliminating finetuning dependencies and leveraging generative-augmented representations, DAR establishes a new trajectory for efficient, adaptive, and scalable cross-modal retrieval systems.

[Arxiv](https://arxiv.org/abs/2501.15379)