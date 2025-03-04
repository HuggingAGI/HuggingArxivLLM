# CE-U：交叉熵遗忘机制

发布时间：2025年03月03日

`LLM理论` `人工智能` `数据安全`

> CE-U: Cross Entropy Unlearning

# 摘要

> 大型语言模型（LLMs）在预训练过程中无意中记忆了敏感数据 \cite{jang2022knowledge}。为解决这一问题，我们提出了CE-U（交叉熵遗忘），一种专为遗忘任务设计的新型损失函数。CE-U克服了梯度上升方法在模型高置信度时梯度消失、低置信度时梯度爆炸的不稳定性问题。我们还成功地将标准交叉熵监督和交叉熵遗忘整合到一个统一框架中。特别值得一提的是，在用于评估遗忘能力的TOFU基准测试 \cite{maini2024tofu}中，CE-U在LLaMA2-7B模型上取得了1%和5%遗忘率下的最先进成果，且无需任何额外参考模型或正样本。通过理论分析，我们发现梯度不稳定性问题同样存在于DPO和GRPO等流行强化学习算法中，因为它们都包含梯度上升的组件。这表明，将CE-U的核心思想应用于强化学习领域，可能成为提升算法稳定性和收敛性的有效途径。

> Large language models (LLMs) inadvertently memorize sensitive data from their massive pretraining corpora \cite{jang2022knowledge}. In this work, we propose CE-U (Cross Entropy Unlearning), a novel loss function designed specifically for unlearning tasks. CE-U addresses fundamental limitations of gradient ascent approaches which suffer from instability due to vanishing gradients when model confidence is high and gradient exploding when confidence is low. We also unify standard cross entropy supervision and cross entropy unlearning into a single framework. Notably, on the TOFU benchmark for unlearning \cite{maini2024tofu}, CE-U achieves state-of-the-art results on LLaMA2-7B with 1\% and 5\% forgetting, even without the use of any extra reference model or additional positive samples. Our theoretical analysis further reveals that the gradient instability issues also exist in popular reinforcement learning algorithms like DPO and GRPO, as they include a gradient ascent component. This suggests that applying CE-U principles to reinforcement learning could be a promising direction for improving stability and convergence.

[Arxiv](https://arxiv.org/abs/2503.01224)