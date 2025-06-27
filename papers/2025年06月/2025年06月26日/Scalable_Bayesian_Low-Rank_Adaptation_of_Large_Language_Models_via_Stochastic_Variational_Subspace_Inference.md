# 基于随机变分子空间推理的大型语言模型可扩展贝叶斯低秩适应

发布时间：2025年06月26日

`LLM理论` `自动驾驶`

> Scalable Bayesian Low-Rank Adaptation of Large Language Models via Stochastic Variational Subspace Inference

# 摘要

> 尽管大型语言模型（LLMs）被广泛应用，但它们生成错误信息和校准不足的问题也广为人知。这使得对这些模型的不确定性量化变得至关重要，尤其是在自动驾驶和医疗等高风险领域。此前的研究通过基于LLMs微调模型的低秩适配（LoRA）参数进行推理，使基于贝叶斯深度学习的方法更具可行性。虽然这些方法有效，但它们在扩展到更大规模的LLMs时面临困难，因为与LoRA相比，它们需要额外的参数。在此项研究中，我们提出了通过随机变分子空间推理实现的可扩展贝叶斯低秩适配（ScalaBL）。我们在LoRA秩为r的r维子空间中进行贝叶斯推理，并将LoRA参数重新用作投影矩阵，从而将子空间中的样本映射到LLM的全权重空间。这使我们能够使用随机变分推理来学习方法中的所有参数。尽管我们的子空间维度较低，但通过仅增加约1000个额外参数，我们能够与最先进的方法相媲美。此外，这使我们能够扩展到迄今为止最大的贝叶斯LLM，其基础参数数量是此前研究的四倍。

> Despite their widespread use, large language models (LLMs) are known to hallucinate incorrect information and be poorly calibrated. This makes the uncertainty quantification of these models of critical importance, especially in high-stakes domains, such as autonomy and healthcare. Prior work has made Bayesian deep learning-based approaches to this problem more tractable by performing inference over the low-rank adaptation (LoRA) parameters of a fine-tuned model. While effective, these approaches struggle to scale to larger LLMs due to requiring further additional parameters compared to LoRA. In this work we present $\textbf{Scala}$ble $\textbf{B}$ayesian $\textbf{L}$ow-Rank Adaptation via Stochastic Variational Subspace Inference (ScalaBL). We perform Bayesian inference in an $r$-dimensional subspace, for LoRA rank $r$. By repurposing the LoRA parameters as projection matrices, we are able to map samples from this subspace into the full weight space of the LLM. This allows us to learn all the parameters of our approach using stochastic variational inference. Despite the low dimensionality of our subspace, we are able to achieve competitive performance with state-of-the-art approaches while only requiring ${\sim}1000$ additional parameters. Furthermore, it allows us to scale up to the largest Bayesian LLM to date, with four times as a many base parameters as prior work.

[Arxiv](https://arxiv.org/abs/2506.21408)