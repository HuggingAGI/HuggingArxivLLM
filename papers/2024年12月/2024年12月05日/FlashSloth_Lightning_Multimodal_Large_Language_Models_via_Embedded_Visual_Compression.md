# FlashSloth：借助嵌入式视觉压缩的闪电多模态大型语言模型

发布时间：2024年12月05日

`LLM应用` `多模态` `语言模型`

> FlashSloth: Lightning Multimodal Large Language Models via Embedded Visual Compression

# 摘要

> 尽管能力大幅提升，但多模态大型语言模型（MLLMs）在实际运用中常如树懒般，响应迟缓且延迟较大。近来，人们致力于构建小巧的 MLLMs 以提升效率，然而大量的视觉标记仍限制了其实际加速效果。本文中，我们提出了一种强大且快速的小型 MLLM——FlashSloth。与以往不同，FlashSloth 着重于在压缩冗余语义的过程中增强视觉标记的描述力。具体而言，FlashSloth 引入嵌入式视觉压缩设计，以抓取视觉显著及与指令相关的图像信息，从而凭借更少的视觉标记达成出色的多模态性能。我们开展了大量实验来验证所提出的 FlashSloth，并对诸如 InternVL2、MiniCPM-V2 和 Qwen2-VL 等一系列小巧却强劲的 MLLMs 进行了全面对比。实验结果显示，相较于这些先进的小型 MLLMs，我们的 FlashSloth 能够大幅减少视觉标记数量、训练内存及计算复杂度，同时在各类 VL 任务中保持高性能。

> Despite a big leap forward in capability, multimodal large language models (MLLMs) tend to behave like a sloth in practical use, i.e., slow response and large latency. Recent efforts are devoted to building tiny MLLMs for better efficiency, but the plethora of visual tokens still used limit their actual speedup. In this paper, we propose a powerful and fast tiny MLLM called FlashSloth. Different from previous efforts, FlashSloth focuses on improving the descriptive power of visual tokens in the process of compressing their redundant semantics. In particular, FlashSloth introduces embedded visual compression designs to capture both visually salient and instruction-related image information, so as to achieving superior multimodal performance with fewer visual tokens. Extensive experiments are conducted to validate the proposed FlashSloth, and a bunch of tiny but strong MLLMs are also comprehensively compared, e.g., InternVL2, MiniCPM-V2 and Qwen2-VL. The experimental results show that compared with these advanced tiny MLLMs, our FlashSloth can greatly reduce the number of visual tokens, training memory and computation complexity while retaining high performance on various VL tasks.

[Arxiv](https://arxiv.org/abs/2412.04317)