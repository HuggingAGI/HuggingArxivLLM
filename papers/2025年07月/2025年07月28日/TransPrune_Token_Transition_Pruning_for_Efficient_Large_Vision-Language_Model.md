# TransPrune：通过标记转换剪枝实现高效大视觉-语言模型

发布时间：2025年07月28日

`LLM应用

理由：这篇论文主要探讨了如何优化大型视觉语言模型（LVLMs）的计算效率，通过提出一种新的token剪枝方法TransPrune，减少了计算成本。虽然涉及多模态模型，但核心在于应用层面的优化，因此归类为LLM应用。` `多模态学习` `模型优化`

> TransPrune: Token Transition Pruning for Efficient Large Vision-Language Model

# 摘要

> 大型视觉语言模型（LVLMs）在多模态学习领域取得了显著进展，但其高昂的计算成本（源于庞大的视觉token数量）促使我们探索更高效的token剪枝方法。现有方法多依赖注意力机制评估token重要性，但这些方法存在位置偏见等局限。本研究从LVLMs的token转换特性出发，提出了一种全新视角。我们发现，token表示的转换蕴含了重要的语义信息。基于此，我们开发了无需训练的高效剪枝方法——TransPrune。该方法通过结合Token Transition Variation（TTV）和Instruction-Guided Attention（IGA）来逐步剪枝token。TTV衡量token表示的变化幅度和方向，而IGA则衡量指令对图像token的关注程度。实验结果表明，TransPrune在八项基准测试中达到了与原始LVLMs（如LLaVA-v1.5和LLaVA-Next）相当的性能，同时将推理计算量减少了超过一半。值得注意的是，TTV本身即可作为有效的评估标准，无需依赖注意力机制，其性能可与基于注意力的方法相媲美。代码将在论文被接受后开源，地址为https://github.com/liaolea/TransPrune。


> Large Vision-Language Models (LVLMs) have advanced multimodal learning but face high computational costs due to the large number of visual tokens, motivating token pruning to improve inference efficiency. The key challenge lies in identifying which tokens are truly important. Most existing approaches rely on attention-based criteria to estimate token importance. However, they inherently suffer from certain limitations, such as positional bias. In this work, we explore a new perspective on token importance based on token transitions in LVLMs. We observe that the transition of token representations provides a meaningful signal of semantic information. Based on this insight, we propose TransPrune, a training-free and efficient token pruning method. Specifically, TransPrune progressively prunes tokens by assessing their importance through a combination of Token Transition Variation (TTV)-which measures changes in both the magnitude and direction of token representations-and Instruction-Guided Attention (IGA), which measures how strongly the instruction attends to image tokens via attention. Extensive experiments demonstrate that TransPrune achieves comparable multimodal performance to original LVLMs, such as LLaVA-v1.5 and LLaVA-Next, across eight benchmarks, while reducing inference TFLOPs by more than half. Moreover, TTV alone can serve as an effective criterion without relying on attention, achieving performance comparable to attention-based methods. The code will be made publicly available upon acceptance of the paper at https://github.com/liaolea/TransPrune.

[Arxiv](https://arxiv.org/abs/2507.20630)