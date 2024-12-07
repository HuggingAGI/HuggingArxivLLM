# 释放自回归模型的上下文学习以用于少样本图像的操作

发布时间：2024年12月02日

`LLM应用` `图像操作` `多模态`

> Unleashing In-context Learning of Autoregressive Models for Few-shot Image Manipulation

# 摘要

> 近年来，文本引导的图像操作取得了显著进步。为减轻语言的模糊性，针对训练集中代表性不足或纯语言难以描述的指令，已采用带有视觉示例的少样本学习。但从视觉提示学习需要强大推理能力，扩散模型在这方面颇为吃力。为解决此问题，我们推出一种新颖的多模态自回归模型，名为$	extbf{InstaManip}$，它能通过上下文学习，从文本和视觉引导中即刻学会新的图像操作，并应用于新的查询图像。具体而言，我们提出创新的组自注意力机制，将上下文学习过程分为学习和应用两个独立阶段，把复杂问题简化为两个较易的任务。我们还引入关系正则化方法，进一步把图像变换特征与示例图像中的无关内容区分开。大量实验表明，我们的方法大幅优于以往的少样本图像操作模型（人类评估中≥19%）。我们还发现，增加示例图像的数量或多样性，能进一步优化我们的模型。

> Text-guided image manipulation has experienced notable advancement in recent years. In order to mitigate linguistic ambiguity, few-shot learning with visual examples has been applied for instructions that are underrepresented in the training set, or difficult to describe purely in language. However, learning from visual prompts requires strong reasoning capability, which diffusion models are struggling with. To address this issue, we introduce a novel multi-modal autoregressive model, dubbed $\textbf{InstaManip}$, that can $\textbf{insta}$ntly learn a new image $\textbf{manip}$ulation operation from textual and visual guidance via in-context learning, and apply it to new query images. Specifically, we propose an innovative group self-attention mechanism to break down the in-context learning process into two separate stages -- learning and applying, which simplifies the complex problem into two easier tasks. We also introduce a relation regularization method to further disentangle image transformation features from irrelevant contents in exemplar images. Extensive experiments suggest that our method surpasses previous few-shot image manipulation models by a notable margin ($\geq$19% in human evaluation). We also find our model can be further boosted by increasing the number or diversity of exemplar images.

[Arxiv](https://arxiv.org/abs/2412.01027)