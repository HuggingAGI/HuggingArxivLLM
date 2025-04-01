# 预训练大型语言模型中的自适应层跳过

发布时间：2025年03月31日

`LLM应用

理由：这篇论文探讨了优化大型语言模型（LLMs）生成过程的方法，具体是通过动态调整Transformer层数来提高效率。这属于将理论应用于实际模型优化的范畴，因此归类为LLM应用。` `生成模型`

> Adaptive Layer-skipping in Pre-trained LLMs

# 摘要

> 加速大型语言模型 (LLMs) 中的 token 生成，已提出多种层跳过方法。然而，这些方法忽视了一个基本问题：不同 token 的生成在计算需求上存在怎样的差异？本研究中，我们提出了 FlexiDepth 方法，该方法能够动态调整文本生成过程中所使用的 Transformer 层的数量。通过引入插件式路由器和适配器，FlexiDepth 实现了无需修改原始参数即可在 LLMs 中进行自适应层跳过。将 FlexiDepth 应用于 Llama-3-8B 模型，实现了 32 层中的 8 层跳过，同时保持了 100% 的基准性能。实验结果表明，LLMs 中的计算需求因 token 类型而异。具体来说，生成重复性 token 或固定短语所需的层数较少，而涉及复杂计算或高度不确定性的 token 则需要更多层数。有趣的是，这种自适应分配模式与人类直觉相吻合。为了推动这一领域的研究，我们开源了 FlexiDepth 以及记录其层分配模式的数据集，以供未来进一步探索。

> Various layer-skipping methods have been proposed to accelerate token generation in large language models (LLMs). However, they have overlooked a fundamental question: How do computational demands vary across the generation of different tokens? In this work, we introduce FlexiDepth, a method that dynamically adjusts the number of Transformer layers used in text generation. By incorporating a plug-in router and adapter, FlexiDepth enables adaptive layer-skipping in LLMs without modifying their original parameters. Introducing FlexiDepth to Llama-3-8B model achieves layer skipping of 8 layers out of 32, and meanwhile maintains the full 100\% benchmark performance. Experimental results with FlexiDepth demonstrate that computational demands in LLMs significantly vary based on token type. Specifically, generating repetitive tokens or fixed phrases requires fewer layers, whereas producing tokens involving computation or high uncertainty requires more layers. Interestingly, this adaptive allocation pattern aligns with human intuition. To advance research in this area, we open sourced FlexiDepth and a dataset documenting FlexiDepth's layer allocation patterns for future exploration.

[Arxiv](https://arxiv.org/abs/2503.23798)