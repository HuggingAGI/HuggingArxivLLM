# 强化学习为自回归图像编辑带来的无限可能

发布时间：2025年08月01日

`LLM应用` `图像编辑` `图像处理`

> The Promise of RL for Autoregressive Image Editing

# 摘要

> 我们探索了三种策略来提升图像编辑任务的性能：监督微调（SFT）、强化学习（RL）以及链式推理（CoT）。为了在一个统一的框架中研究所有这些组件，我们采用了自回归多模态模型，该模型以统一的方式处理文本和视觉令牌。我们发现，结合大型多模态LLM验证器的强化学习是这些策略中最有效的。因此，我们发布了EARL：基于自回归和强化学习的编辑模型。与强大的基线模型相比，EARL在各种编辑任务上表现优异，尽管使用了更少的训练数据。因此，EARL推动了自回归多模态模型在图像编辑领域的前沿。我们已在https://github.com/mair-lab/EARL发布了我们的代码、训练数据和训练好的模型。

> We explore three strategies to enhance performance on a wide range of image editing tasks: supervised fine-tuning (SFT), reinforcement learning (RL), and Chain-of-Thought (CoT) reasoning. In order to study all these components in one consistent framework, we adopt an autoregressive multimodal model that processes textual and visual tokens in a unified manner. We find RL combined with a large multi-modal LLM verifier to be the most effective of these strategies. As a result, we release EARL: Editing with Autoregression and RL, a strong RL-based image editing model that performs competitively on a diverse range of edits compared to strong baselines, despite using much less training data. Thus, EARL pushes the frontier of autoregressive multimodal models on image editing. We release our code, training data, and trained models at https://github.com/mair-lab/EARL.

[Arxiv](https://arxiv.org/abs/2508.01119)