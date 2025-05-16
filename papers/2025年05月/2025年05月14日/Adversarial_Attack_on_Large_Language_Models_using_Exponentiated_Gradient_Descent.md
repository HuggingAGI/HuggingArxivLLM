# 基于指数梯度下降的大型语言模型对抗攻击

发布时间：2025年05月14日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在越狱攻击中的应用，提出了一种新的优化技术来提升攻击的成功率和效率。虽然涉及一些理论分析，但核心内容是应用层面的改进和实现。` `大型语言模型` `安全性`

> Adversarial Attack on Large Language Models using Exponentiated Gradient Descent

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，系统性理解它们对于提升安全性和发挥其潜力至关重要。尽管许多模型通过人类反馈强化学习（RLHF）等技术进行了对齐，但它们仍然容易受到越狱攻击。现有的对抗攻击方法主要分为两类：一类通过搜索可能使模型越狱的离散token，另一类则试图优化模型词汇表中token所表示的连续空间。然而，基于离散空间的技术效率较低，而对连续token嵌入的优化需要通过投影生成离散token，这可能使其失效。为充分利用空间的约束和结构，我们开发了一种基于指数梯度下降和Bregman投影方法的内在优化技术，确保优化后的one-hot编码始终位于概率单形内。我们证明了该技术的收敛性，并实现了一个高效的算法，能够在越狱多个广泛使用的LLMs中发挥作用。我们使用五个开源LLMs在四个公开可用的数据集上展示了所提技术的有效性。实验结果表明，与另外三种最先进的越狱技术相比，该技术不仅成功率更高，而且效率显著提升。我们的实现源代码可在以下链接获取：https://github.com/sbamit/Exponentiated-Gradient-Descent-LLM-Attack

> As Large Language Models (LLMs) are widely used, understanding them systematically is key to improving their safety and realizing their full potential. Although many models are aligned using techniques such as reinforcement learning from human feedback (RLHF), they are still vulnerable to jailbreaking attacks. Some of the existing adversarial attack methods search for discrete tokens that may jailbreak a target model while others try to optimize the continuous space represented by the tokens of the model's vocabulary. While techniques based on the discrete space may prove to be inefficient, optimization of continuous token embeddings requires projections to produce discrete tokens, which might render them ineffective. To fully utilize the constraints and the structures of the space, we develop an intrinsic optimization technique using exponentiated gradient descent with the Bregman projection method to ensure that the optimized one-hot encoding always stays within the probability simplex. We prove the convergence of the technique and implement an efficient algorithm that is effective in jailbreaking several widely used LLMs. We demonstrate the efficacy of the proposed technique using five open-source LLMs on four openly available datasets. The results show that the technique achieves a higher success rate with great efficiency compared to three other state-of-the-art jailbreaking techniques. The source code for our implementation is available at: https://github.com/sbamit/Exponentiated-Gradient-Descent-LLM-Attack

[Arxiv](https://arxiv.org/abs/2505.09820)