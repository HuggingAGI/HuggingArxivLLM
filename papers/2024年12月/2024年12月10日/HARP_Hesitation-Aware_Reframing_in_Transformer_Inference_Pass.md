# HARP：Transformer 推理过程中具有犹豫感知的重框定

发布时间：2024年12月10日

`LLM应用` `语言模型` `推理优化`

> HARP: Hesitation-Aware Reframing in Transformer Inference Pass

# 摘要

> 这篇论文致力于解决推理步骤中存在的可变计算需求，以此提升大型语言模型的性能，因为在推理过程中，部分标记所需的计算资源多于其他标记。我们推出了 HARP，这是对“现成”的 Transformer 前向传播的一项简易修改。借鉴决策中的犹豫和框架效应，HARP 会在模型生成标记时遭遇不确定性时，有选择地进行额外计算。我们的方法模仿了人类的认知过程，即在困难的决策点暂停，并重新构建输入以获取不同视角。和其他方法不同，HARP 不依赖特定模型，无需训练，且易于实现。我们在各类下游任务和不同规模的模型中全面评估了该方法，证明其性能提升高达 +5.16%。特别要指出的是，HARP 在保持推理时间比波束搜索快两倍的同时实现了这些提升。简单却成效显著，HARP 为以最小计算代价提升基于 Transformer 的语言模型性能提供了切实可行的方案。

> This paper aims to improve the performance of large language models by addressing the variable computational demands in inference steps, where some tokens require more computational resources than others. We present HARP, a simple modification to "off-the-shelf" Transformer forward pass. Drawing from hesitation and the framing effect in decision-making, HARP selectively applies additional computation when the model encounters uncertainty during token generation. Our method mimics human cognitive processes by pausing at difficult decision points and reframing inputs for a different perspective. Unlike other approaches, HARP is model-agnostic, training-free, and easy to implement. We thoroughly evaluate our method across various downstream tasks and model sizes, demonstrating performance improvements up to +5.16%. Notably, HARP achieves these gains while maintaining inference times twice faster than beam search. Simple and yet with significant gains, HARP offers a practical solution for enhancing the performance of Transformer-based language models with minimal computational impact.

[Arxiv](https://arxiv.org/abs/2412.07282)