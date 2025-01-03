# OP-LoRA：维度的馈赠

发布时间：2024年12月13日

`LLM理论

理由：这篇论文主要讨论了低秩适配器（Low-rank adapters）在优化大型模型时的改进方法，特别是通过过参数化来加速训练并提高收敛性。虽然论文提到了代理任务和图像生成等应用场景，但其核心贡献在于提出了一种新的理论方法（过参数化）来改进低秩适配器的优化过程。因此，这篇论文更适合归类为LLM理论，因为它主要关注的是模型优化和训练的理论改进，而不是具体的应用或代理行为。` `机器学习` `图像生成`

> OP-LoRA: The Blessing of Dimensionality

# 摘要

> 低秩适配器（Low-rank adapters）通过少量参数微调大型模型，降低了存储成本并减少了灾难性遗忘的风险。然而，它们常面临优化难题，收敛性较差。为此，我们提出了一种过参数化方法，在不增加推理成本的情况下加速训练。该方法通过为每一层引入独立的MLP和学习嵌入，重新参数化低秩适配。学习嵌入输入MLP，生成适配器参数。这种过参数化隐式地充当了自适应学习率和动量，加速了优化。推理时，MLP可被丢弃，仅保留标准的低秩适配器。为验证MLP过参数化在小而复杂的代理任务中的效果，我们将其应用于矩阵分解，发现其收敛更快且最终损失更低。将该方法扩展至更大规模任务时，我们观察到跨领域的性能提升，尤其在图像生成方面，CMMD分数提升了多达15分。

> Low-rank adapters enable fine-tuning of large models with only a small number of parameters, thus reducing storage costs and minimizing the risk of catastrophic forgetting. However, they often pose optimization challenges, with poor convergence. To overcome these challenges, we introduce an over-parameterized approach that accelerates training without increasing inference costs. This method reparameterizes low-rank adaptation by employing a separate MLP and learned embedding for each layer. The learned embedding is input to the MLP, which generates the adapter parameters. Such overparamaterization has been shown to implicitly function as an adaptive learning rate and momentum, accelerating optimization. At inference time, the MLP can be discarded, leaving behind a standard low-rank adapter. To study the effect of MLP overparameterization on a small yet difficult proxy task, we implement it for matrix factorization, and find it achieves faster convergence and lower final loss. Extending this approach to larger-scale tasks, we observe consistent performance gains across domains. We achieve improvements in vision-language tasks and especially notable increases in image generation, with CMMD scores improving by up to 15 points.

[Arxiv](https://arxiv.org/abs/2412.10362)