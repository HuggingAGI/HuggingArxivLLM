# U-MARVEL: 揭秘通用多模态检索的关键因素，基于多语言大模型的嵌入学习

发布时间：2025年07月20日

`LLM应用` `信息检索` `跨媒体`

> U-MARVEL: Unveiling Key Factors for Universal Multimodal Retrieval via Embedding Learning with MLLMs

# 摘要

> # 摘要
通用多模态检索（UMR）旨在解决跨越多种模态的复杂检索任务。得益于多模态大语言模型（MLLMs）的出现，UMR取得了显著进展。尽管最前沿的 MLLM 基础方法主要采用对比学习原则，但它们在具体训练方案上往往有所不同。尽管这些方法取得了成功，但它们检索能力背后的工作机制仍然 largely 未被探索，这可能导致性能 suboptimal 和 generalization 能力有限。为了解决这些问题，我们开展了一项全面研究，旨在揭示使用 MLLMs 进行 UMR 有效嵌入学习的关键因素。我们首先实现了一个通用的 MLLM 基础的嵌入学习管道，并系统地分析了高性能通用检索系统的主要贡献者。在此基础上，我们探讨了嵌入生成和训练策略中各种细节的方面，包括渐进式转换、困难负样本挖掘和重排序器蒸馏。值得注意的是，我们的研究发现，经常被忽视的因素可能对模型性能产生重大影响。在此基础上，我们引入了一个统一的框架，称为 U-MARVEL（通过嵌入学习实现通用多模态检索的框架），在有监督设置下，该框架在 M-BEIR 基准测试中显著优于最先进的竞争对手，并在图像检索和文本到视频检索等任务中也表现出强大的零样本性能。这些结果突显了我们的框架在各种基于嵌入的检索任务中的泛化潜力。代码可在 https://github.com/chaxjli/U-MARVEL 获取。

> Universal multimodal retrieval (UMR), which aims to address complex retrieval tasks where both queries and candidates span diverse modalities, has been significantly advanced by the emergence of MLLMs. While state-of-the-art MLLM-based methods in the literature predominantly adopt contrastive learning principles, they often differ in their specific training recipes. Despite their success, the mechanisms underlying their retrieval capabilities remain largely unexplored, potentially resulting in suboptimal performance and limited generalization ability. To address these issues, we present a comprehensive study aimed at uncovering the key factors that drive effective embedding learning for UMR using MLLMs. We begin by implementing a general MLLM-based embedding learning pipeline, and systematically analyze the primary contributors to high-performing universal retrieval systems. Based on this, we explore various aspects of the details in embedding generation and training strategies, including progressive transition, hard negative mining and re-ranker distillation. Notably, our findings reveal that often-overlooked factors can have a substantial impact on model performance. Building on these discoveries, we introduce a unified framework termed U-MARVEL (\textbf{U}niversal \textbf{M}ultimod\textbf{A}l \textbf{R}etrie\textbf{V}al via \textbf{E}mbedding \textbf{L}earning), which outperforms state-of-the-art competitors on the M-BEIR benchmark by a large margin in supervised settings, and also exihibits strong zero-shot performance on several tasks such as composed image retrieval and text-to-video retrieval. These results underscore the generalization potential of our framework across various embedding-based retrieval tasks. Code is available at https://github.com/chaxjli/U-MARVEL

[Arxiv](https://arxiv.org/abs/2507.14902)