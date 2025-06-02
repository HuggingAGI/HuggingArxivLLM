# # 动态层剪枝在大型语言模型中的应用

发布时间：2025年05月27日

`LLM应用` `人工智能` `模型压缩`

> DLP: Dynamic Layerwise Pruning in Large Language Models

# 摘要

> 剪枝技术近年来成为减少大型语言模型（LLMs）参数规模、提升推理效率的热门方法。目前主流的均匀层间剪枝策略在高稀疏度下往往导致性能大幅下降。鉴于LLMs中各层贡献差异显著，研究者逐渐转向非均匀层间剪枝方法。然而，这些方法常依赖预设值，影响性能表现。针对这些局限，我们提出了一种创新的动态层间剪枝（DLP）方法。该方法通过整合模型权重与输入激活信息，自适应地评估各层重要性并动态分配剪枝率。实验结果表明，DLP在多个LLMs上实现了高性能保持，尤其在高稀疏度下表现突出。具体而言，在70%稀疏度下，DLP较现有最优方法将LLaMA2-7B的困惑度降低了7.79，平均准确率提升了2.7%。此外，DLP与现有多种LLM压缩技术兼容，并可无缝融入参数高效微调（PEFT）流程。我们已将代码开源至https://github.com/ironartisan/DLP，以助力未来研究发展。

> Pruning has recently been widely adopted to reduce the parameter scale and improve the inference efficiency of Large Language Models (LLMs). Mainstream pruning techniques often rely on uniform layerwise pruning strategies, which can lead to severe performance degradation at high sparsity levels. Recognizing the varying contributions of different layers in LLMs, recent studies have shifted their focus toward non-uniform layerwise pruning. However, these approaches often rely on pre-defined values, which can result in suboptimal performance. To overcome these limitations, we propose a novel method called Dynamic Layerwise Pruning (DLP). This approach adaptively determines the relative importance of each layer by integrating model weights with input activation information, assigning pruning rates accordingly. Experimental results show that DLP effectively preserves model performance at high sparsity levels across multiple LLMs. Specifically, at 70% sparsity, DLP reduces the perplexity of LLaMA2-7B by 7.79 and improves the average accuracy by 2.7% compared to state-of-the-art methods. Moreover, DLP is compatible with various existing LLM compression techniques and can be seamlessly integrated into Parameter-Efficient Fine-Tuning (PEFT). We release the code at https://github.com/ironartisan/DLP to facilitate future research.

[Arxiv](https://arxiv.org/abs/2505.23807)