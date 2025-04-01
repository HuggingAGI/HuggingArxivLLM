# # 评估与设计稀疏自动编码器：基于近似类正交性方法

发布时间：2025年03月31日

`LLM理论` `机器学习` `稀疏自动编码器`

> Evaluating and Designing Sparse Autoencoders by Approximating Quasi-Orthogonality

# 摘要

> 稀疏自动编码器（SAEs）已成为现代机制可解释性的重要工具，但现有基于top-$k$激活函数的SAE方法在选择超参数$k$时缺乏理论依据。SAEs基于两个核心假设：线性表示假设（LRH）和叠加假设（SH）。LRH认为大型语言模型（LLMs）的表示是线性编码的，而SH则表明模型中可以包含比其维度更多的特征。我们证明，基于LRH和SH的正式定义，稀疏特征向量的幅度（SAEs从LLMs的密集嵌入中学习到的潜在表示）可以通过其对应的密集向量以闭合形式的误差界限进行近似。为了直观展示这一点，我们提出了ZF图，揭示了LLM隐藏嵌入与SAE特征向量之间之前未被发现的关系，使我们能够首次对预训练SAE特征向量在给定输入下是过激活还是欠激活进行经验测量。我们引入了近似特征激活（AFA），用于近似真实稀疏特征向量的幅度，并提出了一种基于AFA的新评估指标，用于衡量输入与激活之间的对齐程度。我们还利用AFA引入了一种新型的SAE架构——top-AFA SAE，使得SAEs不仅更符合理论依据，而且无需调参稀疏性超参数。最终实验表明，top-AFA SAEs在无需调参$k$的情况下，能够达到与现有最优top-$k$ SAEs相当的重构损失。我们的代码可在以下链接获取：https://github.com/SewoongLee/top-afa-sae。

> Sparse autoencoders (SAEs) have emerged as a workhorse of modern mechanistic interpretability, but leading SAE approaches with top-$k$ style activation functions lack theoretical grounding for selecting the hyperparameter $k$. SAEs are based on the linear representation hypothesis (LRH), which assumes that the representations of large language models (LLMs) are linearly encoded, and the superposition hypothesis (SH), which states that there can be more features in the model than its dimensionality. We show that, based on the formal definitions of the LRH and SH, the magnitude of sparse feature vectors (the latent representations learned by SAEs of the dense embeddings of LLMs) can be approximated using their corresponding dense vector with a closed-form error bound. To visualize this, we propose the ZF plot, which reveals a previously unknown relationship between LLM hidden embeddings and SAE feature vectors, allowing us to make the first empirical measurement of the extent to which feature vectors of pre-trained SAEs are over- or under-activated for a given input. Correspondingly, we introduce Approximate Feature Activation (AFA), which approximates the magnitude of the ground-truth sparse feature vector, and propose a new evaluation metric derived from AFA to assess the alignment between inputs and activations. We also leverage AFA to introduce a novel SAE architecture, the top-AFA SAE, leading to SAEs that: (a) are more in line with theoretical justifications; and (b) obviate the need to tune SAE sparsity hyperparameters. Finally, we empirically demonstrate that top-AFA SAEs achieve reconstruction loss comparable to that of state-of-the-art top-k SAEs, without requiring the hyperparameter $k$ to be tuned. Our code is available at: https://github.com/SewoongLee/top-afa-sae.

[Arxiv](https://arxiv.org/abs/2503.24277)