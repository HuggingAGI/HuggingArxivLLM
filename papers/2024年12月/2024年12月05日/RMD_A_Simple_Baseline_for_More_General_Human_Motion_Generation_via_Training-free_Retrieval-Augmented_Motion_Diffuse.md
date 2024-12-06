# RMD：通过无训练的检索增强运动扩散来实现更通用人类运动生成的简单基线

发布时间：2024年12月05日

`LLM应用` `动作生成` `检索技术`

> RMD: A Simple Baseline for More General Human Motion Generation via Training-free Retrieval-Augmented Motion Diffuse

# 摘要

> 尽管动作生成已取得显著进步，但其实际应用仍受数据集的多样性和规模所限，导致处理分布外场景的能力不足。为解决此问题，我们提出了一个简便有效的基线——RMD，它借助检索增强技术提升了动作生成的泛化能力。与以往基于检索的方法不同，RMD 无需额外训练，且具备三大关键优势：（1）外部检索数据库可灵活替换；（2）运动数据库中的身体部位能够复用，LLM 有助于拆分和重组；（3）预先训练的运动扩散模型充当先验，以提升通过检索和直接组合获取的动作质量。无需任何训练，RMD 便达到了最先进的性能，在分布外数据方面优势明显。

> While motion generation has made substantial progress, its practical application remains constrained by dataset diversity and scale, limiting its ability to handle out-of-distribution scenarios. To address this, we propose a simple and effective baseline, RMD, which enhances the generalization of motion generation through retrieval-augmented techniques. Unlike previous retrieval-based methods, RMD requires no additional training and offers three key advantages: (1) the external retrieval database can be flexibly replaced; (2) body parts from the motion database can be reused, with an LLM facilitating splitting and recombination; and (3) a pre-trained motion diffusion model serves as a prior to improve the quality of motions obtained through retrieval and direct combination. Without any training, RMD achieves state-of-the-art performance, with notable advantages on out-of-distribution data.

[Arxiv](https://arxiv.org/abs/2412.04343)