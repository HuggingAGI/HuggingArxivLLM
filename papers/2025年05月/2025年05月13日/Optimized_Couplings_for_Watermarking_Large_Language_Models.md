# # 优化的耦合方法用于大型语言模型的水印技术

发布时间：2025年05月13日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）生成文本中的水印技术，从理论角度分析了水印检测能力与生成文本质量失真之间的权衡，并提出了最优策略。这属于对LLM的理论分析和改进，因此归类为LLM理论。` `信息与通信技术` `文本水印`

> Optimized Couplings for Watermarking Large Language Models

# 摘要

> 大型语言模型（LLMs）生成的文本在许多情况下已难以区分于人类生成的内容。这推动了水印技术的发展，这些技术能够在对 LLM 输出进行最小干扰的情况下，在生成的文本中嵌入 ``信号''。本文分析了单次设置下的文本水印技术。通过结合侧边信息的假设检验视角，我们探讨并分析了水印检测能力与生成文本质量失真之间的基本权衡。我们认为，水印设计的关键在于在水印检测器共享的侧边信息与 LLM 词汇表的随机划分之间建立耦合关系。我们的分析确定了在最坏情况下满足最小熵约束的 LLM 下一词分布中的最优耦合和随机化策略。我们给出了所提出的方案下检测率的闭式表达式，并以最大最小意义上的量化成本进行了评估。最后，我们通过合成数据和 LLM 水印实验，比较了所提出的方案与理论最优和现有方案的表现。我们的代码可在 https://github.com/Carol-Long/CC_Watermark 获取。


> Large-language models (LLMs) are now able to produce text that is, in many cases, seemingly indistinguishable from human-generated content. This has fueled the development of watermarks that imprint a ``signal'' in LLM-generated text with minimal perturbation of an LLM's output. This paper provides an analysis of text watermarking in a one-shot setting. Through the lens of hypothesis testing with side information, we formulate and analyze the fundamental trade-off between watermark detection power and distortion in generated textual quality. We argue that a key component in watermark design is generating a coupling between the side information shared with the watermark detector and a random partition of the LLM vocabulary. Our analysis identifies the optimal coupling and randomization strategy under the worst-case LLM next-token distribution that satisfies a min-entropy constraint. We provide a closed-form expression of the resulting detection rate under the proposed scheme and quantify the cost in a max-min sense. Finally, we provide an array of numerical results, comparing the proposed scheme with the theoretical optimum and existing schemes, in both synthetic data and LLM watermarking. Our code is available at https://github.com/Carol-Long/CC_Watermark

[Arxiv](https://arxiv.org/abs/2505.08878)